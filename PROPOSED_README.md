# SpeechFlow: AI-Powered Text-to-Speech Browser Extension

[![Build Status](https://img.shields.io/github/actions/workflow/user/chirag127/SpeechFlow-AI-Powered-Text-to-Speech-Browser-Extension/ci.yml?style=flat-square)](https://github.com/chirag127/SpeechFlow-AI-Powered-Text-to-Speech-Browser-Extension/actions/workflows/ci.yml)
[![Code Coverage](https://img.shields.io/codecov/c/github/chirag127/SpeechFlow-AI-Powered-Text-to-Speech-Browser-Extension?style=flat-square)](https://codecov.io/gh/chirag127/SpeechFlow-AI-Powered-Text-to-Speech-Browser-Extension)
[![Tech Stack](https://img.shields.io/badge/tech-TypeScript%2CVite%2CRust%2CWebExtensions-blue?style=flat-square)](https://github.com/chirag127/SpeechFlow-AI-Powered-Text-to-Speech-Browser-Extension)
[![License](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgreen?style=flat-square)](https://creativecommons.org/licenses/by-nc/4.0/)
[![GitHub Stars](https://img.shields.io/github/stars/chirag127/SpeechFlow-AI-Powered-Text-to-Speech-Browser-Extension?style=flat-square)](https://github.com/chirag127/SpeechFlow-AI-Powered-Text-to-Speech-Browser-Extension)

**Effortlessly transform any web page into natural-sounding audio with SpeechFlow, enhancing productivity and accessibility for hands-free listening.**

## 🚀 Project Overview

SpeechFlow is an advanced AI-powered browser extension designed to convert on-page text into speech. Leveraging cutting-edge AI models, it provides a seamless and accessible way for users to consume web content, making it ideal for multitasking, learning, or users with visual impairments.

## 🌳 Architecture

mermaid
graph TD
    A[Browser Extension] --> B{Content Script}
    B --> C{Background Script}
    C --> D[AI Text-to-Speech API]
    D --> E[Generated Audio]
    E --> C
    C --> B
    B --> F[User Interface (Popup/Options)]


## 📚 Table of Contents

*   [🚀 Project Overview](#-project-overview)
*   [🌳 Architecture](#-architecture)
*   [⭐ Key Features](#-key-features)
*   [💡 AI Agent Directives](#-ai-agent-directives)
*   [🛠️ Development & Setup](#-development--setup)
*   [🧪 Testing](#-testing)
*   [📄 License](#-license)
*   [🌟 Community & Contribution](#-community--contribution)

## ⭐ Key Features

*   **AI-Powered Natural Voices:** Utilizes advanced AI for highly realistic and human-like speech output.
*   **Cross-Browser Compatibility:** Supports Chrome, Firefox, and Edge.
*   **Selective Reading:** Highlight text for focused listening.
*   **Customizable Playback:** Adjust reading speed, pitch, and voice selection.
*   **Accessibility Focus:** Enhances web content accessibility for all users.
*   **Productivity Boost:** Enables hands-free content consumption.

<details>
<summary>🤖 AI Agent Directives (December 2025 Standard)</summary>

## 🤖 AI Agent Directives

This repository adheres to the Apex Technical Authority's AI Agent Directives for late 2025 standards, ensuring high-velocity, zero-defect, and future-proof development.

### 1. Identity & Prime Directive

*   **Role:** Apex Technical Authority & Elite Architect.
*   **Prime Directive:** Execute with absolute precision, enforce FAANG-level standards, and uphold the wisdom of "Managing the Unmanageable." **Output Standard:** EXECUTION-ONLY. No plans, only executed code, updated docs, and applied fixes.
*   **Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

### 2. Input Processing & Cognition

*   **SPEECH-TO-TEXT INTERPRETATION PROTOCOL:**
    *   **Context:** User inputs may contain phonetic errors (homophones, typos).
    *   **Semantic Correction:** **STRICTLY FORBIDDEN** from executing literal typos. You must **INFER** technical intent based on the project context.
    *   **Logic Anchor:** Treat the `README.md` as the **Single Source of Truth (SSOT)**.
*   **MANDATORY MCP INSTRUMENTATION:**
    *   **No Guessing:** Do not hallucinate APIs.
    *   **Research First:** Use `linkup`/`brave` to search for **December 2025 Industry Standards**, **Security Threats**, and **2026 UI Trends**.
    *   **Validation:** Use `docfork` to verify *every* external API signature.
    *   **Reasoning:** Engage `clear-thought-two` to architect complex flows *before* writing code.

### 3. Context-Aware Apex Tech Stacks (Late 2025 Standards)

*   **PROJECT TYPE:** Web Extension / Frontend Application
*   **STACK:**
    *   **Language:** TypeScript 6.x (Strict Mode Enabled).
    *   **Build Tool:** Vite 7 (Utilizing Rolldown engine).
    *   **Framework/Platform:** WebExtensions API standard.
    *   **Runtime:** Potentially bundled with native components via Tauri v2.x (if applicable for desktop applications, though primary focus is browser extension).
    *   **State Management:** Signals (Standardized).
    *   **Styling:** Tailwind CSS v4.
*   **ARCHITECTURE:**
    *   **Pattern:** Feature-Sliced Design (FSD) for modularity and scalability.
    *   **Structure:** Clear separation of concerns between content scripts, background scripts, popup UI, and options pages.

### 4. Linting, Formatting, & Testing (Apex Toolchain)

*   **Linter & Formatter:** Biome 2.x (Ultra-fast, integrated linter and formatter).
*   **Unit Testing:** Vitest 2.x (Fast, Jest-compatible unit test runner).
*   **End-to-End (E2E) Testing:** Playwright 2.x (Robust E2E testing framework for browsers).

### 5. Security & Compliance

*   **Dependency Scanning:** Automated scans via GitHub Dependabot or equivalent.
*   **Vulnerability Management:** Strict adherence to the `.github/SECURITY.md` guidelines. Regular review of AI model outputs and API interactions for potential security risks.
*   **Data Privacy:** Compliance with GDPR, CCPA, and other relevant privacy regulations. Minimize user data collection and ensure secure handling of any required data.

### 6. Deployment & CI/CD

*   **CI/CD Pipeline:** `.github/workflows/ci.yml` configured for automated builds, linting, testing, and packaging on every push and pull request.
*   **Deployment Targets:** Automated builds for Chrome Web Store, Firefox Add-ons, and Edge Add-ons.

### 7. Documentation & Maintainability

*   **Code Comments:** JSDoc/TSDoc for public APIs and complex logic.
*   **README:** Comprehensive `README.md` as the project's SSOT.
*   **Contribution:** Clear guidelines in `.github/CONTRIBUTING.md`.

### 8. Verification Commands

*   **Setup:**
    bash
    git clone https://github.com/chirag127/SpeechFlow-AI-Powered-Text-to-Speech-Browser-Extension.git
    cd SpeechFlow-AI-Powered-Text-to-Speech-Browser-Extension
    uv install
    
*   **Lint & Format:**
    bash
    biome lint --apply
    biome format --write
    
*   **Unit Tests:**
    bash
    vitest run
    
*   **E2E Tests:**
    bash
    npx playwright test
    
*   **Build:**
    bash
    vite build
    

</details>

## 🛠️ Development & Setup

Follow these steps to set up the development environment:

1.  **Clone the Repository:**
    bash
    git clone https://github.com/chirag127/SpeechFlow-AI-Powered-Text-to-Speech-Browser-Extension.git
    cd SpeechFlow-AI-Powered-Text-to-Speech-Browser-Extension
    

2.  **Install Dependencies:**
    This project uses `uv` for efficient package management.
    bash
    uv install
    

3.  **Run Development Server:**
    Vite provides a fast development server with Hot Module Replacement (HMR).
    bash
    npm run dev
    
    Or using uv:
    bash
    uv run dev
    

## 🧪 Testing

This project employs a robust testing strategy:

*   **Linting & Formatting:** Ensure code quality and consistency.
    bash
    biome lint --apply
    biome format --write
    
*   **Unit Testing:** Run unit tests using Vitest.
    bash
    vitest run
    
*   **End-to-End (E2E) Testing:** Execute E2E tests with Playwright.
    bash
    npx playwright test
    

## 📄 License

This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)**.

See the `LICENSE` file for more details.

## 🌟 Community & Contribution

We welcome contributions to SpeechFlow! Please refer to `.github/CONTRIBUTING.md` for guidelines on how to submit bug reports, feature requests, and pull requests. To encourage community engagement, please consider starring ⭐ this repository if you find it useful!

[Back to Top](#speechflow-ai-powered-text-to-speech-browser-extension)
