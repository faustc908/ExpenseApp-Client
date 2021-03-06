ExpenseApp- Client repository

Summary: Current times are tough and keeping track of your expenses is as important as ever.  ExpenseApp allows you to calculate your daily transactions so you can keep track of and see where your money is spent.  It also allows you to record any relevant information on a database so you can keep track of disposable income as well as any notes you want to add on good deals or nuances in your daily or monthly expenses.  This app was designed to give you more control in uncertain times.

Link to server repository - https://github.com/faustc908/ExpenseApp-Server

Link to live app: https://expense-app-client.vercel.app/

[![Expense-App.png](https://i.postimg.cc/761DVbCq/Expense-App.png)](https://postimg.cc/MMGhZ6bL)

API endpoints for the back end include:

    POST to '/expense' to add a user note to the database
    PUT to '/expense' to update a note you already submitted
    GET to '/expense' to get all of the note stored
    DELETE to '/expense' to delete unwanted note from database

Front end:
React.js/CSS3/HTML5/Jest/Enzyme

Back end:
Node.js/PostgreSQL/Express/Jest/Supertest
