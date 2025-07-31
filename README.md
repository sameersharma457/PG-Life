# PG-Life 🏠

A comprehensive full-stack web application designed to streamline the search and booking process for Paying Guest (PG) accommodations. Built with modern web technologies to provide an intuitive and responsive user experience for students and working professionals seeking quality PG accommodations.

## 🌟 Features

### 🔍 **Smart Search & Discovery**
- **City-based Search**: Search for PGs across multiple cities with an intelligent search bar
- **Interactive City Cards**: Quick access to popular cities through visually appealing circular sections
- **Advanced Filtering**: Sort PGs by rent, ratings, amenities, and availability
- **Real-time Results**: Dynamic search results with instant filtering

### 🏡 **Property Management**
- **Detailed Listings**: Comprehensive PG information with high-quality images
- **Image Carousel**: Beautiful photo galleries for each property
- **Amenities Showcase**: Clear display of available facilities and services
- **Location Integration**: Interactive maps and address details
- **Popularity Metrics**: See how many users have shown interest in each property

### 👤 **User Experience**
- **User Authentication**: Secure signup and login system
- **Personal Dashboard**: Manage your profile and view account details
- **Wishlist Feature**: Save favorite PGs with a simple heart icon toggle
- **Interest Tracking**: View all your interested properties in one place
- **Responsive Design**: Seamless experience across desktop, tablet, and mobile devices

### 📱 **Interactive Features**
- **Dynamic UI**: Real-time updates for user interactions
- **AJAX Integration**: Smooth, page-reload-free experience
- **User Reviews**: Read testimonials from previous tenants
- **Contact Integration**: Easy connection with property owners

## 🛠️ Tech Stack

### Frontend
- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling and animations
- **Bootstrap 5** - Responsive design framework
- **JavaScript (ES6+)** - Interactive functionality
- **AJAX** - Asynchronous data loading

### Backend
- **PHP** - Server-side logic and API endpoints
- **MySQL** - Database management and storage

### Additional Tools
- **phpMyAdmin** - Database administration
- **XAMPP/WAMP** - Local development environment

## 🚀 Getting Started

### Prerequisites
- Web server (Apache/Nginx)
- PHP 7.4 or higher
- MySQL 5.7 or higher
- phpMyAdmin (recommended)

### Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/sameersharma457/PG-Life.git
   cd PG-Life
   ```

2. **Database Setup**
   - Open phpMyAdmin in your browser
   - Create a new database named `pglife`
   - Import the SQL file from the `database/` directory
   ```sql
   -- Navigate to the database directory and import
   -- pglife.sql or similar database file
   ```

3. **Configure Database Connection**
   - Open `includes/database_connect.php`
   - Update the database credentials:
   ```php
   $conn = mysqli_connect(
       "localhost",           // Host
       "your_username",       // Username
       "your_password",       // Password
       "pglife"              // Database name
   );
   ```

4. **Start Local Server**
   - If using XAMPP: Place project in `htdocs/` folder
   - If using WAMP: Place project in `www/` folder
   - Start Apache and MySQL services
   - Navigate to `http://localhost/PG-Life`

## 📁 Project Structure

```
PG-Life/
├── 📁 css/              # Stylesheets
├── 📁 js/               # JavaScript files
├── 📁 images/           # Image assets
├── 📁 includes/         # PHP includes and database connection
├── 📁 database/         # SQL database file
├── 📄 index.php         # Homepage
├── 📄 property_list.php # Property listings page
├── 📄 property_detail.php # Individual property details
├── 📄 dashboard.php     # User dashboard
├── 📄 login.php         # User authentication
├── 📄 signup.php        # User registration
└── 📄 README.md         # Project documentation
```

## 🎯 Usage

### For Users
1. **Browse Properties**: Visit the homepage and explore available cities
2. **Search & Filter**: Use the search bar and filters to find suitable PGs
3. **View Details**: Click on any property to see detailed information
4. **Create Account**: Sign up to access personalized features
5. **Save Favorites**: Mark interesting properties with the heart icon
6. **Manage Profile**: Access your dashboard to view saved properties

### For Developers
1. **Add New Cities**: Update the database with new city information
2. **Manage Properties**: Add/edit/remove PG listings through the admin panel
3. **Customize UI**: Modify CSS files for design changes
4. **Extend Features**: Add new functionality using the existing PHP/JS structure

## 🌐 Live Demo

Check out the live version of PG-Life: [Add your live demo URL here]

*Login credentials for demo:*
- Username: `demo@pglife.com`
- Password: `demo123`

## 📸 Screenshots

### HomePage
![Homepage Screenshot](images/homepage-preview.png)

### Property Listings
![Property List Screenshot](images/property-list-preview.png)

### Property Details
![Property Detail Screenshot](images/property-detail-preview.png)

### User Dashboard
![Dashboard Screenshot](images/dashboard-preview.png)

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📋 Future Enhancements

- [ ] **Payment Integration**: Online booking and payment system
- [ ] **Chat System**: Real-time communication between users and owners
- [ ] **Mobile App**: Native mobile application
- [ ] **Admin Panel**: Comprehensive admin dashboard
- [ ] **Email Notifications**: Automated email alerts for bookings
- [ ] **Review System**: Detailed rating and review functionality
- [ ] **Map Integration**: Interactive property location maps
- [ ] **Multi-language Support**: Support for regional languages

## 🐛 Known Issues

- Image upload size limitation on some hosting providers
- Session timeout on shared hosting environments
- Mobile responsiveness on older browsers

## 📞 Support

If you encounter any issues or have questions:

- 📧 Email: sameersharma457@gmail.
