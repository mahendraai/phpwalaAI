🛠️ Product Vision
“An AI-powered Laravel playground with built-in Supabase integration.”

Users can:

Generate full Laravel apps with AI prompts (like “Build me a blog with comments and likes”)

Edit Laravel code in-browser

Deploy instantly to a cloud dev server

Connect, query, and manage Supabase DB in real-time

Export to GitHub or deploy to their own server

🧩 Core Features
1. AI Laravel Generator (v0-style)
Prompt-to-code generator using OpenAI + Laravel template engine

Includes routes, controllers, models, migrations, factories

Blade templates with Tailwind (or Livewire/Inertia)

2. In-browser Laravel IDE
Monaco editor (VSCode in the browser)

Real-time preview for routes/views

Terminal logs, migrations, seeders

3. Supabase Integration
OAuth with Supabase

Visual schema designer or SQL editor

Generate Laravel DB models & migrations from Supabase schema

Supabase client built into Laravel (env auto-configured)

4. One-click Dev Environment
Containerized Laravel instance per user (via Dagger, Docker, or Railway-style infra)

Auto-provisioning for new apps

Supabase URL & keys auto-wired into .env

5. Export / Deploy
GitHub export

Download as zip

Optional deploy to Vercel or Render for frontend/API

🏗️ Tech Stack
Layer	Tech
Frontend	Next.js + Tailwind + shadcn/ui
Backend	Node.js or Laravel (for orchestrating AI, Docker, Supabase, etc)
AI	OpenAI GPT-4 (fine-tuned on Laravel apps)
Database	Supabase (PostgreSQL)
Container	Docker + Railway / Fly.io / Dagger
Auth	Supabase Auth (email, GitHub, Google)
Editor	Monaco Editor
⚡ User Flow (like v0.dev + Laravel + Supabase)
Prompt: “Create a Laravel job board with company profiles”

AI Output: Laravel app structure, model classes, routes, controllers, Blade templates

Supabase DB: Auto-create tables and insert DB URL into .env

Code & Preview: Modify logic, preview locally via sandbox

Export or Deploy: One-click deploy or GitHub export
