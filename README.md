# Personal Expense Tracker

## Overview
The **Personal Expense Tracker** is a robust and intuitive web application designed to help users track, manage, and analyze their daily expenses. With a user-friendly interface and powerful features, this app empowers users to make informed financial decisions and achieve their budgeting goals.

---

## Features
### ✨ **Core Functionalities**
- **Expense Tracking**: Log and categorize daily expenses with ease.
- **Income Management**: Record income sources to maintain a complete financial overview.
- **Real-Time Analytics**: View graphical representations of spending trends.
- **Custom Categories**: Add, edit, or delete categories to suit your needs.

### ⚙️ **Additional Features**
- **Authentication**: Secure login and registration using JWT.
- **Cloud Storage**: Persistent data storage with MongoDB Atlas.
- **Responsive Design**: Fully functional across all devices.
- **Export Data**: Download your financial data in CSV format.
- **Dark Mode**: Toggle between light and dark themes.

---

## Technologies Used
### Frontend
- **React** (with Vite for faster development)
- **Tailwind CSS**
- **React Router** for navigation

### Backend
- **Node.js**
- **Express.js**
- **MongoDB Atlas** for database

### Authentication
- **JWT (JSON Web Token)**
- **BCrypt** for secure password hashing

---

## Installation and Setup

### Prerequisites
Ensure you have the following installed:
- **Node.js** (v14 or later)
- **npm** or **yarn**

### Steps to Run the Project
1. **Clone the Repository**
   ```bash
   git clone https://github.com/nikhil31082005/personal-expense-tracker.git
   cd personal-expense-tracker
   ```

2. **Install Dependencies**
   ```bash
   # For backend
   cd backend
   npm install

   # For frontend
   cd ../frontend
   npm install
   ```

3. **Setup Environment Variables**
   Create a `.env` file in the `backend` directory with the following:
   ```env
   PORT=5000
   MONGO_URL=your-mongodb-uri
   JWT_SECRET=your-jwt-secret
   ```

4. **Start the Application**
   - Start the backend server:
     ```bash
     cd backend
     npm run start
     ```
   - Start the frontend development server:
     ```bash
     cd ../frontend
     npm run dev
     ```

5. **Access the Application**
   Open [http://localhost:5173](http://localhost:5173) in your browser.

---

## Screenshots
### Dashboard
A clean and intuitive dashboard summarizing your expenses:
*(Insert Screenshot)*

### Analytics Page
Visualize your spending with detailed charts:
*(Insert Screenshot)*

---

## Future Enhancements
- **Recurring Transactions**: Automate regular expenses and income.
- **Multi-Currency Support**: Track expenses in different currencies.
- **Budget Alerts**: Get notified when nearing your budget limits.

---

## Contributing
We welcome contributions to enhance the app! Follow these steps:
1. Fork the repository.
2. Create a feature branch.
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes.
   ```bash
   git commit -m "Add feature description"
   ```
4. Push to your branch.
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

## Contact
For queries or support, reach out to:
- **Nikhil**
- Email: nsikarwar496@gmail.com
- LinkedIn: [linkedin.com/in/nikhil3108](https://www.linkedin.com/in/nikhil3108/)

