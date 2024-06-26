### Backend Engineer Challenge: Forex Marketplace Microservices

#### Project Description
You are tasked with developing a simple foreign exchange (Forex) marketplace. This system will allow users to buy and sell forex, with conversion rates fetched from an external API. This will be a monorepo project involving multiple microservices, employing NestJS, TypeScript, TypeORM, and MongoDB.

#### Service Architecture
The system will be composed of the following services:

1. **Wallet Service**: Manages balances and transactions within user wallets.
2. **Transaction and Order Service**: Handles the creation and management of forex transactions and orders.
3. **User and Authentication Service**: Responsible for user registration, authentication, and profile management.
4. **Integration/Rate Service**: Fetches current forex rates from [ExchangeRate-API](https://www.exchangerate-api.com/) and makes them available to other services via gRPC.

#### Monorepo Structure
- Utilize tools like Nx or Lerna to manage the monorepo.
- Each service must be a separate package/app within the repository.
- Include shared libraries (e.g., logging, error handling) as internal packages.

#### Technology Stack
- **Backend Framework**: NestJS with TypeScript.
- **Database**: MongoDB, integrated using TypeORM.
- **Internal Communication**: gRPC, especially for rate information.
- **External API**: REST for user-facing endpoints.

#### Features and Requirements
Each service should implement the following functionalities:

- **Wallet Service**:
  - Endpoints to check balances and perform wallet transactions (credit/debit).

- **Transaction and Order Service**:
  - Endpoints to place forex buy/sell orders.
  - Transaction history viewing capabilities.

- **User and Authentication Service**:
  - User registration and login functionality.
  - JWT-based session management.

- **Integration/Rate Service**:
  - Regularly fetch forex rates from the external API.
  - Expose these rates through gRPC to other services.

#### Testing and Documentation
- **Testing**: Include unit tests for core functionalities using Jest.
- **Documentation**: Provide a README.md for each service detailing setup instructions, dependencies, and necessary environment variables.

#### Evaluation Criteria
- **Code Quality**: Focus on clarity, maintainability, and effective use of patterns like Dependency Injection.
- **Architectural Design**: Proper application of microservices patterns and separation of concerns.
- **Database Design**: Effective schema design and usage with MongoDB and TypeORM.
- **Error Handling**: Implementation of robust error handling and logging mechanisms.
- **Security Measures**: Ensure secure handling of user data and authentication processes.

Deliverables
- A GitHub repository containing all microservices within a monorepo structure.
- A `docker-compose.yml` file at the repository root to facilitate local deployment and testing.
- A Postman collection or Swagger files for API testing and exploration.

We look forward to reviewing your innovative solutions and understanding how you approach building scalable, maintainable, and secure systems. This challenge will help us assess your suitability for a mid-level backend engineering position within our fintech-focused team.

All final submissions to this email: info.hephzit@gmail.com not later than 2 weeks from receipt  of this email.

You can add this GitHub user for prompt feedback even before the final submissions is done: akinyeleolat
