Recommendation System – Pages & People

A simple Python recommendation system that suggests pages and people using JSON data.
It includes two modules:

Pages You Might Like → recommends pages based on shared likes among users.

People You May Know → suggests potential friends based on mutual connections.

📂 Project Files

PagesYouMightLike.ipynb → Python code to recommend pages.

PeopleYouMayKnow.ipynb → Python code to recommend people.

massive.json → Sample dataset with users, friends, and liked pages.

⚙️ How It Works

Data Loading: Both scripts load user data from massive.json.

Pages Recommendation: Suggests new pages by analyzing overlap in liked pages across users.

People Recommendation: Suggests new friends based on mutual connections.

🚀 Usage

Run either script in Python:

python PagesYouMightLike.ipynb
python PeopleYouMayKnow.ipynb


Make sure massive.json is in the same directory.

🔑 Example Output
Pages You Might Like for User 1: [(101, 3), (102, 2)]
People You May Know for User 1: [5, 7, 9]

📌 Features

Simple, easy-to-read Python code.

Works on any dataset structured like massive.json.

Demonstrates basic recommendation logic using sets and mutual counts.
