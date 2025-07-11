# 🌍 Interactive Map Chat Application

This Flask-based application integrates an interactive map interface with a powerful chat model (Google Gemini) to provide location-specific information and interactive conversational capabilities.

## 🚀 Features

* **Interactive Map:** Click anywhere to select locations, get detailed address information, and store multiple locations.
* **Integrated Search Bar:** Quickly search and navigate to any place.
* **Conversational AI:** Ask questions about selected locations using Gemini, and receive detailed responses in a conversational format.
* **Easy Location Management:** Add, view, and remove selected locations seamlessly.
* **User-Friendly UI:** Stylish, intuitive interface with smooth transitions, aesthetic fonts, and responsive design.

## 🎯 Usage

### 📌 Selecting Locations:

* Click anywhere on the map to select a location.
* The location is stored with address details and shown clearly in the chat window.

### 📌 Asking Questions:

* Type your query about selected locations in the chat input box.
* Gemini AI provides detailed, contextually-aware responses formatted clearly with Markdown support.

### 📌 Managing Locations:

* Easily remove mistakenly added locations using the integrated remove functionality next to each location.

### 📌 Chat Interface:

* Hide or show the chat interface using the toggle button (top-right corner).

## 💻 Technologies Used

* **Frontend:** HTML, CSS, JavaScript, Leaflet.js, Leaflet Control Geocoder, marked.js (Markdown rendering)
* **Backend:** Python, Flask, Google Gemini API
* **Deployment:** Render (recommended)

## ⚙️ Installation & Setup

### 📌 Clone Repository

```bash
git clone <repository_url>
cd map_chat_llm
```

### 📌 Install Dependencies

```bash
pip install -r requirements.txt
```

### 📌 Environment Variables

Create a `.env` file in the project root and define:

```env
GEMINI_API_KEY=<Your_Gemini_API_Key>
SECRET_KEY=<Random_Secret_Key_for_Session>
```

Generate `SECRET_KEY` easily:

```python
import os; print(os.urandom(24))
```

### 📌 Run the Application Locally

```bash
python app.py
```

Open your browser at: [http://127.0.0.1:5000](http://127.0.0.1:5000)

## 🌐 Deployment

The app is easily deployable on platforms like **Render**, **PythonAnywhere**, or **Heroku**.

**Recommended:** Follow deployment instructions clearly detailed for [Render](https://render.com/) or your chosen hosting service.

## 📸 Screenshots

(Add clear and illustrative screenshots of your running application here.)

## 📝 License

MIT License. Feel free to use, modify, and distribute.
