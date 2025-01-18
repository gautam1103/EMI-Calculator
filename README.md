# EMI Calculator

This project is an interactive **EMI Calculator** built using **React.js**. It allows users to calculate the Equated Monthly Installments (EMI) for a loan by dynamically adjusting the inputs such as the total cost, interest rate, down payment, tenure, and processing fee. The application provides a seamless user experience with real-time updates on EMI and down payment calculations.

## Features

- **Dynamic Inputs**: Users can adjust values like total cost, interest rate, processing fee, down payment, and EMI through text inputs and sliders.
- **Real-Time Calculations**: The EMI and down payment are recalculated dynamically as the user changes the inputs.
- **Customizable Tenure**: Choose from predefined loan tenures.
- **Interactive UI**: Built with reusable components like `TextInput` and `SliderInput`.
- **Clear Visualizations**: Displays total down payment and total loan amount in a user-friendly format.

## Preview

Explore the live application at: [EMI Calculator](https://emi-calculator-reactjs.netlify.app/)

## How It Works

The EMI is calculated using the formula:

\[ EMI = \frac{P \times R \times (1+R)^N}{(1+R)^N - 1} \]

Where:
- \( P \): Loan amount (Total Cost - Down Payment)
- \( R \): Monthly interest rate (Annual Rate / 12 / 100)
- \( N \): Number of monthly installments (Tenure in months)

## Project Structure

- **Components**:
  - `TextInput`: Handles numeric input for fields like cost, interest rate, and processing fee.
  - `SliderInput`: Provides sliders for adjusting down payment and EMI dynamically.
- **Utils**:
  - `constants.js`: Contains predefined constants like tenure options.
  - `config.js`: Includes helper functions such as `numberWithCommas` for formatting numbers.
- **Styles**: Custom CSS for styling the application.

## Installation

Follow the steps below to run the project locally:

1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```

2. Navigate to the project directory:
   ```bash
   cd emi-calculator
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm start
   ```

5. Open your browser and visit:
   ```
   http://localhost:3000
   ```

## Usage

1. Enter the total cost of the asset.
2. Specify the annual interest rate and processing fee percentage.
3. Adjust the down payment and EMI using the sliders.
4. Choose the desired loan tenure from the available options.
5. View the calculated EMI, total down payment, and total loan amount.

## Deployment

The project is deployed on **Netlify**. To deploy your version:

1. Build the project:
   ```bash
   npm run build
   ```

2. Deploy the `build` folder to Netlify.

## Technologies Used

- **React.js**: Frontend framework
- **CSS**: Styling
- **Netlify**: Deployment platform

## License

This project is licensed under the MIT License. Feel free to use and modify it as needed.

---

**Author**: Gautam Mishra

For any queries or feedback, feel free to contact me.

