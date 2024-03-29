<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RVA LEAGUE</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            align-items: center;
            background-color: #f5f5f5;
            margin: 0;
            font-family: 'Cursive', sans-serif;
        }

        .header {
            width: 100%;
            text-align: center;
            padding: 20px;
            background-color: #4CAF50;
            color: #fff;
        }

        .tile {
            border: 1px solid #ccc;
            padding: 10px;
            margin: 10px;
            width: 90%;
            max-width: 400px;
        }

        table {
            border-collapse: collapse;
            width: 100%;
            margin-top: 10px;
        }

        th, td {
            border: 1px solid #ddd;
            padding: 8px;
            text-align: left;
        }

        h2 {
            background-color: #add8e6;
            color: #000;
            padding: 10px;
            margin: 0;
        }

        .highlight-row td:last-child {
            background-color: #ffeeba;
        }

        .faq-tile {
            width: 90%;
            order: 4;
        }
    </style>
</head>
<body>

    <div class="header">
        <h1>RVA OPEN LEAGUE 2024</h1>
    </div>

    <div class="tile">
        <h2>Round-Robin Schedule</h2>
        <table>
            <tr>
                <th>Teams</th>
                <th>Winner</th>
            </tr>
            <tr><td>Game 1: A vs B</td><td>Yet to Play</td></tr>
            <tr><td>Game 2: A vs C</td><td>Yet to Play</td></tr>
            <tr><td>Game 3: A vs D</td><td>Yet to Play</td></tr>
            <tr><td>Game 4: A vs E</td><td>Yet to Play</td></tr>
            <tr><td>Game 5: B vs C</td><td>Yet to Play</td></tr>
            <tr><td>Game 6: B vs D</td><td>Yet to Play</td></tr>
            <tr><td>Game 7: B vs E</td><td>Yet to Play</td></tr>
            <tr><td>Game 8: C vs D</td><td>Yet to Play</td></tr>
            <tr><td>Game 9: C vs E</td><td>Yet to Play</td></tr>
            <tr class="highlight-row"><td>Game 10: D vs E</td><td style="background-color: #ffeeba;">Yet to Play</td></tr>
        </table>
    </div>

    <div class="tile">
        <h2>Standings</h2>
        <table>
            <tr>
                <th>Team</th>
                <th>Points</th>
            </tr>
            <tr><td>Team A</td><td>0</td></tr>
            <tr><td>Team B</td><td>0</td></tr>
            <tr><td>Team C</td><td>0</td></tr>
            <tr><td>Team D</td><td>0</td></tr>
            <tr><td>Team E</td><td>0</td></tr>
        </table>
    </div>

    <div class="tile">
        <h2>Team Information</h2>
        <table>
            <tr>
                <th>Team Name</th>
                <th>Team Members</th>
            </tr>
            <tr><td>Team A</td><td>AYUSH | ARAVIND</td></tr>
            <tr><td>Team A</td><td>SATHYA | SHINOJ</td></tr>
            <tr><td>Team B</td><td>RAJ | PRAVEEN</td></tr>
            <tr><td>Team C</td><td>LOGU | MADHU</td></tr>
            <tr><td>Team D</td><td>MIRAJ | SAJIN</td></tr>
        </table>
    </div>

    <div class="tile faq-tile">
        <h2>FAQ</h2>
        <table>
            <tr><td>Semi Final</td><td>Top 4 teams after round-robin</td></tr>
            <tr><td>Final</td><td>Top 2 teams after semi-final</td></tr>
            <tr><td>Registration Fees</td><td>$20 Per Team</td></tr>
            <tr><td>Rating Cap</td><td>7.5</td></tr>
        </table>
    </div>

</body>
</html>
