<h1>Tayyab Bank Application</h1>
<h2>Prerequisites</h2>
    <p>To run the <strong>Tayyab Bank</strong> application, ensure you have the following installed and set up:</p>
    <ul>
        <li><strong>Python Environment</strong>: Python 3.7 or later.<br>
            Install Python from <a href="https://www.python.org/downloads/">python.org</a>.
        </li>
        <li><strong>Jupyter Notebook</strong>:<br>
            Install Jupyter Notebook using pip:
            <pre><code>pip install notebook</code></pre>
        </li>
        <li><strong>Required Libraries</strong>:<br>
            The application uses standard Python libraries (<code>datetime</code>, <code>sys</code>). Ensure your Python environment is configured correctly.
        </li>
        <li><strong>Execution Environment</strong>:<br>
            Clone or download the script into a <code>.pynb</code> file.<br>
            Run the script using Jupyter Notebook:
            <pre><code>jupyter notebook</code></pre>
        </li>
    </ul>

  <h2>File Overview</h2>
    <p>The <code>.pynb</code> file contains:</p>
    <ul>
        <li><strong>Class Definitions</strong>:
            <ul>
                <li><code>Account</code>: Handles user accounts, transactions, deposits, withdrawals, and balance checking.</li>
                <li><code>Bank</code>: Manages multiple accounts and provides authentication and administrative functionalities.</li>
            </ul>
        </li>
        <li><strong>Application Logic</strong>:<br>
            <code>TayyabBank()</code>: Main function implementing user interaction with the bank system through a menu-driven interface.
        </li>
    </ul>

  <h2>How to Run</h2>
    <ol>
        <li>Launch the <code>.pynb</code> file in Jupyter Notebook.</li>
        <li>Execute all the code cells to ensure the application is loaded.</li>
        <li>Call the <code>TayyabBank()</code> function in a code cell to start the program.</li>
    </ol>

  <h2>Accessing Admin Functionality</h2>
    <p>The admin functionality includes viewing <strong>total deposits</strong> and the <strong>total number of accounts</strong> in the bank.</p>
    <p>To access:</p>
    <ol>
        <li><strong>Run the Program</strong>: Start the application and follow the menu-driven interface.</li>
        <li><strong>Admin Options</strong>: Select the following menu options:
            <ul>
                <li><strong>Option 8</strong>: View total deposits in the bank.</li>
                <li><strong>Option 9</strong>: View the total number of accounts.</li>
            </ul>
        </li>
    </ol>

  <h2>Features</h2>
    <h3>User Options</h3>
    <ul>
        <li><strong>Open Account</strong>: Create a new bank account.</li>
        <li><strong>Deposit Money</strong>: Deposit funds into an account.</li>
        <li><strong>Withdraw Money</strong>: Withdraw funds from an account.</li>
        <li><strong>Check Balance</strong>: View the balance of an account.</li>
        <li><strong>Transfer Money</strong>: Transfer funds between accounts.</li>
        <li><strong>View Statement</strong>: See the transaction history of an account.</li>
        <li><strong>Exit</strong>: Exit the application.</li>
    </ul>

   <h3>Admin Options</h3>
    <ul>
        <li><strong>Total Deposits</strong>: Display the sum of all account balances in the bank.</li>
        <li><strong>Total Accounts</strong>: Display the number of accounts in the bank.</li>
    </ul>

   <h2>Notes</h2>
    <ul>
        <li><strong>Authentication</strong>: Each account is secured with a password. Ensure you remember your password to access your account.</li>
        <li><strong>Error Handling</strong>: The application validates user input and ensures secure and accurate transactions.</li>
        <li><strong>Scalability</strong>: The <code>Bank</code> class is designed to handle multiple accounts efficiently.</li>
    </ul>

  <hr>
    <p>For questions or support, please contact Me.</p>

