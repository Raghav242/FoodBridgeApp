# Food Bridge

## Overview
**Food Bridge** is a web application designed to connect restaurants willing to donate leftover food with people in need. This platform provides an efficient way for users to browse and collect available food items from restaurants that have listed surplus food.

## Features

### User Features:
- **User Authentication:** Users can sign up and log in using their credentials.
- **Food Browsing:** View a variety of available food items posted by restaurants.
- **Order Placement:** Place an order for food items and receive pickup details.
- **Pickup Management:** Users can collect food from the specified restaurant locations.
- **User Profile Management:** Manage personal details and order history.

### Admin Features:
- **Restaurant Management:** Add and manage restaurant profiles.
- **Food Item Management:** Add, update, and remove food items.
- **Order Tracking:** Monitor placed orders and ensure smooth pickups.

## Technologies Used

### Frontend:
- **Angular** – Frontend framework for building a dynamic and responsive user interface.

### Backend:
- **Python Flask** – Lightweight web framework to handle business logic and API interactions.

### Database:
- **MySQL** – Storage and management of user data, restaurant details, and food items.

## Installation

### Prerequisites
Ensure the following are installed on your system:
- Node.js (>=14.0)
- Angular CLI
- Python (>=3.8)
- MySQL (>=5.7)

### Steps to Install
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/food-bridge.git
   ```
2. Navigate to the project directory:
   ```bash
   cd food-bridge
   ```
3. Install frontend dependencies:
   ```bash
   cd frontend
   npm install
   ```
4. Set up backend dependencies:
   ```bash
   cd backend
   pip install -r requirements.txt
   ```
5. Import the database:
   - Locate the `food_bridge.sql` file.
   - Import it into MySQL using phpMyAdmin or command line:
     ```bash
     mysql -u root -p < food_bridge.sql
     ```
6. Configure database connection:
   - Edit `config.py` and update the database credentials accordingly.

7. Start the backend server:
   ```bash
   python app.py
   ```

8. Start the frontend server:
   ```bash
   cd frontend
   ng serve
   ```
9. Access the application in your web browser:
   ```
   http://localhost:4200
   ```

## Usage
- **For Users:**
  1. Sign up or log in.
  2. Browse available food items.
  3. Place an order.
  4. Pick up food from the specified location.

- **For Admins:**
  1. Log in via the admin panel.
  2. Manage restaurants and food items.
  3. Track and oversee orders.

## Contribution
Contributions are welcome! If you'd like to contribute:
1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Submit a pull request.

Thank you for using **Food Bridge**!

