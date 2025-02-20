# 💳 Web Payment Gateway

This project implements a web payment gateway using HTML, CSS, and JavaScript for the frontend, along with Node.js for integration with a payment API.

## ✨ Features
- Attractive and responsive user interface.  
- Integration with a payment API.  
- Secure transaction handling.  
- Data validation on both frontend and backend.  
- Use of Ngrok to simulate an SSL certificate.  

## 🛠️ Technologies  
### Frontend:  
- HTML5  
- CSS3  
- JavaScript  

### Backend:  
- Node.js  
- Payment API (MercadoPago)  

## ⚙️ Setup & Installation  

### Prerequisites  
Make sure you have installed:  
- [Node.js](https://nodejs.org/)  
- A package manager like `npm` or `yarn`  
- [Ngrok](https://ngrok.com/)  

### Steps to Run the Project  

1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/web-payment-gateway.git
   cd web-payment-gateway
   
2. Install the dependencies:
   ````bash
   npm install
   
3. Configure the environment variables in a `.env` file:
   ````bash
   MERCADOPAGO_API_KEY=your_api_key
   
4. Start the server:  
   ````bash
   npm start

5. In another terminal, start Ngrok to expose the server with HTTPS:  
   ````bash
   ngrok http 3000

