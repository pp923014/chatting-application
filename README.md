# MERN Chatting App (Messenger)

A real-time chat application built using the **MERN (MongoDB, Express, React, Node.js) stack**, where users can create accounts, send messages, and change the background theme.

## Features
- ✅ **User Authentication** – Signup/Login with JWT authentication
- ✅ **Real-Time Messaging** – Send and receive messages instantly
- ✅ **Chat Rooms** – One-to-one and group chats
- ✅ **Profile Management** – Users can update their profile
- ✅ **Theme Customization** – Change the chat background theme
- ✅ **Online Status** – See which users are online
- ✅ **Secure Backend** – Uses bcrypt for password hashing

---

## Tech Stack
### Frontend
- React.js
- Tailwind CSS
- React Router
- Redux (optional for state management)
- Socket.io-client (for real-time communication)

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose for database management)
- JWT (for authentication)
- bcrypt.js (for password encryption)
- Socket.io (for real-time communication)

---
## API Endpoints
### User Authentication
| Method | Endpoint               | Description             |
|--------|------------------------|-------------------------|
| POST   | `/api/v1/user/register` | Register a new user     |
| POST   | `/api/v1/user/login`    | Login user             |
| GET    | `/api/v1/user/logout`   | Logout user            |

### Chat Routes
| Method | Endpoint              | Description                  |
|--------|-----------------------|------------------------------|
| GET    | `/api/v1/chat`        | Get all user chats           |
| POST   | `/api/v1/chat`        | Create a new chat            |
| GET    | `/api/v1/chat/:id`    | Get messages of a chat       |
| POST   | `/api/v1/message`     | Send a message               |

---

## Screenshots
![3](https://github.com/user-attachments/assets/848901fb-f8f3-4bdd-a50f-b0e1145f602f)
![2](https://github.com/user-attachments/assets/cc22da7e-bf9c-4080-9f8e-8413ecb1916c)
![1](https://github.com/user-attachments/assets/b46f982d-3749-473a-a837-77ef6471e052)




## License
This project is **MIT Licensed**.

## Developed By Priyanshu Kumar Pandey
