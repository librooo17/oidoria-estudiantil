<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>  Oidoría Estudiantil FFyL</title>
    <style>
        /* Formal styling */
        body {
            font-family: 'Georgia', serif;
            line-height: 1.6;
            color: #333;
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
            background-color: #fafafa;
        }
        
        header {
            border-bottom: 1px solid #e1e1e1;
            padding-bottom: 20px;
            margin-bottom: 30px;
        }
        
        h1 {
            font-size: 2.5em;
            color: #2c3e50;
            margin-bottom: 10px;
        }
        
        .description {
            font-size: 1.1em;
            color: #7f8c8d;
            font-style: italic;
        }
        
        .article-container {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 25px;
            margin: 40px 0;
        }
        
        .article-card {
            background: white;
            border-radius: 4px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
            overflow: hidden;
        }
        
        .article-img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-bottom: 1px solid #eee;
        }
        
        .article-content {
            padding: 20px;
        }
        
        .links-section {
            margin-top: 40px;
            background: white;
            padding: 25px;
            border-radius: 4px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        
        .resource-link {
            display: block;
            margin: 15px 0;
            color: #3498db;
            text-decoration: none;
            font-weight: 500;
        }
        
        .resource-link:hover {
            text-decoration: underline;
        }
        
        footer {
            margin-top: 50px;
            text-align: center;
            color: #95a5a6;
            font-size: 0.9em;
            border-top: 1px solid #e1e1e1;
            padding-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Professional Insights</h1>
        <p class="description">Thoughtful analysis on industry trends and professional development</p>
    </header>
    
    <main>
        <div class="article-container">
            <!-- Article 1 -->
            <div class="article-card">
                <img src="images/business-meeting.jpg" alt="Team meeting in conference room" class="article-img">
                <div class="article-content">
                    <h2>Effective Team Collaboration</h2>
                    <p>Strategies for improving communication and productivity in professional settings.</p>
                </div>
            </div>
            
            <!-- Article 2 -->
            <div class="article-card">
                <img src="images/data-analysis.jpg" alt="Data visualization on computer screen" class="article-img">
                <div class="article-content">
                    <h2>Data-Driven Decision Making</h2>
                    <p>How to leverage analytics for better business outcomes.</p>
                </div>
            </div>
            
            <!-- Article 3 -->
            <div class="article-card">
                <img src="images/leadership.jpg" alt="Mentor speaking to group" class="article-img">
                <div class="article-content">
                    <h2>Modern Leadership Principles</h2>
                    <p>Adapting management styles for today's diverse workforce.</p>
                </div>
            </div>
            
            <!-- Article 4 -->
            <div class="article-card">
                <img src="images/innovation.jpg" alt="Lightbulb with circuit board" class="article-img">
                <div class="article-content">
                    <h2>Fostering Innovation</h2>
                    <p>Creating environments that encourage creative problem solving.</p>
                </div>
            </div>
        </div>
        
        <div class="links-section">
            <h2>Links a el formulario, el grupo de signal y la página vieja de la Oidoría</h2>
            <a href="https://hbr.org" class="resource-link">Harvard Business Review - Latest Management Research</a>
            <a href="https://www.ted.com/topics/business" class="resource-link">TED Talks: Business Innovations</a>
            <a href="https://www.forbes.com/business" class="resource-link">Forbes Business Strategy Section</a>
        </div>
    </main>
    

</body>
</html>
