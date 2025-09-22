# UK Home Affordability Calculator

A simple, user-friendly web application to calculate home affordability in the UK, including accurate Stamp Duty Land Tax (SDLT) calculations for both first-time buyers and second home purchases.

## Use the website
You can use the website [here](https://alessiocasco.github.io/UK-Home-Affordability/)

## Features

- **Dual Home Type Support**: Calculate affordability for both first homes and second homes
- **Accurate SDLT Calculations**: Up-to-date Stamp Duty Land Tax rates as of April 2025
- **LTV Analysis**: Loan-to-Value ratio calculations with 90% LTV limits
- **Income-Based Affordability**: Uses 4.5x income multiplier for mortgage affordability
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Input Validation**: Comprehensive error checking and user-friendly error messages

## How It Works

The calculator takes into account:

1. **Property Cost**: The purchase price of the home
2. **Annual Income**: Total household income for mortgage qualification
3. **Current Savings**: Available funds for deposit and purchase costs
4. **Minimum Bank Balance**: Amount you want to keep as emergency funds

The tool then calculates:
- Stamp Duty Land Tax based on property value and home type
- Total purchase cost (property + SDLT)
- Available deposit funds
- Required mortgage amount
- Affordability based on income and LTV limits

## SDLT Rates (April 2025)

### First Home Buyers
- £0 - £125,000: 0%
- £125,001 - £250,000: 2%
- £250,001 - £925,000: 5%
- £925,001 - £1,500,000: 10%
- £1,500,001+: 12%

### Second Home Buyers (Additional 3% surcharge)
- £0 - £40,000: 0%
- £40,001 - £125,000: 5%
- £125,001 - £250,000: 7%
- £250,001 - £925,000: 10%
- £925,001 - £1,500,000: 15%
- £1,500,001+: 17%

## Usage

1. Open `index.html` in your web browser
2. Select whether this is a first home or second home purchase
3. Enter the property cost, your annual income, current savings, and minimum bank balance
4. Click "Calculate Affordability" to see the results

## Technical Details

- **Frontend Only**: Pure HTML, CSS, and JavaScript - no server required
- **Styling**: Tailwind CSS via CDN
- **Responsive**: Mobile-first design approach
- **Browser Compatibility**: Works in all modern browsers

## Getting Started

Simply download or clone this repository and open `index.html` in your web browser. No installation or setup required.

```bash
git clone https://github.com/AlessioCasco/UK-Home-Affordability.git
cd UK-Home-Affordability
open index.html
```

## Disclaimer

This calculator provides estimates based on general guidelines and current SDLT rates. For accurate mortgage advice and qualification, please consult with a qualified mortgage advisor or financial institution. SDLT rates and mortgage lending criteria may change.

## License

MIT License - see [LICENSE](LICENSE) file for details.

## Contributing

Feel free to submit issues and enhancement requests!
