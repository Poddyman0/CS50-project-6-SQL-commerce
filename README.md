# Project Description

The Commerce project is a web-based auction platform where users can post auction listings, place bids, comment on listings, and manage their watchlists. The site emulates the core functionalities of eBay, allowing users to interact with auction items, track bidding, and engage in discussions. It also includes features for users to manage their watchlist and categorize items, providing a comprehensive auction experience.

## Technologies Used

- **Django**: A high-level Python web framework that facilitates rapid development and clean, pragmatic design.
- **Python**: The programming language used to build the application logic and interact with Django.
- **PostgreSQL**: A powerful, open-source relational database system used to store data.
- **Bootstrap**: A front-end framework to design and style the user interface.
- **HTML/CSS**: Markup and styling languages for creating the structure and appearance of web pages.

## Features

### User Authentication

- **Registration/Login/Logout**: Users can create accounts, log in, and log out.
- **Authentication Check**: Different content is shown based on user authentication status.

### Auction Listings

- **Create Listing**: Users can create new auction listings with details such as title, description, starting bid, image URL, and category.
- **Active Listings Page**: Displays all currently active auctions with details like title, description, current price, and photo.

### Listing Details

- **View Listing**: Users can view detailed information about a specific auction listing.
- **Bid on Listing**: Signed-in users can place bids on listings, with validation to ensure bids meet the minimum requirements.
- **Add/Remove Watchlist**: Users can add or remove listings from their watchlist.
- **Close Auction**: The listing creator can close the auction, marking it as complete and assigning the highest bidder as the winner.
- **Comment on Listing**: Users can add comments to a listing and view all comments made on that listing.

### Watchlist

- **Manage Watchlist**: Signed-in users can view and manage their watchlist of favorite listings.

### Categories

- **Category Pages**: Users can view all categories and see active listings within a selected category.

### Admin Interface

- **Django Admin**: Admins can view, add, edit, and delete listings, comments, and bids.

Setup Instructions and Running the Code in a Browser
Download the Project
Clone or download the project files from the repository.

Navigate to Project Directory
Open a terminal and navigate (cd) into the project directory: cd CS50-project-6-SQL-commerce

Set Up the Environment
Make sure you have Django and PostgreSQL installed. Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Configure Database
Update the settings.py file with your PostgreSQL credentials. Then, apply migrations:

bash
Copy code
python manage.py migrate
Create a Superuser (Optional for Admin Access)
Run:

bash
Copy code
python manage.py createsuperuser
Start the Web Server
Run:

bash
Copy code
python manage.py runserver
Open the application in your browser at http://127.0.0.1:8000/.

Explore the Auction Platform
Register or log in to access features like creating listings, placing bids, managing watchlists, and more.
