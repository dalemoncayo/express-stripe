# Express Stripe Integration

This project demonstrates integrating Stripe checkout functionality into a Node.js Express application.

## Installation

1. Clone the repository:
   `
   git clone https://github.com/your-username/express-stripe.git
   `
2. Navigate to the project directory:
   `
   cd express-stripe
   `
3. Install dependencies:
   `
   npm install
   `

## Configuration

Before running the application, you need to configure your Stripe secret key. Replace 'YOUR_STRIPE_SECRET_KEY' in index.js with your actual Stripe secret key.

## Usage

To start the server, run:
`
npm start
`

The server will start listening on port 4000 by default.

## API Endpoints

### Create Checkout Session

- **URL:** /create-checkout-session
- **Method:** POST
- **Request Body:**
 `
  {
    "productName": "Sample Product",
    "price": 1000
  }
  `
- **Response:**
  `
  {
    "id": "checkout-session-id"
  }
  `

## Dependencies

- Express: ^4.19.2
- Stripe: ^15.6.0
- Cors: ^2.8.5

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
