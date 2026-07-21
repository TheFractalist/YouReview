# Development Setup

## Prerequisites

- **Android Studio** (Hedgehog or later)
- **JDK 11+**
- **Gradle** (included via wrapper)
- **Git**

## Environment Setup

### 1. Clone & Open

```bash
git clone https://github.com/[your-username]/YouReview.git
cd YouReview
```

Open in Android Studio:
- File → Open → Select project directory
- Android Studio will auto-detect and download dependencies

### 2. Configure Local Settings (if needed)

Create `local.properties`:
```properties
sdk.dir=/path/to/android/sdk
```

### 3. Build & Run

Build the project:
```bash
./gradlew build
```

Run on emulator or connected device:
```bash
./gradlew installDebug
adb shell am start -n com.yourcompany.youreview/.ui.MainActivity
```

## Development Workflow

### Build Commands

```bash
./gradlew build              # Full build
./gradlew assemble           # Assemble debug & release APKs
./gradlew clean              # Clean build artifacts
./gradlew lint               # Run Android lint checks
```

### Testing

```bash
./gradlew test               # Unit tests
./gradlew connectedAndroidTest  # Instrumented tests
./gradlew testDebug          # Debug variant tests only
```

### Debugging

- Use logcat in Android Studio to view logs
- Set breakpoints and run with debugger
- Use Profiler for performance analysis

## Gradle Properties

Edit `gradle.properties` to configure:
- JVM arguments
- Compilation settings
- SDK versions
