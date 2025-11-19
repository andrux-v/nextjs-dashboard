## Next.js Dashboard with Supabase

This is a Next.js dashboard application with Supabase integration for authentication and database management.

## Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/andrux-v/nextjs-dashboard.git
   cd nextjs-dashboard
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   pnpm install
   ```

3. **Configure environment variables**
   - Copy `.env.example` to `.env`
   - Fill in your Supabase credentials:
     - Go to [Supabase](https://supabase.com)
     - Create a new project or use existing one
     - Get your project URL and API keys from Settings > API
     - Update the `.env` file with your actual values

4. **Run the development server**
   ```bash
   npm run dev
   # or
   pnpm dev
   ```

5. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## Database Setup

This project uses Supabase as the database. Make sure to:
- Set up your Supabase project
- Configure the database schema as needed
- Update the environment variables with your Supabase credentials

For more information, see the [Next.js course curriculum](https://nextjs.org/learn) on the Next.js Website.
