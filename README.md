This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

Based on the codebase, this is an Event Management System called "EventMaster" built with Next.js. Here are its key functionalities:

Core Features

1. Event Management
- Create and manage events with details like title, date, time, description, and budget
- Track event sessions and agendas
- View upcoming and completed events
- Event registration system

2. User Roles
- Multiple user types:
  - Participants
  - Organizers 
  - Speakers
  - Admins

3. Authentication & Authorization
- User authentication using Lucia auth
- Role-based access control
- Session management

4. Registration System
- Participants can register for events
- Track registration status
- Attendance tracking
- Registration approval system by admins

5. Dashboard
- Event analytics and statistics
- Track participant counts
- Monitor event budgets
- View attendance data
- Feedback collection and ratings

6. Technical Stack
- Frontend: Next.js, React
- UI: Tailwind CSS with shadcn/ui components
- Database: MySQL with Prisma ORM
- Authentication: Lucia
- API: REST endpoints using Next.js API routes

7. Data Management
- Organizer management
- Speaker assignments
- Participant tracking
- Event scheduling
- Feedback collection
- Phone number and contact management

This  is a comprehensive system designed specifically for academic events and conferences, with features to handle the entire lifecycle of event management from creation to completion.
