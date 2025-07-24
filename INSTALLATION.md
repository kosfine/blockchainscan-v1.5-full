# BlockchainScan v1.5 - Installation Guide

## Quick Start

### Prerequisites
- Node.js 18.0 or higher
- npm or yarn package manager
- Git

### Installation Steps

1. **Clone the repository:**
```bash
git clone https://github.com/kosfine/blockchainscan-v1.5-full.git
cd blockchainscan-v1.5-full
```

2. **Navigate to the app directory:**
```bash
cd app
```

3. **Install dependencies:**
```bash
npm install
# or
yarn install
```

4. **Create environment file:**
```bash
cp .env.example .env.local
```

5. **Configure environment variables in `.env.local`:**
```env
NEXT_PUBLIC_API_URL=http://localhost:3000
NEXTAUTH_SECRET=your-secret-key-here
NEXTAUTH_URL=http://localhost:3000
DATABASE_URL="file:./dev.db"
```

6. **Initialize the database:**
```bash
npx prisma generate
npx prisma db push
npm run seed
```

7. **Start the development server:**
```bash
npm run dev
```

8. **Open your browser and navigate to:**
```
http://localhost:3000
```

## Admin Panel Access

- URL: `http://localhost:3000/auth/login`
- Username: `admin`
- Password: `admin123`

**Important:** Change the default credentials after first login!

## Production Deployment

### Build for production:
```bash
npm run build
npm start
```

### Environment Variables for Production:
```env
NEXT_PUBLIC_API_URL=https://your-domain.com
NEXTAUTH_SECRET=your-production-secret-key
NEXTAUTH_URL=https://your-domain.com
DATABASE_URL="your-production-database-url"
```

## Troubleshooting

### Common Issues:

1. **Port already in use:**
   - Change the port: `npm run dev -- -p 3001`

2. **Database connection issues:**
   - Ensure DATABASE_URL is correctly set
   - Run: `npx prisma db push`

3. **Missing dependencies:**
   - Delete node_modules and package-lock.json
   - Run: `npm install`

4. **Build errors:**
   - Clear Next.js cache: `rm -rf .next`
   - Rebuild: `npm run build`

## Features Overview

- **Multi-blockchain Support**: Bitcoin, Ethereum, BSC
- **Real-time Monitoring**: Live transaction tracking
- **Admin Panel**: Comprehensive management tools
- **Search Functionality**: Advanced blockchain search
- **Responsive Design**: Mobile-friendly interface
- **Dark Theme**: Modern UI with animations

## Support

For issues and questions:
- Create an issue on GitHub
- Check the main README.md for detailed documentation
- Review the troubleshooting section above