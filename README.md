<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aaditya Kapoor | Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
</head>
<body>
    <header>
        <div class="profile">
            <img src="profile.jpg" alt="Aaditya Kapoor Profile Picture" class="profile-img">
            <h1>Aaditya Kapoor</h1>
            <p>Entrepreneur | Digital Media Enthusiast | Social Impact Advocate</p>
            <a href="resume.pdf" class="btn" download>Download Resume</a>
        </div>
    </header>

    <main>
        <section id="about">
            <h2>About Me</h2>
            <p>Hi, I'm Aaditya Kapoor. I’m a passionate and curious learner with a strong interest in entrepreneurship, digital media, and social impact. Currently a commerce student at Shaheed Bhagat Singh Evening College, I thrive on turning ideas into action—whether it’s leading my school’s Entrepreneurship Committee, managing social media for a medical startup, or volunteering to support visually challenged students. I love exploring new skills—from graphic design to consumer behavior—and believe in the power of teamwork, empathy, and creativity to drive meaningful change. This site is a window into my journey so far and the exciting paths I’m building for the future.</p>
        </section>

        <section id="education">
            <h2>Education</h2>
            <div class="education-item">
                <h3>B.Com Program</h3>
                <p>Shaheed Bhagat Singh Evening College, Delhi University</p>
                <p>Ongoing</p>
            </div>
            <div class="education-item">
                <h3>BBA - Digital Business & Entrepreneurship</h3>
                <p>IIM Bangalore</p>
                <p>Ongoing</p>
            </div>
            <div class="education-item">
                <h3>High School</h3>
                <p>Birla Vidya Niketan, New Delhi</p>
                <p>Completed</p>
            </div>
        </section>

        <section id="skills">
            <h2>Skills</h2>
            <ul class="skills-list">
                <li>Video Editing</li>
                <li>Social Media Management</li>
                <li>Strong Communication Skills</li>
            </ul>
        </section>

        <section id="experiences">
            <h2>Experiences</h2>
            <div class="experience-item">
                <h3>Video Editor Intern</h3>
                <p>Excel4Entrepreneurs (Instagram Content Creator)</p>
                <p>Created engaging videos on Excel tips and shortcuts for a growing Instagram audience.</p>
            </div>
            <div class="experience-item">
                <h3>Vice-President, Entrepreneurship Committee</h3>
                <p>Birla Vidya Niketan, New Delhi</p>
                <p>Led initiatives to foster entrepreneurial thinking and organized events to promote innovation among students.</p>
            </div>
            <div class="experience-item">
                <h3>Active Member, Inayat Interact Club</h3>
                <p>Birla Vidya Niketan, New Delhi</p>
                <p>Contributed to community service projects, including support for visually challenged students.</p>
            </div>
            <div class="experience-item">
                <h3>Social Media Advisor</h3>
                <p>Vaidic Wellness Products (D2C Medical Startup)</p>
                <p>Managed social media strategy to boost brand visibility and engagement.</p>
            </div>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <p>Email: kapooraaditya16@gmail.com</p>
            <p>Phone: 8447649691</p>
            <div class="social-links">
                <a href="https://www.linkedin.com/in/aaditya-kapoor-100a79249/" class="social-icon" target="_blank">LinkedIn</a>
            </div>
        </section>
    </main>

    <footer>
        <p>© 2025 Aaditya Kapoor. All rights reserved.</p>
    </footer>
</body>
</html>

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Poppins', sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #f4f4f4;
}

header {
    background-color: #1e3a8a;
    color: white;
    text-align: center;
    padding: 2rem 1rem;
}

.profile {
    max-width: 600px;
    margin: 0 auto;
}

.profile-img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    object-fit: cover;
    margin-bottom: 1rem;
}

h1 {
    font-size: 2.5rem;
    margin-bottom: 0.5rem;
}

header p {
    font-size: 1.2rem;
    margin-bottom: 1rem;
}

.btn {
    display: inline-block;
    padding: 0.8rem 1.5rem;
    background-color: #3b82f6;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s;
}

.btn:hover {
    background-color: #2563eb;
}

main {
    max-width: 800px;
    margin: 2rem auto;
    padding: 0 1rem;
}

section {
    margin-bottom: 3rem;
}

h2 {
    font-size: 2rem;
    color: #1e3a8a;
    margin-bottom: 1rem;
    text-align: center;
}

.skills-list {
    list-style: none;
    display: flex;
    flex-wrap: wrap;
    gap: 1rem;
    justify-content: center;
}

.skills-list li {
    background-color: #e5e7eb;
    padding: 0.5rem 1rem;
    border-radius: 5px;
}

.education-item, .experience-item {
    background-color: white;
    padding: 1rem;
    border-radius: 5px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    margin-bottom: 1rem;
}

.education-item h3, .experience-item h3 {
    color: #1e3a8a;
    margin-bottom: 0.5rem;
}

.social-links {
    display: flex;
    gap: 1rem;
    justify-content: center;
    margin-top: 1rem;
}

.social-icon {
    color: #3b82f6;
    text-decoration: none;
    font-weight: bold;
}

.social-icon:hover {
    color: #2563eb;
}

footer {
    background-color: #1e3a8a;
    color: white;
    text-align: center;
    padding: 1rem;
    margin-top: 2rem;
}

@media (max-width: 600px) {
    h1 {
        font-size: 2rem;
    }

    h2 {
        font-size: 1.5rem;
    }

    .profile-img {
        width: 120px;
        height: 120px;
    }

    .btn {
        padding: 0.6rem 1rem;
    }

    .skills-list {
        flex-direction: column;
        align-items: center;
    }
}
