# PulseBoard

**A modern, full-stack project management and collaboration platform built with Angular, NestJS, Neon (Postgres), and Tailwind CSS.**

## Features

- **Workspace & Project Management**: Organize teams into workspaces and projects.
- **Advanced Task Management**: Tasks, subtasks, priorities, labels, due dates, assignees.
- **Kanban Boards**: Drag-and-drop task management.
- **Analytics Dashboard**: Insights into productivity, completion rates, etc.
- **Team Collaboration**: Comments, activity logs, invitations.
- **Secure Auth**: JWT, password hashing, role-based access.
- **Responsive UI**: Beautiful Tailwind-styled interface with dark mode.
- **Production Ready**: Docker support, tests, environment configs, CI/CD ready.

## Tech Stack

- **Frontend**: Angular 18+ with Standalone Components, Tailwind CSS, RxJS
- **Backend**: NestJS with TypeScript, Prisma ORM
- **Database**: Neon Serverless Postgres
- **Styling**: Tailwind CSS
- **Other**: JWT Auth, Docker, GitHub Actions

## Quick Start

1. Clone the repo
2. Set up .env files (see .env.example)
3. Install dependencies:
   - Backend: `cd backend && npm install`
   - Frontend: `cd frontend && npm install`
4. Database: Create Neon Postgres DB and set DATABASE_URL
5. Prisma: `cd backend && npx prisma generate && npx prisma db push`
6. Run backend: `npm run start:dev`
7. Run frontend: `npm run start`

## Development

See detailed setup in docs.

## Contributing
Pull requests welcome!

Built with impeccable skill for real-world use.