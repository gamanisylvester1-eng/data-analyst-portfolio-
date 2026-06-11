<body>
    <!-- Navigation -->
    <nav>
        <div class="logo">DataAnalyst</div>
        <ul class="nav-links">
            <li><a href="#home">Home</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
        <button class="theme-toggle" onclick="toggleTheme()">
            <i class="fas fa-moon"></i>
        </button>
    </nav>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="hero-content">
            <h1>Hi, I'm <span>Isa Sylvester Gamani</span></h1>
            <p>Data Analyst | Turning Raw Data into Actionable Insights</p>
            <div class="cta-buttons">
                <a href="#projects" class="btn btn-primary">
                    <i class="fas fa-chart-line"></i> View My Work
                </a>
                <a href="#contact" class="btn btn-secondary">
                    <i class="fas fa-envelope"></i> Get In Touch
                </a>
            </div>
        </div>
    </section>

    <!-- Stats Bar -->
    <div class="stats-bar">
        <div class="stat-item">
            <h3>50+</h3>
            <p>Projects Completed</p>
        </div>
        <div class="stat-item">
            <h3>5+</h3>
            <p>Years Experience</p>
        </div>
        <div class="stat-item">
            <h3>99%</h3>
            <p>Client Satisfaction</p>
        </div>
        <div class="stat-item">
            <h3>10M+</h3>
            <p>Rows Analyzed</p>
        </div>
    </div>

    <!-- Projects Section -->
    <section id="projects">
        <h2 class="section-title fade-in">Featured Projects</h2>
        <div class="projects-grid">
            <!-- Project 1: Sales Dashboard -->
            <div class="project-card fade-in">
                <div class="project-header">
                    <h3><i class="fas fa-chart-bar"></i> Sales Performance Dashboard</h3>
                    <span class="project-tag">Data Visualization</span>
                </div>
                <div class="project-body">
                    <p>Interactive dashboard analyzing sales trends, regional performance, and product metrics using real-time data processing.</p>
                    <div class="chart-container">
                        <canvas id="salesChart"></canvas>
                    </div>
                    <div class="project-metrics">
                        <div class="metric">
                            <div class="metric-value">$2.4M</div>
                            <div class="metric-label">Revenue</div>
                        </div>
                        <div class="metric">
                            <div class="metric-value">+23%</div>
                            <div class="metric-label">Growth</div>
                        </div>
                        <div class="metric">
                            <div class="metric-value">1.2K</div>
                            <div class="metric-label">Orders</div>
                        </div>
                    </div>
                    <div class="project-links">
                        <a href="#" class="view-project">View Project</a>
                        <a href="#" class="view-code">View Code</a>
                    </div>
                </div>
            </div>

            <!-- Project 2: Customer Segmentation -->
            <div class="project-card fade-in">
                <div class="project-header">
                    <h3><i class="fas fa-users"></i> Customer Segmentation</h3>
                    <span class="project-tag">Machine Learning</span>
                </div>
                <div class="project-body">
                    <p>K-Means clustering analysis to segment customers based on purchasing behavior, demographics, and engagement metrics.</p>
                    <div class="chart-container">
                        <canvas id="clusterChart"></canvas>
                    </div>
                    <div class="project-metrics">
                        <div class="metric">
                            <div class="metric-value">5</div>
                            <div class="metric-label">Segments</div>
                        </div>
                        <div class="metric">
                            <div class="metric-value">0.82</div>
                            <div class="metric-label">Silhouette</div>
                        </div>
                        <div class="metric">
                            <div class="metric-value">50K</div>
                            <div class="metric-label">Customers</div>
                        </div>
                    </div>
                    <div class="project-links">
                        <a href="#" class="view-project">View Project</a>
                        <a href="#" class="view-code">View Code</a>
                    </div>
                </div>
            </div>

            <!-- Project 3: Sentiment Analysis -->
            <div class="project-card fade-in">
                <div class="project-header">
                    <h3><i class="fas fa-comments"></i> Sentiment Analysis</h3>
                    <span class="project-tag">NLP</span>
                </div>
                <div class="project-body">
                    <p>Natural Language Processing project analyzing customer reviews and social media sentiment for brand reputation management.</p>
                    <div class="chart-container">
                        <canvas id="sentimentChart"></canvas>
                    </div>
                    <div class="project-metrics">
                        <div class="metric">
                            <div class="metric-value">85%</div>
                            <div class="metric-label">Accuracy</div>
                        </div>
                        <div class="metric">
                            <div class="metric-value">100K</div>
                            <div class="metric-label">Reviews</div>
                        </div>
                        <div class="metric">
                            <div class="metric-value">3.2s</div>
                            <div class="metric-label">Response</div>
                        </div>
                    </div>
                    <div class="project-links">
                        <a href="#" class="view-project">View Project</a>
                        <a href="#" class="view-code">View Code</a>
                    </div>
                </div>
            </div>

            <!-- Project 4: Predictive Analytics -->
            <div class="project-card fade-in">
                <div class="project-header">
                    <h3><i class="fas fa-chart-line"></i> Predictive Analytics</h3>
                    <span class="project-tag">Time Series</span>
                </div>
                <div class="project-body">
                    <p>ARIMA and LSTM models for forecasting sales trends, inventory demand, and market predictions with 95% accuracy.</p>
                    <div class="chart-container">
                        <canvas id="forecastChart"></canvas>
                    </div>
                    <div class="project-metrics">
                        <div class="metric">
                            <div class="metric-value">95%</div>
                            <div class="metric-label">Accuracy</div>
                        </div>
                        <div class="metric">
                            <div class="metric-value">30d</div>
                            <div class="metric-label">Forecast</div>
                        </div>
                        <div class="metric">
                            <div class="metric-value">2.1%</div>
                            <div class="metric-label">MAPE</div>
                        </div>
                    </div>
                    <div class="project-links">
                        <a href="#" class="view-project">View Project</a>
                        <a href="#" class="view-code">View Code</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <h2 class="section-title fade-in">Technical Skills</h2>
        <div class="skills-container">
            <div class="skills-grid">
                <div class="skill-category fade-in">
                    <h3><i class="fas fa-code"></i> Programming</h3>
                    <div class="skill-item"><span>Python</span><span>95%</span></div>
                    <div class="skill-bar"><div class="skill-progress" style="width: 95%"></div></div>
                    <div class="skill-item"><span>R</span><span>85%</span></div>
                    <div class="skill-bar"><div class="skill-progress" style="width: 85%"></div></div>
                    <div class="skill-item"><span>SQL</span><span>90%</span></div>
                    <div class="skill-bar"><div class="skill-progress" style="width: 90%"></div></div>
                    <div class="skill-item"><span>JavaScript</span><span>75%</span></div>
                    <div class="skill-bar"><div class="skill-progress" style="width: 75%"></div></div>
                </div>

                <div class="skill-category fade-in">
                    <h3><i class="fas fa-database"></i> Data Tools</h3>
                    <div class="skill-item"><span>Pandas/NumPy</span><span>95%</span></div>
                    <div class="skill-bar"><div class="skill-progress" style="width: 95%"></div></div>
                    <div class="skill-item"><span>Tableau</span><span>90%</span></div>
                    <div class="skill-bar"><div class="skill-progress" style="width: 90%"></div></div>
                    <div class="skill-item"><span>Power BI</span><span>85%</span></div>
                    <div class="skill-bar"><div class="skill-progress" style="width: 85%"></div></div>
                    <div class="skill-item"><span>Excel/Google Sheets</span><span>95%</span></div>
                    <div class="skill-bar"><div class="skill-progress" style="width: 95%"></div></div>
                </div>

                <div class="skill-category fade-in">
                    <h3><i class="fas fa-brain"></i> Machine Learning</h3>
                    <div class="skill-item"><span>Scikit-learn</span><span>90%</span></div>
                    <div class="skill-bar"><div class="skill-progress" style="width: 90%"></div></div>
                    <div class="skill-item"><span>TensorFlow/Keras</span><span>80%</span></div>
                    <div class="skill-bar"><div class="skill-progress" style="width: 80%"></div></div>
                    <div class="skill-item"><span>PyTorch</span><span>75%</span></div>
                    <div class="skill-bar"><div class="skill-progress" style="width: 75%"></div></div>
                    <div class="skill-item"><span>NLP (spaCy/NLTK)</span><span>85%</span></div>
                    <div class="skill-bar"><div class="skill-progress" style="width: 85%"></div></div>
                </div>

                <div class="skill-category fade-in">
                    <h3><i class="fas fa-cloud"></i> Cloud & Big Data</h3>
                    <div class="skill-item"><span>AWS (S3, EC2, Redshift)</span><span>80%</span></div>
                    <div class="skill-bar"><div class="skill-progress" style="width: 80%"></div></div>
                    <div class="skill-item"><span>Google Cloud Platform</span><span>75%</span></div>
                    <div class="skill-bar"><div class="skill-progress" style="width: 75%"></div></div>
                    <div class="skill-item"><span>Apache Spark</span><span>70%</span></div>
                    <div class="skill-bar"><div class="skill-progress" style="width: 70%"></div></div>
                    <div class="skill-item"><span>Hadoop</span><span>65%</span></div>
                    <div class="skill-bar"><div class="skill-progress" style="width: 65%"></div></div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about">
        <h2 class="section-title fade-in">About Me</h2>
        <div class="about-container">
            <div class="about-image fade-in">
                <img src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?w=400&h=400&fit=crop&crop=face" alt="Profile">
            </div>
            <div class="about-content fade-in">
                <h3>Data Analyst & Business Intelligence Specialist</h3>
                <p>Passionate data analyst with expertise in transforming complex datasets into clear, actionable insights. I specialize in statistical analysis, predictive modeling, and creating compelling data visualizations that drive business decisions.</p>
                <p>My approach combines technical proficiency with business acumen to deliver solutions that not only answer questions but also uncover new opportunities for growth and optimization.</p>
                <ul class="experience-list">
                    <li><i class="fas fa-briefcase"></i><div><strong>Senior Data Analyst</strong><br><small>TechCorp Inc. | 2021 - Present</small></div></li>
                    <li><i class="fas fa-briefcase"></i><div><strong>Data Analyst</strong><br><small>DataDriven Solutions | 2019 - 2021</small></div></li>
                    <li><i class="fas fa-graduation-cap"></i><div><strong>MSc. Data Science</strong><br><small>University of Technology | 2017 - 2019</small></div></li>
                </ul>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2 class="section-title fade-in">Get In Touch</h2>
        <div class="contact-container">
            <p style="color: var(--text-muted); font-size: 1.1rem;">I'm currently open to new opportunities and collaborations. Let's discuss how I can help your organization leverage data for success.</p>
            <div class="contact-grid">
                <div class="contact-item fade-in"><i class="fas fa-envelope"></i><h3>Email</h3><a href="mailto:gamanisylvester1@gmail.com">gamanisylvester1@gmail.com</a></div>
                <div class="contact-item fade-in"><i class="fab fa-linkedin"></i><h3>LinkedIn</h3><a href="https://linkedin.com/in/yourprofile" target="_blank">linkedin.com/in/yourprofile</a></div>
                <div class="contact-item fade-in"><i class="fab fa-github"></i><h3>GitHub</h3><a href="https://github.com/yourusername" target="_blank">github.com/yourusername</a></div>
                <div class="contact-item fade-in"><i class="fab fa-twitter"></i><h3>Twitter</h3><a href="https://twitter.com/yourhandle" target="_blank">@yourhandle</a></div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Isa Sylvester Gamani. Built with passion for data.</p>
    </footer>

    <script>
        function toggleTheme() {
            document.body.classList.toggle('light-mode');
            const icon = document.querySelector('.theme-toggle i');
            if (document.body.classList.contains('light-mode')) {
                icon.classList.remove('fa-moon');
                icon.classList.add('fa-sun');
            } else {
                icon.classList.remove('fa-sun');
                icon.classList.add('fa-moon');
            }
        }
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({ behavior: 'smooth' });
            });
        });
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => { if (entry.isIntersecting) entry.target.classList.add('visible'); });
        }, { threshold: 0.1, rootMargin: "0px 0px -50px 0px" });
        document.querySelectorAll('.fade-in').forEach(el => observer.observe(el));
        Chart.defaults.color = '#94a3b8'; Chart.defaults.borderColor = '#334155';
        new Chart(document.getElementById('salesChart'), {
            type: 'line', data: { labels: ['Jan','Feb','Mar','Apr','May','Jun'], datasets: [{ label: 'Revenue ($K)', data: [320,380,420,390,450,480], borderColor: '#6366f1', backgroundColor: 'rgba(99,102,241,0.1)', fill: true, tension: 0.4 }, { label: 'Target ($K)', data: [300,350,400,400,420,450], borderColor: '#ec4899', borderDash: [5,5], tension: 0.4 }] }, options: { responsive: true, maintainAspectRatio: false, plugins: { legend: { position: 'bottom' } }, scales: { y: { beginAtZero: true } } }
        });
        new Chart(document.getElementById('clusterChart'), {
            type: 'scatter', data: { datasets: [{ label: 'Cluster 1 - Premium', data: [{x:80,y:90},{x:85,y:85},{x:75,y:95},{x:90,y:80}], backgroundColor: '#6366f1' }, { label: 'Cluster 2 - Standard', data: [{x:50,y:60},{x:55,y:55},{x:45,y:65},{x:60,y:50}], backgroundColor: '#ec4899' }, { label: 'Cluster 3 - Budget', data: [{x:20,y:30},{x:25,y:25},{x:15,y:35},{x:30,y:20}], backgroundColor: '#10b981' }] }, options: { responsive: true, maintainAspectRatio: false, plugins: { legend: { position: 'bottom' } }, scales: { x: { title: { display: true, text: 'Purchase Frequency' } }, y: { title: { display: true, text: 'Spending Score' } } } }
        });
        new Chart(document.getElementById('sentimentChart'), {
            type: 'doughnut', data: { labels: ['Positive','Neutral','Negative'], datasets: [{ data: [65,20,15], backgroundColor: ['#10b981','#6366f1','#ef4444'], borderWidth: 0 }] }, options: { responsive: true, maintainAspectRatio: false, plugins: { legend: { position: 'bottom' } } }
        });
        new Chart(document.getElementById('forecastChart'), {
            type: 'bar', data: { labels: ['Week 1','Week 2','Week 3','Week 4','Week 5','Week 6'], datasets: [{ label: 'Actual Sales', data: [450,520,480,590,610,580], backgroundColor: '#6366f1' }, { label: 'Predicted', data: [460,510,490,580,600,590], backgroundColor: '#ec4899' }] }, options: { responsive: true, maintainAspectRatio: false, plugins: { legend: { position: 'bottom' } }, scales: { y: { beginAtZero: true } } }
        });
    </script>
</body>
</html>
