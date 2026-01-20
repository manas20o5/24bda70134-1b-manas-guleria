# Simple Banking UI

A clean, modern web application for managing bank balance with deposit and withdrawal functionality. This project demonstrates HTML, CSS, and JavaScript fundamentals with local storage persistence.

## Features

- **Balance Display** - Real-time balance updates
- **Deposit Funds** - Add money to your account
- **Withdraw Funds** - Remove money with validation (prevents overdrafts)
- **Input Validation** - Ensures valid positive amounts
- **Persistent Storage** - Balance saved to browser local storage
- **Error Messages** - Clear feedback for invalid transactions
- **Responsive Design** - Works on desktop and mobile devices

## Project Structure

```
├── index.html      # Main HTML structure
├── styles.css      # Styling and layout
├── script.js       # Transaction logic and DOM manipulation
└── README.md       # Project documentation
```

## Technologies Used

- **HTML5** - Semantic markup for banking form interface
- **CSS3** - Modern styling with CSS variables and flexbox layout
- **JavaScript (Vanilla)** - Event handling and balance management
- **LocalStorage API** - Persistent data storage across sessions

## How to Use

1. **Open the Application** - Open `index.html` in a web browser
2. **Enter Amount** - Type a positive number in the amount field
3. **Deposit** - Click "Deposit" to add funds to your account
4. **Withdraw** - Click "Withdraw" to remove funds (must have sufficient balance)
5. **Balance Persistence** - Your balance is automatically saved and restored on page reload

## Getting Started

No installation or build tools required. Simply download the files and open `index.html` in your browser.

```bash
# Clone or download the project
cd 24bda70134-1b-manas-guleria

# Open in browser
open index.html
```

## Features in Detail

### Deposit Transaction
- Enter a positive amount and click "Deposit"
- Balance increases immediately
- Input field clears after successful transaction
- Error message appears for invalid amounts

### Withdraw Transaction
- Enter a positive amount and click "Withdraw"
- Validates that withdrawal doesn't exceed current balance
- Prevents overdrafts with error feedback
- Input field clears after successful transaction

### Data Persistence
- Balance is automatically saved to browser's local storage
- Balance persists even after closing the browser
- Default starting balance is $1000 (editable in script.js)

## Browser Compatibility

Works in all modern browsers that support:
- ES6 JavaScript
- LocalStorage API
- CSS Variables
- Flexbox Layout

## Future Enhancements

- Transaction history log
- Multiple account support
- Export/import functionality
- Dark mode theme
- Transaction categories
- Interest calculation

## Author

Created as a banking UI demonstration project.