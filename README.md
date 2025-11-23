
# Memory Palace App

This project is a cross-platform memory palace application with the following structure:

- **web/**: Web application frontend
- **android/**: Android mobile application
- **ios/**: iOS mobile application
- **api/**: Common web API for all platforms
- **shared/**: Shared resources, models, or logic

## High-Level Requirements & Design Decisions

### Answers to Expert Questions (User Decisions)

- Reminders and spaced repetition: Yes, include these features.
- Medical privacy features: Yes, allow users to mark cards as private and add extra protection.
- Usage tracking: Yes, but only with user opt-in and ability to disable reminders.
- Mood/stress tracking: Yes, include this feature.
- Guided onboarding/tutorials: Yes, provide for new users.
- Peer support/professional guidance: Maybe, for future plans after basics are covered.
- Reminders integration: Can be an option, but app should handle natively as well.
- Voice interaction languages: Start with English, plan for more languages; system should be adaptable.
- Offline functionality: Yes, all core features should work offline; only sync may require network.
- Sync reminders/notifications: Yes, sync across devices.
- Third-party services: Use free/open source options; Google Drive for backup with user login.
- Scalability: Target 10k users initially, design for 100k, 1m+.
- Collaborative map features: Can be added, with privacy warnings.
- Visual styles: Start with one, allow switching; data storage should be adaptable.
- AI suggestions for clusters/tags: Yes.
- Visualization rendering: Use web views for consistency and maintainability.
- AI clustering requirements: Yes, support explainability and user override.
- Secure sharing: Yes, allow sharing with encryption and privacy warnings.
- Compliance: Ensure GDPR compliance by default; add more as needed.
- Anonymity/pseudonymity: Yes, allow use without personal info or with nicknames.
- Import/export: Yes, support for other platforms.
- Multimedia formats: Support all (images, audio, video, PDFs, etc.).
- Templates: Yes, provide for common card types.
- Milestones/goals: MVP in one week, major release in one month.
- Feedback: Collect via in-app forms and app store reviews.
- Target audience: Anyone with memory challenges; expand to categories later.

### Planned Features

- Include games and interactive tutorials to help users improve attention and retention capabilities. These may include cognitive exercises, memory games, and step-by-step guides for memory techniques.

### Data Storage & Privacy Requirements

- All user data is stored locally on the user's mobile device; no data is stored on project servers.
- For backup and cross-device access, use user-controlled cloud storage (e.g., Google Drive, iCloud, or other preferred providers), similar to WhatsApp.
- The web version should sync data in real-time across devices without storing any data on project servers, emulating WhatsApp Web behavior.
- Prioritize open source and free libraries for all features and integrations.

### Expert Insights (Summary)

#### Neurologist Perspective
- Target users: forgetfulness due to age, ADHD, or difficulty converting short-term to long-term memory.
- Design: rapid storage/retrieval, fuzzy search, flash cards, quick access, multimedia, internet search.
- Rationale: minimize cognitive load, maximize retrieval cues, multiple recall pathways.

#### Psychologist Perspective
- Behavioral strategies: positive reinforcement, gamification, personalization, feedback.
- Motivation: reminders, streaks, achievements, social features, journaling.
- Rationale: emotional connection, habit formation, reduce anxiety.

#### UI/UX Expert Perspective
- Speed/simplicity, text/voice interaction, accessible reminders, readable design, easy navigation.
- Accessibility: screen reader, customizable UI.

#### System Design Architect Perspective
- Modular, scalable, fast search, voice/NLP, reliable notifications, secure sync, multimedia support.
- Reliability: low-latency, offline support, robust error handling.

#### Accessibility Specialist Perspective
- Visual map/graph, zoom/deep navigation, AI/user categorization, accessible map, alternative views, customization.
- Security: private visualization, user-controlled access.

#### Developer Perspective
- Use .NET and JavaScript/jQuery, responsive web design, avoid native coding, simple/maintainable solutions.
- Interactive graph libraries, tagging, hierarchical categorization, voice/text input, cross-platform, performance.

#### Data Privacy/Security Expert Perspective
- Encrypt data, secure authentication, privacy controls, regular audits.
- Compliance: GDPR by default, clear policies, export/deletion options.

#### Content Specialist Perspective
- Flash card design: concise topics, expandable details, tagging, multimedia.
- Retrieval: fuzzy/semantic search, suggestions, memory chains.

#### Product Manager Perspective
- Roadmap: align expert input, prioritize features, iterative development, success metrics.
- User needs: research, onboarding, analytics, feedback.

## Expert Insights: Psychologist Perspective

### Behavioral Strategies
- Incorporate positive reinforcement and gamification to encourage regular use.
- Allow users to personalize cards and retrieval cues for emotional relevance.
- Provide feedback and progress tracking to motivate improvement.

### Motivation & Engagement
- Use reminders, streaks, and achievements to build habits.
- Offer options for collaborative or social features (e.g., sharing cards with trusted contacts).
- Support for journaling or reflection to help users process and retain information.

### Psychological Rationale
- Emotional connection to content increases recall.
- Habit formation is critical for long-term benefit; app should encourage daily or frequent use.
- Reducing anxiety around forgetfulness by providing a reliable, non-judgmental tool.

### Questions for Further Design
- Should the app include mood or stress tracking to correlate with memory performance?
- Would users benefit from guided onboarding or tutorials?
- Should there be options for peer support or professional guidance?
# Memory Palace App

This project is a cross-platform memory palace application with the following structure:

- **web/**: Web application frontend
- **android/**: Android mobile application
- **ios/**: iOS mobile application
- **api/**: Common web API for all platforms
- **shared/**: Shared resources, models, or logic

This README will be updated with high-level requirements and design decisions as the project evolves.

## Answers to Expert Questions (User Decisions)

- Reminders and spaced repetition: Yes, include these features.
- Medical privacy features: Yes, allow users to mark cards as private and add extra protection.
- Usage tracking: Yes, but only with user opt-in and ability to disable reminders.
- Mood/stress tracking: Yes, include this feature.
- Guided onboarding/tutorials: Yes, provide for new users.
- Peer support/professional guidance: Maybe, for future plans after basics are covered.
- Reminders integration: Can be an option, but app should handle natively as well.
- Voice interaction languages: Start with English, plan for more languages; system should be adaptable.
- Offline functionality: Yes, all core features should work offline; only sync may require network.
- Sync reminders/notifications: Yes, sync across devices.
- Third-party services: Use free/open source options; Google Drive for backup with user login.
- Scalability: Target 10k users initially, design for 100k, 1m+.
- Collaborative map features: Can be added, with privacy warnings.
- Visual styles: Start with one, allow switching; data storage should be adaptable.
- AI suggestions for clusters/tags: Yes.
- Visualization rendering: Use web views for consistency and maintainability.
- AI clustering requirements: Yes, support explainability and user override.
- Secure sharing: Yes, allow sharing with encryption and privacy warnings.
- Compliance: Ensure GDPR compliance by default; add more as needed.
- Anonymity/pseudonymity: Yes, allow use without personal info or with nicknames.
- Import/export: Yes, support for other platforms.
- Multimedia formats: Support all (images, audio, video, PDFs, etc.).
- Templates: Yes, provide for common card types.
- Milestones/goals: MVP in one week, major release in one month.
- Feedback: Collect via in-app forms and app store reviews.
- Target audience: Anyone with memory challenges; expand to categories later.


## Expert Insights: Neurologist Perspective

### Target Users
- Individuals with forgetfulness due to age, ADHD, or difficulty converting short-term to long-term memory.

### Design Considerations
- The app should support rapid storage and retrieval of information, focusing on:
	- Keyword and sentence-based search, including fuzzy matching for inexact queries.
	- Flash card format: topic on the front, summary on the back, with expandable details (related cards, images, videos, audio, links).
	- Quick access: Users should retrieve context within seconds, suitable for high-pressure situations (e.g., meetings).
	- Support for both text and audio/image-based search in future versions.
	- Option to search the internet for additional context.

### Neurological Rationale
- Memory aids should minimize cognitive load and maximize retrieval cues.
- Visual, auditory, and semantic associations can help users recall information more effectively.
- The app should be forgiving of imprecise recall and offer multiple pathways to find stored memories.

### Questions for Further Design
- Should the app include reminders or spaced repetition to reinforce memory?
- Is there a need for medical privacy features (e.g., for sensitive notes)?
- Should the app track usage patterns to suggest improvements or personalized retrieval strategies?
