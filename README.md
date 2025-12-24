#  AI Product Categorizer - E-commerce Platform

##  Project Overview

**AI Product Categorizer** is a modern e-commerce platform that leverages artificial intelligence for automatic product categorization using CLIP (Contrastive Language-Image Pre-Training) technology. This graduation project demonstrates the integration of AI capabilities with a full-stack web application, showcasing modern development practices and industry-standard technologies.

##  Key Features

###  AI-Powered Features
- **Automatic Product Categorization** using OpenAI's CLIP model
- **Visual Product Recognition** from uploaded images
- **Smart Search** with semantic understanding
- **Confidence Scoring** for categorization accuracy

###  E-commerce Functionality
- **User Authentication** (Customer & Seller roles)
- **Product Management** (Add, Edit, View, Delete)
- **Shopping Cart** with persistent storage
- **Order Management** and history tracking
- **Marketplace** with advanced filtering and search
- **Responsive Design** for all devices

###  Modern UI/UX
- **Clean Interface** built with Chakra UI
- **Purple Theme** with consistent design system
- **Glassmorphism Effects** and smooth animations
- **Mobile-First** responsive design
- **Accessibility** WCAG-compliant components

## Technology Stack

### Frontend
- **React.js** - Component-based UI framework
- **Chakra UI** - Modern component library
- **React Router** - Client-side routing
- **Axios** - HTTP client for API calls
- **Context API** - State management

### Backend
- **Python Flask** - Web framework
- **SQLite** - Database
- **OpenAI CLIP** - AI model for image classification
- **PIL (Pillow)** - Image processing
- **Flask-CORS** - Cross-origin resource sharing
- **PyTorch** - Deep learning framework

### Development Tools
- **Git** - Version control
- **npm** - Package management (Frontend)
- **pip** - Package management (Backend)

##  Project Structure

```
AIProductCategorizer2/
├──  frontend/                 # React frontend application
│   ├── src/
│   │   ├── components/         # Reusable UI components
│   │   ├── contexts/           # React Context providers
│   │   ├── pages/             # Main application pages
│   │   └── App.js             # Main app component
│   ├── public/                # Static assets
│   └── package.json           # Frontend dependencies
├──  backend/                 # Flask backend application
│   ├── app.py                 # Main Flask application
│   ├── products.db            # SQLite database
│   ├── uploads/               # Uploaded product images
│   ├── requirements.txt       # Python dependencies
│   └── create_test_users.py   # Initial setup script
├──  README.md               # Project overview (this file)
├──  PROJECT_GUIDE.md        # Comprehensive project guide
├──  TECHNOLOGIES.md         # Detailed technology documentation
├──  API_DOCUMENTATION.md    # Complete API reference
└──  .gitignore             # Git ignore rules
```

##  Quick Start

