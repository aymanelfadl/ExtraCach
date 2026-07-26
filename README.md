# Extra Cash App

A cross-platform mobile app for tracking and managing personal income and expenses. Built with React Native and Firebase, Extra Cash gives users a clear picture of where their money goes — log transactions in seconds, categorize spending, and see monthly trends at a glance.

Developed end-to-end as a startup product, following Agile practices and UI/UX design principles from wireframes through to release.

---

## Features

- **Transaction tracking** — Log income and expenses with amount, category, date, and notes
- **Categories** — Organize spending into custom or preset categories
- **Balance overview** — Real-time totals for income, expenses, and net balance
- **Reports & insights** — Monthly and category-level breakdowns with charts
- **Authentication** — Secure email/password sign-up and login via Firebase Auth
- **Cloud sync** — Data persisted to Firestore, so it follows the user across devices
- **Offline support** — Records can be created offline and sync when connectivity returns
- **Responsive UI** — Designed mobile-first with accessible touch targets and consistent visual hierarchy

## Tech Stack

| Layer | Technology |
|---|---|
| Framework | React Native |
| Language | JavaScript / TypeScript |
| Navigation | React Navigation |
| State | Context API / Redux |
| Backend | Firebase (Authentication, Cloud Firestore, Storage) |
| Charts | react-native-chart-kit |
| Design | Figma (wireframes, prototypes, design system) |

## Getting Started

### Prerequisites

- Node.js 18+
- npm or Yarn
- A Firebase project
- Android Studio and/or Xcode (for native builds), or Expo Go for quick testing

### Installation

```bash
git clone https://github.com/your-username/extra-cash-app.git
cd extra-cash-app
npm install
```

### Firebase Setup

1. Create a project at the [Firebase Console](https://console.firebase.google.com).
2. Enable **Authentication** → Email/Password.
3. Create a **Cloud Firestore** database.
4. Register an app and copy the config values.
5. Create a `.env` file in the project root:

```env
FIREBASE_API_KEY=your_api_key
FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
FIREBASE_PROJECT_ID=your_project_id
FIREBASE_STORAGE_BUCKET=your_project.appspot.com
FIREBASE_MESSAGING_SENDER_ID=your_sender_id
FIREBASE_APP_ID=your_app_id
```

> `.env` is gitignored. Never commit real credentials.

### Running the App

```bash
npm start          # start the Metro bundler
npm run android    # run on Android emulator or device
npm run ios        # run on iOS simulator (macOS only)
```

---

## Development Approach

- **Agile** — Work broken into short iterations with a prioritized backlog, sprint planning, and review at the end of each cycle
- **UI/UX process** — User flows and wireframes in Figma, then interactive prototypes, then implementation against a shared design system of color, type, and spacing tokens
- **Iterative feedback** — Usability testing on early builds fed back into layout and copy changes before feature work continued

## Author

**Aelfadl** — [GitHub](https://github.com/aymanelfadl) · [LinkedIn](https://linkedin.com/in/ayman-elfadl)
