# Taskflow

A simple task manager starter built with Next.js, React, TypeScript, and Lucide icons. It is designed to deploy to Vercel and can be pushed to GitHub as a normal Next.js project.

## Features

- Create tasks with a project, due date, and priority
- Track tasks as To do, In progress, and Done by clicking the status box
- Filter and search tasks
- Overview cards for completion, active work, upcoming deadlines, and progress
- Upcoming deadline and recent activity panels
- Responsive layout for desktop and mobile
- Tasks persist in the current browser using localStorage

## Run locally

1. Install Node.js 18.17 or newer.
2. In this folder, run `npm install`.
3. Run `npm run dev` and open http://localhost:3000.
4. Run `npm run build` to create a production build.

## Deploy with GitHub and Vercel

1. Create a GitHub repository and push the contents of this folder.
2. In Vercel, import that repository.
3. Keep the detected Next.js settings and deploy. No environment variables are required.

## Data note

This starter stores tasks in browser localStorage. Each browser profile has its own data, so tasks do not sync between devices or users. Add a database and authentication (for example, Supabase or Vercel Postgres) when you want shared, cross-device task tracking. The activity panel is sample UI content in this starter.
