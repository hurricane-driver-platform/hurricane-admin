# Hurricane Express - Admin Web Portal

A secure web dashboard for Hurricane Express office personnel to manage the driver platform, moderate community forums, and oversee the rewards program. Built as a 2026 Capstone Project.

## 🚀 Tech Stack
- **Frontend Framework:** Next.js (App Router), React, TypeScript
- **UI Components:** Tailwind CSS / Shadcn UI
- **Backend Logic:** Next.js Server Actions (Node.js)
- **Database & Auth:** Supabase (PostgreSQL)
- **Hosting:** Vercel

## ✨ Key Features
- **App Management:** Manage active driver accounts and authentications.
- **Metrics Upload:** Secure interface for uploading and updating driver performance data.
- **Store & Inventory:** Manage rewards inventory and fulfill user redemptions.
- **Forum Moderation:** Monitor, moderate, and remove inappropriate driver community discussions.

## 🛠️ Local Development Setup
1. Clone the repository: `git clone https://github.com/YourOrgName/hurricane-admin.git`
2. Install dependencies: `npm install`
3. Set up environment variables: Create a `.env.local` file and add your `NEXT_PUBLIC_SUPABASE_URL`, `NEXT_PUBLIC_SUPABASE_ANON_KEY`, and the secret `SUPABASE_SERVICE_ROLE_KEY`.
4. Start the development server: `npm run dev`
5. Open `http://localhost:3000` in your browser.
