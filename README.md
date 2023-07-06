# College-Mart
College-Mart is a dynamic web application designed to provide a platform for college students to buy and sell various items, such as books, electronics, and more.
It simplifies the process of connecting buyers and sellers within the college community. Built on the MERN stack (MongoDB, Express.js, React.js, and Node.js), 
this project utilizes RESTful APIs, JWT token-based authentication, cookies, and middlewares for enhanced security. The application features a responsive design 
to ensure seamless user experience across multiple devices. Additionally, it includes a real-time chat feature powered by Socket.io for efficient communication 
between users. The Bcrypt library is used for secure password hashing and storage.

Features
User Registration and Login: College students can easily sign up by providing their email and password. 
Registered users can securely log in to the application using their credentials.

Authentication and JWT Tokens: The application employs JWT (JSON Web Tokens) for secure authentication, providing authorized access to the application's features.

Cookies and Session Management: Cookies are used to manage user sessions, allowing users to stay logged in while navigating the application.

CRUD Operations: Users can easily perform Create, Read, Update, and Delete operations on their listings, enabling efficient management of their items.

Item Listing: Students can create listings for items they want to sell, including detailed information such as title, description, price, and images.

Search and Filtering: Users can search for specific items and apply filters to narrow down their search results, facilitating quick and targeted item exploration.

Real-Time Chat: The chat feature powered by Socket.io enables real-time communication between users, allowing them to ask questions and get instant responses to clear
any queries they may have about a product.

Responsive Design: The application is designed to be fully responsive, ensuring an optimal user experience on various devices, including desktops, tablets, and 
mobile phones.

Technologies Used
Front-end: React.js, HTML5, Tailwind, JavaScript
Back-end: Node.js, Express.js, MongoDB
Authentication: JWT (JSON Web Tokens), Bcrypt library
Real-Time Communication: Socket.io
Other Libraries and Tools: Axios, Redux, Mongoose, Nodemon

For running this :
Install dependencies on both frontend and backend folder respectively
Then use : 
npm run start (frontend)
nodemon app.js (backend)
