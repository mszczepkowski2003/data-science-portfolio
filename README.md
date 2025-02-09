# data-science-portfolio

### About me
I am a third-year student of Informatics and Econometrics at the University of Gdańsk, aspiring to pursue a master's degree in Big Data. I am eager to learn, continuously improve my skills, and take on new challenges. My strong foundation in statistics, data analysis, and machine learning allows me to approach complex problems with a structured and analytical mindset. I am passionate about data-driven decision-making and always looking for opportunities to apply my knowledge to real-world problems.

### Technical skills
- Python
- R
- Excel
- Statistica
- Spss

<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio - Umiejętności</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            padding: 20px;
        }

        h2 {
            text-align: left;
            margin-bottom: 10px;
        }

        .content {
            max-width: 800px;
            margin: 0 auto;
            text-align: left;
        }

        .skills {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 15px;
            margin-top: 20px;
        }

        .skill {
            display: flex;
            align-items: center;
            justify-content: space-between;
            width: 50%;
            background: white;
            padding: 10px 15px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
        }

        .skill label {
            font-weight: bold;
            flex: 1;
            text-align: left;
        }

        progress {
            flex: 2;
            width: 100%;
            height: 20px;
            border-radius: 10px;
            overflow: hidden;
        }

        progress::-webkit-progress-bar {
            background-color: #ddd;
            border-radius: 10px;
        }

        progress::-webkit-progress-value {
            background-color: #007bff;
            border-radius: 10px;
        }

        @media (max-width: 768px) {
            .skill {
                width: 80%;
            }
        }
    </style>
</head>
<body>

<div class="content">
    <h2>Technical Skills</h2>
    <ul>
        <li>Python</li>
        <li>R</li>
        <li>Excel</li>
        <li>Statistica</li>
        <li>SPSS</li>
        <li>SQL</li>
    </ul>

    <div class="skills">
        <div class="skill">
            <label>Python</label>
            <progress value="80" max="100"></progress>
        </div>

        <div class="skill">
            <label>R</label>
            <progress value="75" max="100"></progress>
        </div>

        <div class="skill">
            <label>Excel</label>
            <progress value="90" max="100"></progress>
        </div>

        <div class="skill">
            <label>Statistica</label>
            <progress value="60" max="100"></progress>
        </div>

        <div class="skill">
            <label>SPSS</label>
            <progress value="70" max="100"></progress>
        </div>

        <div class="skill">
            <label>SQL</label>
            <progress value="85" max="100"></progress>
        </div>
    </div>

    <h2>Projects</h2>
    <ol>
        <li>1</li>
        <li>2</li>
        <li>3</li>
        <li>4</li>
        <li>5</li>
    </ol>
</div>

</body>
</html>
