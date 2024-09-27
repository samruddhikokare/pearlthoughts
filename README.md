# Date Picker Component

A reusable date picker component in React that allows users to select recurring dates. This project is built using Next.js and styled with Tailwind CSS, utilizing Zustand for state management.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Components](#components)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)

## Features

- Select recurring options: Daily, Weekly, Monthly, Yearly
- Customize recurrence patterns
- Visual preview of selected recurring dates
- Date range selection
- Responsive design with Tailwind CSS

## Installation

1. Clone the repository:

   ```bash
   git clone <your-repo-url>
   ```

2. Navigate to the project directory:

   ```bash
   cd date-picker-component
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. Install Tailwind CSS by following the official setup guide [here](https://tailwindcss.com/docs/guides/nextjs).

## Usage

1. Start the development server:

   ```bash
   npm run dev
   ```

2. Open your browser and navigate to `http://localhost:3000` to view the date picker component.

3. Import and use the `DatePicker` component in your pages or other components:

   ```javascript
   import DatePicker from '../components/DatePicker';

   const HomePage = () => {
     return (
       <div>
         <h1>Welcome to the Date Picker App</h1>
         <DatePicker />
       </div>
     );
   };

   export default HomePage;
   ```

## Components

- **DatePicker:** Main component handling the date selection and recurrence.
- **RecurrenceOptions:** For selecting the recurrence pattern.
- **RecurrenceCustomization:** For fine-tuning recurrence settings.
- **CalendarPreview:** Displays the selected recurring dates.

## Testing

1. To run the tests, use the following command:

   ```bash
   npm test
   ```

2. Ensure to write unit tests for individual components and integration tests for component functionality.

## Contributing

1. Fork the repository.
2. Create your feature branch:

   ```bash
   git checkout -b feature/new-feature
   ```

3. Commit your changes:

   ```bash
   git commit -m 'Add some feature'
   ```

4. Push to the branch:

   ```bash
   git push origin feature/new-feature
   ```

5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
