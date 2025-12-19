🃏 Slave Online - Ultimate Card Game

Slave Online is a real-time multiplayer web-based card game built with React (Single File) and Firebase Firestore. Experience the classic Thai card game "Slave" with advanced rules like King Down, Auto-Exchange, and Dynamic Turn Direction directly in your browser.

🎮 Play (https://slave-card-game-online.onrender.com/)

✨ Features

Real-time Multiplayer: Play seamlessly with friends using Firebase Firestore synchronization.

Room System: Create private rooms and join via unique 5-character codes.

Advanced Game Rules:

👑 King Down: The King must win 1st place, or they become Slave immediately in the next round.

🔄 Reverse Flow: If a winner clears the trick, the turn direction reverses!

🔀 Auto-Exchange: Automatic card exchange system for King/Slave and Queen/People.

Responsive UI: Optimized for both Desktop and Mobile devices.

Interactive UX:

Visual hints for playable cards (Grayscale for invalid moves).

Auto-select helper for Pairs/Triples/Quads.

Immersive sound effects (Synthesized Web Audio API).

Custom Avatars: Choose from cute emojis, including the legendary Pear 🍐.

📸 Screenshots
Lobby Screen
<img width="1919" height="899" alt="1" src="https://github.com/user-attachments/assets/10985488-03f9-45fd-9c8e-ab88e3580169" />
<img width="1916" height="465" alt="2 1" src="https://github.com/user-attachments/assets/3dd12107-5ba8-4414-ba59-c6ae4004514f" />
<img width="1919" height="904" alt="3" src="https://github.com/user-attachments/assets/fd86eaef-0d72-4437-80cf-c725b27d3e46" />
Gameplay Action
<img width="1919" height="904" alt="4" src="https://github.com/user-attachments/assets/28906a5a-1a91-4a4e-b10a-65d125023d15" />
<img width="1919" height="897" alt="5" src="https://github.com/user-attachments/assets/857d23fe-b603-4674-88cf-3c1df51f4055" />
<img width="1919" height="908" alt="6" src="https://github.com/user-attachments/assets/2069a687-1ef4-42f1-a571-e2f8308f11b1" />
<img width="1919" height="912" alt="11" src="https://github.com/user-attachments/assets/d0379fce-a665-4975-8e07-46c7ed0e0d36" />
![7](https://github.com/user-attachments/assets/5cc43550-a4ad-418a-806c-d78fe8447cdf)
<img width="1919" height="898" alt="8" src="https://github.com/user-attachments/assets/088192fb-0971-4d6d-a46f-d960ae77c311" />
<img width="1919" height="902" alt="9" src="https://github.com/user-attachments/assets/ffad731c-5819-481f-8572-aca2e1200dd2" />
<img width="1919" height="899" alt="10" src="https://github.com/user-attachments/assets/f2388295-5274-4b21-a424-9d9f8317b877" />









<!-- Replace placeholder links with your actual image URLs -->

🛠️ Technology Stack

This project demonstrates the power of modern web technologies in a single-file format:

Frontend: HTML5, React 18 (via CDN), Tailwind CSS (via CDN)

Backend: Firebase (Authentication & Firestore)

Tools: Babel (Standalone for JSX compilation)

Audio: Web Audio API (No external assets required)

🚀 How to Run

Prerequisites

A modern web browser (Chrome, Edge, Safari).

A Firebase Project.

Setup Steps

Clone the repository

git clone [https://github.com/your-username/slave-online.git](https://github.com/your-username/slave-online.git)
cd slave-online


Configure Firebase

Go to Firebase Console.

Create a new project and enable Firestore and Authentication (Anonymous).

Open index.html.

Replace the firebaseConfig object with your own credentials:

const firebaseConfig = {
    apiKey: "YOUR_API_KEY",
    authDomain: "YOUR_PROJECT.firebaseapp.com",
    projectId: "YOUR_PROJECT_ID",
    // ... other config
};


Run Locally

Simply open index.html in your browser!

Or use a local server (e.g., Live Server in VS Code).

Deploy

Push to GitHub and deploy using Render (Static Site), Vercel, or GitHub Pages.

📜 Game Rules

Ranking: 2 > A > K > Q > J > 10 ... > 3.

Suits: ♠ Spades > ♥ Hearts > ♦ Diamonds > ♣ Clubs.

Starting: The player with 3♣ starts the first game.

Winning: The first player to run out of cards becomes King. The last is Slave.

Exchange:

Slave gives 2 best cards to King.

King gives 2 cards back to Slave.

(Similar rule applies for Queen/People with 1 card).

🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

📄 License

This project is open source and available under the MIT License.

<p align="center">Made with ❤️ by Anucha Saelee</p>

