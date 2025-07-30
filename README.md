<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>David Amarh - Network Administrator</title>
    <style>
        /* Modern, professional styling */
        :root {
            --primary: #2c3e50;
            --secondary: #3498db;
            --light: #ecf0f1;
            --dark: #2c3e50;
            --accent: #e74c3c;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }
        
        header {
            background: var(--primary);
            color: white;
            padding: 2rem 0;
        }
        
        .container {
            width: 85%;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        h1, h2, h3 {
            color: var(--dark);
        }
        
        h1 {
            margin-bottom: 0.5rem;
            font-size: 2.5rem;
        }
        
        .tagline {
            font-size: 1.2rem;
            font-weight: 300;
            margin-bottom: 1rem;
            color: var(--secondary);
        }
        
        section {
            padding: 2rem 0;
            border-bottom: 1px solid #eee;
        }
        
        .profile-container {
            display: flex;
            align-items: center;
            gap: 3rem;
            margin-bottom: 1rem;
        }
        
        .profile-img {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            object-fit: cover;
            object-position: center top;
            border: 5px solid white;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        
        .intro-text {
            flex: 1;
        }
        
        .experience-item, .project {
            margin-bottom: 2rem;
            background: white;
            padding: 1.5rem;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        
        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
        }
        
        .skill {
            background: var(--secondary);
            color: white;
            padding: 0.5rem 1rem;
            border-radius: 20px;
            font-size: 0.9rem;
        }
        
        .contact-links {
            display: flex;
            justify-content: center;
            gap: 1rem;
            margin-top: 1rem;
        }
        
        .contact-links a {
            color: white;
            background: var(--secondary);
            padding: 0.8rem 1.5rem;
            text-decoration: none;
            border-radius: 5px;
            transition: all 0.3s ease;
            display: flex;
            align-items: center;
        }
        
        .contact-links a:hover {
            background: var(--primary);
        }
        
        .phone-icon {
            margin-right: 8px;
        }
        
        footer {
            text-align: center;
            padding: 1.5rem;
            background: var(--dark);
            color: white;
        }
        
        /* CV Download Styles */
        .cv-download {
            margin-top: 2rem;
            background: #f5f5f5;
            padding: 1.5rem;
            border-radius: 5px;
            border-left: 4px solid var(--secondary);
        }
        
        .cv-download h4 {
            margin-top: 0;
            color: var(--dark);
        }
        
        .cv-download-btn {
            display: inline-block;
            background: var(--secondary);
            color: white;
            padding: 0.8rem 1.5rem;
            text-decoration: none;
            border-radius: 5px;
            transition: all 0.3s ease;
            margin-top: 1rem;
        }
        
        .cv-download-btn:hover {
            background: var(--primary);
        }
        
        .cv-file-info {
            font-size: 0.9rem;
            margin-top: 0.5rem;
            color: #666;
        }
        
        /* Video Section Styles */
        .video-section {
            background: white;
            padding: 1.5rem;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        
        .video-container {
            position: relative;
            padding-bottom: 56.25%; /* 16:9 aspect ratio */
            height: 0;
            overflow: hidden;
            margin: 1.5rem 0;
            border-radius: 5px;
        }
        
        .video-container iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            border: none;
        }
        
        .video-description {
            margin-top: 1rem;
            color: #555;
            line-height: 1.6;
        }
        
        @media (max-width: 768px) {
            .container {
                width: 95%;
            }
            .profile-container {
                flex-direction: column;
                text-align: center;
                gap: 1rem;
            }
            .contact-links {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div class="profile-container">
                <img src="https://raw.githubusercontent.com/amarteyamarh/David_Amarh/main/SOYK2803.JPG" alt="David Amarh" class="profile-img">
                <div class="intro-text">
                    <h1>David Amarh</h1>
                    <p class="tagline">Certified Cisco Network Administrator | 4+ Years of IT Infrastructure Experience</p>
                    <p>Hi, I'm David Amarh—a dedicated Network Administrator, experienced Freelancer, 
                    and a professional with a sharp eye for detail. I specialize in troubleshooting 
                    complex systems, optimizing network performance, and delivering precise, 
                    error-free solutions.</p>
                    <p>What sets me apart is my ability to anticipate technical issues before they arise, 
                    streamline operations for efficiency, and provide reliable freelance expertise 
                    tailored to my clients' needs. My goal is to save you time, reduce downtime, and 
                    enhance productivity by ensuring your network infrastructure runs smoothly and 
                    securely.</p>
                    <p>If you're looking for a proactive problem-solver who delivers results with precision, 
                    let's connect! I'd love to discuss how I can bring seamless tech solutions to your 
                    team or project. Let's make technology work for you—flawlessly.</p>
                </div>
            </div>
        </div>
    </header>

    <main class="container">
        <section id="about">
            <h2>About Me</h2>
            <ul>
                <li>Designing and maintaining secure network infrastructures</li>
                <li>Troubleshooting hardware/software issues</li>
                <li>Optimizing data workflows</li>
            </ul>
            <p>I thrive in roles that require precision, problem-solving, and seamless tech operations.</p>
        </section>

        <section id="experience">
            <h2>Professional Experience</h2>
            
            <div class="experience-item">
                <h3>Network Assistant - CUBS, Ghana</h3>
                <ul>
                    <li>Deployed and monitored LAN/WAN systems</li>
                    <li>Provided technical support to 50+ staff members</li>
                    <li>Maintained network security and performed regular updates</li>
                </ul>
            </div>
            
            <div class="experience-item">
                <h3>Data Entry Clerk - Ghana Statistical Service</h3>
                <ul>
                    <li>Managed databases with 99.8% accuracy</li>
                    <li>Streamlined data collection processes</li>
                    <li>Prepared statistical reports for government use</li>
                </ul>
            </div>
            
            <div class="experience-item">
                <h3>Virtual Assistant - Harmony Agency (Remote)</h3>
                <ul>
                    <li>Resolved client IT issues remotely</li>
                    <li>Automated administrative tasks using scripting tools</li>
                    <li>Managed schedules and communications for executives</li>
                </ul>
            </div>
        </section>

        <section id="certifications">
            <h2>Certifications & Skills</h2>
            <h3>Certifications:</h3>
            <ul>
                <li>Cisco Certified Network Associate (CCNA)</li>
            </ul>
            
            <h3>Technical Skills:</h3>
            <div class="skills">
                <span class="skill">Network Configuration</span>
                <span class="skill">Cisco IOS</span>
                <span class="skill">VPN Setup</span>
                <span class="skill">Firewall Management</span>
                <span class="skill">Hardware Troubleshooting</span>
                <span class="skill">Data Management</span>
                <span class="skill">Excel</span>
                <span class="skill">Remote Support</span>
                <span class="skill">TeamViewer</span>
                <span class="skill">Zoom Administration</span>
            </div>
        </section>

        <section id="projects">
            <h2>Projects</h2>

            <div class="project">
                <h3>Unified Poultry Access (UPA) Platform</h3>
                <p>A comprehensive platform designed to streamline poultry farming operations through technology:</p>
                <ul>
                    <li>Integrated farm management system with real-time monitoring</li>
                    <li>Automated feed and water supply tracking</li>
                    <li>Data analytics for poultry health and productivity</li>
                    <li>Mobile-friendly interface for remote access</li>
                </ul>
                <a href="https://drive.google.com/file/d/1IXEvVzcQoM8LoEDF0rRf6sNKPNKiUGtH/view?usp=sharing" class="project-link" target="_blank">View UPA Platform Documentation →</a>
            </div>
            
            <div class="project">
                <h3>Network Optimization Project</h3>
                <p>Reduced network downtime by 30% at CUBS through:</p>
                <ul>
                    <li>Implementing proactive monitoring systems</li>
                    <li>Redesigning network topology for better redundancy</li>
                    <li>Creating documentation for troubleshooting procedures</li>
                </ul>
            </div>
            
            <div class="project">
                <h3>Data Automation Script</h3>
                <p>Cut manual data entry time by 50% by:</p>
                <ul>
                    <li>Developing Python scripts to automate repetitive tasks</li>
                    <li>Creating Excel macros for data validation</li>
                    <li>Training team members on new processes</li>
                </ul>
                
                <div class="cv-download">
                    <h4>Download My CV</h4>
                    <p>Get a complete overview of my professional experience and qualifications:</p>
                    <a href="MY%20CV.pdf" download="MY CV.pdf" class="cv-download-btn">
                        Download CV (PDF)
                    </a>
                    <p class="cv-file-info">
                    </p>
                </div>
            </div>
        </section>

        <!-- New Pitch Video Section -->
        <section id="pitch-video" class="video-section">
            <h2>My Professional Pitch</h2>
            <div class="video-container">
                <!-- Replace VIDEO_ID with your actual YouTube video ID -->
                <iframe src="<iframe width="560" height="315" src="https://www.youtube.com/embed/C0StL3PVutk?si=HOHinX2MUOAhsPvI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>" 
                        frameborder="0" 
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
                        allowfullscreen></iframe>
            </div>
            <div class="video-description">
                <p>In this 2-minute video, I introduce myself and explain what makes me an exceptional Network Administrator. 
                You'll learn about my technical expertise, problem-solving approach, and how I can help optimize your 
                organization's network infrastructure for maximum performance and security.</p>
            </div>
        </section>

        <section id="contact">
            <h2>Get In Touch</h2>
            <p>I'm available for network administration roles and IT consulting projects.</p>
            <div class="contact-links">
                <a href="mailto:david@yourdomain.com">Email Me</a>
                <a href="https://www.linkedin.com/in/amarhdavid6081" target="_blank">LinkedIn</a>
                <a href="tel:+233556536988">
                    <svg class="phone-icon" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                        <path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"></path>
                    </svg>
                    Call Me
                </a>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; <span id="year"></span> David Amarh. All rights reserved.</p>
    </footer>

    <script>
        // Simple script to display current year
        document.getElementById('year').textContent = new Date().getFullYear();
    </script>
</body>
</html>
