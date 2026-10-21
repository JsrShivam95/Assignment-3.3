<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>College & Course Information - Assignment 3.3</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
            line-height: 1.6;
        }
        header {
            background-color: #2c3e50;
            color: white;
            padding: 1rem 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .logo {
            font-size: 1.5rem;
            font-weight: bold;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
            font-size: 1rem;
        }
        nav a:hover {
            text-decoration: underline;
        }
        main {
            padding: 2.5rem 2rem;
            max-width: 850px;
            margin: 2rem auto;
            background: white;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            border-radius: 8px;
        }
        h1, h2, h3 {
            color: #2c3e50;
        }
        h1 {
            border-bottom: 2px solid #2c3e50;
            padding-bottom: 10px;
            margin-top: 0;
        }
        section {
            margin-bottom: 2.5rem;
        }
        ul, ol {
            margin-top: 0.5rem;
            margin-bottom: 1rem;
        }
        li {
            margin-bottom: 6px;
        }
        dl {
            background: #fafafa;
            padding: 15px;
            border-left: 4px solid #2c3e50;
            border-radius: 4px;
        }
        dt {
            font-weight: bold;
            color: #2c3e50;
            margin-top: 10px;
        }
        dt:first-child {
            margin-top: 0;
        }
        dd {
            margin-left: 0;
            margin-bottom: 10px;
            color: #555;
        }
        footer {
            text-align: center;
            padding: 1rem;
            margin-top: 3rem;
            color: #777;
        }
    </style>
</head>
<body>

    <header>
        <div class="logo">MyPortfolio</div>
        <nav>
            <a href="index.html">Home</a>
            <a href="about.html">About</a>
            <a href="college-info.html">College Info</a>
        </nav>
    </header>

    <main>
        <!-- 1. Introduction for the College/Course -->
        <section>
            <h1>Computer Science & Web Development Course</h1>
            <p>Welcome to our comprehensive academic program overview. This course equips students with foundational programming skills, modern web standards, version control workflows, and practical software engineering principles required in today's tech-driven world.</p>
        </section>

        <!-- 2. Unordered List for Departments/Subjects -->
        <section>
            <h2>Core Subjects & Departments</h2>
            <p>The curriculum is structured across multiple core computing domains:</p>
            <ul>
                <li>Computer Science and Engineering</li>
                <li>Information Technology and Systems</li>
                <li>Web Technologies and UI/UX Design</li>
                <li>Database Management and Cloud Computing</li>
            </ul>
        </section>

        <!-- 3. Ordered List for Admission Process -->
        <section>
            <h2>Admission Process</h2>
            <p>Follow these sequential steps to apply and secure your admission:</p>
            <ol>
                <li>Submit the online application registration form.</li>
                <li>Upload academic transcripts and required identification documents.</li>
                <li>Appear for the entrance evaluation or counseling session.</li>
                <li>Receive the official admission offer letter.</li>
                <li>Complete fee payment to confirm course enrollment.</li>
            </ol>
        </section>

        <!-- 4. Nested List for Course Topics -->
        <section>
            <h2>Detailed Course Breakdown: Web Development</h2>
            <p>Here is an outline of the modules covered under the frontend web development module:</p>
            <ul>
                <li><strong>Module 1: HTML Fundamentals</strong>
                    <ul>
                        <li>Document structure and DOCTYPE declaration</li>
                        <li>Headings, paragraphs, text formatting tags</li>
                        <li>Working with local images (`src`, `alt`, dimensions)</li>
                    </ul>
                </li>
                <li><strong>Module 2: Hyperlinks & Navigation</strong>
                    <ul>
                        <li>Internal page linking (`&lt;a href&gt;`)</li>
                        <li>External links with security attributes (`target="_blank"`, `rel="noopener noreferrer"`)</li>
                    </ul>
                </li>
                <li><strong>Module 3: Lists & Tables</strong>
                    <ul>
                        <li>Ordered (`&lt;ol&gt;`), unordered (`&lt;ul&gt;`), and nested lists</li>
                        <li>Description lists (`&lt;dl&gt;`, `&lt;dt&gt;`, `&lt;dd&gt;`)</li>
                    </ul>
                </li>
            </ul>
        </section>

        <!-- 5. Description List for Course/Teacher Details -->
        <section>
            <h2>Faculty & Course Information Details</h2>
            <p>Key information regarding course structure and instructors:</p>
            <dl>
                <dt>Course Code & Title</dt>
                <dd>CS-101: Introduction to Web Technologies and HTML Architecture</dd>

                <dt>Lead Instructor</dt>
                <dd>Dr. R. Sharma (Professor of Computer Science & Web Engineering)</dd>

                <dt>Course Duration</dt>
                <dd>16 Weeks (Includes hands-on weekly coding assignments and portfolio projects)</dd>

                <dt>Evaluation Criteria</dt>
                <dd>70% Practical Code Submissions & Projects, 30% Final Assessment</dd>
            </dl>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 Assignment 3.3. All rights reserved.</p>
    </footer>

</body>
</html>