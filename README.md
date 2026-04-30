### 🛒 FastAPI Grocery Delivery Backend

A complete backend system for a grocery delivery application built using FastAPI. This project demonstrates real-world backend concepts such as API design, cart workflows, order processing, and advanced query handling.

---

### 🚀Features
RESTful APIs using FastAPI
Pydantic-based request validation
Full CRUD operations for grocery items
Cart management system (add, remove, view items)
Checkout workflow (cart → orders)
Bulk order discount (8% for large quantities)
Delivery charge calculation (slot-based)
Search, filter, sorting, and pagination
Order management with query support
Interactive API testing via Swagger UI

---


### 🧠 Core Functionalities
### 📦 Items
Add new items
Update item details
Delete items
Filter by category, price, and stock
Search items by keyword
Sort items (price, name, etc.)
Pagination support
### 🛒 Cart
Add items to cart
Merge quantities for existing items
Remove items from cart
View cart with total price
### 💳 Checkout
Convert cart into orders
One order created per item
Apply bulk discount logic
Calculate final cost with delivery charges
### 📑 Orders
Place orders directly
Search orders by customer name
Sort orders by total cost
Pagination support
### 🛠 Tech Stack
Python
FastAPI
Pydantic

---

### ▶️ Run Locally
1. Clone the repository
git clone <your-repo-link>
cd grocery-api
2. Install dependencies
pip install -r requirements.txt
3. Run the server
uvicorn main:app --reload
4. Open API Docs
http://127.0.0.1:8000/docs

---

### 📸 API Preview

Swagger UI is available for testing all endpoints.
(Add your screenshots inside /screenshots folder)

---

### 📁 Project Structure
### grocery-api/
###   │
###   ├── main.py
###   ├── requirements.txt
###   ├── README.md
###   └── screenshots/

---

### ⚠️ Limitations
Uses in-memory data (no database)
No authentication or user management
Not production-ready

---

### 🎯 Future Improvements
Add database (SQLite / PostgreSQL with SQLAlchemy)
Implement authentication (JWT)
Modular structure (routers, services, models)
Dockerize the application

---

### 📌 Author

K Sanjay Kumar

Aspiring Software Developer | FastAPI Enthusiast
  
