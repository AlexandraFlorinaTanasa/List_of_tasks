List of tasks
It is necessary to write a program in React or Next.js that displays a list of tasks that meets the
following specifications:
• Ask the user to enter a task. Store the task in a permanent location so that the task persists
when the program is restarted.
• Allow the user to enter as many tasks as desired, but do not allow empty tasks to be entered (to
prevent empty entries)
• Displays all tasks in a user-friendly interface.
• Allow the user to remove a task to indicate that it has been completed.
Constraints
• store the data in an persistent backend data source (Redis / Parse Server / Firebase)
• consider database persistence using another third-party service such as Parse or Firebase
• implement input validation to ensure no empty tasks or tasks exceeding a character limit
(example: 100 characters)
• store task state ("pending" or "completed") in the external data source to allow filtering
• use Tailwind CSS to style the app and ensure responsive design
• highlight completed tasks visually strike-through text, faded colors)
• enable sorting tasks by: creation date, deadline
• add drag-and-drop functionality to reorder tasks using libraries like react-beautiful-dnd
• deploy the app using Netlify for the React version and Vercel for the Next.js version. Provide a
shareable link
Challenges
• add the ability to categorize tasks ("Work", "Personal", “Shopping”); use dropdown menus or
color-coded labels for task categories
• integrate Firebase Authentication or NextAuth.js; allow users to log in and view their tasks
• investigate how to use IndexedDB to save articles. Enable offline task creation using
IndexedDB and sync tasks to the external data source when the user reconnects
• create your own API for retrieving the list, creating a new item, and marking a task as complete
(use Next.js API routes or a separate Node.js backend for implementation).
Bonus Challenges
• add support for recurring tasks ("Daily", “Weekly")
• allow users to export tasks as a CSV or JSON file; provide an import feature to upload tasks
into the app





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

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
