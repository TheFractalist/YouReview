# Current State

- **Prototype/evidence:** Harness catalogued this root as `application` with status `active`.
- Current objective: YouReview/ ├── app/ # Main application module │ ├── src/ │ │ ├── main/ │ │ │ ├── java/ # Application source code │ │ │ ├── res/ # Resources (layouts, strings, drawables) │ │ │ └── AndroidManifest.xml │ │ ├── test/ # Unit tests │ │ └── androidTest/ # Instrumented tests │ ├── build.gradle # App-level build configuration │ └── proguard-rules.pro # ProGuard/R8 rules ├── gradle/ # Gradle wrapper and scripts ├── build.gradle # Project-level build configuration ├── settings.gradle # Gradle settings ├── gradle.properties # Gradle properties └── docs/ # Documentation
- Documentation source: readme-docs.
