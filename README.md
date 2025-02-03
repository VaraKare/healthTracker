# Health Challenge Tracker

A Angular 14+ single-page application for tracking user workouts.

## Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)
- Angular CLI (v14 or higher)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/VaraKare/health-challenge-tracker-t.git
cd health-challenge-tracker-t
```

2. Install dependencies:
```bash
npm install
```

3. Install Tailwind CSS:
```bash
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init
```

4. Configure Tailwind CSS by updating tailwind.config.js:
```javascript
module.exports = {
  content: [
    "./src/**/*.{html,ts}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

5. Add Tailwind directives to src/styles.css:
```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Running unit tests

Run `ng test` to execute the unit tests via Karma.

To generate code coverage report:
```bash
ng test --code-coverage
```
The coverage report will be available in the `coverage` directory.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Features

- Add new users with workout details
- Display user workout list
- Search by username
- Filter by workout type
- Pagination
- Workout progress charts
- Data persistence using localStorage
- Unit tests with 100% coverage
- Responsive design with Tailwind CSS

## Assumptions

1. Workout types are predefined (Running, Cycling, Swimming, Yoga)
2. Each user can have multiple workouts
3. Local storage is used for data persistence
4. Pagination shows 5 items per page

## Libraries Used

- Angular Material
- Chart.js for workout visualization
- Tailwind CSS for styling

## Deployment

The application is deployed on  Vercel and can be accessed at [ `health-tracker-ten-blush.vercel.app ` ].

