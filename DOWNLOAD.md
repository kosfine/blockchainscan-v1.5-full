# Download BlockchainScan v1.5 Full Source Code

## Complete Project Download

This repository contains the complete BlockchainScan v1.5 source code with all components and features.

### Option 1: Git Clone (Recommended)
```bash
git clone https://github.com/kosfine/blockchainscan-v1.5-full.git
cd blockchainscan-v1.5-full
```

### Option 2: Download ZIP
Click the green "Code" button above and select "Download ZIP" to get the complete source code.

### Option 3: Direct Archive Download
A compressed archive (275KB) of the complete source code is available. The archive contains:
- Complete Next.js application
- All React components and UI elements
- Admin panel with full functionality
- API routes and backend logic
- Database schema and migrations
- Configuration files
- Documentation in English and Russian

## What's Included

### 📁 Project Structure
```
blockchainscan-v1.5-full/
├── README.md                 # English documentation
├── README_RU.md             # Russian documentation  
├── INSTALLATION.md          # Installation guide
├── .gitignore              # Git ignore rules
└── app/                    # Main application
    ├── package.json        # Dependencies and scripts
    ├── components/         # React components
    ├── app/               # Next.js app router
    ├── lib/               # Utility libraries
    ├── hooks/             # Custom React hooks
    ├── prisma/            # Database schema
    └── public/            # Static assets
```

### 🚀 Key Features
- **Multi-blockchain Support**: Bitcoin, Ethereum, BSC, and more
- **Real-time Transaction Monitoring**: Live blockchain data
- **Advanced Search**: Wallet addresses, transaction hashes, blocks
- **Admin Panel**: Complete management interface
- **Responsive Design**: Mobile-first approach
- **Dark Theme**: Modern UI with animations
- **API Integration**: RESTful endpoints
- **Security**: JWT authentication, role-based access

### 🛠️ Technologies Used
- **Frontend**: Next.js 14, React 18, TypeScript
- **UI Framework**: Tailwind CSS, Radix UI
- **Database**: Prisma ORM with SQLite/PostgreSQL
- **Authentication**: NextAuth.js
- **Charts**: Chart.js, Plotly.js, Recharts
- **State Management**: Zustand, Jotai
- **Forms**: React Hook Form, Formik
- **Animations**: Framer Motion

## Quick Start

1. **Download the source code** using any method above
2. **Navigate to the app directory**: `cd app`
3. **Install dependencies**: `npm install`
4. **Set up environment**: Copy `.env.example` to `.env.local`
5. **Initialize database**: `npx prisma generate && npx prisma db push`
6. **Seed data**: `npm run seed`
7. **Start development**: `npm run dev`
8. **Open browser**: `http://localhost:3000`

## Admin Access
- **URL**: `/auth/login`
- **Username**: `admin`
- **Password**: `admin123`

## File Sizes
- **Complete repository**: ~50MB (without node_modules)
- **Compressed archive**: ~275KB
- **After npm install**: ~200MB (with dependencies)

## Support & Documentation

- **English Documentation**: [README.md](README.md)
- **Russian Documentation**: [README_RU.md](README_RU.md)
- **Installation Guide**: [INSTALLATION.md](INSTALLATION.md)
- **GitHub Issues**: For bug reports and feature requests

## License
MIT License - Free for personal and commercial use

---

**BlockchainScan v1.5** - Professional blockchain explorer and analytics platform