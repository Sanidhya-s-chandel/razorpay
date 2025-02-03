# Razorpay Basic Implementation

This repository provides a basic implementation of Razorpay payment gateway integration. It includes step-by-step setup instructions, code samples, and usage details to help you integrate Razorpay into your project.

## Features
- Razorpay payment gateway integration
- Server-side API call setup
- Basic frontend UI for initiating payments
- Success and failure response handling

## Prerequisites
- Node.js (for backend, if applicable)
- Razorpay account ([Sign up here](https://razorpay.com/))
- API keys from Razorpay Dashboard

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/Sanidhya-s-chandel/razorpay
cd razorpay
```

### 2. Install Dependencies (If applicable)
```bash
npm install
```

## Configuration
1. Get your **Key ID** and **Key Secret** from the [Razorpay Dashboard](https://dashboard.razorpay.com/)
2. Create a `.env` file and add:
   ```env
   RAZORPAY_KEY_ID=your_key_id
   RAZORPAY_KEY_SECRET=your_key_secret
   ```

## Usage
### 1. Start the Server
```bash
node server.js
```

### 2. Start Payment
- Open the frontend UI in the browser
- Click on **Pay with Razorpay**
- Complete the payment process

## Folder Structure
```
razorpay-basic-implementation/
├── public/         # Frontend UI files
├── server.js       # Backend logic
├── package.json    # Dependencies and scripts
├── .env            # Environment variables
├── README.md       # Project documentation
```

## License
This project is licensed under the MIT License.

## Author
Developed by [Sanidhya Singh Chandel](https://github.com/Sanidhya-s-chandel)

## Acknowledgments
- [Razorpay API Documentation](https://razorpay.com/docs/)
- [Node.js](https://nodejs.org/)

