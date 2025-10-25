<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub README Preview</title>
    <style>
:root {
  /* Primitive Color Tokens */
  --color-white: rgba(255, 255, 255, 1);
  --color-black: rgba(0, 0, 0, 1);
  --color-cream-50: rgba(252, 252, 249, 1);
  --color-cream-100: rgba(255, 255, 253, 1);
  --color-gray-200: rgba(245, 245, 245, 1);
  --color-gray-300: rgba(167, 169, 169, 1);
  --color-gray-400: rgba(119, 124, 124, 1);
  --color-slate-500: rgba(98, 108, 113, 1);
  --color-brown-600: rgba(94, 82, 64, 1);
  --color-charcoal-700: rgba(31, 33, 33, 1);
  --color-charcoal-800: rgba(38, 40, 40, 1);
  --color-slate-900: rgba(19, 52, 59, 1);
  --color-teal-300: rgba(50, 184, 198, 1);
  --color-teal-400: rgba(45, 166, 178, 1);
  --color-teal-500: rgba(33, 128, 141, 1);
  --color-teal-600: rgba(29, 116, 128, 1);
  --color-teal-700: rgba(26, 104, 115, 1);
  --color-teal-800: rgba(41, 150, 161, 1);
  --color-red-400: rgba(255, 84, 89, 1);
  --color-red-500: rgba(192, 21, 47, 1);
  --color-orange-400: rgba(230, 129, 97, 1);
  --color-orange-500: rgba(168, 75, 47, 1);

  /* RGB versions for opacity control */
  --color-brown-600-rgb: 94, 82, 64;
  --color-teal-500-rgb: 33, 128, 141;
  --color-slate-900-rgb: 19, 52, 59;
  --color-slate-500-rgb: 98, 108, 113;
  --color-red-500-rgb: 192, 21, 47;
  --color-red-400-rgb: 255, 84, 89;
  --color-orange-500-rgb: 168, 75, 47;
  --color-orange-400-rgb: 230, 129, 97;

  /* Background color tokens (Light Mode) */
  --color-bg-1: rgba(59, 130, 246, 0.08);
  --color-bg-2: rgba(245, 158, 11, 0.08);
  --color-bg-3: rgba(34, 197, 94, 0.08);
  --color-bg-4: rgba(239, 68, 68, 0.08);
  --color-bg-5: rgba(147, 51, 234, 0.08);
  --color-bg-6: rgba(249, 115, 22, 0.08);
  --color-bg-7: rgba(236, 72, 153, 0.08);
  --color-bg-8: rgba(6, 182, 212, 0.08);

  /* Semantic Color Tokens (Light Mode) */
  --color-background: var(--color-cream-50);
  --color-surface: var(--color-cream-100);
  --color-text: var(--color-slate-900);
  --color-text-secondary: var(--color-slate-500);
  --color-primary: var(--color-teal-500);
  --color-primary-hover: var(--color-teal-600);
  --color-primary-active: var(--color-teal-700);
  --color-secondary: rgba(var(--color-brown-600-rgb), 0.12);
  --color-secondary-hover: rgba(var(--color-brown-600-rgb), 0.2);
  --color-secondary-active: rgba(var(--color-brown-600-rgb), 0.25);
  --color-border: rgba(var(--color-brown-600-rgb), 0.2);
  --color-btn-primary-text: var(--color-cream-50);
  --color-card-border: rgba(var(--color-brown-600-rgb), 0.12);
  --color-card-border-inner: rgba(var(--color-brown-600-rgb), 0.12);
  --color-error: var(--color-red-500);
  --color-success: var(--color-teal-500);
  --color-warning: var(--color-orange-500);
  --color-info: var(--color-slate-500);
  --color-focus-ring: rgba(var(--color-teal-500-rgb), 0.4);
  --color-select-caret: rgba(var(--color-slate-900-rgb), 0.8);

  /* Typography */
  --font-family-base: "FKGroteskNeue", "Geist", "Inter", -apple-system,
    BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-family-mono: "Berkeley Mono", ui-monospace, SFMono-Regular, Menlo,
    Monaco, Consolas, monospace;
  --font-size-xs: 11px;
  --font-size-sm: 12px;
  --font-size-base: 14px;
  --font-size-md: 14px;
  --font-size-lg: 16px;
  --font-size-xl: 18px;
  --font-size-2xl: 20px;
  --font-size-3xl: 24px;
  --font-size-4xl: 30px;
  --font-weight-normal: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 550;
  --font-weight-bold: 600;
  --line-height-tight: 1.2;
  --line-height-normal: 1.5;
  --letter-spacing-tight: -0.01em;

  /* Spacing */
  --space-0: 0;
  --space-1: 1px;
  --space-2: 2px;
  --space-4: 4px;
  --space-6: 6px;
  --space-8: 8px;
  --space-10: 10px;
  --space-12: 12px;
  --space-16: 16px;
  --space-20: 20px;
  --space-24: 24px;
  --space-32: 32px;

  /* Border Radius */
  --radius-sm: 6px;
  --radius-base: 8px;
  --radius-md: 10px;
  --radius-lg: 12px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-xs: 0 1px 2px rgba(0, 0, 0, 0.02);
  --shadow-sm: 0 1px 3px rgba(0, 0, 0, 0.04), 0 1px 2px rgba(0, 0, 0, 0.02);
  --shadow-md: 0 4px 6px -1px rgba(0, 0, 0, 0.04),
    0 2px 4px -1px rgba(0, 0, 0, 0.02);
  --shadow-lg: 0 10px 15px -3px rgba(0, 0, 0, 0.04),
    0 4px 6px -2px rgba(0, 0, 0, 0.02);
  --shadow-inset-sm: inset 0 1px 0 rgba(255, 255, 255, 0.15),
    inset 0 -1px 0 rgba(0, 0, 0, 0.03);

  /* Animation */
  --duration-fast: 150ms;
  --duration-normal: 250ms;
  --ease-standard: cubic-bezier(0.16, 1, 0.3, 1);
}

