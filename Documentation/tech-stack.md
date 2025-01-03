# Tech Stack Documentation

## Frontend

### Core Framework & Build Tools
- React 18 with TypeScript
- Vite for build tooling and development server
- TypeScript for type safety
- React Router for navigation

### UI & Styling
- Tailwind CSS for utility-first styling
- Material UI for core components
- Shadcn UI for enhanced components
- CSS Modules for component-specific styles

### State Management
- React Context API for global state
- Custom hooks for local state management
- React Query for server state management

### Forms & Validation
- React Hook Form for form management
- Zod for schema validation
- TypeScript for type checking

## Backend

### Core Framework
- FastAPI for REST API
- Python 3.11+
- Uvicorn as ASGI server

### Database & ORM
- PostgreSQL on Railway
- Prisma as ORM
- Database migrations handling

### Authentication
- Auth0 for authentication
- JWT token management
- Social login (Google)

### AI Integration
- OpenAI API for:
  - Interview simulations
  - Resume analysis
  - Response evaluation
  - Question generation

## Infrastructure

### Deployment
- Vercel for frontend hosting
- Railway for database hosting
- FastAPI backend deployment on Hetzner/Coolify

### Development Tools
- Git for version control
- GitHub for repository
- GitHub Actions for CI/CD
- ESLint & Prettier for code formatting
- Husky for git hooks

### Monitoring & Error Tracking
- Sentry for error tracking
- Basic analytics integration
- Performance monitoring

### Testing
- Jest for frontend testing
- Pytest for backend testing
- Cypress for E2E testing

## Security
- HTTPS enforcement
- Auth0 security features
- API rate limiting
- Input validation
- SQL injection prevention