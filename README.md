# FoodieRadar (MERN Full Stack App)
Our Restaurant Reservation App, developed with the MERN stack, offers a streamlined booking experience for users and restaurant owners. It features three main models: User, Booking, and Restaurant, supporting two user roles - Restaurant Owners and Customers. The app simplifies the process of managing and making restaurant reservations, leveraging the latest web technologies for efficiency and user engagement.


## Technologies Used
### Backend API/DB
* [Mongo DB](https://www.mongodb.com/)
* [Mongoose](https://mongoosejs.com/)
* [Express](https://expressjs.com/)

### Frontend Application
* [React](https://react.dev/)
* [React router dom](https://reactrouter.com/en/main) -Routing system
* [Mantine](https://mantine.dev/) -UI Library
* [Mantine form](https://mantine.dev/form/use-form/) -Form validation

### Other packeges used
* [dayjs](https://www.npmjs.com/package/dayjs) - Date formatting
* [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken)
* [bcrypt](https://www.npmjs.com/package/bcrypt)
* [Nodemailer](https://nodemailer.com/)

## Key Challenges/takeaways
User-Centric Design: Developing FoodieRadar highlighted the importance of creating an intuitive interface that simplifies complex actions like reservations. Ensuring seamless navigation between features like restaurant catalog browsing, reservation management, and account settings improved overall user experience.
Scalable Data Management: Using MongoDB allowed flexibility in managing a large volume of restaurant and reservation data. The document-based approach facilitated scalability, making it easier to expand with new features in the future.
Enhanced Security: Implementing JWT for session management and bcrypt for password hashing ensured robust user authentication and data security, critical for building trust in a web app with user-sensitive data.

Challenges
State Synchronization: Maintaining a consistent global state with multiple simultaneous user actions, especially with reservations and session data, was complex. Implementing Redux successfully addressed this, streamlining the app’s state management.
Real-Time Updates: Handling real-time seat availability updates was challenging, as it required synchronizing frontend and backend data efficiently to avoid reservation conflicts.
Performance Optimization for Data Filtering: Ensuring fast search and filter responses across a large dataset was initially slow. Adding indexes and restructuring some MongoDB queries effectively improved speed, but it remains a point for ongoing improvement as data volume grows.
## Next Steps
Advanced Analytics for Owners: Integrate analytics to provide restaurant owners with insights into reservation patterns, peak times, and customer demographics, empowering them to make data-driven decisions.
Push Notifications and Reminders: Add in-app and push notifications for reservation confirmations, last-minute changes, and reminders, enhancing user engagement and reducing no-shows.
Mobile Application Development: Develop a native mobile app version to make FoodieRadar more accessible and convenient for on-the-go users, especially for last-minute reservations.
AI-Based Recommendations: Implement an AI engine to suggest restaurants to users based on past reservations and preferences, enhancing personalization.
Online Payment Integration: Enable users to make secure payments or deposits for reservations, providing convenience and allowing restaurants to manage cancellations more effectively.
