# Strapi Task 1 – Local Setup

## Overview
This project contains a local Strapi application created as part of Task-1 for onboarding as a DevOps Intern.

The goal of this task was to set up Strapi locally, explore the project structure, create a sample content type, and verify API functionality.

---

## Tech Stack
- Node.js
- Strapi v5
- SQLite (default database)
- npm
- Git

---

## Setup Steps
1. Created a Strapi application using `create-strapi-app`
2. Installed dependencies using npm
3. Ran Strapi locally in development mode
4. Accessed the Admin Panel
5. Created a collection type named **Article**
6. Added fields:
   - title (Text)
   - description (Rich Text)
   - publishedDate (Date)
7. Added and published sample content
8. Enabled public permissions for API access
9. Verified API response in browser

---

## Run the Project Locally

```bash
npm install
npm run develop
