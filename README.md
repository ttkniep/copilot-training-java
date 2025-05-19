# Copilot Training Sample Code (Java)

## Prerequisites

- Java 17+
- Gradle **or** Maven
- A current version of VS Code and the following extensions:
  - Extension Pack for Java (Microsoft)
  - GitHub Copilot
  - GitHub Copilot Chat
  - AsciiDoc (asciidoctor) -- optional 
  - PlantUML (jebbs) -- optional, just for UML diagrams

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/ttkniep/copilot-training-java.git
   cd copilot-training-java
   ```

3. Install dependencies (**may require proxy settings**):
    If using Gradle:
    ```bash
    ./gradlew build
    ```
    or if using Maven:
    ```bash
    mvn install
    ```

4. Run the tests:
    If using Gradle:
    ```bash
    ./gradlew test
    ```
    or if using Maven:
    ```bash
    mvn test
    ```

## Project Structure
- `telemetry-processor/src/main`: Contains the implementation.
- `telemetry-processor/src/test`: Contains unit tests.
