# AGENTS Instructions

This repository hosts the Loop Habit Tracker Android application and library modules.

## Build & Test

- **Unit tests** should pass. Run `./gradlew test` or `./build.sh build`.
- **Code style** follows ktlint. Run `./gradlew ktlintCheck` to ensure formatting.
- **Instrumented tests** exist but require an Android emulator. Use `./build.sh android-tests <API>` only if necessary.

## Contributing

- New development takes place in the `dev` branch. Submit pull requests against `dev`.
- Kotlin is preferred for new classes. Follow the style of nearby files for legacy Java code.
- Keep pull requests small and focused.

