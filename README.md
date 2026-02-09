# Jobbernaut Tabs (Frontend)

The web interface for the Jobbernaut ecosystem. This is a Next.js application that allows users to view their job application pipeline, edit preferences, and download tailored resumes.

## 🖥 Logical Component
* **Jobbernaut Tabs Frontend:** The Client-Side UI.

## 🛠 Tech Stack
* **Framework:** Next.js 14 (App Router)
* **Language:** TypeScript
* **Styling:** Tailwind CSS
* **Hosting:** AWS S3 + CloudFront (Static Export) OR Vercel
* **State Management:** React Query (TanStack Query) for fetching from the ReDirector API.

## 🔌 Integration
* Connects to **Jobbernaut ReDirector** (API Gateway) for all data operations.
* Uses Presigned URLs from S3 to securely download PDF artifacts.
