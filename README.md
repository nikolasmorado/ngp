# NGP (Nest.js, GraphQL, PostgreSQL) Starter

NGP is a starter project that combines the power of Nest.js, GraphQL, and PostgreSQL to kickstart your server-side application development. It provides a solid foundation for building efficient and scalable applications with modern technologies. Follow the steps below to get started with this project:

## Prerequisites

Before you begin, make sure you have the following software and dependencies installed on your machine:

- [Node.js](https://nodejs.org/): Make sure to install the latest LTS version.
- [PostgreSQL](https://www.postgresql.org/): You'll need a PostgreSQL database instance to store your data.

## Getting Started

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/ngp.git
   ```

2. Navigate to the project directory:

   ```bash
   cd ngp
   ```

3. Install the project dependencies using your preferred package manager. We recommend using [PNPM](https://pnpm.io/) for better performance:

   ```bash
   pnpm install
   ```

4. Configure your PostgreSQL database connection by updating the database settings in the `src/config/database.config.ts` file.

5. Start the development server:

   ```bash
   pnpm start
   ```

6. Open your web browser and visit [http://localhost:3000](http://localhost:3000/graphql) to interact with the GraphQL API using a GraphQL playground.

<!-- ## Project Structure

The project structure is organized as follows:

- `src`: Contains your application source code.
  - `controllers`: Define your API endpoints and route handlers.
  - `modules`: Organize your application into different modules, each responsible for specific functionality.
  - `resolvers`: Define GraphQL resolvers to handle GraphQL queries and mutations.
  - `entities`: Define your database entities using TypeORM decorators.
  - `services`: Implement business logic and services.
  - `config`: Store configuration files and settings.
  - `utils`: Utility functions and helpers. -->

<!-- ## Testing

NGP provides testing utilities using Jest. You can run the following commands to perform different types of tests:

- Unit tests:

  ```bash
  pnpm run test
  ```

- End-to-end tests:

  ```bash
  pnpm run test:e2e
  ```

- Test coverage:

  ```bash
  pnpm run test:cov
  ``` -->
