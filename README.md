# Country Details Application

A simple React application that fetches and displays information about countries. It includes features such as search, filters by region, and detailed country pages.

## Features

- **Search Functionality**: Allows users to search for countries by name.
- **Filter by Region**: Filter countries based on their region (e.g., Asia, Europe).
- **Country Details**: Users can click on a country to view detailed information such as population, native names, languages, currencies, and more.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## Tech Stack

- **React**: Frontend framework for building user interfaces.
- **React Router**: For handling navigation between pages.
- **Axios**: For making API calls to fetch country data.

## Setup

### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (Recommended version: LTS)
- [npm](https://www.npmjs.com/) (Node Package Manager)

### Getting Started

# Country Details Application

A simple React application that fetches and displays information about countries. It includes features such as search, filters by region, and detailed country pages.

## Features

- **Search Functionality**: Allows users to search for countries by name.
- **Filter by Region**: Filter countries based on their region (e.g., Asia, Europe).
- **Country Details**: Users can click on a country to view detailed information such as population, native names, languages, currencies, and more.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## Tech Stack

- **React**: Frontend framework for building user interfaces.
- **React Router**: For handling navigation between pages.
- **Axios**: For making API calls to fetch country data.
- **Tailwind CSS**: For styling the application.

## Setup

### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (Recommended version: LTS)
- [npm](https://www.npmjs.com/) (Node Package Manager)

### Getting Started

1. **Clone the repository**:
   ```bash
   git remote add origin git@github.com:mdmehedihashanmolla/React19-Country-Showing-Project.git
   npm install
   npm run dev
   API Used
The application uses the Rest Countries API to fetch country information.

Endpoints
GET /all?fields=name,population,region,capital,flags: Fetches a list of all countries.
GET /name/{countryName}?fullText=true&fields=name,population,region,subregion,capital,tld,currencies,languages,borders,flags: Fetches detailed information about a specific country.


