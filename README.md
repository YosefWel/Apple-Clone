Apple Clone
Apple.com clone web application built with React.js, using a JSON file for static data and the YouTube API to fetch Apple's YouTube channel content.

🚀 Motivation
I aimed to recreate the Apple.com website while enhancing it by integrating the YouTube API. This addition allows users to access Apple's official YouTube content directly from the site, making it both functional and interactive.

📝 Description
Backend:
Static JSON data is used, which is located in the public folder to simulate the backend.
Frontend:
Built with React.js and styled with CSS, Bootstrap, and jQuery.
Integrated the YouTube API (Google Cloud) to display Apple's official YouTube channel content dynamically.
📊 Build Status
Live Demo: (https://yosefclone.netlify.app/)

🛠️ Technologies Used
React.js
CSS
jQuery
Bootstrap
APIs: YouTube API (Google Cloud)
⚙️ Requirements
Node.js
Google Cloud YouTube API Key
Apple's YouTube Channel ID
🛠️ Setup Instructions
Clone the Repository

bash
Copy code
git clone https://github.com/YosefWel/Apple-Clone.git
Navigate to the Client Directory

bash
Copy code
cd client
Install Dependencies

bash
Copy code
npm install
Set Up API Keys
Create a .env file in the client directory and add the following:

bash
Copy code
VITE_API_KEY=<your_youTube_api_key>
VITE_APP_CHANNEL_ID=<your_channel_id>
Run the Application

bash
Copy code
npm run dev
Access the App
Open your browser and navigate to http://localhost:5173 (default Vite port).

🌟 Features
Dynamic YouTube Integration: Fetches and displays videos directly from Apple's official YouTube channel.
Static JSON Data: Provides content for simulating backend responses.
Responsive Design: Styled with CSS, Bootstrap, and jQuery for cross-device compatibility.
