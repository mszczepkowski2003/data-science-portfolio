# data-science-portfolio

### About me
I am a third-year student of Informatics and Econometrics at the University of Gdańsk, aspiring to pursue a master's degree in Big Data. I am eager to learn, continuously improve my skills, and take on new challenges. My strong foundation in statistics, data analysis, and machine learning allows me to approach complex problems with a structured and analytical mindset. I am passionate about data-driven decision-making and always looking for opportunities to apply my knowledge to real-world problems.


<font size="6">Technical skills</font>
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

</body>
</html>

<font size="6">Projects</font>

<div class="projects">
    <h2>My Projects</h2>
    <div class="project-list">
        <div class="project">
            <h3>Real Estate Data Scraping with Selenium</h3>
            <p>This project involved building a web scraper using Selenium to collect real estate listings from the Morizon website, focusing on apartments in Gdynia, Poland. The scraper automates data extraction across multiple pages and collects detailed property information, including price, size, number of rooms, floor, location, and various additional attributes (e.g., building type, construction year, heating system, balcony, etc.).</p>
            <p><strong>Key Features:</strong></p>
            <ul>
                <li><strong>Web Scraping with Selenium:</strong> Automated browsing and data collection from dynamically loaded pages.</li>
                <li><strong>Data Extraction:</strong> Gathered detailed listing information and parsed it into structured data.</li>
                <li><strong>Data Storage:</strong> Exported collected data into a CSV format for further analysis or use.</li>
                <li><strong>Error Handling & Robust Design:</strong> Managed pop-ups, timeouts, and missing elements gracefully for uninterrupted scraping.</li>
                <li><strong>Efficient Navigation:</strong> Implemented a strategy to handle multi-page listings, collecting unique links and efficiently moving across pages.</li>
            </ul>
            <a href="#">View Project</a>
        </div>
        <div class="project">
            <h3>Breast Cancer Classification with Random Forest Classifier</h3>
            <p>Short description of the project. What problem does it solve?</p>
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

<style>
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
</style>





