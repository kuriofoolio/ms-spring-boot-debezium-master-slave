# ms-spring-boot-debezium-master-slave

This project  is a Spring Boot application that uses Debezium to replicate changes from a Postgres database to
the application layer

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The proposed application aims to integrate Debezium into a Spring project to enable real-time streaming of data changes from a database. By leveraging Debezium's powerful capabilities, the application will capture database events such as inserts, updates, and deletes, and stream them to downstream systems for further processing or analysis.

## Features

- Real-time capture of database changes using Debezium.
- Support for PostgreSQL DB. 
- Seamless integration with Spring Boot framework for easy development and deployment.
- Customizable event handling and routing based on specific business requirements.
- Scalable architecture to handle large volumes of data changes efficiently.
- Detailed monitoring and error handling mechanisms to ensure data integrity and reliability.

## Installation

To install and set up the project, follow these steps:

1. Clone the project repository from GitHub.

    ```git clone https://github.com/kuriofoolio/ms-spring-boot-debezium-master-slave.git```


2. Configure the Docker Image details in the docker-compose.yml file.

3. Run the docker-compose.yml file

    ```docker-compose up -d```

4. Build the project using Maven or Gradle.

5. Run the application.

6. For more detailed instructions, refer to [Debezium Configuration](
https://safaricom.atlassian.net/wiki/spaces/IPE/pages/3102998535/Debezium+Configuration)


## Usage

To use the project:

1. Start the application, ensuring that the database is running and accessible.
2. Monitor the logs to verify successful initialization and connection to the database.
3. Perform data operations (inserts, updates, deletes) in the connected database.
4. Observe the streaming of data changes in real-time through the application.

For advanced usage and customization, refer to [Debezium Postman Collection](docs/ms-spring-boot-debezium.postman_collection.json.pdf)

## Contributing

Contributions to the project are welcome! If you encounter any issues or have suggestions for improvements, please open an issue on GitHub. To contribute code changes, fork the repository, make your changes, and submit a pull request.

Before contributing, please review the contribution guidelines outlined in the project repository.

## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute the code for both commercial and non-commercial purposes.
