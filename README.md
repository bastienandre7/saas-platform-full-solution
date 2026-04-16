# 🚀 Evines — Full-Stack SaaS Platform

A production-ready SaaS boilerplate I built to demonstrate modern full-stack development practices. This personal project showcases a complete authentication system, subscription management, and database integration using the latest web technologies.

## 🎯 About the Project

Evines is a comprehensive SaaS starter application I developed to explore and master the full stack of modern web development. The goal was to build a solid foundation that handles all the essential features of a SaaS product—authentication, billing, database management—while maintaining clean architecture and type safety throughout.

## ✨ Features Implemented

### 🔐 Authentication System

- Secure authentication with Auth.js v5
- Social login integration (Google, GitHub)
- Magic link email authentication
- Session management and protected routes

### 💳 Subscription & Billing

- Complete Stripe integration
- Multiple pricing tiers (Pro & Elite)
- Monthly and yearly billing options
- Webhook handling for subscription events
- Customer portal integration

### 🗄️ Database Management

- PostgreSQL database with Prisma ORM
- Type-safe database queries
- Schema migrations and seeding
- Visual database editor with Prisma Studio

### 📧 Email System

- Transactional emails via Resend
- Magic link authentication emails
- Welcome and onboarding sequences
- Custom email templates

### 🛠 Tech Stack

- Framework: Next.js 16.1 with App Router
- Library: React 19 (Server Actions & New Hooks)
- Styling: Tailwind CSS v4 (Next-gen engine)
- Database: Prisma (Type-safe ORM)
- Auth: Auth.js v5
- Payments: Stripe
- Email: Resend

## 📁 Project Architecture

```
evines/
├── app/                      # Next.js App Router
│   ├── (auth)/              # Authentication routes
│   ├── (dashboard)/         # Protected dashboard routes
│   ├── api/                 # API routes & webhooks
│   └── actions/             # Server actions
├── components/
│   ├── auth/                # Authentication components
│   ├── dashboard/           # Dashboard UI components
│   ├── pricing/             # Pricing & subscription components
│   └── ui/                  # Reusable UI components
├── lib/
│   ├── auth/                # Auth configuration
│   ├── db/                  # Database client
│   └── stripe/              # Stripe utilities
├── prisma/
│   └── schema.prisma        # Database schema
└── public/                  # Static assets
```

## 🎨 Technical Highlights

### Type Safety

- Full TypeScript implementation
- Prisma-generated types for database models
- Type-safe API routes and server actions
- Zod schema validation

### Authentication Flow

- Multiple authentication providers
- Passwordless magic link system
- Secure session handling
- Role-based access control

### Payment Integration

- Subscription lifecycle management
- Webhook signature verification
- Usage-based billing ready
- Customer portal redirect

### Database Design

- Normalized schema structure
- Efficient indexing strategy
- Relationship management
- Migration versioning

## 💡 Skills Demonstrated

- Full-stack Development: End-to-end feature implementation
- Authentication & Security: Auth.js integration, session management
- Payment Processing: Stripe API, webhooks, subscription handling
- Database Design: Prisma ORM, schema design, migrations
- API Development: RESTful endpoints, server actions
- Email Integration: Transactional email system
- TypeScript: Advanced typing, type safety
- Modern React: Server Components, Server Actions, React 19 hooks
- DevOps: Environment configuration, deployment pipelines

## 🔗 Links :

Live Demo: (https://evines-saas-platform-full-solution.vercel.app/)

---

Developed by Bastien Andre
