# data-science-portfolio

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

        .projects {
            max-width: 800px;
            margin: 40px auto;
            text-align: center;
        }

        .project-list {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .project {
            background: white;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease;
        }

        .project:hover {
            transform: translateY(-5px);
        }

        .project h3 {
            margin-bottom: 10px;
        }

        .project a {
            display: inline-block;
            margin-top: 10px;
            padding: 8px 15px;
            background: #007bff;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }

        .project a:hover {
            background: #0056b3;
        }

        .key-features {
            display: flex;
            flex-direction: column;
            gap: 15px;
            margin-top: 20px;
            padding-left: 20px;
            text-align: left;
        }

        .feature {
            display: flex;
            align-items: start;
            gap: 15px;
            background-color: #f9f9f9;
            padding: 10px 15px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .icon {
            font-size: 1.5rem;
            flex-shrink: 0;
        }

        .text {
            font-size: 1rem;
            color: #333;
        }

        .feature strong {
            color: #007bff;
        }
    </style>
</head>
<body>

<div class="content">
    <h3>About me</h3>
    <p>I am a third-year student of Informatics and Econometrics at the University of Gdańsk, aspiring to pursue a master's degree in Big Data. I am eager to learn, continuously improve my skills, and take on new challenges. My strong foundation in statistics, data analysis, and machine learning allows me to approach complex problems with a structured and analytical mindset. I am passionate about data-driven decision-making and always looking for opportunities to apply my knowledge to real-world problems.</p>
    
    <h2>Technical skills</h2>
    <div class="skills">
        <div class="skill">
            <label>Python</label>
            <progress value="20" max="100"></progress>
        </div>
        <div class="skill">
            <label>R</label>
            <progress value="10" max="100"></progress>
        </div>
        <div class="skill">
            <label>Excel</label>
            <progress value="70" max="100"></progress>
        </div>
        <div class="skill">
            <label>Statistica</label>
            <progress value="10" max="100"></progress>
        </div>
        <div class="skill">
            <label>SPSS</label>
            <progress value="20" max="100"></progress>
        </div>
        <div class="skill">
            <label>SQL</label>
            <progress value="10" max="100"></progress>
        </div>
    </div>
</div>

<h2>Projects</h2>
<div class="projects">
    <div class="project-list">
        <div class="project">
            <h3>Real Estate Data Scraping with Python</h3>
            <p>This project involved building a web scraper using Selenium to collect real estate listings from the Morizon website, focusing on apartments in Tricity, Poland. The scraper automates data extraction across multiple pages and collects detailed property information, including price, size, number of rooms, floor, location, and various additional attributes (e.g., building type, construction year, heating system, balcony, etc.).</p>
            <p><strong>Key Features:</strong></p>
            <div class="key-features">
                <div class="feature">
                    <div class="icon">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/1/12/Flag_of_Poland.svg" alt="Polska" style="width: 30px; height: 20px;">
                        </div>
                <div class="text">
                <strong>Project Language:</strong> Polish
                    </div>
                </div>
                <div class="feature">
                    <div class="icon">🔄</div>
                    <div class="text">
                        <strong>Web Scraping with Selenium:</strong>
                        Automated browsing and data collection from dynamically loaded pages.
                    </div>
                </div>
                <div class="feature">
                    <div class="icon">📊</div>
                    <div class="text">
                        <strong>Data Extraction:</strong>
                        Gathered detailed listing information and parsed it into structured data.
                    </div>
                </div>
                <div class="feature">
                    <div class="icon">💾</div>
                    <div class="text">
                        <strong>Data Storage:</strong>
                        Exported collected data into a CSV format for further analysis or use.
                    </div>
                </div>
                <div class="feature">
                    <div class="icon">⚙️</div>
                    <div class="text">
                        <strong>Error Handling & Robust Design:</strong>
                        Dealt with pop-ups, timeouts, and missing elements to ensure smooth scraping.
                    </div>
                </div>
                <div class="feature">
                    <div class="icon">🔁</div>
                    <div class="text">
                        <strong>Efficient Navigation:</strong>
                        Developed a way to manage multi-page listings, gather unique links, and move smoothly between pages.
                    </div>
                </div>
            </div>
            <a href="#">View Project</a>
        </div>
        <div class="project">
            <h3>Breast Cancer Classification with Random Forest Classifier</h3>
            <p>This project was about developing a machine learning model to classify breast cancer cases using a dataset of tumor characteristics. The workflow included data preprocessing, exploratory data analysis, and feature engineering to optimize model performance. The classification model predicts whether a tumor is benign or malignant based on key attributes such as radius, texture, perimeter, and                  smoothness. Various evaluation metrics, including ROC curves and confusion matrices, were used to assess accuracy and reliability. Final model classifies cases with 95% accuracy.</p>
            <a href="#">View Project</a>
        </div>
        <div class="project">
            <h3>NLP Classification of Film Reviews</h3>
            <p>Short description of the project. What problem does it solve?</p>
            <a href="#">View Project</a>
        </div>
        <div class="project">
            <h3>Protein Yoghurts Marketing Survey and Analysis</h3>
            <p>Short description of the project. What problem does it solve?</p>
            <a href="#">View Project</a>
        </div>
        <div class="project">
            <h3>Project 5</h3>
            <p>Short description of the project. What problem does it solve?</p>
            <a href="#">View Project</a>
        </div>
    </div>
</div>

</body>
</html>





