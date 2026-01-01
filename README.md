# Mini Store (Next.js + Prisma)

Mini Store is a small ecommerce storefront demo built with Next.js and Prisma to showcase product browsing and order flow.

## Features
- Product catalog
- Order capture
- Event tracking
- SQLite dev database with seed data

## Screenshot
![Screenshot](docs/screenshot.png)

Replace `docs/screenshot.png` with a real screenshot or GIF.

## Quickstart
### Prerequisites
- Node.js 20+
- npm

### Run locally
```bash
cp .env.example .env
npm install
npx prisma migrate dev --name init
npx prisma db seed
npm run dev
```

Open `http://localhost:3000`.

## Configuration
- `DATABASE_URL` in `.env`

## Tests
```bash
npm test
```
