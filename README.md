# VYOMANG Frontend

This is the frontend for the VYOMANG event registration system. It connects to the backend API to handle user registration, OTP verification, and ticket generation.

## Features

- Email verification with OTP
- Student and guest registration flows
- Payment processing integration
- Responsive design for all devices

## Environment Variables

To run this project, you will need to add the following environment variable to your `.env` file:

`VITE_API_URL` - The URL of the backend API (e.g., https://vyomang-backend-production.up.railway.app)

## Installation

1. Clone the repository
2. Install dependencies: `npm install`
3. Create a `.env` file with the required environment variables
4. Run the development server: `npm run dev`

## Deployment

This project is configured for deployment on Netlify. The build command is `npm run build` and the publish directory is `dist`.

## Tech Stack

- React 19
- TypeScript
- Vite
- Tailwind CSS
- Framer Motion for animations