# 📄 Product Requirements Document (PRD)  
## Inventory & Supply Chain Dashboard  
**Project Name:** DA-python-driven-database-ui-SQL

---

## 1. 📌 Purpose

The purpose of this product is to design and develop a **Python-driven Inventory and Supply Chain Management Dashboard** that connects directly to a SQL database and provides real-time insights, monitoring, and operational controls through an interactive Streamlit UI.

This system is intended to help businesses and inventory managers track stock levels, suppliers, sales, restocking activity, and reorder needs efficiently.

---

## 2. 🎯 Goals & Objectives

- Provide real-time visibility into inventory and supply chain data  
- Enable data-driven decision-making for stock replenishment  
- Reduce stockouts through automated low-stock identification  
- Offer a simple, intuitive UI for non-technical users  
- Demonstrate strong Python, SQL, and dashboard development skills  

---

## 3. 👥 Target Users

- Inventory Managers  
- Supply Chain Analysts  
- Small Business Owners  
- Data Analysts / Students (Portfolio Use)  

---

## 4. 🧩 Functional Requirements

### 4.1 Dashboard Metrics
The system must display the following key metrics:
- Total Suppliers  
- Total Products  
- Total Categories Dealing  
- Total Sales Value (Last 3 Months)  
- Total Restock Value (Last 3 Months)  
- Number of Products Needing Reorder  

### 4.2 Supplier Management
- Display supplier contact details  
- Show supplier name, city, email, and phone number  

### 4.3 Product & Stock Monitoring
- Display product-wise stock quantity  
- Show minimum stock threshold  
- Map products to suppliers  
- Highlight low-stock products  

### 4.4 Operational Tasks (UI Driven)
The user must be able to:
- Add new products  
- Assign category, supplier, price, and stock quantity  
- Place reorder entries  
- Receive stock updates  
- View product and stock history  

---

## 5. ⚙️ Non-Functional Requirements

- Responsive and user-friendly UI  
- Secure database connection  
- Optimized SQL queries for fast performance  
- Scalable structure for future enhancements  
- Error handling for invalid inputs  

---

## 6. 🛠️ Technical Requirements

### Tech Stack
- **Programming Language:** Python  
- **UI Framework:** Streamlit  
- **Database:** MySQL  
- **Data Handling:** Pandas  
- **Visualization:** Plotly  
- **Database Connector:** mysql-connector-python  

### Database Tables
- `suppliers`  
- `products`  
- `categories`  
- `stock_entries`  

---

## 7. 🔄 User Flow

1. User launches the Streamlit application  
2. Dashboard loads real-time inventory metrics  
3. User views supplier and product details  
4. User performs operational tasks (add product, reorder, receive stock)  
5. Database updates instantly  
6. Dashboard reflects updated values  

---

## 8. 📈 Success Metrics

- Accurate real-time dashboard metrics  
- Correct identification of low-stock products  
- Smooth execution of CRUD operations  
- Positive user experience with minimal learning curve  

---

## 9. 🔮 Future Enhancements

- Role-based user authentication  
- Automated reorder alerts (Email/SMS)  
- Report export (CSV / PDF)  
- Cloud database integration  
- Deployment on Streamlit Cloud or AWS  

---

## 10. 💼 Resume & Learning Value

### Learning Outcomes
- Python–SQL integration  
- Real-time dashboard development  
- SQL analytics & query optimization  
- Inventory management logic  
- Business-focused data visualization  

### Resume Value
- End-to-end data application development  
- Strong SQL & database skills  
- Python-driven UI design  
- Inventory & supply chain analytics  
- Real-world business problem solving  

---

## 11. 👤 Author

**Gautam Keshri**  
Data Analyst | Python | SQL | Streamlit  

⭐ If you like this project, don’t forget to star the repository!
