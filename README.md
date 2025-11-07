# ⚡ FlashPass  
**AI-Powered Flashcard Application**

FlashPass is a full-stack web application that leverages **AI to generate personalized flashcards** from user input. It combines a responsive **Next.js/React frontend**, a **Node.js backend**, and the **OpenAI API** to deliver an intelligent study experience — deployed on **Amazon EC2** for scalability and reliability.

---

## 🚀 Features

- 🧠 **AI-Generated Flashcards:** Dynamically creates flashcards using the OpenAI API based on user-provided topics.  
- 🔐 **User Authentication:** Integrated with **Clerk** for secure sign-in and session management.  
- 💳 **Subscription Management:** Utilizes **Stripe** for handling premium subscriptions and payments.  
- ⚡ **Real-Time Sync:** Built with **Firebase** to provide live flashcard updates and progress tracking.  
- ☁️ **Cloud Deployment:** Hosted on **Amazon EC2**, ensuring scalable performance and uptime.

---

## 🧩 Tech Stack

| Layer | Technologies |
|-------|---------------|
| **Frontend** | Next.js, React, Material-UI |
| **Backend** | Node.js, Express.js |
| **AI Integration** | OpenAI API |
| **Authentication** | Clerk |
| **Database / Sync** | Firebase |
| **Payments** | Stripe |
| **Hosting / Deployment** | Amazon EC2 |

---

## 🛠️ Getting Started

Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/flashpass.git
cd flashpass
npm install
````

Run the development server:

```bash
npm run dev
```

Then open [**http://localhost:3000**](http://localhost:3000) to view the app.

---

## 📦 Environment Variables

Create a `.env.local` file in the root directory and include the following keys:

```
OPENAI_API_KEY=
STRIPE_SECRET_KEY=
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
FIREBASE_API_KEY=
FIREBASE_PROJECT_ID=
```

---

## ☁️ Deployment

FlashPass is deployed on **Amazon EC2** using a Node.js server configuration optimized for scalability.
You can also deploy via [**Vercel**](https://vercel.com/) or any platform that supports Next.js apps.

---


## 🤝 Contributing

Contributions are welcome!
Feel free to fork the repository, open issues, or submit pull requests.

