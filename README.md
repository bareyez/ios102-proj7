# Product Spec Design: *Ex Libris Moi* 📚

### 📲 App Description

Ex Libris Moi is a personal library management system that helps users catalog their books and media, track lending activities, and explore new titles. The app provides an elegant and minimalist user interface for organizing collections and interacting with friends or the community.

## 🧾 User Stories

The following are features within the app that the user is able to do. They are separated by "must-have" (required) and "nice-to-have" (optional).

#### Required Stories

For Ex Libris Moi, I identified the following required features which a user needs to be able to perform the app to work:

- User is able to add, edit, and delete books or media from a personal library
    - *User can scan ISBN/UPC barcode to add media via external API*
    - User can search and filter by title, author, genre, or year
- User is able to explore new books/media through an external API
    - User is able to add books from discovery to a wishlist
- User can check-in/check-out books to track lending and borrowing
    - Record borrower details (name, profile, contact)
    - Mark items as returned
- User is able to manage user account and log off
- Tab-based navigation with Home, Discover, Community (optional), Lending, and Profile

#### Optional Stories
- User can share collections or book recommendations
- View borrowing stats or ratings of shared titles
- User can send reminders for overdue or upcoming returns
- Wishlist is able to lead to an online store to buy book

## 🤳 Screens

The following are the screens that the user will encounter while working in the app. Like the features, they are separated by required and optional.

### Required Screens

- Home Screen
    - Displays the user's library collection
    - Includes search, filter, and sort functionalities
    - Allows user to scan new books into their collection
- Discover Screen
    - Shows feed of books/media from external sources
    - Allows users to add new items to a wishlist 
- Lending Screen
    - Tracks books lent out and borrowed
    - Includes status labels like "Due soon" and "Borrowed out"
    - Add new loans and mark items as returned
- Profile Screen
    - User account details and app settings
    - Options to log out
 
## Optional Screens

- Community Screen
    - A social feed for recommendations and shared collections
 
## 🔄️ Navigation Flow

### Tab Navigation (Tab to Screen)

- Home/overall personal library
- Discover new titles
- Lending
- Profile

### Flow Navigation

- Login/sign up screen => Home
- Home => Add new book/media
- Discover titles => View wishlist
- (For future version) Community feed (Find friends) => Create post
- Lending/manage loans => Add new loan
- Profile => Login/sign up screen (if user logs out)
