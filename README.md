# 📺 YouTube Clone

A fully responsive YouTube clone built with **React.js**, powered by the **YouTube Data API**, and styled with **Tailwind CSS** and **Material UI**. Browse videos, view channel details, search for content, and watch videos — all in a sleek, YouTube-inspired interface.

---

## 🚀 Live Demo

> _Coming soon / Add your deployed URL here_

---

## ✨ Features

- 🏠 **Home Feed** — Browse trending and categorized videos
- 🔍 **Search** — Search for any video on YouTube
- 📺 **Video Playback** — Watch videos with a full-featured player
- 📡 **Channel Details** — View channel info and related videos
- 🌙 **Dark Mode** — Toggle between light and dark themes
- 📱 **Responsive Design** — Works seamlessly on all screen sizes

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| [React.js](https://reactjs.org/) | Frontend UI library |
| [React Router DOM](https://reactrouter.com/) | Client-side routing |
| [Redux Toolkit](https://redux-toolkit.js.org/) | State management |
| [Axios](https://axios-http.com/) | API requests |
| [Material UI](https://mui.com/) | UI components |
| [Tailwind CSS](https://tailwindcss.com/) | Utility-first styling |
| [React Player](https://github.com/cookpete/react-player) | Video playback |
| [React Icons](https://react-icons.github.io/react-icons/) | Icon library |
| [YouTube Data API v3](https://developers.google.com/youtube/v3) | Video & channel data |

---

## 📁 Project Structure

```
youtube-clone/
├── public/
│   └── index.html
├── src/
│   ├── assets/            # Static assets (images, etc.)
│   ├── components/        # Reusable UI components
│   │   ├── Navbar.jsx
│   │   ├── Sidebar.jsx
│   │   ├── VideoCard.jsx
│   │   └── DarkModeButton.jsx
│   ├── pages/             # Page-level components
│   │   ├── Feed.jsx
│   │   ├── VideoDetails.jsx
│   │   ├── ChannelDetails.jsx
│   │   └── SearchFeed.jsx
│   ├── redux/             # Redux state slices
│   ├── utils/             # Helper functions & API config
│   ├── App.js
│   └── index.js
├── Dockerfile
├── package.json
└── tailwind.config.js
```

---

## ⚙️ Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) v16+
- A **YouTube Data API v3** key from [Google Cloud Console](https://console.cloud.google.com/)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/youtube-clone.git
   cd youtube-clone
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**

   Create a `.env` file in the root directory:
   ```env
   REACT_APP_YOUTUBE_API_KEY=your_youtube_api_key_here
   ```

4. **Start the development server**
   ```bash
   npm start
   ```

   The app will be available at `http://localhost:3000`

---

## 🐳 Docker

You can also run the project using Docker:

```bash
docker build -t youtube-clone .
docker run -p 3000:3000 youtube-clone
```

---

## 📜 Available Scripts

| Command | Description |
|---|---|
| `npm start` | Run the app in development mode |
| `npm run build` | Build the app for production |
| `npm test` | Run the test suite |
| `npm run eject` | Eject from Create React App |

---

## 🔑 API Setup

This project uses the **YouTube Data API v3**. To get your API key:

1. Go to [Google Cloud Console](https://console.cloud.google.com/)
2. Create a new project
3. Enable the **YouTube Data API v3**
4. Generate an **API Key** under Credentials
5. Add the key to your `.env` file as shown above

---

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

1. Fork the project
2. Create your feature branch: `git checkout -b feature/AmazingFeature`
3. Commit your changes: `git commit -m 'Add some AmazingFeature'`
4. Push to the branch: `git push origin feature/AmazingFeature`
5. Open a Pull Request

---

## 📄 License

This project is licensed under the terms of the [MIT License](./License.md).

---

## 👤 Author

**Ayush Prabhavale**

- GitHub: [@AyushPrabhavale](https://github.com/AyushPrabhavale)

---

> ⭐ If you found this project helpful, please consider giving it a star!
