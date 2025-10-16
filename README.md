# My-Portfolio-during-my-Masters-Data-science-study.
A plug and play Data Expert.
my-eportfolio/
│
├── index.html         <-- Home / About Me
├── style.css          <-- Styling
├── module1.html       <-- Module 1 page
├── module2.html       <-- Module 2 page
└── assets/           <-- Optional folder for images or PDFs
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My E-Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Welcome to My E-Portfolio</h1>
        <nav>
            <a href="index.html">About Me</a>
            <a href="module1.html">Module 1</a>
            <a href="module2.html">Module 2</a>
        </nav>
    </header>

    <main>
        <section id="about-me">
            <h2>About Me</h2>
            <p>Hello! My name is [Your Name]. I am a [Your Program/Role] interested in [Your Interests].</p>
            <h3>Curriculum Vitae</h3>
            <p>Briefly summarize your CV here: education, experience, skills.</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 [Your Name]</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Module 1</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Module 1: [Module Name]</h1>
        <nav>
            <a href="index.html">About Me</a>
            <a href="module1.html">Module 1</a>
            <a href="module2.html">Module 2</a>
        </nav>
    </header>

    <main>
        <section id="learning-outcomes">
            <h2>Learning Outcomes</h2>
            <ul>
                <li>Outcome 1</li>
                <li>Outcome 2</li>
            </ul>
        </section>

        <section id="artefacts">
            <h2>Artefacts</h2>
            <ul>
                <li>
                    <strong>Artefact 1:</strong> Brief description. <em>Feedback received: ...</em>
                </li>
                <li>
                    <strong>Artefact 2:</strong> Brief description. <em>Feedback received: ...</em>
                </li>
            </ul>
        </section>

        <section id="reflection">
            <h2>Reflection</h2>
            <p>What exactly I have learnt and how...</p>
        </section>

        <section id="meeting-notes">
            <h2>Meeting Notes</h2>
            <p>Summary of meetings with team members and tutor.</p>
        </section>

        <section id="skills">
            <h2>Professional Skills Matrix & Action Plan</h2>
            <p>Skills gained/enhanced and how I can use them.</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 [Your Name]</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background: #f4f4f4;
    color: #333;
}

header {
    background: #333;
    color: #fff;
    padding: 1em 0;
    text-align: center;
}

header nav a {
    color: #fff;
    margin: 0 1em;
    text-decoration: none;
}

main {
    padding: 2em;
    max-width: 900px;
    margin: auto;
    background: #fff;
    border-radius: 10px;
}

h1, h2, h3 {
    color: #333;
}

footer {
    text-align: center;
    padding: 1em;
    background: #333;
    color: #fff;
    position: fixed;
    width: 100%;
    bottom: 0;
}
