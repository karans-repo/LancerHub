# LancerHub: Freelance Project Workspace

**LancerHub** is a full-stack MERN web application designed to streamline project management and collaboration between freelancers and clients. Unlike basic job boards, this platform focuses on the active project lifecycle from proposal bidding to real-time communication and deliverable management.

## 🚀 Key Features

*   **Role-Based Dashboards:** Distinct interfaces and functionality for 'Clients' and 'Freelancers'.
*   **Real-Time Collaboration:** Project-specific group chats and direct messaging powered by **Socket.IO**.
*   **Kanban Task Management:** Visual task tracking (To-Do, In-Progress, Done).
*   **Cloud Deliverables:** Secure file and image uploads using **Cloudinary**.
*   **Project Bidding System:** Freelancers can submit proposals, and clients can review and accept bids.
*   **Secure Authentication:** JWT-based sessions with Bcrypt encrypted passwords.

## 🛠️ Tech Stack

*   **Frontend:** React (Vite), React Router DOM, Tailwind CSS (Custom Styles), Axios
*   **Backend:** Node.js, Express.js
*   **Database:** MongoDB Atlas
*   **Real-time:** Socket.IO
*   **Storage:** Cloudinary

## 💻 Local Setup Instructions

1.  **Clone the Repository**
2.  **Install Dependencies**
    *   Navigate to `/Frontend` and run `npm install`
    *   Navigate to `/Backend` and run `npm install`
3.  **Environment Variables**
    *   Create a `.env` file in the `/Backend` directory (use `.env.example` as a template).
    *   Add your `MONGO_URI`, `JWT_SECRET`, and Cloudinary API credentials.
4.  **Run the Application**
    *   Backend: `npm start` (Runs on `http://localhost:5001` or your configured port)
    *   Frontend: `npm run dev` (Runs on `http://localhost:5173`)

## 👨‍💻 Author

**Karan Kabdal**
*   Email: karankabdal05@gmail.com
