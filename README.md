
# Steven's Blog

A dynamic and responsive blog website built with HTML, CSS, and JavaScript. Users can sign up, sign in, and enjoy personalized experiences such as welcome messages and session-based logout functionality.

## 🚀 Features

- Responsive homepage with featured articles
- Quick-read swiper section
- Sign up & Sign in functionality using `localStorage`
- Welcome message for logged-in users
- Logout button that dynamically appears when signed in
- Trending articles, popular tags, and newsletter section
- Fully mobile responsive layout

## 🛠 Tech Stack

- HTML5
- CSS3
- JavaScript (Vanilla)
- Swiper.js for sliders
- LocalStorage for session handling

## 📂 Project Structure

/project-root │ ├── index.html ├── signin.html ├── signup.html ├── assets/ │ ├── css/ │ │ ├── main.css │ │ ├── signin.css │ │ └── signup.css │ ├── js/ │ │ └── main.js │ └── images/ │ ├── featured/ │ ├── trending/ │ ├── quick_read/ │ └── tags/


## 🔐 User Authentication

- Accounts are stored in `localStorage` under the key `user`
- Logged-in session is stored as `loggedInUser`
- Homepage checks for `loggedInUser` to display a welcome message and logout option

## 💻 Getting Started

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/stevens-blog.git
   ## 🖼 Screenshot

![Homepage Screenshot](./assets/images/final%20project%20screenshot.png)

