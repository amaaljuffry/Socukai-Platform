# Socukai

Tax Compliance Automation Platform

Socukai is a modern web application designed to simplify and automate tax compliance workflows. Built with Next.js 15, Tailwind CSS, Radix UI, and Zod, the platform focuses on secure submissions, validation accuracy, and an intuitive user experience for individuals and small businesses.

## Features

### Core Capabilities

* Intelligent tax form submission and validation
* Step-by-step compliance workflow
* Email notifications via Nodemailer
* Light and dark mode support
* Progress tracking and completion summary
* Secure data handling using schema-based validation (Zod)

### UI and UX

* Radix UI component primitives
* Lucide icons
* Tailwind CSS and shadcn-style patterns
* Smooth transitions and feedback using Sonner
* Fully responsive layout

### Developer Experience

* Next.js App Router
* Turbopack for fast local development
* ESLint + Prettier with Tailwind sort
* TypeScript strict mode
* React Hook Form for highly optimized forms

## Tech Stack

| Layer         | Tools / Libraries                              |
| ------------- | ---------------------------------------------- |
| Framework     | Next.js 15 (App Router, Server Components)     |
| Styling       | Tailwind CSS 4, clsx, class-variance-authority |
| UI Components | Radix UI, Lucide React                         |
| Forms         | React Hook Form + Zod                          |
| Notifications | Sonner                                         |
| Theming       | next-themes                                    |
| Email         | Nodemailer                                     |
| Validation    | Zod                                            |
| Build Tools   | Turbopack, TypeScript 5, ESLint 9, Prettier 3  |

## Getting Started

### Prerequisites

* Node.js 20.x
* pnpm, npm, or yarn installed globally

### Installation

```bash
cd socukai
npm install
```

### Development

```bash
npm run dev
```

Runs the app locally using Turbopack on
`http://localhost:3000`

### Production Build

```bash
npm run build
npm start
```

## Environment Variables

Create `.env.local` in the project root:

```
EMAIL_HOST=smtp.example.com
EMAIL_PORT=465
EMAIL_USER=your_email_user
EMAIL_PASSWORD=your_email_password

# Any additional keys used by Socukai
```

## Project Structure

```
socukai/
 ├─ app/                # Next.js routes and server components
 ├─ components/         # UI components
 ├─ lib/                # Utilities, Zod schemas, helpers
 ├─ styles/             # Global styles
 ├─ public/             # Static assets
 ├─ package.json
 └─ README.md
```

## Scripts

| Script          | Description                          |
| --------------- | ------------------------------------ |
| `npm run dev`   | Start development server (Turbopack) |
| `npm run build` | Build output for production          |
| `npm start`     | Run production build                 |
| `npm run lint`  | Lint using ESLint                    |

## Roadmap

* Automated tax calculation engine
* Multi-tenant business support
* Integration with e-government APIs
* Bank-grade encryption for sensitive fields
* Dashboard for accountants and agencies

## Contribution Guide

1. Fork the repository
2. Create a feature branch
3. Submit a pull request with clear description
4. Ensure ESLint and Prettier pass before merging

## License

MIT License. You are free to use, modify, and distribute with attribution.

## Acknowledgements

* Next.js team
* Radix UI
* Tailwind CSS
* Zod
* Vercel for hosting and analytics