@media (prefers-color-scheme: dark) {
  :root {
    --color-gray-400-rgb: 119, 124, 124;
    --color-teal-300-rgb: 50, 184, 198;
    --color-gray-300-rgb: 167, 169, 169;
    --color-gray-200-rgb: 245, 245, 245;

    --color-bg-1: rgba(29, 78, 216, 0.15);
    --color-bg-2: rgba(180, 83, 9, 0.15);
    --color-bg-3: rgba(21, 128, 61, 0.15);
    --color-bg-4: rgba(185, 28, 28, 0.15);
    --color-bg-5: rgba(107, 33, 168, 0.15);
    --color-bg-6: rgba(194, 65, 12, 0.15);
    --color-bg-7: rgba(190, 24, 93, 0.15);
    --color-bg-8: rgba(8, 145, 178, 0.15);

    --color-background: var(--color-charcoal-700);
    --color-surface: var(--color-charcoal-800);
    --color-text: var(--color-gray-200);
    --color-text-secondary: rgba(var(--color-gray-300-rgb), 0.7);
    --color-primary: var(--color-teal-300);
    --color-primary-hover: var(--color-teal-400);
    --color-primary-active: var(--color-teal-800);
    --color-secondary: rgba(var(--color-gray-400-rgb), 0.15);
    --color-secondary-hover: rgba(var(--color-gray-400-rgb), 0.25);
    --color-secondary-active: rgba(var(--color-gray-400-rgb), 0.3);
    --color-border: rgba(var(--color-gray-400-rgb), 0.3);
    --color-error: var(--color-red-400);
    --color-success: var(--color-teal-300);
    --color-warning: var(--color-orange-400);
    --color-info: var(--color-gray-300);
    --color-focus-ring: rgba(var(--color-teal-300-rgb), 0.4);
    --color-btn-primary-text: var(--color-slate-900);
    --color-card-border: rgba(var(--color-gray-400-rgb), 0.2);
    --color-card-border-inner: rgba(var(--color-gray-400-rgb), 0.15);
  }
}

body {
  font-family: var(--font-family-base);
  background: var(--color-background);
  color: var(--color-text);
  line-height: var(--line-height-normal);
  margin: 0;
  padding: var(--space-24);
  max-width: 1000px;
  margin: 0 auto;
}

.readme-container {
  background: var(--color-surface);
  padding: var(--space-32);
  border-radius: var(--radius-lg);
  box-shadow: var(--shadow-lg);
  border: 1px solid var(--color-card-border);
}

