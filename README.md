# 🏪 Toko Web - Frontend

Modern React TypeScript frontend for Toko Management System with comprehensive CRUD operations and responsive design.

## ✨ Features

### 📊 **Dashboard**
- Real-time statistics and overview
- Interactive charts and metrics
- Quick navigation to main features

### 👥 **Pelanggan (Customer Management)**
- Complete CRUD operations
- Advanced search and filtering
- Sortable data tables
- Export to CSV functionality

### 📦 **Barang (Product Management)**
- Product catalog management
- Category-based organization
- Price and inventory tracking
- Bulk operations support

### 🛒 **Penjualan (Sales Management)**
- Multi-item transaction support
- Automatic subtotal calculation
- Customer relationship linking
- Transaction history tracking

## 🚀 Tech Stack

- **Frontend Framework**: React 18 with TypeScript
- **Build Tool**: Vite
- **UI Library**: Ant Design
- **Styling**: CSS3 with responsive design
- **HTTP Client**: Axios
- **Date Handling**: Day.js
- **Icons**: Ant Design Icons

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/rizqyyourin/toko-web.git
   cd toko-web
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment**
   ```bash
   cp .env.example .env
   # Edit .env with your API endpoint
   ```

4. **Start development server**
   ```bash
   npm run dev
   ```

5. **Build for production**
   ```bash
   npm run build
   ```

## 📱 Responsive Design

The application is fully responsive and optimized for:
- 📱 **Mobile devices** (< 768px)
- 📱 **Tablets** (768px - 992px)
- 💻 **Desktop** (> 992px)

### Mobile Features
- Collapsible navigation drawer
- Touch-friendly interface
- Optimized table layouts
- Adaptive button sizing

## 🔧 Configuration

### API Integration
The frontend connects to Laravel backend API. Update base URL in `vite.config.js` proxy or set environment variable:

```env
VITE_API_BASE=http://localhost:8000/api
```

### Default API Endpoints
- `/api/pelanggan` - Customer management
- `/api/barang` - Product management  
- `/api/penjualan` - Sales transactions

## 📂 Project Structure

```
src/
├── components/
│   └── common/           # Reusable components
├── lib/
│   ├── api.ts           # API client configuration
│   ├── hooks.ts         # Custom React hooks
│   ├── useSearch.ts     # Search functionality
│   └── exportCSV.ts     # CSV export utility
├── pages/
│   ├── dashboard/       # Dashboard page
│   ├── pelanggan/       # Customer management
│   ├── barang/          # Product management
│   └── penjualan/       # Sales management
├── styles/
│   ├── common-crud.css  # Shared CRUD styling
│   └── styles.css       # Global styles
└── types.ts             # TypeScript type definitions
```

## 🎨 UI/UX Features

- **Modern Design**: Clean and intuitive interface
- **Consistent Styling**: Unified design system
- **Interactive Elements**: Smooth animations and transitions
- **Accessibility**: Keyboard navigation and screen reader support
- **Performance**: Optimized rendering and lazy loading

## 📋 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint (if configured)
- `npm run type-check` - TypeScript type checking

## 🔌 Backend Requirements

This frontend requires a Laravel backend API running on `http://localhost:8000` with endpoints for:
- Customer management (`/api/pelanggan`)
- Product management (`/api/barang`)
- Sales transactions (`/api/penjualan`)

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License.

## 🙏 Acknowledgments

- Built with [React](https://reactjs.org/) and [TypeScript](https://www.typescriptlang.org/)
- UI components by [Ant Design](https://ant.design/)
- Bundled with [Vite](https://vitejs.dev/)

---

**Made with ❤️ for modern web development**
