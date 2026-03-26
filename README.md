# CypRide
Cyprus Ride - Sharing Car Community App
---------------------------------------

CypRide — Smart Ride-Sharing for Cyprus 🇨🇾 — is a privacy-focused, open-source ride-sharing application built exclusively for Cyprus with Flutter. Designed to fill the mobility gap in a market where major international ride-hailing services don't operate, CypRide empowers Cypriots to share journeys safely, affordably, and locally.

Dual-Role Ride Marketplace
- Riders: Offer available seats in your vehicle for specific routes and times
- Guests: Find and join rides matching your destination and schedule
- Smart filtering between ride types with intuitive tab navigation

Privacy-First Architecture
- Location data is only collected during active rides — never stored or tracked in the background
- End-to-end encrypted chat between riders and guests
- Minimal data collection policy compliant with GDPR standards
 
Real-Time Features
- Live ride discovery with departure time filtering
- Search rides by origin/destination locations
- Favorites system for saving preferred routes (offline-capable via Hive)
- Real-time availability status ("active rides only" filtering)

User Experience
- Beautiful onboarding flow explaining the privacy model upfront
- Dark/light theme support with adaptive UI
- Responsive design (mobile-first with desktop testing support)
- Native splash screen for optimal startup performance
- Intuitive navigation with drawer menu (Profile, Tile, Favorites, Chat, Settings, FAQ, Contact)

Technical Foundation
- Built with Flutter for cross-platform consistency (iOS/Android)
- Firebase backend (Authentication, Firestore) with offline resilience
- GoRouter for type-safe navigation
- Hive for local favorites storage (no cloud dependency)
- Modular architecture for easy maintenance and contribution
