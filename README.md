# Next.js Dashboard (course practice)

My practice project for the official [Next.js App Router course](https://nextjs.org/learn). The course builds a finance dashboard with invoices and customers.

> 📚 **Learning project.** The UI components and starter code come from the course. My work so far covers the early chapters.

## What I've done so far

- Set up a Next.js 15 project with TypeScript and Tailwind CSS
- Global styles and fonts
- File-based routing with nested layouts: `/dashboard`, `/dashboard/invoices`, `/dashboard/customers`
- A shared dashboard layout with side navigation
- Database seeding route for PostgreSQL
- Fixed the TypeScript config so the project builds for production on Vercel

## Up next (from the course)

- Fetching real data from PostgreSQL for the dashboard cards and revenue chart
- Streaming and loading skeletons
- Search and pagination for invoices
- Creating, editing and deleting invoices with Server Actions
- Login with NextAuth

## Run it

```bash
pnpm install
pnpm dev        # http://localhost:3000
```

## Built with

Next.js · React · TypeScript · Tailwind CSS · PostgreSQL
