## Overview

This project is an online marketplace where users can buy and sell fashion items. It is built using Django and demonstrates my skills in web development, particularly with the Django framework. The platform supports various fashion categories such as shoes, shirts, t-shirts, pants, shorts, and more.

## Features

### User Authentication and Authorization

- **Sign Up & Login**: Users can create an account and log in securely.
- **Profile Management**: Users can update their profile information.
- **Authorization**: Different permissions are set for buyers and sellers to ensure a secure transaction environment.

### Marketplace

- **Item Listings**: Sellers can list items for sale, including details such as price, description, and category.
- **Item Browsing**: Buyers can browse through items by category or search for specific items.
- **Item Details**: Detailed view of each item with high-quality images and descriptions.

### Conversations

- **Messaging**: Built-in messaging system allows buyers and sellers to communicate directly within the platform.
- **Conversation Management**: Users can view their conversation history and manage their messages.

## Tech Stack

- **Backend**: Django, Django REST framework
- **Frontend**: HTML, CSS, JavaScript
- **Database**: SQLite (for development), PostgreSQL (for production)

## How It Works

### Setting Up the Project

1. **Clone the repository**:
    
    `git clone https://github.com/lokeshwarlakhi/Q-Mart-Online-Marketplace.git cd fashion-marketplace`
    
2. **Install dependencies**:
    
    `pip install -r requirements.txt`
    
3. **Apply migrations**:
    
    `python manage.py migrate`
    
4. **Run the development server**:
    
    `python manage.py runserver`
    

### Key Django Implementations

#### Authentication and Authorization

- **Django's built-in authentication system**: Utilized for user sign-up, login, and profile management.
- **Custom User Model**: Extended to include additional user information.
- **Permissions**: Implemented using Django's permissions framework to ensure only authorized users can perform certain actions (e.g., only sellers can list items).

#### Conversations

- **Messaging System**: Built using Django models and views, allowing users to send and receive messages.
- **Real-time Updates**: Integrated Django Channels for real-time messaging updates.

### Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.