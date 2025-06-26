# Frontend Application

## Overview

The frontend is built with Next.js and TypeScript, providing a modern, responsive user interface for the multi-tenant SaaS AI platform. It offers a seamless user experience with real-time updates and AI-powered features.

## Responsibilities

- **User Interface**: Modern, responsive web application
- **State Management**: Client-side state management with React hooks
- **API Integration**: Communication with the backend API
- **Authentication**: User login/logout and session management
- **Multi-tenancy**: Tenant-specific UI customization
- **Real-time Features**: WebSocket integration for live updates

## Architecture

- **Framework**: Next.js 14+ with App Router
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **State Management**: Zustand or Redux Toolkit
- **UI Components**: Headless UI or Radix UI
- **Forms**: React Hook Form with Zod validation
- **HTTP Client**: Axios or TanStack Query

## Key Features

- Server-side rendering (SSR)
- Static site generation (SSG)
- Progressive Web App (PWA) capabilities
- Dark/light theme support
- Responsive design
- Accessibility compliance
- Internationalization (i18n)

## Development Setup

1. Install Node.js 18+ and npm/yarn
2. Install dependencies: `npm install`
3. Configure environment variables
4. Start development server: `npm run dev`

## Project Structure

```
src/
├── app/              # Next.js App Router pages
├── components/       # Reusable UI components
├── lib/             # Utility functions and configurations
├── hooks/           # Custom React hooks
├── types/           # TypeScript type definitions
└── styles/          # Global styles and Tailwind config
```

## Environment Variables

- `NEXT_PUBLIC_API_URL`
- `NEXT_PUBLIC_APP_NAME`
- `NEXT_PUBLIC_WS_URL`
- `NEXTAUTH_SECRET`
- `NEXTAUTH_URL`

## Build & Deployment

- **Development**: `npm run dev`
- **Build**: `npm run build`
- **Production**: `npm start`
- **Linting**: `npm run lint`
- **Type Checking**: `npm run type-check` 