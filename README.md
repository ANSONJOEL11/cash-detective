# Cash Detective

Expense Tracker is a web application built with Next.js, Firebase, and Tailwind CSS that allows users to track their expenses. Users can log in or register, add and view their transactions, and see a summary of their total balance.

## Features

The application enables secure user authentication through Firebase, allowing users to create accounts and log in. On the dashboard, users can add transactions, view their transaction history, and access the total balance. 
Leveraging Firebase Realtime Database, the app provides real-time updates to the transaction list, ensuring up-to-date information. With a responsive design, the application delivers an optimal user experience on desktop and mobile devices. 
Robust error handling mechanisms are in place to manage errors gracefully, ensuring a seamless user experience.

## Installation

npm install

Set up Firebase:

   - Create a new Firebase project at [https://console.firebase.google.com](https://console.firebase.google.com) and enable Firebase Authentication and Realtime Database.
   - Copy the Firebase configuration settings and replace them in the `.env.local` file:

     ```
     NEXT_PUBLIC_FIREBASE_API_KEY=<YOUR_API_KEY>
     NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=<YOUR_AUTH_DOMAIN>
     NEXT_PUBLIC_FIREBASE_DATABASE_URL=<YOUR_DATABASE_URL>
     NEXT_PUBLIC_FIREBASE_PROJECT_ID=<YOUR_PROJECT_ID>
     NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=<YOUR_STORAGE_BUCKET>
     NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=<YOUR_MESSAGING_SENDER_ID>
     NEXT_PUBLIC_FIREBASE_APP_ID=<YOUR_APP_ID>
     ```

Start the development server:

npm run dev


5. Open your browser and visit [http://localhost:3000](http://localhost:3000) to see the app.

## Technologies Used

- Reactfire: A library that provides hooks and components for Firebase integration in React applications.
- Next.js: A React framework for building server-rendered applications.
- Firebase: A platform that provides various services including authentication and real-time database.
- Tailwind CSS: A utility-first CSS framework for rapid UI development.

