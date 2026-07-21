# YouReview

An Android application.

## Project Structure

```
YouReview/
├── app/                          # Main application module
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/            # Application source code
│   │   │   ├── res/             # Resources (layouts, strings, drawables)
│   │   │   └── AndroidManifest.xml
│   │   ├── test/                # Unit tests
│   │   └── androidTest/         # Instrumented tests
│   ├── build.gradle             # App-level build configuration
│   └── proguard-rules.pro        # ProGuard/R8 rules
├── gradle/                       # Gradle wrapper and scripts
├── build.gradle                  # Project-level build configuration
├── settings.gradle               # Gradle settings
├── gradle.properties             # Gradle properties
└── docs/                         # Documentation
```

## Getting Started

### Prerequisites
- Android Studio (latest)
- JDK 11 or higher
- Gradle (included via wrapper)

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/[your-username]/YouReview.git
   cd YouReview
   ```

2. Open in Android Studio:
   - File → Open → Select project directory
   - Android Studio will download necessary dependencies

3. Build the project:
   ```bash
   ./gradlew build
   ```

4. Run on emulator or device:
   ```bash
   ./gradlew installDebug
   ```

## Development

### Building
```bash
./gradlew build
```

### Running Tests
```bash
./gradlew test              # Unit tests
./gradlew connectedAndroidTest  # Instrumented tests
```

### Running the App
```bash
./gradlew run
```

## Documentation

See [docs/](docs/) for detailed documentation.

## License

[To be determined]
