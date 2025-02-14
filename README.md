# Diego's Full-Stack Template (updated ansh template-2 fork)

This is a modern full-stack template project for building AI-powered applications. The template has been updated to use the latest Next.js 14 and includes all the essential dependencies for building production-ready applications.

## Getting started

To create a new project, you go to `/paths`, choose from our list of Paths, and then use Cursor's Composer feature to quickly scaffold your project!

You can also edit the Path's prompt template to be whatever you like!

## Technologies used

This template uses the following modern tech stack:

- React 18 with Next.js 14 App Router
- TailwindCSS with modern UI components and automatic class sorting
- Firebase Auth, Storage, and Database (v10.9)
- Multiple AI endpoints including:
  - OpenAI with latest AI SDK
  - Anthropic Claude 3.5 Sonnet
  - Replicate Stable Diffusion
  - Deepgram for real-time audio transcription
- TypeScript 5.4 with strict type checking
- ESLint and Prettier for code quality
- Vercel Analytics and Speed Insights for monitoring

## Features

### Developer Experience

- Strict TypeScript configuration with comprehensive type checking
- Advanced ESLint setup with Tailwind CSS linting
- Prettier integration with automatic class sorting
- Path aliases for cleaner imports
- Improved build and development configurations

### UI/UX Components

- Framer Motion for smooth animations
- Lucide React for modern iconography
- Dark mode support via next-themes
- Date formatting with date-fns
- Responsive and mobile-first design patterns

### Performance & Security

- Edge Runtime support for AI endpoints
- Zod for runtime type validation
- Enhanced API route organization and error handling
- LRU caching for improved performance
- Comprehensive image optimization
- Type-safe API routes

### AI Integration

- Vercel AI SDK for streaming responses
- Multiple AI model support
- Real-time audio transcription
- Image generation capabilities
- Efficient streaming and error handling

### Firebase Integration

- Complete authentication system
- Real-time database operations
- Storage management
- Type-safe Firebase utilities

## Project Structure

- `/src/app` - Pages and layouts
- `/src/app/api` - API routes for AI and other services
- `/src/app/components` - Reusable React components
- `/src/lib` - Utilities, hooks, and contexts
  - `/lib/firebase` - Firebase configuration and utilities
  - `/lib/contexts` - React contexts for auth and features
  - `/lib/hooks` - Custom React hooks
