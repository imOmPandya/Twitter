# Twitter Clone

This project is a clone of Twitter built with Next.js, NextAuth, Firebase, Context API, and Tailwind CSS. It provides a platform where users can sign up using their Google accounts, and they can then post tweets, like tweets, and add comments to tweets. Users can post various types of content in their tweets, including text, photos, documents, and emojis.

## Features

- User authentication with Google Sign Up.
- Post tweets with various types of content (text, photos, documents, and emojis).
- Like tweets to show appreciation.
- Add comments to tweets.
- Responsive design with Tailwind CSS.

## Technologies Used

- Next.js: A React framework for building server-side rendered and static websites.
- NextAuth: An authentication library for Next.js applications.
- Firebase: A cloud-based platform for building web and mobile applications.
- Context API: A state management solution for React applications.
- Tailwind CSS: A utility-first CSS framework for building responsive designs.

## Getting Started

To get started with the project, follow these steps:

1. Clone the repository:

   ```shell
   git clone https://github.com/imOmPandya/Twitter.git

1. Install the dependencies:

cd Twitter
npm install

2. Set up Firebase configuration:

Create a Firebase project and enable authentication with Google.
Set up Firestore for database storage.
Obtain the Firebase configuration credentials.
Replace the placeholders in the src/firebase/config.js file with your Firebase configuration.

3. Run the development server:

npm run dev

4. Open your browser and visit http://localhost:3000 to see the application.
