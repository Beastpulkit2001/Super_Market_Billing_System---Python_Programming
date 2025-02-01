# Super_Market_Billing_System---Python_Programming
Python Programming Project
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
</head>
<body>
    <h1>Supermarket Billing System</h1>

  <p>This is a simple Python-based supermarket billing system that allows customers to enter their details, select products, and receive a bill with applied discounts based on the total amount. The system keeps track of products, quantities, and prices, and provides a summary at the end.</p>

   <h2>Features:</h2>
    <ul>
        <li>Customer information entry (Name, Age, Phone number)</li>
        <li>Product selection from a predefined list (Apple, Chips, Burger, Pepsi)</li>
        <li>Quantity input for each selected product</li>
        <li>Bill calculation with applied discount based on the total amount</li>
        <li>Option to add multiple customers and generate separate bills for each</li>
        <li>Displays a clear summary of the bill including discount percentage and total amount to be paid.</li>
    </ul>

  <h2>Requirements:</h2>
    <ul>
        <li>Python 3.14</li>
        <li>Check the python version run the following Command:</li>
    </ul>
    <pre><code>python --version</code></pre>

  <h2>How to Run:</h2>
    <ol>
        <li>Clone this repository or download the Python file.</li>
        <li>Open the terminal or command prompt.</li>
        <li>Navigate to the directory where the Python file is saved.</li>
        <li>Run the following command:</li>
    </ol>
    <pre><code>python supermarket_billing_system.ipynb</code></pre>
    <h2>Code Walkthrough:</h2>
    <ul>
        <li><strong>Customer Information:</strong> The system asks the customer for their name, age, and phone number.</li>
        <li><strong>Product List:</strong> A list of products (Apple, Chips, Burger, and Pepsi) with corresponding prices is displayed.</li>
        <li><strong>Cart Update:</strong> The user can select products and enter the quantity they wish to purchase. The total amount is calculated as products are added to the cart.</li>
        <li><strong>Discount Application:</strong> Depending on the total amount spent, a discount is applied:
            <ul>
                <li>Amount &lt;= 500: No discount</li>
                <li>Amount between 501 and 600: 5% discount</li>
                <li>Amount between 601 and 800: 10% discount</li>
                <li>Amount &gt; 800: 15% discount</li>
            </ul>
        </li>
        <li><strong>Bill Summary:</strong> At the end of the purchase, a summary is displayed, showing customer details, the products purchased, discount applied, and the total amount to be paid.</li>
        <li><strong>Repeat for Multiple Customers:</strong> After generating the bill for a customer, the system allows you to add more customers and generate separate bills.</li>
    </ul>

</body>
</html>