### Prerequisites
- **Node.js** (v14 or higher) - [Download](https://nodejs.org/)
- **Python** (v3.8 or higher) - [Download](https://python.org/)
- **Git** - [Download](https://git-scm.com/)

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd AIProductCategorizer2
   ```

2. **Backend Setup**
   ```bash
   cd backend
   
   # Create virtual environment
   python -m venv venv
   
   # Activate virtual environment
   # Windows:
   venv\Scripts\activate
   
   # macOS/Linux:
   source venv/bin/activate
   
   # Install dependencies
   pip install -r requirements.txt
   
   # Initialize database with test users
   python create_test_users.py
   
   # Start backend server
   python app.py
   ```

3. **Frontend Setup** (Open new terminal)
   ```bash
   cd frontend
   
   # Install dependencies
   npm install
   
   # Start frontend development server
   npm start
   ```

4. **Access the application**
   - **Frontend**: http://localhost:4001 (React app)
   - **Backend API**: http://localhost:8000 (Flask API)

###  macOS Specific Notes
- **Python**: Use `python3` instead of `python` if needed
- **Homebrew**: Install Node.js with `brew install node`
- **Virtual Environment**: May need `python3 -m venv venv`
- **Permissions**: Use `sudo` if permission errors occur

###  Linux Specific Notes
- **Python**: Install with `sudo apt install python3 python3-pip python3-venv`
- **Node.js**: Install with `sudo apt install nodejs npm`
- **Dependencies**: May need `sudo apt install python3-dev`

###  Troubleshooting
- **Port conflicts**: Change ports in app.py (backend) or package.json (frontend)
- **Python not found**: Ensure Python is in PATH or use full path
- **Permission errors**: Use virtual environment and avoid sudo with pip
- **Module not found**: Ensure virtual environment is activated

##  Demo Accounts

### Test Accounts for Demonstration
| Role     | Email                | Password     | Description                    |
|----------|---------------------|--------------|--------------------------------|
| Customer | user@user.com       | usersuser    | Customer test account          |
| Seller   | admin@admin.com     | adminadmin   | Platform seller account       |

### Role-Based Access
- **Customers** : Browse marketplace, add to cart, view order history
- **Sellers** : Upload products, manage inventory, view sales analytics
- **New Users** : Can register for customer or seller accounts
- **Platform Features**: AI-powered categorization, smart search, responsive design

##  Core Functionality

### For Customers 
- Browse products with AI-powered search
- Filter by categories, price range
- Add items to cart and checkout
- View order history and tracking

### For Sellers 
- Upload products with automatic AI categorization
- Manage product inventory and pricing
- View sales and product performance
- Edit product details and images
- Access platform seller tools

### AI Features 
- **Image Upload**: Upload product images for automatic categorization
- **Category Prediction**: AI suggests the most appropriate categories
- **Confidence Scores**: Shows how confident the AI is about each category
- **Smart Filtering**: Enhanced search and filtering capabilities
- **AI Description Generation**: Automatically generates detailed product descriptions based on uploaded images and basic product information, helping sellers create compelling product listings efficiently

##  Supported Categories

The platform supports 13 main product categories:
-  Electronics
-  Fashion & Clothing
-  Home & Furniture
-  Beauty & Personal Care
-  Health & Wellness
-  Groceries & Food
-  Baby & Kids
-  Sports & Outdoors
-  Books & Stationery
-  Automotive & Tools
-  Pet Supplies
-  Toys & Games
-  Travel & Luggages

##  Development Features

### Code Quality
- **Clean Code** principles followed
- **Component-based** architecture
- **Responsive design** implementation
- **Error handling** and validation

### Security Features
- User authentication and authorization
- Role-based access control
- Input validation and sanitization
- Secure file upload handling
- Password hashing with bcrypt
- JWT token management

##  Responsive Design

The platform is fully responsive and works seamlessly across all devices:
- **Desktop** (1200px+) - Full feature access
- **Tablet** (768px - 1199px) - Optimized layouts
- **Mobile** (320px - 767px) - Touch-friendly interface

##  Documentation

###  Complete Documentation
- **[PROJECT_GUIDE.md](PROJECT_GUIDE.md)** - Comprehensive project guide and features
- **[TECHNOLOGIES.md](TECHNOLOGIES.md)** - Detailed technology stack and implementation
- **[API_DOCUMENTATION.md](API_DOCUMENTATION.md)** - Complete REST API reference

###  Project Highlights
This project demonstrates:
- Full-stack web development skills
- AI/ML integration capabilities
- Modern software architecture
- Industry best practices
- Problem-solving and technical implementation

##  Future Enhancements

### Technical Improvements
- Advanced AI models for better categorization
- Real-time notifications system
- Payment gateway integration
- Advanced analytics dashboard
- Mobile app development

### Feature Additions
- Product reviews and ratings
- Advanced recommendation system
- Inventory management tools
- Multi-language support
- Social features and wishlists

##  Contributing

This project demonstrates modern development practices and serves as a learning resource for full-stack development with AI integration.

##  License

This project is created for educational and demonstration purposes.

##  Author

**AI Product Categorizer**
- Full-stack e-commerce platform
- AI-powered product categorization
- Modern web development implementation

##  AI Description 

**To generate "AI Description":**
- Create your own Gemini API key
- Go to backend/.env file
- Paste your API key right after "GEMINI_API_KEY="
- Save and use description feature  

###  Quick Links
- [ Setup Guide for Collaborators](SETUP_GUIDE.md) - Step-by-step setup after cloning
- [ Project Guide](PROJECT_GUIDE.md) - Detailed project overview and features
- [ Technology Stack](TECHNOLOGIES.md) - Complete technical documentation
- [ API Reference](API_DOCUMENTATION.md) - REST API endpoints and usage
- [ Frontend Source](frontend/) - React application code
- [ Backend Source](backend/) - Flask API and AI integration

---

*This project demonstrates the practical integration of artificial intelligence with modern web development technologies to create a complete, functional e-commerce platform suitable for real-world deployment.* 
