# About

StackInfo is an API developed to provide detailed information about various development technologies, known as "stacks." This API allows users to access essential information about a particular stack, such as its name, identifying tag, and link to a representative image.

## Key Features

- **Stack Query:** Users can query the API by providing the name or identifier of the desired stack, such as "Angular," "React," "Vue," among others.
- **Detailed Information:** The API returns detailed information about the queried stack, including its name, identifying tag, and a link to a representative image.
- **Easy Integration:** The StackInfo API is designed to be easily integrated into different applications and services, providing quick and efficient access to information about various technology stacks.
- **Constant Updates:** The API is kept up-to-date with the latest information on the most popular technology stacks, ensuring users always have access to the most recent information.

## Benefits

- **Development Efficiency:** Software developers can save time and effort by quickly accessing information about different technology stacks, aiding decision-making during the development process.
- **Comprehensive Knowledge:** Both beginners and experienced professionals can benefit from easy access to detailed information about a wide variety of technology stacks.
- **Simplified Integration:** The StackInfo API can be easily integrated into various platforms and applications, providing a reliable source of information about technology stacks.

## Use Cases

- **Software Development:** Software developers can use the API to quickly obtain information about different technology stacks when starting new projects or evaluating alternative technologies.
- **Technology Education:** Educational institutions and students can leverage the API to access up-to-date information about various technology stacks, enriching learning and understanding of industry trends.

## Technologies Used

Node.js, Express.js, MongoDB (or another database of your choice), RESTful API.

# How It Works

## Prerequisites

Before using the StackInfo API, it is necessary to have a basic knowledge of web technologies and familiarity with API integration in applications.

## Installation

To install and start using the StackInfo API, follow these steps:

1. Clone the StackInfo repository to your local environment.
2. Install the necessary dependencies using npm or yarn.
3. Configure necessary environment variables, such as API access keys.
4. Start the server locally.
5. You're ready to begin making queries to the API!

# Usage

To use the StackInfo API, you can send HTTP requests to the provided endpoints, providing the necessary parameters such as the name or identifier of the stack you wish to query.

## Making Requests

To make a request to the StackInfo API, you can use a tool such as cURL or a programming language's built-in HTTP request functionality. For example, you can use the following cURL command to query information about the "React" stack:

```bash
curl -X GET "http://localhost:3000/stacks?tag=React" -H "accept: application/json"
```

# Endpoints

The StackInfo API offers the following endpoints:

- `/stacks`: Endpoint to query information about a particular stack.
- `/stacks/{stack_name}`: Endpoint to get detailed information about a specific stack.

# Temporary Server

The StackInfo API is temporarily hosted on AWS. You can access the API using the following base URL:
    
```
https://www.stackinfo.eduardovaz.dev/stacks?tag={stack_name}
```

Requests can be made to the API using the provided base URL and the necessary parameters.

```bash
curl -X GET "https://www.stackinfo.eduardovaz.dev/stacks?tag=angular" -H "accept: application/json"
```


# Contributing

Contributions to the StackInfo API are welcome and encouraged. To contribute to the project, you can follow these steps:

1. Fork the StackInfo repository to your GitHub account.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them to your branch.
4. Push your changes to your fork.
5. Open a pull request to the main StackInfo repository.
6. Your pull request will be reviewed and merged if approved.
7. Congratulations! You have successfully contributed to the StackInfo API.
8. Don't forget to add your name to the list of contributors in the README file.

# Contributors

- [Eduardo Vaz](https://github.com/eduardocvaz)

# License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
