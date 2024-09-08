
# Crypto Wallet Project

This project is a comprehensive cryptocurrency wallet application designed to deliver a secure and efficient experience for users. The application enables users to manage their cryptocurrency portfolios, conduct transactions, and access real-time market data. The backend leverages modern technologies for speed, security, and scalability, while the frontend is designed to be responsive and user-friendly across all devices.

## Project Overview

The crypto wallet is built with a robust tech stack that ensures both frontend and backend reliability. The backend is powered by Fastify, Prisma, and PostgreSQL, providing fast API responses, secure data handling, and efficient database management. The frontend is developed using React and Next.js, offering a seamless user experience with responsive design principles.

Key features include user authentication, secure transactions, portfolio management, real-time market data, and mobile accessibility.

## Tech Stack

### Backend
The backend of this project is built using Fastify, which is known for its fast performance and low overhead. Prisma is used as an ORM to interact with a PostgreSQL database, ensuring smooth data management and migrations. Fastify plugins like `@fastify/jwt` and `@fastify/cors` help with authentication and cross-origin resource sharing, respectively. Passwords are hashed with bcrypt for added security.

- Fastify: v4.27.0
- Prisma: v5.14.0
- PostgreSQL: Integrated with Prisma using `@fastify/postgres`
- JWT Authentication: `@fastify/jwt`
- Password Hashing: bcrypt
- HTTP Client: Axios
- Logging: Pino

### Frontend
The frontend is developed using Next.js, allowing for both static and server-side rendering, which improves performance and SEO. Tailwind CSS is used for styling, enabling rapid UI development with a modern, responsive design. React Query and Formik are used for managing API data and form handling, respectively.

- Next.js: v14.2.5
- React: v18
- Tailwind CSS: v3.4.6
- Formik: v2.4.5
- React Query: v3.39.3
- React Toastify: For notifications
- React Slick: For responsive carousels and sliders


cd packages\api 
pnpm run dev


cd packages\newclient 
pnpm run dev
