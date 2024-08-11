# Zavy - An eCommerce Marketplace

## Local Development Steps:

### 1️⃣ Database Setup:

This project uses PostgreSQL as the database. The easiest way to install it is using docker. Enter the following command on your terminal if you already have docker installed. This will install and run the latest version of postgreSQL.

$ `docker run --name zavy -e POSTGRES_PASSWORD=password -p 5432:5432 -d --rm postgres`

### 2️⃣ Dependencies Setup

This project uses [pnpm](https://pnpm.io/) for managing dependancies. If you don't already have it installed, install it using `npm install -g pnpm` or choose other available methods [here](https://pnpm.io/installation) and then:

- `git clone` this repo and `cd` into it
- `pnpm install`

#### 🛑 Complete 3️⃣ before continuing...

- `pnpm exec prisma migrate dev` (_Will apply migrations, make sure database setup is completed_)
- `pnpm exec prisma db seed` (_Will seed databse with required data_)
- `pnpm dev`
# ecommerce
