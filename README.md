
🎬 Movie Recommendation System (Content-Based Filtering)
A movie recommendation system using Content-Based Filtering. Users can enter a movie name, and the system suggests similar movies based on their genres.

This project uses Flask, Pandas, scikit-learn, and TF-IDF Vectorization to compute recommendations based on movie content.


📌 Features
✅ Case-insensitive search (e.g., "avatar" matches "Avatar")
✅ Partial matching (e.g., "dark knight" matches "The Dark Knight")
✅ User-friendly interface (simple input form with recommendations)
✅ Real-time movie recommendations
✅ Responsive and clean UI


🛠️ Tech Stack
Backend: Flask, Pandas, Scikit-Learn
Frontend: HTML, CSS, JavaScript
Machine Learning Algorithm: TF-IDF Vectorization + Cosine Similarity
📂 Project Structure
csharp
Copy
Edit
📂 movie-recommendation
│── 📄 app.py             # Flask Backend
│── 📄 movie_dataset.csv  # Movie Data
│── 📂 templates          # HTML Frontend
│    ├── 📄 index.html    # Main UI
│── 📄 static             # CSS & JS Files (Optional)
│── 📄 README.md          # Documentation


🛠️ Installation & Setup
1️⃣ Clone the Repository
sh
git clone https://github.com/your-username/movie-recommendation.git
cd movie-recommendation

2️⃣ Install Dependencies
Make sure you have Python 3+ installed, then run:
sh
pip install flask pandas scikit-learn

3️⃣ Download the Movie Dataset
Place your movie dataset (movie_dataset.csv) in the project folder.
Ensure the dataset has at least id, title, and genres columns.

4️⃣ Run the Flask App
sh
python app.py

5️⃣ Open in Your Browser
Go to http://127.0.0.1:5000/ and start searching for movies! 🎬

🎯 How It Works
1️⃣ User enters a movie name.
2️⃣ System finds the closest match (case-insensitive, allows partial matching).
3️⃣ It calculates similar movies using TF-IDF Vectorization and Cosine Similarity.
4️⃣ Recommended movies are displayed in a clean list.

🔍 Example Searches
User Input	Matched Movie	Recommended Movies
dark knight	The Dark Knight	Inception, Batman Begins, Joker
avengers	The Avengers	Iron Man, Thor, Captain America
spider	Spider-Man	Spider-Man 2, The Amazing Spider-Man
xyz123	❌ No Match Found	Try another title


🚀 Future Improvements
🔹 Improve recommendations using movie descriptions
🔹 Add user-based collaborative filtering
🔹 Use Deep Learning (Neural Networks) for better results
🔹 Deploy the app online using Render, Heroku, or AWS

🤝 Contributing
1️⃣ Fork the repo
2️⃣ Create a new branch (git checkout -b feature-name)
3️⃣ Commit your changes (git commit -m "Added feature")
4️⃣ Push to your branch (git push origin feature-name)
5️⃣ Open a Pull Request 🚀

📜 License
📜 This project is licensed under the MIT License – feel free to modify and use it.

🙋‍♂️ Ajobe Ismail
👤 IsmailAyub-web
📧 liamsaje@gmail.com

🚀 Give a ⭐ if you like this project!
