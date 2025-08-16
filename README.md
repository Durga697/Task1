🎬 Movie Analytics with OMDb API

This project fetches movie data from the OMDb API and visualizes it using Python, Matplotlib, and Seaborn.
It includes both Tollywood and Hollywood movies, analyzing aspects such as IMDb ratings, runtimes, genres, and release years.

📌 Features

✅ Fetches real-time movie data from OMDb API

✅ Handles multiple movies (Tollywood + Hollywood)

✅ Extracts details such as:

Title

Year

IMDb Rating

Runtime

Genre

✅ Generates insightful visualizations:

IMDb Ratings (Bar Chart)

Movie Runtimes (Line Plot)

Genre Frequency (Bar Chart)

Movie Release Years (Scatter Plot)

IMDb Rating vs Runtime (Scatter Plot)

Top 5 Most Common Genres (Bar Chart)

📊 Sample Visualizations
IMDb Ratings of Movies

Genre Frequency

(Add your generated plots in an assets/ folder and update the links.)

🚀 Getting Started
1️⃣ Clone Repository
git clone https://github.com/your-username/movie-analytics-omdb.git
cd movie-analytics-omdb

2️⃣ Install Dependencies

Make sure you have Python 3.7+ installed.
Install required libraries:

pip install requests matplotlib seaborn pandas

3️⃣ Set Up API Key

Get your free OMDb API key from 👉 OMDb API

Replace it in the script:

API_KEY = "your_api_key_here"

4️⃣ Run the Script
python movie_analysis.py

📂 Project Structure
movie-analytics-omdb/
│── movie_analysis.py      # Main Python script
│── README.md              # Documentation
│── requirements.txt       # Dependencies (optional)
│── assets/                # Store generated plots

🔮 Future Improvements

Add support for more industries (Bollywood, Korean Cinema, etc.)

Store data in a CSV/Excel file for further analysis

Build an interactive dashboard with Plotly/Dash

🤝 Contributing

Contributions are welcome!

Fork the repo

Create a new branch (feature-branch)

Commit your changes

Open a Pull Request

📜 License

This project is licensed under the MIT License.
