# Contributing to SignBridge AI

Thank you for your interest in contributing to **SignBridge AI**! We welcome contributions from developers, accessibility researchers, sign language experts, and UI/UX designers to help improve real-time communication accessibility for the deaf and hard-of-hearing community.

## Code of Conduct

By participating in this project, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md). Please treat all contributors with respect, empathy, and constructive communication.

## How to Contribute

### 1. Reporting Bugs
- Use GitHub Issues to submit bug reports.
- Include browser version (Chrome, Edge, Safari, Firefox), OS, and camera specifications.
- Provide clear steps to reproduce, expected behavior, and screenshots or console logs if applicable.

### 2. Suggesting Gestures & Feature Enhancements
- If proposing new Indian Sign Language (ISL) or American Sign Language (ASL) recognition models, explain the hand geometry and cultural context.
- Discuss significant architectural changes in an issue before submitting a PR.

### 3. Development Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/saivishal89/Signlangugage.git
   cd Signlangugage
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the Vite local development server:
   ```bash
   npm run dev
   ```
4. Verify TypeScript and production build:
   ```bash
   npm run build
   ```

### 4. Pull Request Guidelines
- Branch naming convention: `feat/feature-name`, `fix/bug-fix-name`, or `docs/doc-update`.
- Ensure `npm run build` passes with zero TypeScript warnings or errors.
- Keep commits atomic, clean, and follow conventional commit messages (`feat:`, `fix:`, `docs:`, `ci:`, `refactor:`).
- Open the PR against the `main` branch with a clear description of changes made.

## Technology Stack
- **Frontend**: React 18 with TypeScript 5
- **Vision Pipeline**: Google MediaPipe Tasks Vision (`@mediapipe/tasks-vision`)
- **Speech Engine**: Web Speech API (`SpeechSynthesisUtterance`)
- **Styling**: Modern responsive CSS with custom glassmorphism design tokens
- **Build Tool**: Vite 6

Thank you for making accessibility tools accessible to everyone! 🤟
