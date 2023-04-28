# Full Stack Airbnb Clone

This is a Full Stack Airbnb Clone built with Next.js, React, Tailwind, Prisma, MongoDB, and NextAuth. The project allows users to browse and search for different Airbnb listings, create a user account, create Airbnb listings, and book available listings.

## Technologies Used

- Next.js 13
- React
- Tailwind CSS
- Prisma
- MongoDB
- NextAuth

## Getting Started

To get started with this project, follow the steps below:

1. Clone the repository:

   ```
   git clone https://github.com/YOUR-USERNAME/full-stack-airbnb-clone.git
   ```

2. Install dependencies:

   ```
   cd full-stack-airbnb-clone
   npm install
   ```

3. Set up environment variables:

   ```
   cp .env.example .env.local
   ```

   Open the `.env.local` file and fill in the required values.

4. Set up MongoDB:

   - Create a MongoDB Atlas account or set up a local instance of MongoDB.
   - Create a new database and add the connection string to your `.env.local` file.

5. Set up NextAuth:

   - Create a new application in your NextAuth dashboard.
   - Copy the Client ID and Client Secret to your `.env.local` file.

6. Set up Prisma:

   - Run the following command to create the database schema:

     ```
     npx prisma migrate dev
     ```

   - Run the following command to seed the database with sample data:

     ```
     npx prisma db seed
     ```

7. Start the development server:

   ```
   npm run dev
   ```

   This will start the development server on `http://localhost:3000`.

## Features

- Browse different Airbnb listings with details like location, price, and descriptions.
- Search for listings by location, price range, and number of guests.
- Create a user account with email and password or sign in with Google or GitHub.
- Book available listings with dates and number of guests.
- View booked listings and manage bookings.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
