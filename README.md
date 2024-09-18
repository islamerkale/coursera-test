<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Inventory Management</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        .sidebar {
            width: 100%;
            background-color: #333;
            height: auto;
            padding-top: 20px;
            position: fixed;
            top: 0;
            left: 0;
            z-index: 1000;
        }
        .sidebar a {
            padding: 15px;
            text-decoration: none;
            font-size: 18px;
            color: white;
            display: block;
            text-align: left;
        }
        .sidebar a:hover {
            background-color: #575757;
        }
        .content {
            margin-left: 0;
            padding: 20px;
            margin-top: 70px; /* Adjust based on the height of the sidebar */
        }
        table {
            width: 100%;
            border-collapse: collapse;
        }
        table, th, td {
            border: 1px solid black;
        }
        th, td {
            padding: 15px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
        }

        /* Media queries for responsive design */
        @media screen and (min-width: 768px) {
            .sidebar {
                width: 20%;
                height: 100vh;
                padding-top: 20px;
                position: fixed;
            }
            .content {
                margin-left: 20%;
                margin-top: 0;
            }
        }
    </style>
</head>
<body>

<div class="sidebar">
    <a href="#inventory">Inventory Management</a>
    <a href="#addInventory">Add Inventory</a>
    <a href="#viewInventory">View Inventory</a>
    <a href="#employee">Employee Management</a>
    <a href="#addEmployee">Add Employee</a>
    <a href="#viewEmployee">View Employees</a>
    <a href="#menu">Menu Management</a>
    <a href="#addMenu">Add Item</a>
    <a href="#viewMenu">View Menu</a>
</div>

<div class="content">
    <h2>Inventory Management</h2>
    <input type="text" id="search" placeholder="Search Inventory...">
    <table>
        <tr>
            <th>Product Name</th>
            <th>Category</th>
            <th>Place</th>
            <th>Quantity</th>
            <th>Last Updated</th>
        </tr>
        <tr>
            <td>Ricotta Cheese</td>
            <td>Fridge</td>
            <td>1st Shelf</td>
            <td>22</td>
            <td>March 19, 2024</td>
        </tr>
        <!-- Add more rows as needed -->
    </table>
</div>

</body>
</html>
