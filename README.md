<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>README Preview</title>
    <style>
        :root {
            --color-bg: #0d1117;
            --color-surface: #161b22;
            --color-border: #30363d;
            --color-text: #c9d1d9;
            --color-text-muted: #8b949e;
            --color-primary: #58a6ff;
            --color-success: #3fb950;
            --font-mono: ui-monospace, SFMono-Regular, 'SF Mono', Menlo, Consolas, 'Liberation Mono', monospace;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Noto Sans', Helvetica, Arial, sans-serif;
            background: var(--color-bg);
            color: var(--color-text);
            line-height: 1.6;
            padding: 40px 20px;
            margin: 0;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            background: var(--color-surface);
            padding: 40px;
            border-radius: 6px;
            border: 1px solid var(--color-border);
        }

        h1 {
            font-size: 2em;
            margin-bottom: 0.5em;
            border-bottom: 1px solid var(--color-border);
            padding-bottom: 0.3em;
        }

        h2 {
            font-size: 1.5em;
            margin-top: 1.5em;
            margin-bottom: 0.5em;
            border-bottom: 1px solid var(--color-border);
            padding-bottom: 0.3em;
        }

        h3 {
            font-size: 1.25em;
            margin-top: 1.2em;
            margin-bottom: 0.5em;
        }

        a {
            color: var(--color-primary);
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        code {
            background: var(--color-bg);
            padding: 0.2em 0.4em;
            border-radius: 3px;
            font-family: var(--font-mono);
            font-size: 0.9em;
        }

        pre {
            background: var(--color-bg);
            padding: 16px;
            border-radius: 6px;
            overflow: auto;
            border: 1px solid var(--color-border);
        }

        pre code {
            background: none;
            padding: 0;
        }

        ul, ol {
            padding-left: 2em;
        }

        li {
            margin: 0.25em 0;
        }

        .badge {
            display: inline-block;
            padding: 4px 8px;
            margin: 2px;
            background: var(--color-bg);
            border: 1px solid var(--color-border);
            border-radius: 4px;
            font-size: 0.85em;
            font-family: var(--font-mono);
        }

        .highlight {
            color: var(--color-success);
        }

        img {
            max-width: 100%;
            height: auto;
        }

        blockquote {
            margin: 1em 0;
            padding-left: 1em;
            border-left: 3px solid var(--color-border);
            color: var(--color-text-muted);
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin: 1em 0;
        }

        th, td {
            padding: 8px 12px;
            border: 1px solid var(--color-border);
            text-align: left;
        }

        th {
            background: var(--color-bg);
            font-weight: 600;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>🌐 Personal Portfolio Website</h1>

        <p>A modern, responsive portfolio website showcasing my skills, projects, and experience as a Java Full-Stack Developer. Built with Bootstrap 5 and custom CSS featuring glassmorphism design elements.</p>

        <p>
            <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white" alt="HTML5">
            <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white" alt="CSS3">
            <img src="https://img.shields.io/badge/Bootstrap_5-7952B3?style=flat&logo=bootstrap&logoColor=white" alt="Bootstrap">
            <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" alt="JavaScript">
        </p>

        <h2>✨ Features</h2>

        <ul>
            <li><strong>Responsive Design</strong> - Fully optimized for desktop, tablet, and mobile devices</li>
            <li><strong>Glassmorphism UI</strong> - Modern design with frosted glass effects and smooth animations</li>
            <li><strong>Smooth Navigation</strong> - Single-page application with smooth scrolling to sections</li>
            <li><strong>Project Showcase</strong> - Dedicated section highlighting key projects with hover effects</li>
            <li><strong>Skills Display</strong> - Interactive skill badges with hover animations</li>
            <li><strong>Contact Form</strong> - Integrated contact form for easy communication</li>
            <li><strong>Clean Code</strong> - Well-structured HTML with semantic elements and organized CSS</li>
        </ul>

        <h2>🚀 Demo</h2>

        <p><strong>Live Demo:</strong> <a href="https://yourusername.github.io/portfolio">https://yourusername.github.io/portfolio</a></p>

        <h2>📸 Screenshots</h2>

        <blockquote>
            <p><em>Add screenshots of your portfolio here after deployment</em></p>
        </blockquote>

        <pre><code>![Hero Section](./screenshots/hero.png)
![Projects Section](./screenshots/projects.png)
![Contact Section](./screenshots/contact.png)</code></pre>

        <h2>🛠️ Built With</h2>

        <table>
            <thead>
                <tr>
                    <th>Technology</th>
                    <th>Purpose</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td><strong>HTML5</strong></td>
                    <td>Semantic markup and structure</td>
                </tr>
                <tr>
                    <td><strong>CSS3</strong></td>
                    <td>Custom styling, animations, and glassmorphism effects</td>
                </tr>
                <tr>
                    <td><strong>Bootstrap 5</strong></td>
                    <td>Responsive grid system and components</td>
                </tr>
                <tr>
                    <td><strong>JavaScript</strong></td>
                    <td>Interactive navigation and smooth scrolling</td>
                </tr>
                <tr>
                    <td><strong>Google Fonts</strong></td>
                    <td>Poppins font family for modern typography</td>
                </tr>
            </tbody>
        </table>

        <h2>📂 Project Structure</h2>

        <pre><code>portfolio/
│
├── index.html              # Main HTML file
├── RelativePathImages/     # Image assets directory
│   └── photo.jpg          # Profile photo
├── screenshots/            # Screenshots for README
│   ├── hero.png
│   ├── projects.png
│   └── contact.png
└── README.md              # Project documentation</code></pre>

        <h2>🎨 Design Features</h2>

        <h3>Color Scheme</h3>
        <ul>
            <li><strong>Background:</strong> Light neutral tones (#f9fafc)</li>
            <li><strong>Accent:</strong> Soft blue (#eaf3ff)</li>
            <li><strong>Primary:</strong> Bootstrap blue (#007bff)</li>
            <li><strong>Glass Effect:</strong> Frosted white with backdrop blur</li>
        </ul>

        <h3>Key Design Elements</h3>
        <ul>
            <li><strong>Glassmorphism:</strong> Backdrop blur effects on cards and navbar</li>
            <li><strong>Smooth Transitions:</strong> Hover animations on all interactive elements</li>
            <li><strong>Modern Typography:</strong> Poppins font with proper hierarchy</li>
            <li><strong>Shadow Depth:</strong> Layered shadows for depth perception</li>
        </ul>

        <h2>🚀 Getting Started</h2>

        <h3>Prerequisites</h3>
        <ul>
            <li>A modern web browser (Chrome, Firefox, Safari, Edge)</li>
            <li>Text editor (VS Code, Sublime Text, etc.) for customization</li>
        </ul>

        <h3>Installation</h3>

        <p><strong>1. Clone the repository</strong></p>
        <pre><code>git clone https://github.com/yourusername/portfolio.git
cd portfolio</code></pre>

        <p><strong>2. Add your profile photo</strong></p>
        <pre><code>mkdir -p RelativePathImages
# Add your photo.jpg to the RelativePathImages folder</code></pre>

        <p><strong>3. Open in browser</strong></p>
        <pre><code># Simply open index.html in your browser
# Or use a local server:
python -m http.server 8000
# Visit http://localhost:8000</code></pre>

        <h2>⚙️ Customization Guide</h2>

        <h3>1. Personal Information</h3>
        <p>Edit the following sections in <code>index.html</code>:</p>

        <pre><code>&lt;!-- Update name --&gt;
&lt;h1 class="display-6 fw-semibold"&gt;Your Name&lt;/h1&gt;

&lt;!-- Update tagline --&gt;
&lt;p class="lead text-muted"&gt;Your Role | Your Skills&lt;/p&gt;

&lt;!-- Update contact details --&gt;
&lt;a href="tel:+91XXXXXXXXXX"&gt;+91 XXXXX XXXXX&lt;/a&gt;
&lt;a href="mailto:your.email@gmail.com"&gt;your.email@gmail.com&lt;/a&gt;</code></pre>

        <h3>2. Skills Section</h3>
        <p>Add or remove skill badges:</p>

        <pre><code>&lt;span class="badge bg-light text-dark skill-badge"&gt;Your Skill&lt;/span&gt;</code></pre>

        <h3>3. Projects Section</h3>
        <p>Duplicate the card structure for additional projects:</p>

        <pre><code>&lt;div class="col-md-6"&gt;
  &lt;div class="card card-project h-100"&gt;
    &lt;div class="card-body"&gt;
      &lt;h5 class="card-title"&gt;Project Name&lt;/h5&gt;
      &lt;p class="card-text"&gt;Description...&lt;/p&gt;
      &lt;p class="mb-0"&gt;&lt;strong&gt;Tech:&lt;/strong&gt; Technologies&lt;/p&gt;
    &lt;/div&gt;
  &lt;/div&gt;
&lt;/div&gt;</code></pre>

        <h3>4. Color Customization</h3>
        <p>Modify CSS variables in the <code>&lt;style&gt;</code> section:</p>

        <pre><code>:root {
  --bg-light: #f9fafc;      /* Main background */
  --bg-accent: #eaf3ff;     /* Accent background */
  --text-main: #1a1a1a;     /* Primary text */
  --primary: #007bff;       /* Primary color */
  --shadow: 0 10px 30px rgba(0, 0, 0, 0.08);
  --radius: 18px;           /* Border radius */
}</code></pre>

        <h2>📱 Responsive Breakpoints</h2>

        <table>
            <thead>
                <tr>
                    <th>Device</th>
                    <th>Breakpoint</th>
                    <th>Behavior</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Mobile</td>
                    <td>&lt; 768px</td>
                    <td>Stacked layout, smaller profile image</td>
                </tr>
                <tr>
                    <td>Tablet</td>
                    <td>768px - 991px</td>
                    <td>Two-column layout for projects</td>
                </tr>
                <tr>
                    <td>Desktop</td>
                    <td>&gt; 992px</td>
                    <td>Full multi-column layout with animations</td>
                </tr>
            </tbody>
        </table>

        <h2>🌐 Deployment</h2>

        <h3>GitHub Pages (Recommended)</h3>

        <p><strong>1. Push your code to GitHub</strong></p>
        <pre><code>git add .
git commit -m "Initial portfolio commit"
git push origin main</code></pre>

        <p><strong>2. Enable GitHub Pages</strong></p>
        <ul>
            <li>Go to your repository settings</li>
            <li>Navigate to "Pages" section</li>
            <li>Select "main" branch as source</li>
            <li>Click "Save"</li>
        </ul>

        <p><strong>3. Access your site</strong></p>
        <pre><code>https://yourusername.github.io/portfolio</code></pre>

        <h3>Alternative Deployment Options</h3>

        <ul>
            <li><strong>Netlify:</strong> Drag and drop the folder to <a href="https://app.netlify.com/drop">Netlify Drop</a></li>
            <li><strong>Vercel:</strong> Import repository via <a href="https://vercel.com/">Vercel dashboard</a></li>
            <li><strong>Firebase Hosting:</strong> Use Firebase CLI to deploy</li>
        </ul>

        <h2>📝 To-Do / Future Enhancements</h2>

        <ul>
            <li>[ ] Add dark mode toggle</li>
            <li>[ ] Integrate blog section</li>
            <li>[ ] Add project detail pages</li>
            <li>[ ] Implement working contact form backend</li>
            <li>[ ] Add GitHub contribution graph</li>
            <li>[ ] Include testimonials section</li>
            <li>[ ] Add animations on scroll (AOS library)</li>
            <li>[ ] SEO optimization with meta tags</li>
            <li>[ ] Add resume download button</li>
        </ul>

        <h2>🐛 Known Issues</h2>

        <ul>
            <li>Contact form uses <code>mailto:</code> which may not work on all email clients - consider integrating FormSubmit, Formspree, or a backend solution</li>
            <li>Profile image path is relative - ensure proper folder structure</li>
        </ul>

        <h2>🤝 Contributing</h2>

        <p>Contributions, issues, and feature requests are welcome! Feel free to check the <a href="https://github.com/yourusername/portfolio/issues">issues page</a>.</p>

        <p><strong>To contribute:</strong></p>
        <ol>
            <li>Fork the project</li>
            <li>Create your feature branch (<code>git checkout -b feature/AmazingFeature</code>)</li>
            <li>Commit your changes (<code>git commit -m 'Add some AmazingFeature'</code>)</li>
            <li>Push to the branch (<code>git push origin feature/AmazingFeature</code>)</li>
            <li>Open a Pull Request</li>
        </ol>

        <h2>📄 License</h2>

        <p>This project is licensed under the MIT License - see the <a href="LICENSE">LICENSE</a> file for details.</p>

        <h2>👤 Author</h2>

        <p><strong>Venkatesh Jaggaraju</strong></p>

        <ul>
            <li>Email: <a href="mailto:venkateshjaggaraju2002@gmail.com">venkateshjaggaraju2002@gmail.com</a></li>
            <li>Phone: <a href="tel:+919618348231">+91 96183 48231</a></li>
            <li>GitHub: <a href="https://github.com/yourusername">@yourusername</a></li>
            <li>LinkedIn: <a href="https://linkedin.com/in/yourprofile">Your Profile</a></li>
        </ul>

        <h2>⭐ Show Your Support</h2>

        <p>Give a ⭐️ if you like this project and find it helpful!</p>

        <hr>

        <p style="text-align: center; color: var(--color-text-muted); margin-top: 2em;">
            Made with ❤️ by Venkatesh Jaggaraju
        </p>
    </div>
</body>
</html>
