# Z STATION APP

This is a project based on Z, a fuel provider in New Zealand. It allows users to plan journeys and find Z stations along their specified route, as well as look up fuel prices at Z stations.


## Project Structure

- `public/`: Static assets.
- `src/`: Source files for the project.
  - `assets/`: Images etc.
  - `components/`: Reusable components.
    - `Common/`: Common components like Header and Footer.
    - `FindStation/`: Components for the "Find a Station" page.
    - `JourneyPlanner/`: Components for the "Journey Planner" page.
    - `StoreInformation/`: Components for the "Store Information" page.
    - `LandingPage/`: Components for the landing page.
  - `pages/`: Page components.
  - `App.jsx`: Main application component with routing.
  - `main.jsx`: Entry point for the application.

## Setup Instructions

### Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)

### Installation

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/SarahC233/m5-frontend.git
   cd m5-frontend
   ```

2. **Install Dependencies:**
   ```sh
   npm install
   ```

3. **Start the Development Server:**
   ```sh
   npm run dev
   ```
   The application should now be running at http://localhost:5173

## Branching Workflow

Create own branch for development:

1. **Create new branch:** 
```sh
git checkout -b your-branch-name
```

2. **Push your branch to the repo:**
```sh
git push origin your-branch-name
```

3. **Make changes and commit:**
```sh
git add .
git commit -m "Your commit message"
```

4. **Push changes to your branch:**
```sh
git push origin your-branch-name
```

5. **Create pull request for review**

## Maps Demo

Heres a showcase of the two maps features 'find a station' and 'journey planner' along with custom pins and marker clustering.



https://github.com/user-attachments/assets/af446637-d37a-490e-a265-d3d66e9c2492



## Routing

This project uses `react-router-dom` v6 for client-side routing.

## Notes

- **React Router v6:** Ensure that you are using `react-router-dom` v6, as the routing setup is based on this version.
- **Development Server:** Always restart the development server after making changes to the configuration or dependencies.

