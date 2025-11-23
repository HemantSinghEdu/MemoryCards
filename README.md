
# Memory Cards App

**Purpose:**
Memory Cards App is a cross-platform application designed to help users with memory challenges (such as forgetfulness, ADHD, or age-related issues) quickly store, organize, and retrieve their memories. The app uses flash cards, visual maps, reminders, and cognitive games to improve attention and retention, while ensuring privacy and local data storage.

**Project Structure:**
- **web/**: Web application frontend
- **android/**: Android mobile application
- **ios/**: iOS mobile application
- **api/**: Common web API for all platforms
- **shared/**: Shared resources, models, or logic

## High-Level Requirements & Design Decisions

### Key Decisions
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
- Games and interactive tutorials to help users improve attention and retention capabilities (cognitive exercises, memory games, step-by-step guides).

### Data Storage & Privacy Requirements
- All user data is stored locally on the user's mobile device; no data is stored on project servers.
- For backup and cross-device access, use user-controlled cloud storage (e.g., Google Drive, iCloud, or other preferred providers), similar to WhatsApp.
- The web version should sync data in real-time across devices without storing any data on project servers, emulating WhatsApp Web behavior.
- Prioritize open source and free libraries for all features and integrations.

### Expert Insights (Summary)
- Neurologist: Rapid storage/retrieval, fuzzy search, flash cards, quick access, multimedia, internet search.
- Psychologist: Positive reinforcement, gamification, personalization, feedback, habit formation, reduce anxiety.
- UI/UX: Speed/simplicity, text/voice interaction, accessible reminders, readable design, easy navigation, customizable UI.
- System Architect: Modular, scalable, fast search, voice/NLP, reliable notifications, secure sync, multimedia support, offline support, robust error handling.
- Accessibility: Visual map/graph, zoom/deep navigation, AI/user categorization, accessible map, alternative views, customization, private visualization.
- Developer: .NET and JavaScript/jQuery, responsive web design, avoid native coding, simple/maintainable solutions, interactive graph libraries, tagging, hierarchical categorization, voice/text input, cross-platform, performance.
- Data Privacy/Security: Encrypt data, secure authentication, privacy controls, regular audits, GDPR compliance, clear policies, export/deletion options.
- Content: Concise topics, expandable details, tagging, multimedia, fuzzy/semantic search, suggestions, memory chains.
- Product Manager: Align expert input, prioritize features, iterative development, success metrics, user research, onboarding, analytics, feedback.


