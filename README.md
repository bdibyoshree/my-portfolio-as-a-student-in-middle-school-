# my-portfolio-as-a-student-in-middle-school-<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Personal Portfolio</title>
    <style>
        /* CSS Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f4f7f6;
            color: #333;
            line-height: 1.6;
        }

        header {
            background: linear-gradient(135deg, #4f46e5, #06b6d4);
            color: white;
            text-align: center;
            padding: 5rem 1rem;
        }

        header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }

        header p {
            font-size: 1.2rem;
            opacity: 0.9;
        }

        .container {
            max-width: 900px;
            margin: 2rem auto;
            padding: 0 1.5rem;
        }

        section {
            background: white;
            padding: 2rem;
            border-radius: 8px;
            margin-bottom: 2rem;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
        }

        h2 {
            color: #4f46e5;
            margin-bottom: 1rem;
            border-bottom: 2px solid #e5e7eb;
            padding-bottom: 0.5rem;
        }

        .skills-tags {
            display: flex;
            flex-wrap: wrap;
            gap: 0.5rem;
            margin-top: 1rem;
        }

        .tag {
            background-color: #e0e7ff;
            color: #4338ca;
            padding: 0.4rem 0.8rem;
            border-radius: 20px;
            font-size: 0.9rem;
            font-weight: bold;
        }

        .project-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 1.5rem;
            margin-top: 1rem;
        }

        @media (max-width: 600px) {
            .project-grid {
                grid-template-columns: 1fr;
            }
        }

        .project-card {
            border: 1px solid #e5e7eb;
            padding: 1.5rem;
            border-radius: 6px;
            background-color: #fafafa;
        }

        .project-card h3 {
            color: #06b6d4;
            margin-bottom: 0.5rem;
        }

        footer {
            text-align: center;
            padding: 2rem;
            color: #666;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>

    <header>
        <h1>Hello, I'm Your Name</h1>
        <p>Student | Creator | Problem Solver</p>
    </header>

    <div class="container">
        <section id="about">
            <h2>About Me</h2>
            <p>Welcome to my portfolio! I am an 8th-grade student passionate about technology, creative writing, and building cool things. When I'm not studying or coding, you can find me practicing grammar quizzes, reading books, or working on creative short stories.</p>
        </section>

        <section id="skills">
            <h2>My Skills</h2>
            <p>Here are some of the things I am great at or currently learning:</p>
            <div class="skills-tags">
                <span class="tag">HTML & CSS</span>
                <span class="tag">Creative Writing</span>
                <span class="tag">Public Speaking</span>
                <span class="tag">Grammar Mastery</span>
                <span class="tag">Video Editing</span>
            </div>
        </section>

        <section id="projects">
            <h2>My Projects</h2>
            <div class="project-grid">
                <div class="project-card">
                    <h3>Project Title 1</h3>
                    <p>A brief description of a cool science project, website, or app you created recently.</p>
                </div>
                <div class="project-card">
                    <h3>Project Title 2</h3>
                    <p>A short story compilation, essay series, or presentation you worked on for class.</p>
                </div>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2026 Your Name. Built from scratch with code.</p>
    </footer>

</body>
</html>