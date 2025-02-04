# Bookface Backend

## Description

Bookface is a social media platform designed exclusively for KCA University students. It allows students to interact, share posts, comment, like, and message each other.

## Tech Stack

- **Backend:** Firebase

## Running Locally

To set up the backend locally for development and contribution, follow these steps:

### Prerequisites

- Node.js installed
- Firebase CLI installed

### Setup

1. Clone the repository:
   ```sh
   git clone https://github.com/KCAU-Tech/bookface-backend.git
   ```
2. Navigate to the project directory:
   ```sh
   cd bookface-backend
   ```
3. Install dependencies:
   ```sh
   cd functions
   npm install
   ```
4. Log in to Firebase:
   ```sh
   firebase login
   ```
5. Initialize Firebase project:
   ```sh
   firebase init
   ```
   Select Firestore and Functions when prompted.
6. Start the development server:
   ```sh
   firebase emulators:start
   ```

Now you can contribute to the backend locally!
