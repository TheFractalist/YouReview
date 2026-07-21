# YouReview Architecture

## Overview

YouReview is built using modern Android development practices with Kotlin, AndroidX, and Material Design 3.

## Project Structure

### Modules
- **app** — Main application module (UI, business logic, data layer)

### Package Structure

```
com.yourcompany.youreview/
├── ui/                          # UI layer (Activities, Fragments, ViewModels)
│   └── MainActivity.kt
├── data/                        # Data layer (Repositories, API clients, local DB)
├── domain/                      # Domain/business logic layer
├── utils/                       # Utility classes and helpers
└── App.kt                       # Application class
```

## Architecture Pattern

We follow the **MVVM (Model-View-ViewModel)** pattern with:
- **View** — Activities and Fragments
- **ViewModel** — Manages UI state and business logic
- **Repository** — Abstracts data sources (API, local DB)
- **Model** — Data classes representing domain entities

## Technology Stack

- **Language** — Kotlin
- **UI Framework** — AndroidX, Material Components
- **Architecture** — MVVM with LiveData/StateFlow
- **Testing** — JUnit 4, Espresso
- **Build System** — Gradle

## Guidelines

1. **Naming** — Use descriptive names following Kotlin conventions
2. **Comments** — Explain *why*, not *what* — well-named code is self-documenting
3. **Testing** — Write tests for business logic; UI tests for critical flows
4. **Dependencies** — Keep minimal; prefer AndroidX libraries
