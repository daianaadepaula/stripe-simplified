# Subscription Platform with Stripe, Clerk & Convex

A modern and fully-featured SaaS starter built with Next.js 14, Clerk for authentication, Stripe for payments (one-time and subscriptions), Convex for real-time backend functions, and Resend for transactional emails. Includes a billing portal, dark/light mode support, rate limiting, and production-ready configurations.

## 🚀 Tech Stack

**Frontend:** Next.js 14, React 18, Tailwind CSS, Lucide React, Radix UI, Sonner (Toast Notifications), Framer Motion  
**Backend/Infra:** Convex, Stripe, Clerk, Upstash Redis, Resend (email delivery), Svix (webhooks)
**Utilities:** Tailwind Merge, Tailwind CSS Animate, Class Variance Authority, CLSX  
**Developer Experience:** TypeScript, ESLint, PostCSS, Environment Variables, Project structured with best practices

## 🔑 Features

- One-time payments with Stripe
- Subscriptions (Monthly & Yearly billing)
- Billing portal for customer management
- Authentication using Clerk
- Secure webhook integration via Svix
- Transactional emails using Resend and React Email
- Rate limiting with Upstash Redis
- Dark and Light theme support
- Reusable components and clean code architecture
- Optimized developer experience with ESLint and TypeScript

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/daianaadepaula/stripe-simplified.git
cd stripe-simplified
```

### 2. Install dependencies for both frontend and backend:

```bash
   npm run build
```

Create a .env file in the root directory with the following content:

```bash
# Convex
CONVEX_DEPLOYMENT=...
NEXT_PUBLIC_CONVEX_URL=...
# Clerk Auth
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=...
CLERK_SECRET_KEY=...
# Stripe Billing
STRIPE_SECRET_KEY=...
STRIPE_WEBHOOK_SECRET=...
STRIPE_MONTHLY_PRICE_ID=...
STRIPE_YEARLY_PRICE_ID=...
# Redis Rate Limiting
UPSTASH_REDIS_REST_URL=...
UPSTASH_REDIS_REST_TOKEN=...
# Email via Resend
RESEND_API_KEY=...
# App
NEXT_PUBLIC_APP_URL=...
```

### 3. Run the application in development mode:

 ```bash
   npm run dev
 ```

The app will be running at: [http://localhost:3000](http://localhost:3000)

## Scripts

- **Development**: npm run dev — Starts the development server.
- **Production**: npm start — Starts the production server.
- **Build**: npm run build — Builds the project for production.

## 🧪 Best Practices

* Authentication and authorization with Clerk
* Secure, scalable payments via Stripe
* Emails built with @react-email components
* Rate limiting to protect sensitive endpoints
* Modular architecture and clean separation of concerns
* Built-in toast notifications with Sonner
* Dark mode with next-themes
* Fully typed with TypeScript
* Reusable components and hooks
* Webhook support and validation with Svix

## 👤 Author

Name: Daiana de Paula </br>
Email: daianaadepaula1@gmail.com </br>
LinkedIn: [https://www.linkedin.com/in/daianadepaula](https://www.linkedin.com/in/daianadepaula/) </br>

## 📄 License

This project is licensed under the MIT License.
