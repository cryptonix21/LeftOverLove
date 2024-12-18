# Food Donation Platform

## 🍽️ Project Overview

The Food Donation Platform is a web application designed to tackle food waste by creating an efficient, user-friendly system that connects food donors with individuals and organizations in need. Our mission is to bridge the gap between surplus food and hunger, ensuring that edible resources reach those who can benefit from them most.

## 🚀 Technology Stack

- **Frontend**: React, Next.js, Tailwind CSS
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Additional Libraries**: Supporting libraries for enhanced functionality

## ✨ Key Features

- Food Donation Submission
- Comprehensive Donation Search
- Direct Donor-Recipient Communication
- Secure User Authentication
- Real-Time Updates and Notifications
- Location-Based Matching (Google Maps Integration)

## 🔧 Installation

### Prerequisites

- Node.js (v16+)
- npm or Yarn
- MongoDB

### Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/cryptonix21/LeftOverLove.git
   cd LeftOverLove
   ```

2. **Install Dependencies**
   ```bash
   # Frontend installation
   cd frontend
   npm install

   # Backend installation
   cd ../backend
   npm install
   ```

3. **Configure Environment**
   - Create `.env` files in both frontend and backend directories
   - Set up MongoDB connection string
   - Configure third-party service credentials (Google Maps, etc.)

4. **Run the Application**
   ```bash
   # Start backend server
   cd backend
   npm start

   # In another terminal, start frontend
   cd frontend
   npm run dev
   ```

## 📡 API Documentation

### Available Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/donations` | Retrieve available food donations |
| POST | `/api/donations` | Submit a new food donation |
| GET | `/api/users` | User profile management |
| POST | `/api/auth` | User authentication routes |

## 🧪 Testing

The project supports comprehensive testing using:
- Jest for unit and integration testing
- Cypress for end-to-end testing

Run tests with:
```bash
npm test
```

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Contribution Guidelines

- Follow existing code style
- Write clear, concise commit messages
- Include tests for new features
- Update documentation as needed

## 📄 License

This project is licensed under the MIT License. See `LICENSE` file for details.

## 📞 Contact

For questions or support, please:
- Open an issue in the GitHub repository
- Contact the maintainers directly

---

**Made with ❤️ to reduce food waste and support communities**