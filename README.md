# 🎵 Lyrics API Project

This is a simple web application built with **Streamlit** that allows users to search for song lyrics using the [lyrics.ovh](https://lyrics.ovh) API.

---

## 🌟 Features
- Search for song lyrics by artist/band and song title.
- User-friendly interface powered by **Streamlit**.
- Displays lyrics or returns an error message if the song/artist combination is not found.

---

## 🚀 Live Demo
Check out the live app: [Lyrics API App](https://lyrics-api-gzg9pouc8j5kwjfcvrvk2s.streamlit.app)

---

## 🛠️ Technologies Used
- **Python**: Core programming language.
- **Streamlit**: Framework for creating web-based user interfaces.
- **Requests**: For making HTTP requests to the lyrics API.
- **Poetry**: Dependency management and virtual environment.

---

## 📝 How to Run Locally
Follow these steps to run the project on your machine:

### 1. Clone the Repository
```bash
git clone git@github.com:D-Salge/lyrics-api.git
cd lyrics-api
```

### 2. Install Dependencies
Ensure you have **Poetry** installed. Then, run:
```bash
poetry install
```

### 3. Run the Application
Start the Streamlit app:
```bash
poetry run streamlit run app.py
```

### 4. Open in Your Browser
The application will run locally at:
```
http://localhost:8501
```

---

## 📚 File Structure
- **`app.py`**: Main application file.
- **`pyproject.toml`**: Dependencies and project settings managed by Poetry.
- **`poetry.lock`**: Lock file for consistent dependency resolution.
- **`teste.ipynb`**: Jupyter Notebook for additional testing or documentation.

---

## 📸 Screenshots
![App Screenshot](https://i.imgur.com/SmktDIH.png)

---

## 🤝 Contributing
Contributions are welcome! If you'd like to improve this project:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your message here"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

## 💡 Inspiration
This project was created as a practice exercise to learn and demonstrate skills in Python and web development using Streamlit.
