# Reality AI Internship Contributions

## Overview
This repository highlights my contributions during my internship at Reality AI. I played key roles in the development of the **Marvel Platform**, an open-source teaching assistant AI project. My responsibilities included leading and co-leading the development of significant features such as the **Tool History Page** and **Onboarding** systems. All my contributions were successfully merged into the main repository, demonstrating my ability to deliver production-quality code and collaborate effectively in a team environment.

---

## Contributions

### Tool History Page
- **Role**: Team Lead
- **Description**: Designed and implemented the **Tool History Page**, enabling users to view, categorize, and interact with their tool usage history.
  - Created components such as `ToolHistoryCard`, `ToolOutputHistoryDrawer`, and `ToolHistoryListingContainer` to display categorized historical data by date (Week, Month, Year, Older).
  - Built advanced features like exporting data to CSV and a copy-to-clipboard functionality.
  - Developed a skeleton loader to improve user experience during data fetching.
  - Designed and implemented the backend integration to fetch and categorize history data using Firebase Firestore and Redux.
- **Repository Impact**: PR [#60](https://github.com/marvelai-org/marvel-platform/pull/60) was merged into the main repository.

### Onboarding System
- **Role**: Co-Lead
- **Description**: Co-led the development of the **Onboarding System**, enhancing user engagement and platform accessibility.
  - Built the **Profile Setup Form** using `react-hook-form` for collecting user data, with regex validation for form fields.
  - Implemented routing logic to direct users to onboarding based on Firestore status flags.
  - Integrated Firebase Storage to handle profile image uploads only upon completing onboarding.
  - Focused on a polished, Figma-inspired UI for a modern user experience.
- **Repository Impact**: PR [#105](https://github.com/marvelai-org/marvel-platform/pull/105) is currently pending review.

---

## Project Structure
- **frontend/**: Contains Next.js components for the platform, including:
  - **ToolHistory Components**: Displays and manages historical tool usage data.
  - **Onboarding Components**: Manages onboarding workflows, including the profile setup form and progress tracking.
- **functions/**: Houses Firebase Functions for backend operations:
  - `controller/`: Contains logic for user management and session handling.

---

## Merged Pull Requests
- **Tool History Page PR**: Merged into the main repository ([#60](https://github.com/marvelai-org/marvel-platform/pull/60)).
- **Onboarding PR**: Currently pending review ([#105](https://github.com/marvelai-org/marvel-platform/pull/105)).

---

## Technologies Used
- **Frontend**: React, Next.js, JavaScript.
- **Backend**: Firebase Functions, Firestore.
- **Development Tools**: Git, Firebase Emulator Suite, VSCode.

---

## Acknowledgments
This repository focuses on my individual contributions during my internship. For the complete project and additional details, visit the original [Marvel Platform repository](https://github.com/marvelai-org/marvel-platform).

---

## License
This project is part of the Radical AI open-source initiative and is licensed under the MIT License.
