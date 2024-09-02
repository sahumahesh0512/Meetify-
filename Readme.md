# videoconferencing-app Documentation

## About The Project

videoconferencing-app is a web-based video conferencing app built with ReactJS. You can start an instant meeting or schedule one for later. The app supports in-meeting chat and allows unlimited participants in a single meeting.


## Features

- Instant one-click meetings
- Meeting scheduling
- In-meeting chat
- Unlimited participants

## Tech Stack

- React
- Socket.io
- Tailwind CSS
- Bootstrap
- Node.js
- Express.js
- Gulp
- jQuery

## Folder Structure

```
├── src/
    ├── components/         code for different components
    ├── constants/          constant data
    ├── context/            code for firebase user authentication
    ├── firebase/           code related to firebase connection 
    ├── hooks/              custom hooks
    ├── page/               code of different pages
    ├── sounds/             used audio files
 
```
 
## Installation

1. Ensure you have [Node.js](https://nodejs.org/) v10+ installed.
2. Clone the repository:
    ```
    cd videoconferencing-app
    ```
3. Install dependencies:
    ```
    npm install
    ```
4. Start the development server:
    ```
    npm start
    ```
5. Open `http://localhost:3000` in your browser.

![Webpage](https://user-images.githubusercontent.com/84511419/194266338-6288daa8-9880-4d1e-8058-79ab1d2a1eb9.png)

## Getting Started

1. Fork the [repository](https://github.com/ashavijit/Meetify).
2. Clone your fork:
    ```
    git clone https://github.com/<your_user_name>/Meetify.git
    ```
3. Navigate to the project directory:
    ```
    cd Meetify
    ```
4. Add the original repository as a remote:
    ```
    git remote add upstream https://github.com/ashavijit/Meetify.git
    ```
5. Keep your fork updated:
    ```
    git pull upstream main
    ```
6. Create a new branch:
    ```
    git checkout -b <your_branch_name>
    ```
7. Make and commit your changes:
    ```
    git add .
    git commit -m "your message"
    ```
8. Push your branch:
    ```
    git push -u origin <your_branch_name>
    ```
9. Create a pull request on GitHub.


