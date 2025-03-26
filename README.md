<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nithish M - Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #ff0033;
            margin: 0;
            padding: 0;
        }
        .header {
            background-color: #a4db02;
            text-align: center;
            padding: 20px;
            font-size: 24px;
            font-weight: bold;
            color: white;
        }
        .navigation {
            display: flex;
            justify-content: center;
            background-color: red;
            padding: 10px;
        }
        .navigation a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
        }
        .container {
            width: 80%;
            margin: auto;
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            margin-top: 20px;
        }
        .section-title {
            font-size: 20px;
            font-weight: bold;
            border-bottom: 2px solid red;
            padding-bottom: 5px;
            margin-bottom: 10px;
        }
        .resume-btn {
            display: flex;
            justify-content: center;
            margin-top: 20px;
        }
        .resume-btn a {
            background-color: black;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
        }
        .footer {
            text-align: center;
            padding: 10px;
            background-color: black;
            color: white;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <div class="header">
        Nithish M <br>
        <span style="font-size: 18px;">BCA Student</span>
    </div>

    <div class="navigation">
        <a href="#">About</a>
        <a href="#">Education</a>
        <a href="#">Skills</a>
        <a href="#">Projects</a>
        <a href="#">Resume</a>
    </div>

    <div class="container">
        <div class="section">
            <div class="section-title">About Me</div>
            <p>I am a student currently pursuing a BCA degree.</p>
        </div>

        <div class="section">
            <div class="section-title">Education</div>
            <p>University of Madras, BCA</p>
        </div>

        <div class="section">
            <div class="section-title">Skills</div>
            <ul>
                <li>Python</li>
                <li>Java</li>
                <li>C++</li>
            </ul>
        </div>

        <div class="section">
            <div class="section-title">Projects</div>
            <ul>
                <li>Adventure Gaming using Java</li>
            </ul>
        </div>

        <div class="resume-btn">
            <a href="#">Download CV</a>
        </div>
    </div>

    <div class="footer">
        © 2025 Nithish M
    </div>

</body>
</html>

