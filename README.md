# 🧪 User Management API Testing Project

A complete **API Testing project** built using **Postman** and **Newman**, simulating a real-world user management service.  
This project is designed to demonstrate end-to-end API testing skills for portfolio and interview purposes.

---

## 📦 Project Structure
User Management API (MockAPI)
├── Authentication (Simulated)
├── Users (CRUD)
├── Negative Tests
└── Pre-request Dynamic Data


---

## 🧰 Tools & Technologies
- **Postman** – API testing & automation
- **MockAPI.io** – fake REST API for testing
- **Newman** – command-line runner for Postman collections
- **HTML Reporter** – generate detailed test reports

---

## ⚙️ Environment Setup
1. Clone or download this repository.
2. Open Postman and import:
   - `User Management API (MockAPI).postman_collection.json`
   - `UserEnv.postman_environment.json`
3. Make sure your environment variables are configured:
   - `base_url` → `https://68f184e0b36f9750dee980f1.mockapi.io`
   - `user_id` → (auto-set after POST)
   - `token` → (simulated in pre-request)

---

## 🚀 How to Run with Newman

# Run collection with environment and CSV data
newman run "User Management API (MockAPI).postman_collection.json" \
  -e "UserEnv.postman_environment.json" \
  -d "users.csv" \
  -r cli,html --reporter-html-export "UserManagementReport.html"

---

🧠 Key Features Tested
✅ CRUD operations (POST, GET, PUT, PATCH, DELETE)
✅ Dynamic data generation via Pre-request Scripts
✅ CSV-driven data testing
✅ Negative testing (missing fields, invalid IDs)
✅ Mock authentication simulation
✅ HTML reports with Newman

---

📊 Example Report Screenshot
<img width="1227" height="781" alt="Capture" src="https://github.com/user-attachments/assets/38380244-c39e-49b0-a7c1-ebcf8d58c6dd" />
<img width="1089" height="884" alt="Capture PNG1" src="https://github.com/user-attachments/assets/cea775a9-838b-40d3-923d-314383da4cbf" />
<img width="1073" height="879" alt="Capture PNG2" src="https://github.com/user-attachments/assets/d3171409-aed5-4a1a-a50d-118eebf4c374" />

---

👤 Author

Ibrahim Ahmed 
📧 kingdingawy@gmail.com
💼 https://www.linkedin.com/in/ibrahim-dingawy