h1, h2 {
  color: var(--color-text);
  font-weight: var(--font-weight-bold);
  margin-top: var(--space-24);
  margin-bottom: var(--space-16);
}

h1 {
  font-size: var(--font-size-4xl);
  text-align: center;
  border-bottom: 2px solid var(--color-primary);
  padding-bottom: var(--space-16);
}

h2 {
  font-size: var(--font-size-2xl);
  border-bottom: 1px solid var(--color-border);
  padding-bottom: var(--space-8);
}

p {
  color: var(--color-text-secondary);
  margin-bottom: var(--space-16);
  line-height: 1.7;
}

.skills {
  display: flex;
  flex-wrap: wrap;
  gap: var(--space-8);
  margin: var(--space-16) 0;
}

.skill-badge {
  background: var(--color-secondary);
  color: var(--color-text);
  padding: var(--space-6) var(--space-12);
  border-radius: var(--radius-full);
  font-size: var(--font-size-sm);
  font-weight: var(--font-weight-medium);
  border: 1px solid var(--color-border);
  transition: all var(--duration-fast) var(--ease-standard);
}

.skill-badge:hover {
  background: var(--color-secondary-hover);
  transform: translateY(-2px);
}

.projects {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: var(--space-20);
  margin: var(--space-20) 0;
}

.project-card {
  background: var(--color-background);
  border: 1px solid var(--color-card-border);
  border-radius: var(--radius-md);
  padding: var(--space-20);
  transition: all var(--duration-normal) var(--ease-standard);
}

.project-card:hover {
  transform: translateY(-4px);
  box-shadow: var(--shadow-md);
  border-color: var(--color-primary);
}

.project-card h3 {
  color: var(--color-primary);
  font-size: var(--font-size-xl);
  margin-top: 0;
  margin-bottom: var(--space-12);
}

.project-card p {
  font-size: var(--font-size-base);
  margin-bottom: var(--space-12);
}

.tech-stack {
  color: var(--color-text-secondary);
  font-size: var(--font-size-sm);
  font-style: italic;
}

.contact-section {
  background: var(--color-bg-1);
  border-radius: var(--radius-md);
  padding: var(--space-20);
  margin-top: var(--space-24);
  border: 1px solid var(--color-card-border);
}

.contact-links {
  display: flex;
  gap: var(--space-16);
  flex-wrap: wrap;
  margin-top: var(--space-16);
}

.contact-link {
  color: var(--color-primary);
  text-decoration: none;
  font-weight: var(--font-weight-medium);
  transition: color var(--duration-fast) var(--ease-standard);
}

.contact-link:hover {
  color: var(--color-primary-hover);
  text-decoration: underline;
}

.stats {
  display: flex;
  justify-content: center;
  gap: var(--space-16);
  margin: var(--space-24) 0;
  flex-wrap: wrap;
}

.stat-item {
  background: var(--color-bg-3);
  padding: var(--space-12) var(--space-20);
  border-radius: var(--radius-base);
  border: 1px solid var(--color-card-border);
  text-align: center;
}

.code-block {
  background: var(--color-secondary);
  border: 1px solid var(--color-border);
  border-radius: var(--radius-sm);
  padding: var(--space-16);
  margin: var(--space-16) 0;
  overflow-x: auto;
  font-family: var(--font-family-mono);
  font-size: var(--font-size-sm);
  color: var(--color-text);
}

@media (max-width: 768px) {
  body {
    padding: var(--space-12);
  }
  
  .readme-container {
    padding: var(--space-20);
  }
  
  .projects {
    grid-template-columns: 1fr;
  }
  
  .stats {
    flex-direction: column;
  }
}
    </style>
