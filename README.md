<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Roma Sahu | ML Portfolio</title>
  <link rel="stylesheet" href="style.css"/>
</head>
<body>
  <header>
    <h1>👋 Hi, I'm <span>Roma Sahu</span></h1>
    <p>Aspiring ML Engineer | Python Enthusiast</p>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>I love solving real-world problems using data and machine learning. I’m currently exploring deep learning and building fun projects.</p>
  </section>

  <section id="skills">
    <h2>Tech Stack</h2>
    <div class="badges">
      <span>Python</span>
      <span>Pandas</span>
      <span>Scikit-learn</span>
      <span>NumPy</span>
      <span>Jupyter</span>
      <span>GitHub</span>
    </div>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <ul>
      <li>
        <strong>Spam Classifier</strong> — Classifies spam using NLP + TF-IDF
        <a href="https://github.com/romasahu24/spam-classifier" target="_blank">View</a>
      </li>
      <li>
        <strong>House Price Predictor</strong> — Regression model on housing data
        <a href="https://github.com/romasahu24/house-price-prediction" target="_blank">View</a>
      </li>
      <li>
        <strong>Covid Data Analysis</strong> — Data cleaning and visualization
        <a href="https://github.com/romasahu24/covid-analysis" target="_blank">View</a>
      </li>
    </ul>
  </section>

  <footer>
    <p>📫 Connect with me:</p>
    <a href="https://linkedin.com/in/romasahu" target="_blank">LinkedIn</a> |
    <a href="mailto:romasahu24@gmail.com">Gmail</a>
  </footer>

  <script src="script.js"></script>
</body>
</html>
body {
  font-family: 'Segoe UI', sans-serif;
  margin: 0;
  padding: 0;
  background: #f0f4f8;
  color: #333;
  line-height: 1.6;
}

header {
  background: #5c67f2;
  color: white;
  padding: 2rem;
  text-align: center;
}

header span {
  color: #ffe066;
}

section {
  padding: 2rem;
}

h2 {
  color: #5c67f2;
}

.badges span {
  background: #dbeafe;
  color: #1e40af;
  padding: 8px 12px;
  border-radius: 10px;
  margin: 5px;
  display: inline-block;
  font-weight: bold;
}

ul {
  list-style: none;
  padding: 0;
}

li {
  background: #fff;
  border-left: 5px solid #5c67f2;
  margin-bottom: 1rem;
  padding: 1rem;
  box-shadow: 0 2px 6px rgba(0,0,0,0.1);
}

li a {
  color: #5c67f2;
  text-decoration: none;
  margin-left: 10px;
}

footer {
  background: #e0e7ff;
  text-align: center;
  padding: 1rem;
  margin-top: 2rem;
}
// Simple fade-in effect on load
document.addEventListener('DOMContentLoaded', () => {
  document.body.style.opacity = 0;
  setTimeout(() => {
    document.body.style.transition = 'opacity 1s';
    document.body.style.opacity = 1;
  }, 100);
});



---


---
