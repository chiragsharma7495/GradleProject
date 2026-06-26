GradleProject

This is a simple Gradle demo project showing basic Gradle project structure and common tasks. It contains sample source code and a Gradle wrapper so builds are reproducible across machines.

Getting started

- On Windows: use gradlew.bat
- On macOS/Linux: use ./gradlew

Common Gradle commands

- Build the project:    ./gradlew build
- Run tests:            ./gradlew test
- List tasks:           ./gradlew tasks
- Clean build outputs:  ./gradlew clean
- Run (if an application): ./gradlew run

Notes

- Prefer the Gradle wrapper (gradlew) so contributors use the correct Gradle version.
- For CI, run: ./gradlew build --no-daemon --console=plain

