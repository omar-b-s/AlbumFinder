# 🎵 AlbumFinder

AlbumFinder is a React app that lets you search for artists on Spotify and view their albums in a clean, card-based interface. It uses the [Spotify Web API](https://developer.spotify.com/documentation/web-api/) and React-Bootstrap for styling.

## 🚀 Features
- Search for any artist on Spotify
- Display albums in card format with:
  - Album cover
  - Album name
  - Release date
  - Direct link to the album on Spotify
- Responsive layout using React-Bootstrap
- Securely manages Spotify API keys with environment variables (`.env` file)

## 🛠️ Tech Stack
- React
- Vite
- React-Bootstrap
- Spotify Web API

## 📦 Installation

```bash
# 1. Clone the repository
git clone https://github.com/omar-b-saleh/AlbumFinder.git
cd AlbumFinder

# 2. Install dependencies
npm install

# 3. Create a .env file in the project root and add your Spotify credentials
echo "VITE_CLIENT_ID=your_client_id_here" >> .env
echo "VITE_CLIENT_SECRET=your_client_secret_here" >> .env

# 4. Start the development server
npm run dev

# 5. Open the app in your browser
# Default: http://127.0.0.1:5173/
