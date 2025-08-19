# 🍽️ Zomato Data Analysis  

## 📌 Project Overview  
This project analyzes **Zomato restaurant data** to uncover customer preferences, restaurant performance, and business insights.  
The analysis is performed using **Python (Pandas, Matplotlib, Seaborn, Plotly)** in Google Colab.  

Key objectives:  
- Identify trends in **online orders, table booking, ratings, and cost**.  
- Explore **correlations between cost, votes, and ratings**.  
- Find **top-performing restaurants** by votes and ratings.  
- Provide **actionable business insights** for restaurants.  

---

## 🛠️ Tools & Libraries  
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn
- Plotly  

---

## 📂 Dataset  
The dataset includes the following columns:  
- **Restaurant Name**  
- **Approx. Cost for Two**  
- **Rating**  
- **Votes**  
- **Online Order Availability**  
- **Table Booking Availability**  
- **Restaurant Type**  

*(Dataset provided via GeeksforGeeks course resources)*  

---

## 📊 Exploratory Data Analysis & Insights  

### 🔹 1. Order Preferences  
- **Online Order:** 39.2%  
- **Table Booking:** 5.41%  
📌 *Pie Chart* → Customers prefer **Online Orders** significantly more.  

---

### 🔹 2. Restaurant Categories  
- Majority restaurants fall under **Dining**.  
📌 *Bar Chart* → Dining is the dominant restaurant category.  

---

### 🔹 3. Ratings Distribution  
- Most ratings lie between **3.5 and 4.0**.  
📌 *Histogram*  

---

### 🔹 4. Online Orders & Ratings  
- Restaurants with **online orders enabled** → higher average ratings.  
📌 *Boxplot*  

---

### 🔹 5. Table Booking & Ratings  
- Restaurants with **table booking enabled** → higher ratings.  
📌 *Violin Plot*  

---

### 🔹 6. Top Restaurants  
- ⭐ **Highest Rating:** Onesta  
- 🏆 **Most Votes:** Empire Restaurant  

---

### 🔹 7. Correlation Analysis  
📌 Correlation Matrix:  

| Feature                       | Approx Cost | Rating  | Votes   |  
|-------------------------------|-------------|---------|---------|  
| Approx Cost                   | 1.000       | 0.275   | 0.324   |  
| Rating                        | 0.275       | 1.000   | 0.489   |  
| Votes                         | 0.324       | 0.489   | 1.000   |  

- Votes ↔ Ratings correlation = **0.489** (moderate positive)  
- Cost ↔ Ratings correlation = **0.275** (weak positive)  
📌 *Scatter Plot* → Votes strongly influence ratings, cost has little effect.  

---

### 🔹 8. Cost Analysis  
- 💰 **Average Cost for Two:** ₹418.24  
- 💵 **Most Common Cost Category:** ₹300  
- 📌 *Bar Chart* →  
   - Most Affordable: **Dining**  
   - Most Expensive: **Buffet**  

---

### 🔹 9. Ratings & Votes by Restaurant Type  
| Type   | Avg Rating | Avg Votes |  
|--------|------------|-----------|  
| Buffet | 3.84       | 432       |  
| Cafes  | 3.76       | 279       |  
| Dining | 3.57       | 185       |  
| Other  | 3.91       | 1170      |  

📌 *Combo Plot (Bar for Votes + Line for Ratings)*  

---

### 🔹 10. Heatmap of Online Orders by Restaurant Type  
- Dining restaurants: **77 without online order, 33 with online order**.  
📌 *Heatmap*  

---

## 🏁 Conclusion  
✔️ Customers prefer **online orders** over table booking.  
✔️ **Votes** have a stronger influence on ratings than cost.  
✔️ Restaurants with **online orders** and **table booking** generally perform better.  
✔️ **Dining** is the most common restaurant type, but **Other** categories attract more votes.  
✔️ **Onesta** and **Empire Restaurant** are clear customer favorites.  

---

## 🚀 How to Run the Project  

### 1️⃣ Clone this repository  
```bash
git clone https://github.com/ananyak091/Zomato_Data_Analysis_.git

2️⃣ Navigate into the project folder
cd Zomato_Data_Analysis_

3️⃣ Install the required dependencies
pip install -r requirements.txt

4️⃣ Open the Jupyter Notebook / Google Colab to run the analysis
jupyter notebook Zomato_Data_Analysis.ipynb


