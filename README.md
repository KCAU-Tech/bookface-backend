# Bookface Backend

## Description

Bookface is a social media platform designed exclusively for KCA University students. It allows students to interact, share posts, comment, like, and message each other.

## Tech Stack

- **Backend:** Firebase

## Running Locally

To set up the backend locally for development and contribution, follow these steps:

### Prerequisites

- [Node.js installed](https://nodejs.org/en/download)
- Firebase CLI installed:
   ```sh
   npm install -g firebase-tools
   ```
- [Postman installed](https://www.postman.com/downloads/)

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
4. Start the development server:
   ```sh
   firebase emulators:start
   ```
5. Testing API Endpoints:

   Get the URL in the format of:
   ```sh
   http://127.0.0.1:<PORT>/bookface-backend/us-central/helloWorld
   ```

## How to Contribute

To contribute to the project, follow these steps:

1. Create a new branch from the `dev` branch using the format `feature-branch-name`:
   ```sh
   git checkout -b feature-branch-name dev
   ```
2. Push your code to the newly created branch:
   ```sh
   git push origin feature-branch-name
   ```
3. Create a pull request (PR) with at least one reviewer.
4. Wait for your PR to be reviewed and approved before merging.

Now you can contribute to the backend locally!

