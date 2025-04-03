### **Swiggy Lite Demo – FastAPI Recommendation & Analytics App**  

#### **Project Description**  
Swiggy Lite Demo is a lightweight food recommendation and analytics system built using **FastAPI**. This project aims to simulate a simplified version of Swiggy’s recommendation engine by leveraging machine learning models and analytics to enhance user experience. The system provides personalized food recommendations, restaurant suggestions, and order analytics based on user behavior.

---

## **README**  

### **Overview**  
Swiggy Lite Demo is a FastAPI-based backend service designed to offer personalized food recommendations and data-driven insights for restaurant orders. The system utilizes machine learning models to recommend meals, analyze user preferences, and generate analytics dashboards.

### **Features**  
✅ **Personalized Recommendations** – Suggests dishes/restaurants based on user history  
✅ **Order Analytics** – Tracks popular items, user preferences, and trends  
✅ **FastAPI Integration** – High-performance API for real-time interactions  
✅ **Database Support** – Uses SQLModel for structured data storage  
✅ **Machine Learning Models** – Implements recommendation models for better suggestions  

### **Tech Stack**  
- **Backend**: FastAPI  
- **Database**: SQLModel (SQLite/PostgreSQL)  
- **Machine Learning**: Scikit-learn/TensorFlow for recommendations  
- **API Documentation**: Automatic OpenAPI with FastAPI  
- **Deployment**: Docker (future scope)  

### **Installation**  

#### **1. Clone the Repository**  
```bash
git clone https://github.com/yourusername/swiggy-lite-demo.git
cd swiggy-lite-demo
```

#### **2. Set Up a Virtual Environment**  
```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

#### **3. Install Dependencies**  
```bash
pip install -r requirements.txt
```

#### **4. Run the FastAPI Server**  
```bash
uvicorn main:app --reload
```
The API will be available at: [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs)  

### **API Endpoints (Initial Plan)**  
| Method | Endpoint | Description |  
|--------|---------|-------------|  
| `GET` | `/recommendations/{user_id}` | Get personalized food recommendations |  
| `POST` | `/order` | Place an order |  
| `GET` | `/analytics/popular-items` | Get trending food items |  
| `GET` | `/analytics/user-preferences/{user_id}` | Fetch a user's food preferences |  

### **Future Enhancements**  
🔹 Integrate real-time analytics with dashboards  
🔹 Deploy using Docker and cloud services  
🔹 Expand ML model for better personalization  

---

Let me know if you want any modifications! 🚀
