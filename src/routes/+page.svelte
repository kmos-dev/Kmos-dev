<script lang="ts">
	// No imports needed for pure brutalist design
</script>

<svelte:head>
	<title>KMOS - SOFTWARE ENGINEERING COLLECTIVE</title>
	<meta name="description" content="KMOS collective of software engineers building innovative software solutions" />
</svelte:head>

<!-- BRUTALIST KMOS COMPANY PAGE -->
<div class="brutalist-container">
	<!-- HEADER SECTION -->
	<header class="hero-section">
		<div class="hero-content">
			<h1 class="hero-title">
				KMOS<br>
				<span class="hero-subtitle">SOFTWARE</span><br>
				COLLECTIVE
			</h1>
			<p class="hero-description">
				WE BUILD SHIT THAT WORKS.<br>
				SOFTWARE ENGINEERS. PROBLEM SOLVERS. CODE WARRIORS.
			</p>
			<div class="hero-cta">
				<a href="#portfolio" class="cta-primary">SEE OUR WORK</a>
				<a href="#contact" class="cta-secondary">HIRE US</a>
			</div>
		</div>
	</header>

	<!-- ABOUT SECTION -->
	<section class="about-section">
		<div class="section-header">
			<h2 class="section-title">ABOUT</h2>
			<p class="section-subtitle">WHO WE ARE</p>
		</div>
		
		<div class="about-content">
			<div class="about-text">
				<p class="about-description">
					KMOS IS A COLLECTIVE OF ELITE SOFTWARE ENGINEERS WHO GIVE ZERO FUCKS ABOUT YOUR BULLSHIT.<br><br>
					WE DON'T CODE FOR MONEY. WE CODE BECAUSE IT'S WHAT WE DO.<br><br>
					WEB APPS, MOBILE APIS, CLOUD INFRASTRUCTURE, AI SYSTEMS - IF IT CAN BE BUILT, WE'LL BUILD IT.<br><br>
					NO AGENCIES. NO CONSULTANTS. NO BULLSHIT. JUST ENGINEERS WHO GET SHIT DONE.
				</p>
			</div>
			<div class="about-stats">
				<div class="stat-item">
					<div class="stat-number">50+</div>
					<div class="stat-label">PROJECTS BUILT</div>
				</div>
				<div class="stat-item">
					<div class="stat-number">99%</div>
					<div class="stat-label">SUCCESS RATE</div>
				</div>
			</div>
		</div>
	</section>

	<!-- TEAM SECTION -->
	<section class="team-section">
		<div class="section-header">
			<h2 class="section-title">TEAM</h2>
			<p class="section-subtitle">THE ENGINEERS</p>
		</div>
		
		<div class="team-grid">
			<div class="team-card">
				<div class="team-role">LEAD ARCHITECT</div>
				<h3 class="team-name">DAYLIGHT</h3>
				<p class="team-description">FULL-STACK NINJA. SYSTEM DESIGN. CLOUD ARCHITECTURE.<br>MAKES COMPLEX SHIT LOOK SIMPLE.</p>
				<div class="team-skills">
					<span class="skill-tag">REACT</span>
					<span class="skill-tag">NODE.JS</span>
					<span class="skill-tag">AWS</span>
					<span class="skill-tag">KUBERNETES</span>
				</div>
			</div>

			<div class="team-card">
				<div class="team-role">BACKEND WARLORD</div>
				<h3 class="team-name">ERROR404FOUND404</h3>
				<p class="team-description">API QUEEN. DATABASE OPTIMIZER. SECURITY EXPERT.<br>BUILDS SHIT THAT SCALES TO INFINITY.</p>
				<div class="team-skills">
					<span class="skill-tag">PYTHON</span>
					<span class="skill-tag">POSTGRES</span>
					<span class="skill-tag">DOCKER</span>
					<span class="skill-tag">GRAPHQL</span>
				</div>
			</div>

			<div class="team-card">
				<div class="team-role">FRONTEND MASTER</div>
				<h3 class="team-name">WHITE-BEAR</h3>
				<p class="team-description">UI/UX DEMON. PERFORMANCE GURU. BROWSER MAGICIAN.<br>MAKES UIs SO FAST THEY BREAK THE SPEED LIMIT.</p>
				<div class="team-skills">
					<span class="skill-tag">TYPESCRIPT</span>
					<span class="skill-tag">REACT</span>
					<span class="skill-tag">WEBPACK</span>
					<span class="skill-tag">WEBRTC</span>
				</div>
			</div>

		</div>
	</section>

	<!-- FOCUS AREAS SECTION -->
	<section class="focus-section">
		<div class="section-header">
			<h2 class="section-title">EXPERTISE</h2>
			<p class="section-subtitle">WHAT WE BUILD</p>
		</div>
		
		<div class="focus-grid">
			<div class="focus-card">
				<div class="focus-number">01</div>
				<h3 class="focus-title">WEB APPLICATIONS</h3>
				<p class="focus-description">SCALABLE WEB APPS. MODERN FRAMEWORKS. LIGHTNING FAST PERFORMANCE.<br>FROM STARTUP MVPS TO ENTERPRISE PLATFORMS.</p>
			</div>

			<div class="focus-card">
				<div class="focus-number">02</div>
				<h3 class="focus-title">MOBILE APPS</h3>
				<p class="focus-description">NATIVE IOS. NATIVE ANDROID. CROSS-PLATFORM SOLUTIONS.<br>APPS THAT USERS ACTUALLY WANT TO USE.</p>
			</div>

			<div class="focus-card">
				<div class="focus-number">03</div>
				<h3 class="focus-title">API DEVELOPMENT</h3>
				<p class="focus-description">ROBUST APIS. GRAPHQL. MICROSERVICES. CLOUD-NATIVE ARCHITECTURE.<br>BUILDS THE BACKBONE OF MODERN SOFTWARE.</p>
			</div>


			<div class="focus-card">
				<div class="focus-number">04</div>
				<h3 class="focus-title">DATA ENGINEERING</h3>
				<p class="focus-description">BIG DATA. REAL-TIME ANALYTICS. DATA PIPELINES. BUSINESS INTELLIGENCE.<br>TURNING DATA INTO ACTIONABLE INSIGHTS.</p>
			</div>
		</div>
	</section>

	<!-- PORTFOLIO SECTION -->
	<section id="portfolio" class="portfolio-section">
		<div class="section-header">
			<h2 class="section-title">PORTFOLIO</h2>
			<p class="section-subtitle">SHIT WE'VE BUILT</p>
		</div>
		
		<div class="portfolio-grid">
			<div class="portfolio-card">
				<div class="portfolio-badge">EDUCATION PORTAL</div>
				<h3 class="portfolio-title">PORTAL SALE</h3>
				<p class="portfolio-description">MODERN EDUCATION PLATFORM WITH BRUTALIST DESIGN.<br>REAL-TIME LEARNING. PROGRESS TRACKING. COMMUNITY FEATURES.</p>
				<div class="portfolio-tech">
					<span class="tech-tag">SVELTEKIT</span>
					<span class="tech-tag">TYPESCRIPT</span>
					<span class="tech-tag">TAILWIND</span>
				</div>
				<a href="/portal" class="portfolio-link">VISIT PROJECT</a>
			</div>


			<div class="portfolio-card">
				<h3 class="portfolio-title">AUTOMATED BACKEND</h3>
				<p class="portfolio-description">CRUD API GENERATION. DATABASE AUTOMATION. RESTFUL ENDPOINTS.<br>BUILD BACKENDS FASTER. DEPLOY FASTER. SCALE FASTER.</p>
				<div class="portfolio-tech">
					<span class="tech-tag">NODE.JS</span>
					<span class="tech-tag">EXPRESS</span>
					<span class="tech-tag">POSTGRES</span>
				</div>
			</div>
		</div>
	</section>

	<!-- CONTACT SECTION -->
	<section id="contact" class="contact-section">
		<div class="section-header">
			<h2 class="section-title">CONTACT</h2>
			<p class="section-subtitle">HIRE US OR DIE</p>
		</div>
		
		<div class="contact-content">
			<div class="contact-info">
				<h3 class="contact-title">LET'S BUILD SOMETHING</h3>
				<p class="contact-description">
					HAVE A PROJECT? WE'VE GOT ENGINEERS.<br>
					HAVE A PROBLEM? WE'VE GOT SOLUTIONS.<br>
					HAVE A DEADLINE? WE'VE GOT SPEED.<br><br>
					DON'T EMAIL US. DON'T CALL US. JUST BRING YOUR IDEAS.
				</p>
				<div class="contact-details">
					<div class="contact-item">
						<span class="contact-label">EMAIL:</span>
						<span class="contact-value">kmos.dev@gmail.com</span>
					</div>
					<div class="contact-item">
						<span class="contact-label">GITHUB:</span>
						<span class="contact-value">github.com/Mann-lohchab/kmos-dev</span>
					</div>
					<div class="contact-item">
						<span class="contact-label">RESPONSE TIME:</span>
						<span class="contact-value">24 HOURS OR LESS</span>
					</div>
				</div>
			</div>
		</div>
	</section>

	<!-- FOOTER -->
	<footer class="brutalist-footer">
		<div class="footer-content">
			<div class="footer-section">
				<h3>KMOS</h3>
				<p>SOFTWARE ENGINEERING COLLECTIVE</p>
			</div>
			<div class="footer-section">
				<h4>SERVICES</h4>
				<ul>
					<li><a href="#focus">WEB DEVELOPMENT</a></li>
					<li><a href="#focus">MOBILE APPS</a></li>
					<li><a href="#focus">API DEVELOPMENT</a></li>
					<li><a href="#focus">AI SOLUTIONS</a></li>
				</ul>
			</div>
			<div class="footer-section">
				<h4>COMPANY</h4>
				<ul>
					<li><a href="#about">ABOUT US</a></li>
					<li><a href="#team">TEAM</a></li>
					<li><a href="#portfolio">PORTFOLIO</a></li>
					<li><a href="#contact">CONTACT</a></li>
				</ul>
			</div>
			<div class="footer-section">
				<h4>CONNECT</h4>
				<ul>
					<li><a href="mailto:hello@kmos.dev">EMAIL</a></li>
					<li><a href="https://github.com/kmos-dev">GITHUB</a></li>
					<li><a href="#linkedin">LINKEDIN</a></li>
					<li><a href="#twitter">TWITTER</a></li>
				</ul>
			</div>
		</div>
		<div class="footer-bottom">
			<p>© 2024 KMOS. ALL RIGHTS RESERVED. CODE WITH PRIDE.</p>
		</div>
	</footer>
