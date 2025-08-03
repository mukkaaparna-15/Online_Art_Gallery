# Online_Art_Gallery
A comprehensive web-based Art Gallery Management System built with PHP, MySQL, and Bootstrap. This system provides a complete solution for managing art galleries, artists, art products, and customer inquiries.
## 🎨 Features

### Frontend Features
- **Responsive Design**: Modern, mobile-friendly interface built with Bootstrap
- **Art Gallery Display**: Showcase art products with detailed information
- **Artist Profiles**: Dedicated pages for artist information and portfolios
- **Product Catalog**: Browse art products by type, medium, and artist
- **Search Functionality**: Advanced search capabilities for art products
- **Contact & Enquiry System**: Customer inquiry management
- **About Us**: Gallery information and history

### Admin Panel Features
- **Dashboard**: Comprehensive overview with statistics
- **Artist Management**: Add, edit, and manage artist profiles
- **Art Product Management**: Complete CRUD operations for art products
- **Art Type Management**: Categorize art by types (Paintings, Sculptures, etc.)
- **Art Medium Management**: Organize by medium (Oil, Watercolor, Acrylic, etc.)
- **Enquiry Management**: Handle customer inquiries and responses
- **Profile Management**: Admin profile and password management
- **Image Management**: Upload and manage art product images

## 🛠️ Technology Stack

- **Backend**: PHP
- **Database**: MySQL
- **Frontend**: HTML5, CSS3, JavaScript
- **Framework**: Bootstrap 4
- **Icons**: Font Awesome
- **Server**: Apache (XAMPP/WAMP/LAMP)

## 📋 Prerequisites

Before running this application, make sure you have:

- **Web Server**: XAMPP, WAMP, or LAMP
- **PHP**: Version 7.0 or higher
- **MySQL**: Version 5.6 or higher
- **Web Browser**: Chrome, Firefox, Safari, or Edge

## 🚀 Installation

### Step 1: Download and Extract
1. Download the project files
2. Extract the ZIP file
3. Copy the `agms` folder to your web server's root directory:
   - **XAMPP**: `xampp/htdocs/`
   - **WAMP**: `wamp/www/`
   - **LAMP**: `var/www/html/`

### Step 2: Database Setup
1. Open your web browser and navigate to `http://localhost/phpmyadmin`
2. Create a new database named `agmsdb`
3. Import the database file:
   - Go to the `SQL File` folder
   - Import `agmsdb.sql` into your newly created database

### Step 3: Configuration
1. Open `agms/includes/dbconnection.php`
2. Update the database connection details if needed:
   ```php
   $host = "localhost";
   $username = "root";
   $password = "";
   $database = "agmsdb";
   ```

### Step 4: Access the Application
1. Start your web server (Apache and MySQL)
2. Open your browser and navigate to: `http://localhost/agms`

## 👤 Admin Access

### Default Admin Credentials
- **Username**: `admin`
- **Password**: `Test@123`

### Admin Panel URL
- Access admin panel at: `http://localhost/agms/admin`

## 📁 Project Structure

```
agms/
├── admin/                 # Admin panel files
│   ├── dashboard.php     # Admin dashboard
│   ├── manage-*.php      # Management pages
│   ├── add-*.php         # Add new items
│   ├── edit-*.php        # Edit existing items
│   └── assets/           # Admin assets
├── includes/             # PHP includes
│   ├── dbconnection.php  # Database connection
│   ├── header.php        # Site header
│   └── footer.php        # Site footer
├── css/                  # Stylesheets
├── js/                   # JavaScript files
├── images/               # Image assets
├── webfonts/            # Font files
├── index.php            # Home page
├── about.php            # About page
├── contact.php          # Contact page
├── product.php          # Product listing
├── single-product.php   # Product details
├── search.php           # Search functionality
└── art-enquiry.php      # Enquiry form

SQL File/
└── agmsdb.sql          # Database structure and sample data
```

## 🔧 Key Features Explained

### 1. Art Product Management
- Add new art products with images
- Categorize by type and medium
- Set pricing and availability
- Manage product descriptions

### 2. Artist Management
- Complete artist profiles
- Artist portfolio management
- Biography and contact information

### 3. Customer Enquiry System
- Contact form for visitors
- Admin can respond to enquiries
- Track enquiry status

### 4. Search and Filter
- Search art products by name
- Filter by artist, type, or medium
- Advanced search options

## 🎯 Usage

### For Gallery Owners
1. **Setup**: Follow the installation guide above
2. **Configure**: Add your gallery information in the admin panel
3. **Add Artists**: Create artist profiles and portfolios
4. **Add Products**: Upload art products with images and details
5. **Manage Enquiries**: Respond to customer inquiries

### For Visitors
1. **Browse**: View art products and artist profiles
2. **Search**: Find specific art pieces or artists
3. **Contact**: Submit inquiries through the contact form
4. **Learn**: Read about the gallery and artists

## 🔒 Security Features

- Session-based authentication
- Admin panel access control
- SQL injection prevention
- Input validation and sanitization

## 🎨 Customization

### Styling
- Modify `css/style.css` for custom styling
- Update Bootstrap theme in `css/bootstrap.min.css`
- Customize fonts and colors

### Functionality
- Add new features in the admin panel
- Extend product categories
- Implement additional search filters

## 📞 Support

If you encounter any issues:

1. Check that all prerequisites are installed
2. Verify database connection settings
3. Ensure proper file permissions
4. Check server error logs

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Bootstrap for the responsive framework
- Font Awesome for icons
- PHP community for best practices

---

**Note**: This is a demonstration project. For production use, ensure proper security measures, regular backups, and SSL certificates are implemented.
