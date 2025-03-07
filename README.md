<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Database Systems Exam</title>
</head>
<body>
    <h1>Database Systems Exam</h1>
    <form id="examForm">
        <!-- Question 1 -->
        <div>
            <p><strong>1. What is the primary difference between data and information?</strong></p>
            <label><input type="radio" name="q1" value="a"> a) Data is processed; information is raw.</label><br>
            <label><input type="radio" name="q1" value="b"> b) Information is processed data with context and meaning.</label><br>
            <label><input type="radio" name="q1" value="c"> c) Data requires metadata; information does not.</label><br>
            <label><input type="radio" name="q1" value="d"> d) Information is stored in databases; data is not.</label>
        </div>
        <!-- Repeat for all 15 questions -->
        <br>
        <button type="submit">Submit Exam</button>
    </form>

    <script>
        document.getElementById('examForm').addEventListener('submit', function(event) {
            event.preventDefault();
            alert('Exam submitted!');
        });
    </script>
</body>
</html>
