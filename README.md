# GAA Today

A modern web application for GAA match information, built with Next.js, Express, and Supabase.

## Project Structure

- `/frontend` - Next.js frontend application (deployed on Vercel)
- `/backend` - Express.js backend application (deployed on Railway)

## Tech Stack

- **Frontend**: Next.js, React, TailwindCSS
- **Backend**: Node.js, Express
- **Database**: Supabase
- **Deployment**: 
  - Frontend: Vercel
  - Backend: Railway

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn
- Supabase account
- Railway account
- Vercel account

### Environment Variables

#### Frontend (.env.local)
```
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
NEXT_PUBLIC_API_URL=your_railway_backend_url
```

#### Backend (.env)
```
SUPABASE_URL=your_supabase_url
SUPABASE_SERVICE_KEY=your_supabase_service_key
PORT=3001
```

## Development

1. Clone the repository
2. Install dependencies:
   ```bash
   # Frontend
   cd frontend
   npm install

   # Backend
   cd ../backend
   npm install
   ```
3. Start the development servers:
   ```bash
   # Frontend (in frontend directory)
   npm run dev

   # Backend (in backend directory)
   npm run dev
   ```

## Deployment

### Frontend (Vercel)
1. Push your code to GitHub
2. Connect your repository to Vercel
3. Configure environment variables in Vercel dashboard

### Backend (Railway)
1. Push your code to GitHub
2. Create a new project in Railway
3. Connect your repository
4. Configure environment variables in Railway dashboard

## License

MIT 