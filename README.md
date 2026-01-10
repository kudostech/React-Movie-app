# MovieLand - Movie Recommendation App

MovieLand is a simple and interactive web application built with **React** that allows users to search for movies using the **OMDb API**. It displays movie information such as title, year, type, and poster in a user-friendly interface.

Visit website here:[https://react-movie.app/](https://react-movie-app-kudos.vercel.app/)

---

## Features

- Search for movies by title.
- View movie posters, release year, type, and title.
- Handles missing posters(not supplied by the API) by displaying a placeholder image.
- Responsive design for different screen sizes.

---

## Demo

![MovieLand Demo](./src/Demo.png)

---

## Technologies Used

- **React** - JavaScript library for building user interfaces.
- **OMDb API** - API to fetch movie data.
- **CSS** - Styling the application.
- **Fetch API** - To make asynchronous HTTP requests.

---

## Getting Started

### Prerequisites

- Node.js installed on your machine.
- NPM or Yarn package manager.

### Installation

1. Clone the repository:

```bash
git clone https://github.com/kudostech/movie-app.git
````

2. Navigate to the project folder:

```bash
cd movie-app
```

3. Install dependencies:

```bash
npm install
# or
yarn install
```

4. Start the development server:

```bash
npm start
# or
yarn start
```

5. Open your browser and go to `http://localhost:3000` to view the app.

---

## Usage

* Enter a movie name in the search bar.
* Click the search icon or press **Enter**.
* Browse the search results displayed as movie cards.

---

## File Structure

```
movie-app/
│
├─ src/
│  ├─ App.jsx          # Main application component
│  ├─ MovieCard.jsx    # Component to display individual movie info
│  ├─ search.svg       # Search icon
│  └─ App.css          # Styling
│
├─ package.json        # Project dependencies
└─ README.md           # Project documentation
```

---

## API

This project uses the [OMDb API](http://www.omdbapi.com/) to fetch movie data. You will need an API key to make requests. Replace the API key in `App.jsx` with your own.

```javascript
const API_URL = "https://www.omdbapi.com?apikey=YOUR_API_KEY";
```

---

## License

This project is **open source** and available under the MIT License.

---

## Author

**Qudus Abolaji**

Frontend Developer & UI/UX Designer

Portfolio: [https://kudostech-portfolio-website.vercel.app](https://kudostech-portfolio-website.vercel.app)

GitHub: [https://github.com/kudostech](https://github.com/kudostech)

LinkedIn: [https://www.linkedin.com/in/qudus-abolaji-046784214/](https://www.linkedin.com/in/qudus-abolaji-046784214/)
