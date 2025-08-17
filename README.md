# SkyCast - Weather Dashboard Application 🌤️

A modern, full-stack weather application built with React, TypeScript, and Express.js. Get real-time weather information, forecasts, and beautiful data visualizations.

## ✨ Features

- 🌍 **Global Weather Data** - Get weather information for any city worldwide
- 📊 **Interactive Charts** - Beautiful weather visualizations with Recharts
- 📱 **Responsive Design** - Works perfectly on desktop and mobile devices
- 🌓 **Dark/Light Mode** - Theme switching with persistent preferences
- ⭐ **Favorite Cities** - Save and quick-access your favorite locations
- 🔍 **Smart Search** - City search with autocomplete and search history
- 📈 **Weather Forecasts** - Hourly and daily weather predictions
- 🎨 **Modern UI** - Built with Shadcn/ui and Tailwind CSS

## 🚀 Tech Stack

### Frontend
- **React 18** with TypeScript
- **Vite** for fast development and building
- **Tailwind CSS** for styling
- **Shadcn/ui** for component library
- **Tanstack Query** for data fetching
- **Recharts** for data visualization
- **React Router** for navigation

### Backend
- **Express.js** with TypeScript
- **OpenWeatherMap API** for weather data
- **CORS** enabled for cross-origin requests
- **dotenv** for environment configuration

## 📦 Installation & Setup

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn
- OpenWeatherMap API key (free at [openweathermap.org](https://openweathermap.org/api))

### 1. Clone the repository
```bash
git clone https://github.com/agastya75/SkyCast.git
cd SkyCast
```

### 2. Install dependencies

**Frontend:**
```bash
npm install
```

**Backend:**
```bash
cd backend
npm install
cd ..
```

### 3. Environment Setup

Create a `.env` file in the root directory:
```env
VITE_OPENWEATHER_API_KEY=your_openweathermap_api_key_here
```

Create a `.env` file in the `backend` directory:
```env
WEATHER_API_KEY=your_openweathermap_api_key_here
OPENWEATHER_API_KEY=your_openweathermap_api_key_here
PORT=5000
```

### 4. Get your OpenWeatherMap API Key
1. Go to [OpenWeatherMap](https://openweathermap.org/api)
2. Sign up for a free account
3. Navigate to API keys section
4. Copy your API key and replace `your_openweathermap_api_key_here` in both `.env` files

## 🏃‍♂️ Running the Application

### Development Mode

**Start the backend server:**
```bash
cd backend
npm start
```
Backend will run on `http://localhost:5000`

**Start the frontend development server:**
```bash
npm run dev
```
Frontend will run on `http://localhost:5173`

### Production Build

**Build the frontend:**
```bash
npm run build
```

**Preview the production build:**
```bash
npm run preview
```

## 🐳 Docker Support

The application includes Docker configuration for easy deployment:

```bash
# Build and run with Docker Compose
docker-compose up --build
```

## 📱 Usage

1. **Search for Cities**: Use the search bar to find weather information for any city
2. **View Current Weather**: See current temperature, conditions, and details
3. **Check Forecasts**: Browse hourly and daily weather predictions
4. **Save Favorites**: Star cities to quickly access them later
5. **Toggle Themes**: Switch between light and dark modes
6. **Explore Charts**: View temperature trends and weather patterns

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



## 👨‍💻 Author

**Agastya Joshi** - [agastya75](https://github.com/agastya75)

---

⭐ Star this repository if you found it helpful!
