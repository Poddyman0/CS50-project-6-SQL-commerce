<strong>Project Title:</strong> E-Commerce Auction Platform

<strong>Description:</strong>
This project involves designing an eBay-like e-commerce auction site where users can post auction listings, place bids, comment on listings, and manage their watchlist. The site uses Django for backend functionality and provides a comprehensive user interface to manage auction listings and user interactions.

<strong>Features:</strong>
<strong>Models:</strong>

<ul>
  <li><strong>User:</strong> Inherits from Django's AbstractUser.</li>
  <li><strong>Listing:</strong> Represents an auction listing with fields for title, description, starting bid, current price, image URL, and category.</li>
  <li><strong>Bid:</strong> Represents a bid placed by a user on a listing.</li>
  <li><strong>Comment:</strong> Represents a comment made by a user on a listing.</li>
  <li><strong>Category:</strong> Represents categories for auction listings.</li>
</ul>
<ul>
  <li><strong>Create Listing:</strong> Users can create a new listing by providing a title, description, starting bid, optional image URL, and category. Created listings are displayed on the Active Listings Page.</li>
  <li><strong>Active Listings Page:</strong> Displays all active auction listings with title, description, current price, and optional photo. Users can click on a listing to view its details.</li>
  <li><strong>Listing Page:</strong> Provides details of a specific listing including the current price. Signed-in users can add/remove the item from their watchlist, place bids, or close the auction if they are the creator. Users can add comments to the listing.</li>
  <li><strong>Watchlist:</strong> Displays all listings that a user has added to their watchlist.</li>
  <li><strong>Categories:</strong> Lists all categories and allows users to view all active listings in a specific category.</li>
  <li><strong>Django Admin Interface:</strong> Admins can view, add, edit, and delete listings, comments, and bids through Django’s admin interface.</li>
</ul>