</head>
<body>
    <div class="readme-container">
        <h1>👋 Hi, I'm Venkatesh Jaggaraju</h1>
        
        <div style="text-align: center; margin: var(--space-24) 0;">
            <p style="font-size: var(--font-size-lg); color: var(--color-text);">
                <strong>Java Full-Stack Developer</strong> | Spring Boot Enthusiast | Problem Solver
            </p>
        </div>

        <div class="stats">
            <div class="stat-item">
                <strong style="color: var(--color-primary);">🎓 B.Tech CSE</strong>
                <div style="font-size: var(--font-size-sm);">2024 Graduate</div>
            </div>
            <div class="stat-item">
                <strong style="color: var(--color-primary);">💼 Open to Work</strong>
                <div style="font-size: var(--font-size-sm);">Java Developer</div>
            </div>
            <div class="stat-item">
                <strong style="color: var(--color-primary);">📍 Location</strong>
                <div style="font-size: var(--font-size-sm);">India</div>
            </div>
        </div>

        <h2>🚀 About Me</h2>
        <p>
            Motivated Java Full-Stack Developer with strong knowledge of Java, Spring Boot, REST APIs, SQL, HTML, CSS, and JavaScript. 
            I build reliable backend systems and enjoy solving problems with clean code. Currently exploring object detection using 
            convolutional neural networks and building full-stack e-commerce applications with Spring &amp; MySQL.
        </p>
        <p>
            I'm passionate about problem-solving, debugging, and delivering high-quality software. Always eager to learn new technologies 
            and best practices in software development.
        </p>

        <h2>💻 Technical Skills</h2>
        <div class="skills">
            <span class="skill-badge">Java</span>
            <span class="skill-badge">JDBC</span>
            <span class="skill-badge">Hibernate</span>
            <span class="skill-badge">Spring Boot</span>
            <span class="skill-badge">REST APIs</span>
            <span class="skill-badge">SQL</span>
            <span class="skill-badge">MySQL</span>
            <span class="skill-badge">Git</span>
            <span class="skill-badge">HTML</span>
            <span class="skill-badge">CSS</span>
            <span class="skill-badge">JavaScript</span>
            <span class="skill-badge">React</span>
            <span class="skill-badge">Python</span>
            <span class="skill-badge">TensorFlow</span>
            <span class="skill-badge">OpenCV</span>
        </div>

        <h2>🔥 Featured Projects</h2>
        <div class="projects">
            <div class="project-card">
                <h3>🛒 E-commerce Web Application</h3>
                <p>
                    Full-stack e-commerce application built with Spring Boot for backend, MySQL for persistence, 
                    and JSP/HTML for the frontend. Implemented product management, user authentication, and order 
                    processing flows with secure REST APIs.
                </p>
                <p class="tech-stack">
                    <strong>Tech Stack:</strong> Java, Spring Boot, MySQL, JSP/Servlets, REST APIs
                </p>
            </div>

            <div class="project-card">
                <h3>🤖 Object Detection using CNN</h3>
                <p>
                    Designed and trained convolutional neural networks to detect and localize objects in images. 
                    Implemented data preprocessing pipelines, model training, and evaluation. Explored transfer 
                    learning techniques for improved accuracy and performance.
                </p>
                <p class="tech-stack">
                    <strong>Tech Stack:</strong> Python, TensorFlow/PyTorch, OpenCV, NumPy
                </p>
            </div>
        </div>

        <h2>📊 GitHub Stats</h2>
        <div class="code-block">
// Continuously learning and building
const developer = {
  name: "Venkatesh Jaggaraju",
  role: "Java Full-Stack Developer",
  technologies: ["Java", "Spring Boot", "React", "SQL"],
  currentFocus: ["REST APIs", "Microservices", "Deep Learning"],
  lookingFor: "Entry-level Java Development opportunities"
};
        </div>

        <h2>📫 Get in Touch</h2>
        <div class="contact-section">
            <p style="margin-bottom: var(--space-12);">
                I'm actively seeking opportunities in Java development. Feel free to reach out for collaboration, 
                opportunities, or just to connect!
            </p>
            <div class="contact-links">
                <a href="mailto:venkateshjaggaraju2002@gmail.com" class="contact-link">
                    📧 venkateshjaggaraju2002@gmail.com
                </a>
                <a href="tel:+919618348231" class="contact-link">
                    📱 +91 96183 48231
                </a>
            </div>
        </div>

        <div style="text-align: center; margin-top: var(--space-32); padding-top: var(--space-20); border-top: 1px solid var(--color-border);">
            <p style="color: var(--color-text-secondary); font-size: var(--font-size-sm);">
                ⭐ Feel free to star my repositories if you find them useful!<br>
                💬 Open to feedback and collaboration opportunities
            </p>
        </div>
    </div>
</body>
</html>
