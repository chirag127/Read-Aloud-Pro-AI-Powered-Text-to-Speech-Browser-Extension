# Contributing to SpeechFlow-AI-Powered-Text-to-Speech-Browser-Extension

Thank you for considering contributing to SpeechFlow! We aim to foster a collaborative environment to build the best AI-powered text-to-speech browser extension.

## 1. Code of Conduct

This project adheres to the Contributor Covenant Code of Conduct. By participating, you are expected to uphold this code. Please report any unacceptable behavior to `chirag127@example.com`.

## 2. How to Contribute

### 2.1 Reporting Bugs

If you find a bug, please check if it has already been reported. If not, create a new issue on GitHub. Provide a clear and concise title, a detailed description of the bug, steps to reproduce it, and any relevant environment information (browser version, OS, etc.). Use the `Bug Report` issue template if available.

### 2.2 Suggesting Enhancements

We welcome feature requests and suggestions! Please create a new issue on GitHub and use the `Feature Request` template. Clearly explain the proposed enhancement and the problem it aims to solve.

### 2.3 Contributing Code

We are excited to accept your contributions! Here's the workflow:

1.  **Fork the Repository:** Create your own fork of the `chirag127/SpeechFlow-AI-Powered-Text-to-Speech-Browser-Extension` repository.
2.  **Clone Your Fork:** `git clone https://github.com/chirag127/SpeechFlow-AI-Powered-Text-to-Speech-Browser-Extension.git && cd SpeechFlow-AI-Powered-Text-to-Speech-Browser-Extension`
3.  **Set Up Development Environment:** Follow the setup instructions in the `README.md` to get the project running locally. This typically involves installing dependencies (e.g., `npm install` or `yarn install`) and setting up any necessary build tools.
4.  **Create a New Branch:** Make your changes in a new branch. Give it a descriptive name (e.g., `feature/add-voice-selection` or `fix/audio-playback-bug`).
    bash
    git checkout -b my-contribution-branch
    
5.  **Make Your Changes:** Implement your feature or fix. Ensure your code adheres to the project's coding standards, linting rules (e.g., Biome, ESLint), and formatting.
6.  **Test Your Changes:** Write or update tests to cover your changes. Run the test suite (`npm test` or equivalent) to ensure all tests pass.
7.  **Commit Your Changes:** Commit your work with clear, descriptive messages.
    bash
    git commit -m "feat: Add natural-sounding voice selection" 
    
8.  **Push to Your Fork:** Push your branch to your fork on GitHub.
    bash
    git push origin my-contribution-branch
    
9.  **Open a Pull Request:** Go to the original repository (`chirag127/SpeechFlow-AI-Powered-Text-to-Speech-Browser-Extension`) and open a new Pull Request from your branch.
    *   **Title:** Use a concise and descriptive title.
    *   **Description:** Explain your changes, the problem they solve, and any relevant details. Link to any related issues.

### 2.4 Pull Request Process

*   **Review:** Your Pull Request will be reviewed by the maintainers. Please be patient and responsive to feedback.
*   **CI/CD:** Automated checks (linting, testing, building) will run on your PR. Ensure all checks pass before merging.
*   **Squash and Merge:** Once approved, your changes will be squashed and merged into the main branch.

## 3. Development Guidelines

*   **Technology Stack:** This project uses **TypeScript**, **Vite** (for building), **TailwindCSS v4** (for styling), and **Tauri v2** (for the browser extension core). Linting and formatting are handled by **Biome**. Testing is performed using **Vitest** (unit) and **Playwright** (E2E).
*   **Architecture:** We follow the **Feature-Sliced Design (FSD)** pattern for a scalable and maintainable architecture.
*   **Code Style:** Adhere to the established code style and linting rules enforced by Biome. Run `npx @biomejs/biome lint --apply` and `npx @biomejs/biome format --apply` locally before committing.
*   **Testing:** All new features must include comprehensive unit and/or integration tests. Aim for high code coverage.
*   **Documentation:** Keep code comments concise and up-to-date. Update relevant documentation files (like `README.md`) if your changes impact setup, usage, or architecture.

## 4. Finding Ideas to Work On

*   **Good First Issues:** Look for issues labeled `good first issue`.
*   **Help Wanted:** Issues labeled `help wanted` are areas where we'd particularly appreciate contributions.
*   **Under-Resourced Areas:** Identify areas in the codebase or documentation that could benefit from improvements.

We look forward to your contributions!
