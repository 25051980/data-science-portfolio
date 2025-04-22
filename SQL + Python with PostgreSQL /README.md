
# 🛢️ SQL + Python: PostgreSQL Data Analysis with Pandas

This project demonstrates how to integrate SQL queries with Python using PostgreSQL and the `psycopg2` library. It showcases connections to two popular example databases — `demo` and `dvdrental` — and retrieves data for analysis using Pandas.

---

## 🔌 Database Integration

### Libraries Used:
- psycopg2-binary
- pandas
- sqlalchemy (optional for future ORM usage)

### Key Functionalities:
- Connecting to PostgreSQL using `psycopg2`
- Executing raw SQL queries
- Fetching and transforming query results into Pandas DataFrames
- Performing data cleaning, grouping, and statistical summaries

---

## 🎞️ DVD Rental Database Analysis

### Objective:
Analyze rental characteristics of movies by category using the `dvdrental` PostgreSQL sample database.

### SQL Logic:
```sql
SELECT 
    c.name AS category_name, 
    a.rental_duration, 
    a.rental_rate, 
    a.length, 
    a.replacement_cost
FROM film AS a
LEFT JOIN film_category AS b ON a.film_id = b.film_id
LEFT JOIN category AS c ON b.category_id = c.category_id;
```

### Results:
- Grouped the data by `category_name`
- Calculated the average:
  - `rental_duration`
  - `rental_rate`
  - `length`
  - `replacement_cost`

### Example Output:

| Category   | Avg Rental Duration | Avg Rental Rate | Avg Length | Avg Replacement Cost |
|------------|----------------------|------------------|-------------|------------------------|
| Sports     | 4.72                 | 3.12             | 128.20      | 20.39                  |
| Drama      | 5.08                 | 3.02             | 120.83      | 21.08                  |
| Comedy     | 4.93                 | 3.16             | 115.83      | 19.02                  |

---

## 🧠 Key Insights

- **Drama** and **Sports** categories tend to have longer rental durations.
- Rental rate and replacement cost vary slightly across categories.
- Strong use of SQL joins and type conversion techniques.

---

## 🔧 Modular Functions

The project includes reusable functions for:
- Connecting to PostgreSQL
- Running SQL queries with flexible fetch methods
- Converting query results into Pandas DataFrames

```python
def connect_to_postgres(dbname): ...
def get_results_postgres(conn, query, fetch='all'): ...
def to_df(data, colnames): ...
```

---

## 📎 Access the Notebook

[Click here to view the full project on GitHub](https://github.com/25051980/Mod_21/blob/main/Mod21%20-%20SQL%20%2B%20Python%20(1).ipynb)

---

## 🙋 Author

**Samuel Walford**  
📊 Postgraduate in Data Science – PUC-Rio  
🎓 MSc Cyber Security Student – St Mary’s University, Twickenham  
💡 Enthusiastic about SQL, databases, and turning raw data into insights

---

📝 *This project is a great example of bridging SQL power with Python flexibility for real-world data analysis.*
