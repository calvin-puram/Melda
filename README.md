# Melda is RESTful API that enables you to create, edit and share your favourite books. It's stable, intuitive and, best of all, free! It was built using modern technologies:

### MongoDB - Express - Redis - NodeJS - Typescript

- API:
  - [x] Authentication system - [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken)
    - [x] Sign up - [bcrypt](https://www.npmjs.com/package/bcrypt)
    - [x] login - [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken)
  - [x] Authorization system
    - [x] Role-based access control
    - [x] Principle of least privilege
  - [x] Input validation and sanitization - [validator](https://www.npmjs.com/package/validator)
  - [x] API Security
    - [x] The API is protected with JWT (JSON WEB TOKEN). This allows the application to identify authorized users and restrict access to data for unauthorised users
    - [x] Passwords have also been hashed with strong a crypto-algorithm.
    - [x] A structure has been established for the implementation of rate-limiting, to circumvent DOS security vulnerabilities with the system.
    - [x] user inputs are sanitized against xss and Nosql injection

## Installation

#### Step 1: Clone the repository

```bash
git clone https://github.com/calvin-puram/Melda.git
cd Melda
```

#### Step 2: Setup database

You must have mongodb installed on your local machine

#### Step 3: Setup environment variables

Include necessary variables as found in .env.example into .env

#### Step 4: Install NPM packages

```bash
yarn install
```

#### Step 5: Start in development mode

```bash
yarn build

yarn watch

yarn start:dev
```

## Step 5: TODO

- Write Test
- Cover more edge cases
- Document API
