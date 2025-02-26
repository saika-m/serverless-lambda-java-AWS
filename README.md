# Serverless Lambda Java AWS

This project demonstrates a serverless architecture using **Java 8**, **AWS Lambda**, and **Amazon DynamoDB**. It serves as a reference implementation for building and deploying Java-based serverless applications on AWS.

## Features

* 🚀 **AWS Lambda**: Run code without provisioning or managing servers.
* 📊 **Amazon DynamoDB**: Fully managed NoSQL database service.
* 🔄 **Serverless Framework**: Simplifies deployment and management of serverless applications.
* 🛠️ **Gradle Build System**: Efficient project build and dependency management.
* 📝 **Infrastructure as Code**: Utilizes `serverless.yml` for resource configuration.
* 🎯 **Sample CRUD Operations**: Demonstrates Create, Read, Update, and Delete functionalities.
* ⚡ **Java 8 Compatibility**: Ensures broad compatibility and stability.

## Quick Start

### Prerequisites

Before deploying this application, ensure you have the following installed:

* **Java 8**: Development environment for building the application.
* **Node.js and npm**: Required for the Serverless Framework.
* **Serverless Framework**: CLI tool for deploying serverless applications.
* **AWS CLI**: Command-line tool for interacting with AWS services.

### Installation

1. **Clone the repository**:

```bash
git clone https://github.com/saika-m/serverless-lambda-java-AWS.git
cd serverless-lambda-java-AWS
```

2. **Install Serverless Framework** (if not already installed):

```bash
npm install -g serverless
```

3. **Deploy the application**:

```bash
serverless deploy
```

This command will package and deploy your application to AWS, setting up the necessary resources such as Lambda functions and DynamoDB tables.

## Project Structure

The project includes the following key files and directories:

* `src/main`: Contains the Java source code for the Lambda functions.
* `serverless.yml`: Defines the Serverless Framework configuration, specifying functions, resources, and plugins.
* `build.gradle`: Build configuration file for managing dependencies and packaging the application.

## Available Commands

* **Deploy the service**:

```bash
serverless deploy
```

* **Invoke a function locally**:

```bash
serverless invoke local --function <function-name>
```

* **Fetch the logs**:

```bash
serverless logs --function <function-name>
```

* **Remove the service**:

```bash
serverless remove
```

## Metrics and Monitoring

Monitoring and logging are crucial for serverless applications. AWS provides several tools to assist with this:

* **AWS CloudWatch**: Collects and visualizes operational data, including logs and metrics.
* **AWS X-Ray**: Helps with analyzing and debugging distributed applications.

Ensure that your AWS account has the necessary permissions to access these services.

## Development

### Running Tests

Implement unit and integration tests to ensure code quality. Use testing frameworks compatible with Java, such as JUnit.

```bash
# Run all tests
./gradlew test
```

### Code Style

Maintain consistent code formatting using tools like Checkstyle.

```bash
# Check code style
./gradlew check
```

## License

This project is licensed under the Apache 2.0 License. See the [LICENSE](LICENSE) file for details.

## Tags

serverless, AWS Lambda, Java 8, DynamoDB, Serverless Framework, Gradle, CRUD Operations, NoSQL, cloud computing, infrastructure as code
