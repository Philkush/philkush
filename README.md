<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Philip Kuria Mbugua - IT Solutions Architect & Technical Leader</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        header {
            background: linear-gradient(135deg, #1e3c72 0%, #2a5298 100%);
            color: white;
            padding: 80px 0 60px;
            text-align: center;
        }
        
        header h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
        }
        
        header p {
            font-size: 1.2em;
            margin-bottom: 20px;
            opacity: 0.9;
        }
        
        .contact-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
            margin-top: 20px;
        }
        
        .contact-links a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
            background: rgba(255, 255, 255, 0.2);
            border-radius: 5px;
            transition: background 0.3s;
        }
        
        .contact-links a:hover {
            background: rgba(255, 255, 255, 0.3);
        }
        
        nav {
            background: #fff;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            position: sticky;
            top: 0;
            z-index: 100;
        }
        
        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
            padding: 15px 0;
            flex-wrap: wrap;
        }
        
        nav ul li {
            margin: 0 15px;
        }
        
        nav ul li a {
            color: #1e3c72;
            text-decoration: none;
            font-weight: 600;
            transition: color 0.3s;
        }
        
        nav ul li a:hover {
            color: #2a5298;
        }
        
        section {
            padding: 60px 0;
        }
        
        section:nth-child(even) {
            background: #f8f9fa;
        }
        
        h2 {
            color: #1e3c72;
            font-size: 2em;
            margin-bottom: 30px;
            text-align: center;
        }
        
        .about-content {
            max-width: 800px;
            margin: 0 auto;
            text-align: center;
            font-size: 1.1em;
        }
        
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }
        
        .skill-category {
            background: white;
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
        }
        
        .skill-category h3 {
            color: #2a5298;
            margin-bottom: 15px;
            font-size: 1.3em;
        }
        
        .skill-category ul {
            list-style: none;
        }
        
        .skill-category ul li {
            padding: 8px 0;
            border-bottom: 1px solid #eee;
        }
        
        .skill-category ul li:last-child {
            border-bottom: none;
        }
        
        .experience-timeline {
            max-width: 900px;
            margin: 0 auto;
        }
        
        .job {
            background: white;
            padding: 30px;
            margin-bottom: 30px;
            border-left: 4px solid #2a5298;
            border-radius: 5px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
        }
        
        .job h3 {
            color: #1e3c72;
            font-size: 1.4em;
            margin-bottom: 5px;
        }
        
        .job .company {
            color: #2a5298;
            font-weight: 600;
            margin-bottom: 5px;
        }
        
        .job .duration {
            color: #666;
            font-style: italic;
            margin-bottom: 15px;
        }
        
        .job ul {
            margin-left: 20px;
        }
        
        .job ul li {
            margin-bottom: 8px;
        }
        
        .achievements-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
            margin-top: 40px;
        }
        
        .achievement-card {
            background: white;
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
            text-align: center;
        }
        
        .achievement-number {
            font-size: 2.5em;
            color: #2a5298;
            font-weight: bold;
            display: block;
            margin-bottom: 10px;
        }
        
        .certifications-list {
            max-width: 800px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        
        .cert-item {
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
        }
        
        .cert-item h4 {
            color: #2a5298;
            margin-bottom: 10px;
        }
        
        .contact-section {
            text-align: center;
        }
        
        .contact-info {
            display: flex;
            justify-content: center;
            gap: 40px;
            flex-wrap: wrap;
            margin-top: 30px;
        }
        
        .contact-item {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        
        .contact-item strong {
            color: #1e3c72;
            margin-bottom: 5px;
        }
        
        footer {
            background: #1e3c72;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
        
        @media (max-width: 768px) {
            header h1 {
                font-size: 2em;
            }
            
            nav ul {
                flex-direction: column;
                align-items: center;
            }
            
            nav ul li {
                margin: 5px 0;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Philip Kuria Mbugua</h1>
            <p>Strategic IT Solutions Architect & Technical Operations Leader</p>
            <p>11+ Years Experience | Cloud Solutions | Enterprise Systems</p>
            <div class="contact-links">
                <a href="mailto:philkuria@gmail.com">📧 Email</a>
                <a href="tel:+254723423427">📞 +254 723 423 427</a>
                <a href="#" target="_blank">🔗 LinkedIn</a>
            </div>
        </div>
    </header>
    
    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#experience">Experience</a></li>
            <li><a href="#achievements">Achievements</a></li>
            <li><a href="#certifications">Certifications</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    
    <section id="about">
        <div class="container">
            <h2>About Me</h2>
            <div class="about-content">
                <p>Strategic technology leader with over 11 years of experience in IT infrastructure, cloud technologies, and enterprise systems. Proven expertise in engaging clients to understand technical requirements, designing tailored IT solutions, and delivering compelling technical presentations that drive business growth.</p>
                <p style="margin-top: 20px;">Successfully collaborated with cross-functional teams to win 10+ mission-critical projects for high-profile clients including Statehouse, ICTA, Nairobi County, and KPLC, demonstrating strong ability to bridge technical solutions with customer business needs and translate complex technical concepts into clear business value propositions.</p>
            </div>
        </div>
    </section>
    
    <section id="skills">
        <div class="container">
            <h2>Core Competencies</h2>
            <div class="skills-grid">
                <div class="skill-category">
                    <h3>🔧 Technical Expertise</h3>
                    <ul>
                        <li>Cloud Solutions (AWS)</li>
                        <li>IT Infrastructure Design</li>
                        <li>Solution Architecture</li>
                        <li>EDRMS & Legal Systems</li>
                        <li>Network & Security</li>
                        <li>Backup & Disaster Recovery</li>
                    </ul>
                </div>
                
                <div class="skill-category">
                    <h3>💼 Pre-Sales & Client Engagement</h3>
                    <ul>
                        <li>Client Consultation</li>
                        <li>Technical Presentations</li>
                        <li>Proof of Concept Development</li>
                        <li>Market Intelligence</li>
                        <li>Solution Design</li>
                        <li>Stakeholder Management</li>
                    </ul>
                </div>
                
                <div class="skill-category">
                    <h3>📊 Data & Analytics</h3>
                    <ul>
                        <li>Python for Data Science</li>
                        <li>Power BI</li>
                        <li>AI-driven Analytics</li>
                        <li>Data-Driven Decision Making</li>
                        <li>Business Intelligence</li>
                    </ul>
                </div>
                
                <div class="skill-category">
                    <h3>🎯 Leadership & Management</h3>
                    <ul>
                        <li>Cross-functional Collaboration</li>
                        <li>Team Leadership</li>
                        <li>Vendor Management</li>
                        <li>Strategic Planning</li>
                        <li>Project Management</li>
                        <li>Resource Optimization</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>
    
    <section id="experience">
        <div class="container">
            <h2>Professional Experience</h2>
            <div class="experience-timeline">
                <div class="job">
                    <h3>Technical Operations Manager</h3>
                    <div class="company">Coseke Ltd</div>
                    <div class="duration">August 2020 – Present</div>
                    <ul>
                        <li>Collaborated with high-profile clients (Statehouse, ICTA, Nairobi County, KPLC) to deliver mission-critical IT solutions</li>
                        <li>Presented enterprise-wide workflow automation solutions demonstrating 40% reduction in manual work</li>
                        <li>Designed and implemented EDRMS and Legal Management Systems, expediting project completion by 25%</li>
                        <li>Led hardware procurement and infrastructure upgrade initiatives with cross-functional teams</li>
                    </ul>
                </div>
                
                <div class="job">
                    <h3>Head of Infrastructure & Technology</h3>
                    <div class="company">Annick Solutions Limited</div>
                    <div class="duration">January 2017 – July 2020</div>
                    <ul>
                        <li>Introduced AI-driven analytics solutions with 50% improvement in data retrieval efficiency</li>
                        <li>Developed scalable IT governance frameworks enabling seamless technology expansion</li>
                        <li>Conducted security risk assessments achieving 80% reduction in network vulnerabilities</li>
                        <li>Strengthened strategic partnerships with technology vendors, improving SLA adherence</li>
                    </ul>
                </div>
                
                <div class="job">
                    <h3>ICT Specialist</h3>
                    <div class="company">WPP-Scan Group Ltd</div>
                    <div class="duration">August 2013 – December 2016</div>
                    <ul>
                        <li>Crafted innovative IT solutions for 25+ clients achieving 40% productivity improvements</li>
                        <li>Successfully implemented enterprise-grade backup solutions with 100% success rate during 5 critical system failures</li>
                        <li>Reduced helpdesk service requests by 50% through self-service portal implementations</li>
                        <li>Created comprehensive 3-year technology roadmaps for multiple clients</li>
                    </ul>
                </div>
                
                <div class="job">
                    <h3>Information Technology Specialist</h3>
                    <div class="company">Gertrude's Children's Hospital</div>
                    <div class="duration">November 2010 – July 2013</div>
                    <ul>
                        <li>Provided comprehensive IT support to 500+ staff members maintaining 99.9% system uptime</li>
                        <li>Established data retention policies compliant with healthcare regulations</li>
                        <li>Implemented interoperable systems reducing long-term costs and complexity</li>
                        <li>Achieved 90% reduction in inappropriate access incidents through user training</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>
    
    <section id="achievements">
        <div class="container">
            <h2>Key Achievements</h2>
            <div class="achievements-grid">
                <div class="achievement-card">
                    <span class="achievement-number">10+</span>
                    <p>Mission-critical projects delivered ahead of schedule</p>
                </div>
                <div class="achievement-card">
                    <span class="achievement-number">99.9%</span>
                    <p>System uptime across healthcare and government sectors</p>
                </div>
                <div class="achievement-card">
                    <span class="achievement-number">40%</span>
                    <p>Productivity improvements through modern workplace transformation</p>
                </div>
                <div class="achievement-card">
                    <span class="achievement-number">25%</span>
                    <p>Cost reduction through digital transformation initiatives</p>
                </div>
                <div class="achievement-card">
                    <span class="achievement-number">80%</span>
                    <p>Reduction in network vulnerabilities through security assessments</p>
                </div>
                <div class="achievement-card">
                    <span class="achievement-number">300+</span>
                    <p>Stakeholders trained on technical solutions</p>
                </div>
            </div>
        </div>
    </section>
    
    <section id="certifications">
        <div class="container">
            <h2>Certifications & Education</h2>
            <div class="certifications-list">
                <div class="cert-item">
                    <h4>AWS Certifications (Ongoing)</h4>
                    <p>Solutions Architect, Developer, SysOps Administrator, Cloud Practitioner</p>
                </div>
                <div class="cert-item">
                    <h4>CISA</h4>
                    <p>Certified Information Systems Auditor</p>
                </div>
                <div class="cert-item">
                    <h4>MCSE</h4>
                    <p>Microsoft Certified Solutions Expert - Server Infrastructure</p>
                </div>
                <div class="cert-item">
                    <h4>ITIL v3</h4>
                    <p>Certified in IT Service Management</p>
                </div>
                <div class="cert-item">
                    <h4>Python for Data Science</h4>
                    <p>Professional Certification</p>
                </div>
                <div class="cert-item">
                    <h4>Power BI</h4>
                    <p>Career Boost with Power BI</p>
                </div>
            </div>
            
            <div style="margin-top: 50px; text-align: center;">
                <h3 style="color: #2a5298; margin-bottom: 20px;">Education</h3>
                <div class="cert-item" style="max-width: 600px; margin: 0 auto;">
                    <h4>Bachelor of Science in Information Technology (Hons)</h4>
                    <p>Jomo Kenyatta University of Agriculture and Technology (JKUAT)</p>
                    <p>2011 - 2013</p>
                </div>
            </div>
        </div>
    </section>
    
    <section id="contact" class="contact-section">
        <div class="container">
            <h2>Get In Touch</h2>
            <p style="font-size: 1.1em; margin-bottom: 30px;">Interested in discussing IT solutions or potential collaboration? Feel free to reach out!</p>
            <div class="contact-info">
                <div class="contact-item">
                    <strong>Email</strong>
                    <a href="mailto:philkuria@gmail.com" style="color: #2a5298; text-decoration: none;">philkuria@gmail.com</a>
                </div>
                <div class="contact-item">
                    <strong>Phone</strong>
                    <a href="tel:+254723423427" style="color: #2a5298; text-decoration: none;">+254 723 423 427</a>
                </div>
                <div class="contact-item">
                    <strong>Location</strong>
                    <span>Nairobi, Kenya</span>
                </div>
            </div>
        </div>
    </section>
    
    <footer>
        <div class="container">
            <p>&copy; 2025 Philip Kuria Mbugua. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
