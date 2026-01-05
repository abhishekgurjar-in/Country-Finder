# Country Finder Website

### Introduction
In this blog post, we'll explore how to build a Country Finder application using React. This application allows users to search for countries, filter them by region, and view detailed information about each country. We will utilize React's hooks and context to manage state and theming, and we'll integrate with the REST Countries API to fetch country data.

### Project Overview
The Country Finder application provides an interactive interface where users can:
- Search for countries by name.
- Filter countries by region.
- View detailed information about each country, including its flag, population, and more.

### Features
- **Search Bar**: Allows users to search for countries by name.
- **Filter by Region**: Dropdown menu to filter countries based on their region.
- **Country Details**: Displays detailed information about a selected country.
- **Theme Toggle**: Switch between light and dark themes.

### Technologies Used
- **React**: JavaScript library for building user interfaces.
- **REST Countries API**: Provides data about countries.
- **CSS**: For styling the application.
- **React Router**: For navigating between pages and passing state.

### Project Structure
The project is organized into several components:
- **App.js**: Main component that includes the `Header` and `Outlet` for routing.
- **Header.js**: Displays the application title and theme toggle button.
- **Home.js**: Main page with search and filter options, and a list of countries.
- **SearchBar.js**: Component for searching countries.
- **SelectMenu.js**: Dropdown menu for filtering countries by region.
- **CountriesList.js**: Displays a list of countries based on the search and filter criteria.
- **CountryCard.js**: Displays a summary of each country.
- **CountryDetail.js**: Shows detailed information about a selected country.
- **CountryDetailShimmer.js**: Loading placeholder for country details.
- **Error.js**: Error handling component for routes.

### Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/abhishekgurjarin/country-finder.git
   cd country-finder
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the development server**:
   ```bash
   npm start
   ```

### Usage
1. **Search for a Country**: Enter a country name in the search bar to filter the list of countries.
2. **Filter by Region**: Select a region from the dropdown menu to see countries in that region.
3. **View Details**: Click on a country card to view detailed information about the country.


### Live Demo
You can view a live demo of the Country Finder application by visiting [Country Finder Demo](https://country-finder-in.netlify.app).

### Screenshots
![Screenshot 2024-09-13 103655](https://github.com/user-attachments/assets/b73acde9-1941-491c-a05e-aecb7f072cbb)



### Conclusion
In this project, we built a Country Finder application using React that allows users to search for countries, filter them by region, and view detailed information. We integrated with the REST Countries API and used React's hooks and context to manage state and theming.

### Credits
- **React**: [React](https://reactjs.org/)
- **REST Countries API**: [REST Countries](https://restcountries.com/)
- **Font Awesome**: [Font Awesome](https://fontawesome.com/)

### Author
**Abhishek Gurjar** is a dedicated web developer passionate about creating practical and functional web applications. Check out more of his projects on [GitHub](https://github.com/abhishekgurjarin).
