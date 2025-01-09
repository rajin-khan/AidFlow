![Repo banner](./assets/aidflow%20logo.png)

---

<div align="center">

# AidFlow
##### Donation Platform for Emergency Needs

---

**Frontend**:  
- **Web**: **React.js** for building the web interface.  
- **Mobile App**: **Native Android** (Java/Kotlin).  

**Backend**:  
- **Framework**: Flask (Python) — Easy to set up and excellent for REST API development.  

**Database**:  
- **MongoDB** (NoSQL database, great for flexible schemas and easy integration with Flask).  

**Hosting**:  
- **Website**: AWS (Amazon Web Services) for hosting the web platform.  
- **App**: Google Play Store for Android app deployment.  

**Authentication**:  
- **OAuth2** for Google or Facebook logins, combined with email/password authentication.  

**Payment Gateway**:  
- **Local Payment Options**:  
  - **BKash API**: For seamless mobile wallet integration.  
  - **DBBL Nexus Pay**: For debit/credit card payments and online banking.  
  - **Visa/MasterCard Integration**: Through local gateways like **SSLCOMMERZ** or **ShurjoPay**.  

**Unique Feature**:  
- **Donation Tracker**: Use Flask APIs to fetch real-time data and display stats on donor impact (e.g., number of people helped, amount raised, etc.).  

---

### **Learning Path for the React-Based Tech Stack**

- **Frontend (Web)**  
   Learn **HTML, CSS, and JavaScript basics**.  
   Learn **React.js**: Start with the official React documentation. Focus on creating reusable components, managing state (useState, useEffect), and working with React Router for navigation.  

- **Frontend (Mobile)**  
   Learn **Android Development**:
     - Start with **Java** or **Kotlin** (choose the one you're most comfortable with or want to learn).  
     - Build a simple app (e.g., a weather app) to get familiar with Android Studio, layouts, and components.  

- **Backend**  
   Learn **Python** (if not already familiar).  
   Learn **Flask**: Start with the basics, such as creating routes, handling requests, and building APIs. Practice building REST APIs for CRUD operations.  

- **Database**  
   Learn **MongoDB**:
     - Understand the basics of NoSQL databases, collections, and documents.  
     - Practice with sample datasets, such as creating a user collection and donation records.  

- **API Development**  
   Combine Flask with MongoDB to build REST APIs for the app and website.  
   Learn how to handle user authentication and authorization (OAuth2).  

- **Payment Gateway Integration**  
   Study how to integrate **BKash APIs** from their official documentation.  
   Learn how to implement **SSLCOMMERZ** or **ShurjoPay** for Visa, MasterCard, and DBBL Nexus Pay transactions.  

- **Hosting**  
   Learn how to host a React app on **AWS S3** or **AWS Amplify** for scalable deployment.  
   Learn how to host a Flask app on **AWS Elastic Beanstalk** or **AWS Lightsail**.  
   Learn how to deploy the Android app to **Google Play Store**.  

- **Additional Tools**  
   Explore using **Twilio** for SMS notifications (optional but adds value).  
   Learn how to use **Git for version control** and work with repositories like GitHub or Bitbucket.  

---

### **Revised Development Plan**

#### **Phase 1: Initial Setup (Weeks 1-2)**  
- Learn **React.js basics**: Build simple components and understand state and props.  
- Set up Flask with MongoDB and create basic APIs (e.g., user registration, login).  
- Design the database schema for users, donations, and NGOs.  

#### **Phase 2: Core Development (Weeks 3-6)**  
- Build the website using React and integrate with Flask APIs.  
- Develop the Android app and ensure it syncs with the same backend/database.  
- Add authentication with OAuth2 and email/password.  
- Start integrating payment gateways like BKash and SSLCOMMERZ/ShurjoPay.  

#### **Phase 3: Advanced Features (Weeks 7-8)**  
- Finalize and test payment integrations.  
- Add the donation tracker and stats.  
- Thoroughly test the app and website for bugs and performance.  
- Deploy the website to AWS and the app to the Play Store.  

---

### **Resources for Payment Gateways**
- **BKash API (perhaps nonexistent)**:  
   Visit their website for API documentation and integration tutorials.
- **SSLCOMMERZ**:  
   Access their [official documentation](https://developer.sslcommerz.com/) to learn about payment gateway integration for Visa/MasterCard/DBBL Nexus Pay.  

- **ShurjoPay**:  
   Explore their [developer resources](https://shurjopay.com.bd/) for setup and integration.  

---