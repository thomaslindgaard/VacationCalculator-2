# Danish Vacation Calculator

A comprehensive vacation planning tool designed specifically for Danish employees to track and manage their vacation days according to Danish labor law (Ferieloven).

## Features

### 🗓️ **Interactive Calendar**

- Click to mark vacation days (full day, half day, or none)
- Right-click to mark special vacation days (Feriefridage)
- Visual indicators for weekends, bank holidays, and different vacation types
- Monday-first calendar layout following European standards

### 🇩🇰 **Danish Labor Law Compliance**

- Accurate calculation of 2.0833 vacation days per month worked
- Danish vacation periods: September 1 - August 31 (earning period)
- Usage period: September 1 - December 31 of following year
- Automatic Danish bank holiday detection with Easter calculations
- Special vacation days (Feriefridage) tracking

### 📊 **Comprehensive Tracking**

- **Half-day support**: Book 0.5 or 1.0 vacation days for flexible planning
- **Period-based calculations**: Separate tracking for current and previous vacation periods
- **Carryover rules**: Only 5 vacation days can be transferred to next year
- **Smart validation**: Prevents exceeding special day allowances
- **Real-time statistics**: Shows remaining vacation and special days

### 📈 **Detailed Analytics**

- Period comparison table with earned vs. used vacation days
- Automatic warning system for excess days that must be used before December 31
- Notes and compliance warnings for Danish vacation law requirements
- Visual summary with vacation-themed design for positive user experience

### 💾 **Data Persistence**

- Automatic saving to browser's local storage
- Year-specific special vacation day allowances
- Customizable end date for vacation calculations
- Import/export functionality through browser storage

### 🎨 **Dark Theme Support**

- Toggle between light and dark themes with a single click
- **Monokai color scheme** for dark theme with authentic developer-friendly colors
- Proper contrast ratios for accessibility and eye comfort
- Theme preference automatically saved and restored
- All UI elements adapt seamlessly including:
  - Calendar days and vacation markers
  - Input fields and buttons
  - Tables and summary sections
  - Legend and instructional text

## Usage

### Getting Started

1. Open `vacationcalculator.html` in your web browser
2. Set your current year using the year selector
3. Configure your special vacation days allowance (default: 5 days)
4. Set your employment end date for accurate calculations

### Marking Vacation Days

- **Left-click** any weekday to cycle through: None → Full Day → Half Day → None
- **Right-click** any weekday to cycle through special days: None → Full Special → Half Special → None
- Weekends and bank holidays cannot be marked as vacation days

### Understanding the Display

- **Red days**: Regular vacation days
- **Teal days**: Special vacation days (Feriefridage)
- **Diagonal stripes**: Half days (with ½ symbol)
- **Orange days**: Danish bank holidays
- **Blue border**: Today's date

### Theme Toggle

- Click the **🌙 Dark** / **☀️ Light** button in the top-right corner to switch themes
- Dark theme uses a **Monokai color scheme** with:
  - Deep charcoal background for reduced eye strain
  - Cyan accents for interactive elements
  - High contrast text for excellent readability
  - Authentic developer color palette

### Vacation Summary

When you have excess vacation days that need to be used before December 31, a summary will appear showing:

- How many vacation days and/or special days you need to use
- The deadline (December 31) for using excess days
- Positive, encouraging messaging about having extra vacation time

## Danish Vacation Law Context

This calculator implements the Danish vacation system where:

- Employees earn 2.0833 vacation days per month (25 days per year)
- Vacation is earned from September 1 to August 31
- Earned vacation can be used from September 1 to December 31 of the following year
- Maximum 5 vacation days can be carried over to the next vacation year
- Special vacation days (Feriefridage) are additional days that cannot exceed 5 total
- Unused excess days are typically paid out rather than carried forward

## Technical Details

- **Single-file application**: Everything contained in one HTML file
- **No server required**: Runs entirely in the browser
- **Modern browser support**: Uses ES6+ JavaScript features
- **Responsive design**: Works on desktop and mobile devices
- **Local storage**: Data persists between browser sessions
- **CSS Variables**: Dynamic theming system for light/dark mode switching
- **Accessibility**: Proper contrast ratios and keyboard navigation support
- **Monokai Integration**: Authentic developer color scheme for dark theme

## File Structure

```
VacationCalculator/
├── vacationcalculator.html    # Main application file
└── README.md                  # This documentation
```

## Browser Compatibility

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## License

This project is open source and available under the MIT License.

## Contributing

Feel free to submit issues, feature requests, or pull requests to improve the vacation calculator for Danish employees.
