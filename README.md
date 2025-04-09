# Deanthony_gradebook
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gradebook</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #f4f4f4;
        }
    </style>
</head>
<body>
    <h1>Gradebook</h1>
    <table id="gradebook">
        <caption>Student Grades</caption>
        <thead>
            <tr>
                <th>Student Name</th>
                <th>Assignment 1</th>
                <th>Assignment 2</th>
                <th>Assignment 3</th>
            </tr>
        </thead>
        <tbody>
            <!-- Rows will be populated dynamically with JavaScript -->
        </tbody>
    </table>
    <script src="gradebook.js"></script>
</body>
</html>
