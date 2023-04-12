# Getting Started with RobustVotingSystem

## Prerequisites

- Node.js (version 12 or higher)
- PostgreSQL (version 10 or higher)

## Installation

1. Clone the repository: `git clone https://github.com/your-username/RobustVotingSystem.git`
2. Install dependencies: `npm install`

## Database Initialization

To initialize a Prisma PostgreSQL database, follow these steps:

1. Create a new PostgreSQL database: `createdb mydatabase`
2. Navigate to the `prisma` directory: `cd prisma`
3. Copy the `.env.example` file to `.env`: `cp .env.example .env`
4. Update the `DATABASE_URL` variable in the `.env` file with your PostgreSQL database connection string.
5. Run the Prisma migration command: `npx prisma migrate dev --name init`
6. Seed the database with initial data: `npx prisma db seed --preview-feature`

## Running the Application

To start the application, run the following command: `npm start`