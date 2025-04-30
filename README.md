
# FixMySpace.lk

FixMySpace is a full-stack service marketplace web application that connects customers with local professionals such as electricians, plumbers, carpenters, and more.

## 💡 Features

- Role-based login system for Admin, Customer, and Service Provider
- Service booking, schedule viewing, and service request handling
- Ratings and reviews for providers
- Admin dashboard for managing users, posts, reviews, and service requests
- Contact and notification system
- Privacy policy and terms of service pages

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **Database:** MySQL
- **Development Tools:** Visual Studio Code, WAMP Server, phpMyAdmin
- **Design Tools:** Figma (for wireframes), Trello (for task management)

## 📁 Project Structure

```
FixMySpace/
├── admin/                     # Admin dashboard and functions
│   ├── dashboard.php
│   ├── manage_users.php
│   ├── manage_reviews.php
│   └── ...
├── customer/                  # Customer-facing pages
│   ├── home.php
│   ├── book_service.php
│   ├── profile.php
│   └── ...
├── service_provider/         # Service provider dashboard
│   ├── profile.php
│   ├── schedule.php
│   ├── view_reviews.php
│   └── ...
├── assets/                   # CSS, JS, images
│   ├── css/
│   ├── js/
│   └── images/
├── db/                       # SQL or DB config
│   └── fixmyspace.sql
├── index.php
├── login.php
├── signup.php
└── README.md
```

## 📷 Screenshots

Here are a few screenshots from the working application:

- 🔐 Login page  
- 🏠 Customer home page  
- 🧰 Service booking interface  
- 🧑‍🔧 Service provider dashboard  
- 📊 Admin management panel

_You can upload these in a `/screenshots/` folder or directly on GitHub using the image upload button in edit mode._

## 🧪 Testing

The system includes over 40 functional test cases, including login validation, form handling, profile updates, and booking workflows. All major components were manually tested across browsers and screen sizes.

## 🚀 How to Run

1. Install [WAMP Server](https://www.wampserver.com/en/) or XAMPP
2. Clone or download this repository
3. Place the project folder in `www/` or `htdocs/`
4. Start Apache and MySQL
5. Import the `fixmyspace.sql` database file using phpMyAdmin
6. Navigate to `http://localhost/FixMySpace` in your browser

## 👨‍👩‍👧‍👦 Team Members

- **Abdullah Zahran** – Project Manager & Content Lead  
- **Abinaya Gunasekaran** – Frontend Developer  
- **Thisarani Hettiarachchi** – Backend Developer  
- **Hifdhi Hisham** – UI/UX Designer & QA Tester
