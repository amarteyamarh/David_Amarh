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
        
        /* CV Upload Section Styles */
        .cv-upload {
            background: white;
            padding: 2rem;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            margin: 2rem 0;
            text-align: center;
        }
        
        .upload-btn {
            display: inline-block;
            background: var(--secondary);
            color: white;
            padding: 0.8rem 1.5rem;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 1rem;
            transition: all 0.3s ease;
        }
        
        .upload-btn:hover {
            background: var(--primary);
        }
        
        #file-name {
            margin-top: 1rem;
            font-size: 0.9rem;
            color: var(--dark);
        }
        
        #cv-upload-form {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        
        #cv-upload {
            display: none;
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
        <!-- Previous sections remain unchanged -->
        <!-- ... -->

        <section id="contact">
            <h2>Get In Touch</h2>
            <p>I'm available for network administration roles and IT consulting projects.</p>
            
            <div class="cv-upload">
                <h3>Download or Upload My CV</h3>
                <div class="contact-links">
                    <a href="path-to-your-cv.pdf" download="David_Amarh_CV.pdf">Download CV</a>
                </div>
                <p>or</p>
                <form id="cv-upload-form">
                    <label for="cv-upload" class="upload-btn">Upload Your CV</label>
                    <input type="file" id="cv-upload" name="cv" accept=".pdf,.doc,.docx">
                    <div id="file-name"></div>
                </form>
            </div>
            
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
        
        // CV Upload functionality
        document.getElementById('cv-upload').addEventListener('change', function(e) {
            const fileName = document.getElementById('file-name');
            if (this.files.length > 0) {
                fileName.textContent = 'Selected file: ' + this.files[0].name;
                
                // Here you would typically handle the file upload
                // This would require server-side code to process the upload
                // For demonstration, we'll just show the selected file name
                
                // Example of what you might do with the file:
                // const formData = new FormData();
                // formData.append('cv', this.files[0]);
                // fetch('/upload-cv', { method: 'POST', body: formData })
                //   .then(response => response.json())
                //   .then(data => console.log('Success:', data))
                //   .catch(error => console.error('Error:', error));
            } else {
                fileName.textContent = '';
            }
        });
    </script>
</body>
</html>
