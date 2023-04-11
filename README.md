# README for Account and ATMDeposit Components
This is a simple React application that allows users to deposit or withdraw cash from an account balance. The application consists of two components: Account and ATMDeposit.

## Account Component
The Account component is the main component that renders the UI for the application. It keeps track of the account balance and allows the user to deposit or withdraw cash. The component uses React Hooks to manage the state of the application.

## State
deposit: The amount of cash that the user wants to deposit or withdraw.
totalState: The current balance of the account.
isDeposit: A boolean value that determines if the user wants to deposit or withdraw cash.
## Functions
handleChange: A function that is called when the user inputs the amount of cash they want to deposit or withdraw. It updates the deposit state with the input value.
handleSubmit: A function that is called when the user submits the deposit or withdrawal form. It updates the totalState state based on the isDeposit value.
ATMDeposit Component
The ATMDeposit component is a child component of Account and is responsible for rendering the deposit or withdrawal form. It receives two props from the Account component:

onChange: A function that is called when the user inputs the amount of cash they want to deposit or withdraw.
isDeposit: A boolean value that determines if the user wants to deposit or withdraw cash.
The ATMDeposit component renders a label that displays the form and the appropriate label based on the isDeposit value.

## Props
onChange: A function that is called when the user inputs the amount of cash they want to deposit or withdraw.
isDeposit: A boolean value that determines if the user wants to deposit or withdraw cash.
How to Run the Application
To run the application, first clone the repository:

bash
Copy code
git clone https://github.com/yourusername/react-atm.git
Then, navigate to the project directory and install the dependencies:

bash
Copy code
cd react-atm
npm install
Finally, start the application:

sql
Copy code
npm start
The application should now be running on http://localhost:3000/.