</div>

<style>
	/* BRUTALIST RESET & BASE STYLES */
	:global(*) {
		margin: 0;
		padding: 0;
		box-sizing: border-box;
	}

	:global(body) {
		font-family: 'Courier New', monospace;
		background: #fff;
		color: #000;
		line-height: 1.4;
		letter-spacing: -0.02em;
	}

	:global(html) {
		scroll-behavior: smooth;
	}

	/* MAIN CONTAINER */
	.brutalist-container {
		width: 100%;
		min-height: 100vh;
		background: #fff;
		color: #000;
	}

	/* HERO SECTION */
	.hero-section {
		min-height: 100vh;
		display: grid;
		place-items: center;
		padding: 2rem;
		border-bottom: 4px solid #000;
	}

	.hero-content {
		text-align: center;
		max-width: 1200px;
		width: 100%;
	}

	.hero-title {
		font-size: clamp(3rem, 12vw, 8rem);
		font-weight: 900;
		line-height: 0.9;
		text-transform: uppercase;
		letter-spacing: -0.05em;
		margin-bottom: 2rem;
		border: 4px solid #000;
		padding: 3rem 2rem;
		background: #fff;
		box-shadow: 0 8px 16px -4px rgba(0, 0, 0, 0.2);
	}

	.hero-subtitle {
		background: #000;
		color: #fff;
		padding: 0.5rem 1rem;
		display: inline-block;
	}

	.hero-description {
		font-size: clamp(1rem, 3vw, 1.5rem);
		font-weight: 700;
		text-transform: uppercase;
		margin: 3rem 0;
		line-height: 1.3;
	}

	.hero-cta {
		display: flex;
		justify-content: center;
		gap: 2rem;
		flex-wrap: wrap;
	}

	.cta-primary, .cta-secondary {
		display: inline-block;
		padding: 1rem 2rem;
		text-decoration: none;
		text-transform: uppercase;
		font-weight: 900;
		font-size: 1.1rem;
		border: 3px solid #000;
		transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
		background: #000;
		color: #fff;
		box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.3);
	}

	.cta-secondary {
		background: transparent;
		color: #000;
		box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.3);
	}

	.cta-primary:hover, .cta-secondary:hover {
		background: #000;
		color: #fff;
		transform: translate(-2px, -2px);
		box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.4);
	}

	/* SECTION STYLES */
	.section-header {
		text-align: center;
		padding: 4rem 2rem 2rem;
		border-bottom: 3px solid #000;
	}

	.section-title {
		font-size: clamp(2.5rem, 8vw, 5rem);
		font-weight: 900;
		text-transform: uppercase;
		letter-spacing: -0.03em;
		margin-bottom: 1rem;
	}

	.section-subtitle {
		font-size: 1.2rem;
		font-weight: 700;
		text-transform: uppercase;
		letter-spacing: 0.1em;
	}

	/* ABOUT SECTION */
	.about-section {
		padding: 2rem;
		border-bottom: 4px solid #000;
	}

	.about-content {
		max-width: 1200px;
		margin: 0 auto;
		display: grid;
		grid-template-columns: 2fr 1fr;
		gap: 4rem;
		align-items: start;
	}

	.about-text {
		font-size: 1.1rem;
		line-height: 1.6;
		text-transform: uppercase;
		font-weight: 600;
	}

	.about-description {
		margin-bottom: 2rem;
	}

	.about-stats {
		display: grid;
		grid-template-columns: 1fr 1fr;
		gap: 2rem;
	}

	.stat-item {
		text-align: center;
		border: 3px solid #000;
		padding: 2rem 1rem;
		background: #fff;
		transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
	}

	.stat-item:hover {
		background: #000;
		color: #fff;
		transform: translate(-2px, -2px);
	}

	.stat-number {
		font-size: 2.5rem;
		font-weight: 900;
		margin-bottom: 0.5rem;
	}

	.stat-label {
		font-size: 0.9rem;
		font-weight: 700;
		text-transform: uppercase;
		letter-spacing: 0.05em;
	}

	/* TEAM SECTION */
	.team-section {
		padding: 2rem;
		border-bottom: 4px solid #000;
	}

	.team-grid {
		display: grid;
		grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
		gap: 0;
		max-width: 1400px;
		margin: 0 auto;
	}

	.team-card {
		border: 3px solid #000;
		padding: 2rem;
		background: #fff;
		transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
		box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
	}

	.team-card:hover {
		background: #000;
		color: #fff;
		transform: translate(-2px, -2px);
		box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.3);
	}

	.team-role {
		font-size: 0.8rem;
		font-weight: 900;
		text-transform: uppercase;
		letter-spacing: 0.1em;
		margin-bottom: 1rem;
		opacity: 0.8;
	}

	.team-name {
		font-size: 1.5rem;
		font-weight: 900;
		text-transform: uppercase;
		margin-bottom: 1rem;
		letter-spacing: -0.02em;
	}

	.team-description {
		font-size: 1rem;
		line-height: 1.4;
		margin-bottom: 2rem;
	}

	.team-skills {
		display: flex;
		flex-wrap: wrap;
		gap: 0.5rem;
	}

	.skill-tag {
		background: #000;
		color: #fff;
		padding: 0.3rem 0.8rem;
		font-size: 0.8rem;
		font-weight: 700;
		text-transform: uppercase;
		letter-spacing: 0.05em;
	}

	.team-card:hover .skill-tag {
		background: #fff;
		color: #000;
	}

	/* FOCUS SECTION */
	.focus-section {
		padding: 2rem;
		border-bottom: 4px solid #000;
	}

	.focus-grid {
		display: grid;
		grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
		gap: 0;
		max-width: 1400px;
		margin: 0 auto;
	}

	.focus-card {
		border: 3px solid #000;
		padding: 2rem;
		background: #fff;
		transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
		box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
	}

	.focus-card:hover {
		background: #000;
		color: #fff;
		transform: translate(-4px, -4px);
		box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.3);
	}

	.focus-number {
		font-size: 3rem;
		font-weight: 900;
		margin-bottom: 1rem;
	}

	.focus-title {
		font-size: 1.5rem;
		font-weight: 900;
		text-transform: uppercase;
		margin-bottom: 1rem;
		letter-spacing: -0.02em;
	}

	.focus-description {
		font-size: 1rem;
		line-height: 1.4;
	}

	/* PORTFOLIO SECTION */
	.portfolio-section {
		padding: 2rem;
		border-bottom: 4px solid #000;
	}

	.portfolio-grid {
		display: grid;
		grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
		gap: 0;
		max-width: 1400px;
		margin: 0 auto;
	}

	.portfolio-card {
		border: 3px solid #000;
		padding: 2rem;
		background: #fff;
		text-align: center;
		position: relative;
		transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
		box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
	}

	.portfolio-card:hover {
		background: #000;
		color: #fff;
		transform: translate(-2px, -2px);
		box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.3);
	}

	.portfolio-badge {
		position: absolute;
		top: -1rem;
		left: 50%;
		transform: translateX(-50%);
		background: #fff;
		color: #000;
		padding: 0.5rem 1rem;
		font-size: 0.8rem;
		font-weight: 900;
		text-transform: uppercase;
		border: 2px solid #000;
	}

	.portfolio-title {
		font-size: 1.5rem;
		font-weight: 900;
		text-transform: uppercase;
		margin-bottom: 1rem;
		letter-spacing: -0.02em;
	}

	.portfolio-description {
		font-size: 1rem;
		line-height: 1.4;
		margin-bottom: 2rem;
	}

	.portfolio-tech {
		display: flex;
		justify-content: center;
		flex-wrap: wrap;
		gap: 0.5rem;
		margin-bottom: 2rem;
	}

	.tech-tag {
		background: #000;
		color: #fff;
		padding: 0.3rem 0.8rem;
		font-size: 0.8rem;
		font-weight: 700;
		text-transform: uppercase;
		letter-spacing: 0.05em;
	}

	.portfolio-card:hover .tech-tag {
		background: #fff;
		color: #000;
	}

	.portfolio-link {   
		display: inline-block;
		padding: 1rem 2rem;
		background: #fff;
		color: #000;
		text-decoration: none;
		text-transform: uppercase;
		font-weight: 900;
		border: 3px solid #000;
		transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
	}

	.portfolio-link:hover {
		background: #000;
		color: #fff;
		transform: translate(-2px, -2px);
		box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.3);
	}

	.portfolio-card:hover .portfolio-link {
		background: #fff;
		color: #000;
		border-color: #fff;
	}

	/* CONTACT SECTION */
	.contact-section {
		padding: 2rem;
		border-bottom: 4px solid #000;
	}

	.contact-content {
		max-width: 800px;
		margin: 0 auto;
		text-align: center;
	}

	.contact-title {
		font-size: 2rem;
		font-weight: 900;
		text-transform: uppercase;
		margin-bottom: 2rem;
		letter-spacing: -0.02em;
	}

	.contact-description {
		font-size: 1.1rem;
		line-height: 1.6;
		text-transform: uppercase;
		font-weight: 600;
		margin-bottom: 3rem;
	}

	.contact-details {
		display: grid;
		grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
		gap: 2rem;
		text-align: left;
	}

	.contact-item {
		display: flex;
		justify-content: space-between;
		padding: 1rem;
		border: 2px solid #000;
		background: #fff;
		transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
	}

	.contact-item:hover {
		background: #000;
		color: #fff;
	}

	.contact-label {
		font-weight: 900;
		text-transform: uppercase;
		font-size: 0.9rem;
	}

	.contact-value {
		font-weight: 700;
		text-transform: uppercase;
		font-size: 0.9rem;
	}

	/* FOOTER */
	.brutalist-footer {
		background: #000;
		color: #fff;
		padding: 3rem 2rem 1rem;
		border-top: 4px solid #000;
	}

	.footer-content {
		display: grid;
		grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
		gap: 2rem;
		max-width: 1400px;
		margin: 0 auto 2rem;
	}

	.footer-section h3, .footer-section h4 {
		font-size: 1.2rem;
		font-weight: 900;
		text-transform: uppercase;
		margin-bottom: 1rem;
		letter-spacing: -0.02em;
	}

	.footer-section ul {
		list-style: none;
	}

	.footer-section li {
		margin-bottom: 0.5rem;
	}

	.footer-section a {
		color: #fff;
		text-decoration: none;
		text-transform: uppercase;
		font-weight: 700;
		font-size: 0.9rem;
		transition: all 0.2s ease;
	}

	.footer-section a:hover {
		text-decoration: underline;
		color: #ccc;
	}

	.footer-bottom {
		border-top: 2px solid #fff;
		padding-top: 1rem;
		text-align: center;
	}

	.footer-bottom p {
		font-size: 0.9rem;
		text-transform: uppercase;
		font-weight: 700;
	}

	/* RESPONSIVE */
	@media (max-width: 768px) {
		.hero-cta {
			flex-direction: column;
			align-items: center;
		}

		.about-content {
			grid-template-columns: 1fr;
			gap: 2rem;
		}

		.about-stats {
			grid-template-columns: 1fr 1fr;
		}

		.team-grid,
		.focus-grid,
		.portfolio-grid {
			grid-template-columns: 1fr;
		}

		.team-card,
		.focus-card,
		.portfolio-card {
			border-left: none;
			border-right: none;
		}

		.contact-details {
			grid-template-columns: 1fr;
		}

		.contact-item {
			flex-direction: column;
			text-align: center;
			gap: 0.5rem;
		}
	}

	/* BRUTALIST HOVER EFFECTS */
	.team-card:hover .team-role,
	.focus-card:hover .focus-number,
	.portfolio-card:hover .portfolio-title {
		transform: scale(1.05);
	}

	/* ACCESSIBILITY */
	@media (prefers-reduced-motion: reduce) {
		:global(*) {
			transition: none !important;
			transform: none !important;
		}
	}
</style>