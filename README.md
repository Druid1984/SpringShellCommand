
```markdown```
# Spring Shell Command Project

## Introduction
This project is a Spring Shell application designed to optimize disk space and provide various file and directory operations. It uses Spring Boot and Spring Shell to create an interactive shell environment.

## Features
- **Optimize Disk Space**: Deletes empty directories and old temporary files.
- **Analyze Disk Space**: Displays total, used, and free disk space.
- **List Files**: Lists files in a specified directory.
- **Delete File**: Deletes a specified file.
- **Create Directory**: Creates a new directory.

## Getting Started
### Prerequisites
- **Java 11**: Ensure you have Java 11 installed.
- **Maven**: Ensure you have Maven installed.

### Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git

Navigate to the Project Directory:
bash
cd your-repo-name

Build the Project:
bash
mvn clean install

Run the Application:
bash
mvn spring-boot:run

Usage
Available Commands
Optimize:
text
shell:> optimize --path C:/

This command optimizes disk space by deleting empty directories and old temporary files.
Analyze:
text
shell:> analyze --path C:/

This command analyzes disk space usage and displays total, used, and free space.
List Files:
text
shell:> list-files --path C:/

This command lists files in the specified directory.
Delete File:
text
shell:> delete-file --path C:/example.txt

This command deletes a specified file.
Create Directory:
text
shell:> create-directory --path C:/newdir

This command creates a new directory.
Contributing
Contributions are welcome. Please submit a pull request or open an issue for any suggestions or improvements.
License
This project is licensed under the Apache License 2.0.
Acknowledgments
Special thanks to the Spring Boot and Spring Shell communities for their support and resources.
Contact
For any questions or issues, please contact Your Name or open an issue on this repository.
Documentation
For more detailed documentation on Spring Shell and Spring Boot, refer to the official documentation:
Spring Shell Documentation
Spring Boot Documentation
Future Development
Planned future developments include adding more advanced file and directory operations and improving the user interface.
