# 🌦 Weather It

A live weather web app with geolocation, animated weather effects on HTML5 Canvas, and an hourly forecast. Built with vanilla JavaScript and containerised with Docker.

<!-- Add a screenshot or GIF here — this is the single most important thing in a project README.
     Put an image in the repo (e.g. /screenshot.png) and link it: -->
![Weather It Screenshot](screenshot.png)

<!-- If you have a live version, add it here: -->
🔗 **Live Demo:** [add your live link]

---

## ✨ Features

- 📍 **Geolocation** — detects your location and shows local weather instantly
- 🔍 **City search with autocomplete** — 80+ cities including Cuttack & Bhubaneswar
- 🌧 **Animated Canvas effects** — live rain, snow, and lightning rendered on HTML5 Canvas
- ⏱ **Hourly forecast** — see how the day ahead looks
- 🌗 **Dark / light mode** toggle
- 💀 **Skeleton loaders** for smooth loading states
- 🐳 **Fully containerised** with Docker

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, JavaScript |
| Graphics | HTML5 Canvas API |
| Weather Data | [name the weather API you used, e.g. OpenWeatherMap] |
| Deployment | Docker, [Netlify / GitHub Actions if used] |

---

## 🚀 Getting Started

### Run locally

```bash
# 1. Clone the repo
git clone https://github.com/Amanaich/weather-it.git

# 2. Go into the folder
cd weather-it

# 3. Open index.html in your browser
#    (or use a local server, e.g. VS Code Live Server)
```

<!-- If your app needs an API key, tell people how to add it: -->
### API key setup

This app uses the [weather API name] API.
1. Get a free API key from [link].
2. Add it in `[file where the key goes]`:
   ```js
   const API_KEY = "your_api_key_here";
   ```

### Run with Docker

```bash
docker build -t weather-it .
docker run -p 8080:80 weather-it
```
Then open `http://localhost:8080`.

---

## 📸 Screenshots

<!-- Add 2–3 images: normal view, rain/snow animation, dark mode -->
| Light Mode | Dark Mode | Rain Effect |
|---|---|---|
| ![light](light.png) | ![dark](dark.png) | ![rain](rain.png) |

---

## 🧠 What I Learned

- Rendering real-time animations with the Canvas API
- Working with a third-party weather API and handling async requests
- Managing loading and error states for a smooth UX
- Containerising a frontend app with Docker

---

## 📫 Contact

**Aman Anshuman Aich**
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/amanaich)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:amananshumanaich@gmail.com)
