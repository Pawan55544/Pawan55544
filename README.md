
<!-- index.html -->
<!DOCTYPE html> 

<html> 

  

<head> 

    <title>Expense Tracker</title> 

    <link rel="stylesheet" 

          type="text/css" 

          href="style.css" /> 

</head> 

  

<body> 

    <div class="container"> 

        <h1>Expense Tracker</h1> 

        <form id="expense-form"> 

            <input type="text" 

                   id="expense-name" 

                   placeholder="Expense Name" required /> 

            <input type="number" 

                   id="expense-amount" 

                   placeholder="Amount" required /> 

            <button type="submit"> 

                Add Expense 

            </button> 

        </form> 

        <div class="expense-table"> 

            <table> 

                <thead> 

                    <tr> 

                        <th>Expense Name</th> 

                        <th>Amount</th> 

                        <th>Action</th> 

                    </tr> 

                </thead> 

                <tbody id="expense-list"></tbody> 

            </table> 

            <div class="total-amount"> 

                <strong>Total:</strong>  

                $<span id="total-amount">0</span> 

            </div> 

        </div> 

    </div> 

    <script src="script.js"></script> 

</body> 

  

</html>
