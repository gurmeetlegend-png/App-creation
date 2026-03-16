# App-creation
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Udhaar Management System</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="container">
        <h2>Ledger: Udhaar Records</h2>
        
        <input type="text" id="searchInput" onkeyup="searchTable()" placeholder="Search for names or dates...">

        <table id="udhaarTable">
            <thead>
                <tr class="header">
                    <th>Customer Name</th>
                    <th>Amount (₹)</th>
                    <th>Date</th>
                    <th>Status</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Rahul Sharma</td>
                    <td>500</td>
                    <td>2024-05-10</td>
                    <td class="pending">Pending</td>
                </tr>
                <tr>
                    <td>Anita Desai</td>
                    <td>1200</td>
                    <td>2024-05-12</td>
                    <td class="paid">Paid</td>
                </tr>
                <tr>
                    <td>Vikram Singh</td>
                    <td>350</td>
                    <td>2024-05-14</td>
                    <td class="pending">Pending</td>
                </tr>
            </tbody>
        </table>
    </div>

    <script src="script.js"></script>
</body>
</html>
