# InvBalancePWA
Project that simplifies inventory management. Technologies used: Java, JavaScript.

# 📦 InvBalance

**InvBalance** is a lightweight and user-friendly application designed to simplify inventory and sales management for street vendors and small businesses. With this tool, users can manage products, record inventory movements, track daily sales, and receive stock alerts — all in one centralized platform.

The goal is to empower small-scale sellers with a simple, effective solution to monitor their operations without the complexity or cost of large-scale systems.

---

## 🚀 Key Features

- 🧑‍💼 **User Account Management**  
  Create and manage user profiles for business owners or employees.

- 🏪 **Business Registration**  
  Register and organize multiple businesses or sales units under one account.

- 📦 **Product Management**  
  Add, update, and remove products with details like name, stock quantity, and prices.

- 🔄 **Inventory Movements**  
  Record incoming and outgoing inventory (e.g., restocking, item sales, damaged goods).

- 🚨 **Low Stock Alerts**  
  Automatically receive alerts when product quantities fall below the defined threshold.

- 💰 **End-of-Day Sales Recording**  
  Capture and register daily sales totals to help monitor business performance.

- 📊 **Simple Dashboard (Optional)**  
  Overview of inventory levels, daily sales, and alerts.

---

## 👥 Who Is This For?

This app is designed specifically for:

- Street vendors  
- Small store owners  
- Micro-entrepreneurs  
- Local business operators  
- Informal or mobile sellers needing a lightweight inventory solution  

---

## 🛠️ Technologies Used

| Layer       | Technology          |
|-------------|---------------------|
| Backend     | Java + Spring Boot  |
| Frontend    | React               |
| Database    | MariaDB             |
| Tools       | Maven, npm, Git     |

---

## 📁 Project Structure

```
invbalance/
├── backend/
│ ├── src/main/java/
│ ├── src/main/resources/
│ │ └── application.properties
│ └── pom.xml
├── frontend/
│ ├── public/
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ └── App.js
│ └── package.json
├── database/
├── README.md
└── LICENSE
```

---

## 💡 Getting Started

### Prerequisites

- Java JDK 17+  
- Maven 3+  
- Node.js (16+) & npm  
- MariaDB (10.5+)  

### Installation

1. **Clone the repository:**
   ```bash
   git clone git@github.com:Mikejoya/InvBalancePWA.git
   cd invbalance

2. **Setup the backend (Spring Boot):**

- Import into your preferred Java IDE (IntelliJ, Eclipse, etc.)
- Configure database connection in `src/main/resources/application.properties`:

```properties
spring.datasource.url=jdbc:mariadb://localhost:3306/invbalance
spring.datasource.username=your-username
spring.datasource.password=your-password
spring.jpa.hibernate.ddl-auto=update
```
- Run the main application class:
```
mvn spring-boot:run
```

3. **Setup the frontend (React):**
```
cd frontend
npm install
npm start
```

By default, the app will run at http://localhost:3000

### Database setup (MariaDB):

- Run the SQL scripts inside /database/ or create tables via JPA auto-generation.

### 📈 Future Improvements

- Mobile app version (Android/iOS)

- Barcode scanning support

- Multi-user roles and permissions

- Cloud backup and sync

- Export reports to PDF/Excel

### 📄 License

- This project is licensed under the MIT License.

### 🙌 Contributing

Contributions are welcome! Feel free to fork the repo and submit pull requests to improve features, fix bugs, or enhance documentation.

### 📫 Contact

For questions, suggestions, or collaboration opportunities, please reach out to:

- Email: *******@***********.com

- GitHub: ***********



