# SaaS Starter Platform

A comprehensive SaaS platform with payment processing, user authentication, and mobile responsiveness.

## Features

- User authentication (signup, login, password reset)
- Subscription management with Stripe
- Mobile-responsive design
- Dashboard for users and admins
- SEO optimization
- Cross-platform compatibility

## Project Structure

- `/frontend` - React application
- `/backend` - Node.js/Express API
- `/mobile` - React Native mobile app

## Getting Started

### Prerequisites

- Node.js (v16+)
- MongoDB
- Stripe account

### Installation

1. Clone the repository
2. Install dependencies for both frontend and backend
3. Set up environment variables
4. Start the development servers

```bash
# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install

# Run backend and frontend in development mode
cd ../
npm run dev
```

## Environment Variables

Create a `.env` file in the backend directory with the following variables:

```
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
STRIPE_PUBLISHABLE_KEY=your_stripe_publishable_key
FRONTEND_URL=http://localhost:3000
```

## Documentation

Additional documentation can be found in the `/docs` directory.

## License

MIT