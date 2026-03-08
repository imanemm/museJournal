# MuseJournal

**MuseJournal** is a full-stack web application that blends **music discovery** and **personal reflection**.

It allows users to journal their thoughts and emotions while connecting their entries to the music they listen to.  
Music becomes a way to capture **moments, moods, and memories**.

---

## What You Can Do

- Write journal entries about your day
- Select your current mood
- Attach songs to your entries
- See how your mood and music change over time
- Generate inspirational quotes
- Visualize personal listening trends

The goal is to turn music listening into a **more meaningful and reflective experience**.

---

## Tech Stack

### Frontend

- Next.js
- React
- TypeScript
- Tailwind CSS
- Framer Motion

### Backend

- Next.js API Routes

### Database

- PostgreSQL
- Prisma ORM

### External APIs

- Spotify Web API

### Tooling

- Git & GitHub
- ESLint
- Prettier

---

## ⚙️ Setup & Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/musejournal.git
cd musejournal
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure environment variables

Create a .env file in the root of the project.

Example:
```code
DATABASE_URL=
SPOTIFY_CLIENT_ID=
SPOTIFY_CLIENT_SECRET=
NEXTAUTH_SECRET=
NEXTAUTH_URL=
```

### 4. Setup the database

Generate the Prisma client:

```bash
npx prisma generate
```

Run database migrations:

```bash
npx prisma migrate dev
```

### 5. Start the development server

```bash
npx run dev
```

The app will be available at:

```code
http://localhost:3000
```

--- 

##  Architecture

MuseJournal uses a full-stack Next.js architecture, meaning both the frontend and backend live in the same project.

Spotify integration allows the app to fetch music data and connect songs to journal entries.

---

## MuseJournal is currently under active development.

Planned features include:
-	richer mood analytics
-	better music insights
-	improved visualizations
-	more journaling tools

---

## About This Project

I built MuseJournal as a way to explore full-stack development while working on an idea that mixes technology, creativity, and music.

It’s also part of my journey learning how to design and build complete web applications from scratch.

---

## License
MIT License