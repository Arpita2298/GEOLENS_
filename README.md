# 🌍 GeoLens

**GeoLens** is a modern, interactive web application that provides comprehensive information about countries around the world. Built with React and powered by the REST Countries API, GeoLens offers users an intuitive interface to explore countries, their demographics, geography, and fascinating facts.

## ✨ Features

- 🔍 **Search Functionality** - Quickly find any country by name
- 🗺️ **Region Filtering** - Filter countries by continent/region
- 📊 **Detailed Country Information** - View comprehensive data including:
  - Population statistics
  - Capital cities
  - Regions and subregions
  - Languages and currencies
  - Bordering countries
  - Country flags
- 📱 **Responsive Design** - Seamless experience across all devices
- ⚡ **Fast Performance** - Built with Vite for lightning-fast development and production builds
- 🎨 **Modern UI** - Clean and intuitive user interface with gradient cards

## 🚀 Technologies Used

- **React 18.3.1** - Modern React with hooks
- **React Router DOM 6.26.2** - Client-side routing
- **Axios 1.7.7** - HTTP client for API requests
- **Vite 5.4.1** - Next-generation frontend tooling
- **React Icons 5.3.0** - Icon library
- **REST Countries API** - Country data source

## 📦 Installation

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Steps

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd GeoLens
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173` (or the port shown in your terminal)

## 🛠️ Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build for production
- `npm run preview` - Preview the production build
- `npm run lint` - Run ESLint for code quality checks

## 📁 Project Structure

```
GeoLens/
├── public/           # Static assets
├── src/
│   ├── api/          # API configuration and data
│   │   ├── postApi.jsx      # API calls to REST Countries
│   │   ├── countryData.json # Static country facts
│   │   └── footerApi.json   # Footer data
│   ├── components/   # React components
│   │   ├── Layout/   # Layout components
│   │   └── UI/       # UI components
│   ├── pages/        # Page components
│   │   ├── Home.jsx
│   │   ├── About.jsx
│   │   ├── Country.jsx
│   │   ├── Contact.jsx
│   │   └── ErrorPage.jsx
│   ├── App.jsx       # Main app component with routing
│   ├── App.css       # Global styles
│   └── main.jsx      # Application entry point
├── index.html
├── package.json
└── vite.config.js
```

## 🌐 API Integration

GeoLens uses the [REST Countries API](https://restcountries.com/) to fetch real-time country data:

- **GET /all** - Fetches all countries with basic information
- **GET /name/{name}** - Fetches detailed information for a specific country

## 📄 Pages

- **Home** - Landing page with hero section and interesting country facts
- **About** - Showcases interesting facts about various countries
- **Country** - Browse all countries with search and filter capabilities
- **Country Details** - Detailed view of individual countries
- **Contact** - Contact form page

## 🎨 Features Breakdown

### Search & Filter
Users can search countries by name and filter by region (Africa, Americas, Asia, Europe, Oceania) for quick navigation.

### Country Cards
Each country is displayed in a card format showing:
- Country flag
- Country name
- Population
- Region
- Capital city

### Detailed View
Clicking on a country card navigates to a detailed page showing:
- Full country information
- Languages spoken
- Currencies used
- Neighboring countries
- Top-level domain

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- [REST Countries API](https://restcountries.com/) for providing comprehensive country data
- [React Icons](https://react-icons.github.io/react-icons/) for the icon library
- [Vite](https://vitejs.dev/) for the amazing build tool


---

Built with ❤️ using React and Vite
