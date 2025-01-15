# 🌟 **Second-Hand Marketplace**

The **Second-Hand Marketplace** is a web-based platform allowing users to buy and sell used items. Built with the **MEAN stack** (MongoDB, Express.js, Angular, Node.js), it offers a secure and user-friendly environment for second-hand transactions.

---

## 💡 **Project Overview**

A platform for users to:
- **Buy and sell** used items.
- Create, edit, and delete **product listings**.
- **Search** products by price, category, and location.
- **Chat** in real-time for communication.
- **Admin Panel** to manage users and content.

---

## 🔑 **Key Features**

- **📝 User Registration & Login**: Secure authentication with JWT.
- **🛒 Product Listings**: Create, edit, and delete products with descriptions, images, and categories.
- **🔍 Search & Filters**: Filter products by price, category, and location.
- **💬 Real-Time Chat**: Negotiation support via real-time chat (Socket.IO).
- **🔧 Admin Panel**: Manage users, listings, and inappropriate content.
- **📱 Responsive Design**: Optimized for mobile, tablet, and desktop devices.
- **💳 Optional Payment Integration**: Future implementation for secure transactions.

---

## 🛠️ **Technology Stack**

- **Frontend**:
  - **Angular**: A powerful framework for building web applications.
  - **Angular Material**: Pre-built UI components for modern design.

- **Backend**:
  - **Node.js**: JavaScript runtime environment.
  - **Express.js**: Web framework for building the API.

- **Database**:
  - **MongoDB**: NoSQL database for flexible storage.
  - **Mongoose ORM**: MongoDB object modeling for Node.js.

- **Authentication**:
  - **JWT**: Secure user authentication.

- **Real-Time Communication**:
  - **Socket.IO**: Enables real-time features like chat.

---

## 🚀 **Installation Guide**

### 1. Clone the Repository

```bash
git clone https://github.com/your-repo/second-hand-marketplace.git
cd second-hand-marketplace
```

### 2. Install Backend Dependencies
Navigate to the `server` directory and install the necessary backend dependencies:

```bash
npm install
```

### 3. Install Frontend Dependencies
Navigate to the `client` directory and install the frontend dependencies:

```bash
cd client
npm install
```

### 4. Configure Environment Variables
- Set up the required `.env` file for backend settings like database URL, JWT secret, etc.
- Adjust API URLs in the frontend configuration as needed.

### 5. Start Development Servers

#### Backend Server:

```bash
npm start
```

#### Frontend Server:

```bash
cd client
ng serve
```

Your app will be available at `http://localhost:4200`.
```


Here is the updated section for the `README.md` with proper Markdown formatting for the API Endpoints and Contributors:

```markdown
## 🔧 API Endpoints

### Authentication
- **POST /api/auth/register**: Register a new user.
- **POST /api/auth/login**: Login user and issue JWT.

### Product Listings
- **GET /api/products**: Fetch all products.
- **POST /api/products**: Create a new product (authenticated users).
- **PUT /api/products/:id**: Update product details (authenticated users).
- **DELETE /api/products/:id**: Delete a product (authenticated users).

### Chat
- **GET /api/chat/:conversationId**: Fetch chat history for a specific conversation.
- **POST /api/chat**: Send a message in an ongoing conversation.

## 👥 **Contributors**
- Mohit Kumar Saini
- Rahul Kumar Rajak
- Satyam Kumar
- Harish Choudhary
- Ukirde Jaydeep Shivaji

