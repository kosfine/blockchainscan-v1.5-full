# BlockchainScan v1.5

A comprehensive blockchain explorer and analytics platform built with Next.js, featuring real-time transaction monitoring, wallet analysis, and administrative tools.

## 🚀 Features

### Core Functionality
- **Multi-blockchain Support**: Bitcoin, Ethereum, Binance Smart Chain, and more
- **Real-time Transaction Tracking**: Monitor transactions across multiple networks
- **Wallet Analysis**: Comprehensive wallet information and transaction history
- **Advanced Search**: Search by wallet address, transaction hash, or block number
- **Network Detection**: Automatic blockchain network identification

### Admin Panel
- **Dashboard Analytics**: Real-time statistics and monitoring
- **Transaction Management**: Manual transaction creation and monitoring
- **User Management**: Admin user controls and permissions
- **System Settings**: Configuration management
- **Data Generator**: Test data generation tools
- **Export Functions**: Data export in multiple formats

### Technical Features
- **Responsive Design**: Mobile-first approach with Tailwind CSS
- **Dark Theme**: Modern dark UI with smooth animations
- **Real-time Updates**: WebSocket connections for live data
- **API Integration**: RESTful API with comprehensive endpoints
- **Security**: JWT authentication and role-based access control

## 📋 Requirements

- Node.js 18.0 or higher
- npm or yarn package manager
- Modern web browser with JavaScript enabled

## 🛠️ Installation

### 1. Clone the Repository
```bash
git clone https://github.com/kosfine/blockchainscan-v1.5-full.git
cd blockchainscan-v1.5-full
```

### 2. Install Dependencies
```bash
cd app
npm install
# or
yarn install
```

### 3. Environment Configuration
Create a `.env.local` file in the app directory:
```env
NEXT_PUBLIC_API_URL=http://localhost:3000
NEXTAUTH_SECRET=your-secret-key-here
NEXTAUTH_URL=http://localhost:3000
```

### 4. Run Development Server
```bash
npm run dev
# or
yarn dev
```

The application will be available at `http://localhost:3000`

### 5. Build for Production
```bash
npm run build
npm start
# or
yarn build
yarn start
```

## 🔧 Configuration

### Admin Panel Access
1. Navigate to `/auth/login`
2. Use default credentials:
   - Username: `admin`
   - Password: `admin123`
3. Change default credentials after first login

### API Endpoints
- `/api/search` - Search functionality
- `/api/admin/*` - Admin panel APIs
- `/api/transactions` - Transaction data
- `/api/wallets` - Wallet information

## 📁 Project Structure

```
blockchainscan-v1.5-full/
├── app/                    # Next.js app directory
│   ├── admin/             # Admin panel pages
│   ├── api/               # API routes
│   ├── auth/              # Authentication pages
│   ├── search/            # Search functionality
│   ├── transaction/       # Transaction pages
│   └── wallet/            # Wallet pages
├── components/            # React components
│   ├── admin/            # Admin-specific components
│   ├── layout/           # Layout components
│   └── ui/               # UI components
├── lib/                  # Utility libraries
├── hooks/                # Custom React hooks
├── public/               # Static assets
└── styles/               # CSS styles
```

## 🎯 Usage

### Basic Search
1. Enter wallet address, transaction hash, or block number in the search bar
2. The system automatically detects the query type and blockchain network
3. View detailed information about the searched item

### Admin Panel Features

#### Dashboard
- View real-time statistics
- Monitor system performance
- Track user activity

#### Transaction Management
- Create manual transactions for testing
- Monitor transaction status
- Export transaction data

#### Settings
- Configure system parameters
- Manage user permissions
- Update API settings

#### Data Generator
- Generate test transactions
- Create sample wallet data
- Populate database for testing

## 🔒 Security

- JWT-based authentication
- Role-based access control
- Input validation and sanitization
- CSRF protection
- Secure API endpoints

## 🚀 Deployment

### Vercel (Recommended)
1. Connect your GitHub repository to Vercel
2. Configure environment variables
3. Deploy automatically on push

### Docker
```bash
docker build -t blockchainscan .
docker run -p 3000:3000 blockchainscan
```

### Manual Deployment
1. Build the project: `npm run build`
2. Upload build files to your server
3. Configure web server (nginx/apache)
4. Set up environment variables

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Commit changes: `git commit -am 'Add feature'`
4. Push to branch: `git push origin feature-name`
5. Submit a pull request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🆘 Support

For support and questions:
- Create an issue on GitHub
- Check the documentation
- Contact the development team

## 🔄 Version History

### v1.5 (Current)
- Enhanced admin panel
- Multi-blockchain support
- Improved UI/UX
- Real-time updates
- Advanced search functionality

### v1.4
- Basic blockchain explorer
- Transaction tracking
- Wallet analysis

### v1.3
- Initial release
- Basic search functionality

---

**BlockchainScan v1.5** - Professional blockchain explorer and analytics platform