🛒 FastAPI Grocery Delivery Backend












📌 Project Overview

This project is a real-world backend system for a Grocery Delivery Application built using FastAPI.

It demonstrates complete backend development concepts including:

API design
Data validation
Business logic implementation
Multi-step workflows
🚀 Key Features
🔹 API & Backend
RESTful APIs using FastAPI
Clean endpoint design
Interactive Swagger UI
🔹 Data Validation
Pydantic models for request validation
Proper error handling
🔹 CRUD Operations
Create, Read, Update, Delete grocery items
Dynamic data handling
🧠 Core Functionalities
📦 Item Management
Add new grocery items
Update and delete items
Search items by keyword
Filter by category, price, and stock
Sort items (price, name)
Pagination support
🛒 Cart System
Add items to cart
Update quantities automatically
Remove items from cart
View cart summary with total price
💳 Checkout Workflow (Multi-Step ⭐)
Add items to cart
Validate item stock
Apply bulk discount (8%)
Calculate delivery charges
Generate order
Clear cart
📑 Order Management
Place orders
View order history
Search orders by customer
Sort orders by price
Pagination for large datasets
💡 Business Logic Implemented
🧮 Bulk Discount: 8% for large quantity orders
🚚 Delivery Charges: Based on delivery slots
📊 Dynamic Pricing: Auto total calculation
🔁 Cart Merge Logic: Avoid duplicate entries
🛠 Tech Stack
Python
FastAPI
Pydantic
▶️ How to Run Locally
1️⃣ Install dependencies
pip install -r requirements.txt
2️⃣ Run server
uvicorn main:app --reload
3️⃣ Open Swagger UI
http://127.0.0.1:8000/docs
📸 API Preview
Swagger UI available for testing all endpoints
Includes request/response examples
📁 Project Structure
grocery-api/
│
├── main.py              # Main FastAPI app
├── requirements.txt    # Dependencies
├── README.md           # Project documentation
└── screenshots/        # API screenshots
⚠️ Limitations
Uses in-memory storage (no database)
No authentication system
Not production-ready
🔮 Future Improvements
✅ Database integration (SQLite / PostgreSQL)
🔐 JWT Authentication system
🧩 Modular architecture (routers, services)
🐳 Docker support for deployment
📦 Deployment on cloud (Render / AWS)
🎯 Learning Outcomes

Through this project, I learned:

FastAPI architecture and API design
Real-world backend workflows
Data validation using Pydantic
Implementing business logic
Structuring scalable backend systems
👨‍💻 Author

K Sanjay Kumar
Aspiring Data Scientist | Backend Developer
