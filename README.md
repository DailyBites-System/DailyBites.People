# DailyBites.People

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)

The authentication and user management service for **DailyBites**, handling user registration, login, and authorization with secure JWT token generation to control access across the platform.

## Overview

DailyBites.People is a microservice designed to manage user authentication and profile information. It provides secure user registration, login functionality, and JWT-based authorization using the huzcodes.Extensions library to ensure reliable access control across all DailyBites services.

## Key Features

- **User Registration**: Secure user account creation with validation
- **User Authentication**: Login functionality with email and password verification
- **JWT Token Generation**: Secure token generation via huzcodes.Extensions for API access control
- **User Profiles**: Manage user information and preferences
- **Authorization**: Role-based and token-based access control
- **Security**: Industry-standard security practices for password handling and token management
- **Scalable Architecture**: Microservice design for integration with other DailyBites services

## How It Works

1. **User Registration**: Users create accounts with email and password
2. **Authentication**: Users authenticate with credentials to receive JWT tokens
3. **Token Generation**: Secure JWT tokens are generated using huzcodes.Extensions
4. **Authorization**: Tokens are validated for access to protected resources
5. **User Management**: Profile information is maintained and accessible throughout the platform

## Technology Stack

- **Authentication**: JWT (JSON Web Tokens) via huzcodes.Extensions
- **Database**: SQL for reliable user data storage
- **Language**: C#
- **Framework**: .NET 10
- **Security**: Industry-standard encryption and hashing algorithms

## Getting Started

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -am 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

## Support

For issues, questions, or suggestions, please [create an issue](../../issues) in this repository.

## License

DailyBites is licensed under the MIT License. See [LICENSE](https://github.com/DailyBites-System/DailyBites/blob/main/LICENSE) for more information.

## Related Services

- [DailyBites.Recipes](https://github.com/DailyBites-System/DailyBites.Recipes) - Recipe suggestion service
- [DailyBites.API](https://github.com/DailyBites-System/DailyBites.API) - Main API gateway

## Contact

For questions or feedback, please contact Ahmed Hussain aka huzcodes at huzcodes@outlook.com.

---

**Part of the DailyBites Ecosystem** | [Main Repository](https://github.com/DailyBites-System)
