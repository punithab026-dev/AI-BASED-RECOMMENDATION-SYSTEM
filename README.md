# AI-BASED-RECOMMENDATION-SYSTEM

*COMPANY NAME* : CODTECH IT SOLUTIONS

*NAME* : B.PUNITHA 

*INTERN ID*:CTIS7838

*DOMAIN*: JAVA PROGRAMMING

*DURATION*:4 WEEKS 

*MENTOR *: NEELA SANTHOSH KUMAR

*ABOUT THE PROJECT*:

## 📖 Project Explanation

This AI-Based Recommendation System is developed using Java and is designed to suggest products to users based on their preferences. The system works using a simple collaborative filtering approach, where recommendations are made by analyzing the interests of similar users.

### 🔍 How It Works

The system stores user data and their product ratings using a nested map data structure:
Map<String, Map<String, Integer>>

- The outer map represents users
- The inner map stores products and their ratings given by each user

For example:
User1 → Laptop (5), Mobile (3)  
User2 → Laptop (4), Headphones (5)

### ⚙️ Steps Involved

1. **Data Initialization**  
   User preferences are added using the `addRating()` function.

2. **User Selection**  
   A specific user is selected to generate recommendations.

3. **Comparison with Other Users**  
   The system compares the selected user's data with other users.

4. **Finding Missing Products**  
   Products not used by the selected user are identified.

5. **Score Calculation**  
   Ratings from other users are summed up to calculate a score for each product.

6. **Sorting and Display**  
   Products are sorted based on scores and displayed as recommendations.

### 🔑 Key Components

- **Data Structure**:  
  Map<String, Map<String, Integer>>

- **Functions Used**:
  - `addRating()` – Adds user ratings
  - `recommend()` – Generates recommendations

### 🧠 Core Logic

The system follows the principle:
“Users with similar interests will like similar products.”

It recommends only those products that the user has not interacted with, based on other users' preferences.

### 🎯 Conclusion

This is a simple implementation of a recommendation system similar to those used in platforms like Amazon, Netflix, and Spotify. It can be further enhanced by adding a GUI, database integration, or advanced machine learning algorithms.

**OUTPUT IMAGES**

<img width="1095" height="258" alt="Image" src="https://github.com/user-attachments/assets/0dc07a23-652c-4d3b-b8fc-d20bc9ac9ce4" />
   
