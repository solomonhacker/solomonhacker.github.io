# solomonhacker.github.io[fulll website.html](https://github.com/user-attachments/files/25606667/fulll.website.html)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Galaxy Share | File Sharing & Media Platform</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <script src="https://www.tiktok.com/embed.js" async></script>
    <style>
        :root {
            --primary: #6e00ff;
            --secondary: #00f7ff;
            --accent: #ff00aa;
            --dark: #0a0a20;
            --darker: #050510;
            --light: #f0f0ff;
            --gradient: linear-gradient(135deg, var(--primary), var(--accent));
            --card-bg: rgba(255, 255, 255, 0.05);
            --card-border: rgba(110, 0, 255, 0.2);
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Poppins', sans-serif;
            background: var(--dark);
            color: var(--light);
            line-height: 1.6;
            overflow-x: hidden;
        }
        
        .container {
            width: 100%;
            max-width: 1400px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        /* Header */
        header {
            background: var(--darker);
            padding: 1rem 0;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.3);
            border-bottom: 1px solid rgba(110, 0, 255, 0.3);
        }
        
        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .logo {
            font-family: 'Orbitron', sans-serif;
            font-size: 1.8rem;
            background: linear-gradient(to right, var(--secondary), var(--primary));
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            font-weight: 700;
            letter-spacing: 1px;
        }
        
        .logo span {
            color: var(--secondary);
        }
        
        nav ul {
            display: flex;
            list-style: none;
            gap: 1.5rem;
        }
        
        nav a {
            color: var(--light);
            text-decoration: none;
            font-weight: 500;
            transition: all 0.3s ease;
            padding: 0.5rem 1rem;
            border-radius: 4px;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
        
        nav a:hover, nav a.active {
            background: rgba(110, 0, 255, 0.2);
            color: var(--secondary);
        }
        
        nav a i {
            font-size: 1.1rem;
        }
        
        .user-actions {
            display: flex;
            gap: 1rem;
        }
        
        .btn {
            padding: 0.6rem 1.2rem;
            border-radius: 4px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s ease;
            border: none;
            display: inline-flex;
            align-items: center;
            gap: 0.5rem;
            font-family: 'Poppins', sans-serif;
        }
        
        .btn-primary {
            background: var(--gradient);
            color: white;
        }
        
        .btn-primary:hover {
            transform: translateY(-2px);
            box-shadow: 0 4px 15px rgba(110, 0, 255, 0.4);
        }
        
        .btn-outline {
            background: transparent;
            color: var(--secondary);
            border: 1px solid var(--secondary);
        }
        
        .btn-outline:hover {
            background: rgba(0, 247, 255, 0.1);
        }
        
        /* Hero Section */
        .hero {
            height: 80vh;
            background: linear-gradient(rgba(10, 10, 32, 0.8), rgba(10, 10, 32, 0.9)), 
                        url('https://images.unsplash.com/photo-1635070041078-e363dbe005cb?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2070&q=80') center/cover;
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
            overflow: hidden;
        }
        
        .hero-content {
            text-align: center;
            max-width: 800px;
            padding: 2rem;
            z-index: 2;
        }
        
        .hero h1 {
            font-family: 'Orbitron', sans-serif;
            font-size: 3.5rem;
            margin-bottom: 1rem;
            background: linear-gradient(to right, var(--light), var(--secondary));
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            line-height: 1.2;
        }
        
        .hero p {
            font-size: 1.2rem;
            margin-bottom: 2rem;
            opacity: 0.9;
            max-width: 700px;
            margin-left: auto;
            margin-right: auto;
        }
        
        .hero-btns {
            display: flex;
            gap: 1rem;
            justify-content: center;
            margin-top: 2rem;
        }
        
        /* Sections */
        section {
            padding: 5rem 0;
        }
        
        .section-title {
            font-family: 'Orbitron', sans-serif;
            font-size: 2.5rem;
            margin-bottom: 3rem;
            position: relative;
            display: inline-block;
            text-align: center;
            width: 100%;
        }
        
        .section-title::after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 50%;
            transform: translateX(-50%);
            width: 80px;
            height: 4px;
            background: var(--gradient);
            border-radius: 3px;
        }
        
        /* About Section */
        .about-content {
            display: flex;
            gap: 3rem;
            align-items: center;
            margin-top: 2rem;
        }
        
        .about-image {
            flex: 1;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
        }
        
        .about-image img {
            width: 100%;
            height: auto;
            display: block;
        }
        
        .about-text {
            flex: 1;
        }
        
        .about-text h3 {
            font-size: 1.8rem;
            margin-bottom: 1.5rem;
            color: var(--secondary);
        }
        
        .about-text p {
            margin-bottom: 1.5rem;
        }
        
        .creator-info {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
            margin-top: 1.5rem;
        }
        
        .info-card {
            background: var(--card-bg);
            border: 1px solid var(--card-border);
            border-radius: 8px;
            padding: 1rem;
            flex: 1;
            min-width: 200px;
        }
        
        .info-card h4 {
            color: var(--secondary);
            margin-bottom: 0.5rem;
        }
        
        /* File Sharing Section */
        .file-sharing {
            background: var(--darker);
        }
        
        .upload-container {
            background: var(--card-bg);
            border: 1px solid var(--card-border);
            border-radius: 10px;
            padding: 2rem;
            max-width: 800px;
            margin: 0 auto;
            text-align: center;
        }
        
        .upload-area {
            border: 2px dashed rgba(110, 0, 255, 0.3);
            border-radius: 10px;
            padding: 3rem;
            margin-bottom: 2rem;
            cursor: pointer;
            transition: all 0.3s ease;
        }
        
        .upload-area:hover {
            border-color: var(--primary);
            background: rgba(110, 0, 255, 0.1);
        }
        
        .upload-icon {
            font-size: 3rem;
            margin-bottom: 1rem;
            color: var(--secondary);
        }
        
        .file-preview {
            display: none;
            margin-top: 2rem;
            text-align: left;
        }
        
        .file-preview.active {
            display: block;
        }
        
        .file-info {
            display: flex;
            align-items: center;
            gap: 1rem;
            margin-bottom: 1rem;
            padding: 1rem;
            background: rgba(0, 0, 0, 0.2);
            border-radius: 8px;
        }
        
        .file-icon {
            font-size: 2rem;
            color: var(--secondary);
        }
        
        .file-details {
            flex: 1;
        }
        
        .file-name {
            font-weight: 600;
        }
        
        .file-size {
            font-size: 0.9rem;
            opacity: 0.8;
        }
        
        .progress-container {
            height: 8px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 4px;
            overflow: hidden;
            margin-top: 0.5rem;
        }
        
        .progress-bar {
            height: 100%;
            background: var(--gradient);
            width: 0;
            transition: width 0.5s ease;
        }
        
        .share-link {
            display: none;
            margin-top: 2rem;
            background: rgba(0, 0, 0, 0.3);
            border-radius: 8px;
            padding: 1.5rem;
        }
        
        .share-link.active {
            display: block;
        }
        
        .link-container {
            display: flex;
            gap: 1rem;
            margin-top: 1rem;
        }
        
        .link-container input {
            flex: 1;
            padding: 0.8rem;
            background: rgba(255, 255, 255, 0.1);
            border: 1px solid rgba(255, 255, 255, 0.2);
            border-radius: 4px;
            color: white;
            font-family: 'Poppins', sans-serif;
        }
        
        /* Media Playback */
        .media-playback {
            background: linear-gradient(to bottom, var(--darker), var(--dark));
        }
        
        .media-container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 2rem;
        }
        
        .media-card {
            background: var(--card-bg);
            border: 1px solid var(--card-border);
            border-radius: 10px;
            overflow: hidden;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        .media-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(110, 0, 255, 0.2);
            border-color: rgba(110, 0, 255, 0.4);
        }
        
        .media-thumbnail {
            position: relative;
            width: 100%;
            height: 200px;
            overflow: hidden;
        }
        
        .media-thumbnail img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.5s ease;
        }
        
        .media-card:hover .media-thumbnail img {
            transform: scale(1.05);
        }
        
        .play-icon {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            background: rgba(0, 0, 0, 0.7);
            width: 60px;
            height: 60px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            opacity: 0.8;
            transition: all 0.3s ease;
        }
        
        .play-icon i {
            color: white;
            font-size: 1.5rem;
            margin-left: 5px;
        }
        
        .media-card:hover .play-icon {
            opacity: 1;
            background: var(--primary);
        }
        
        .media-info {
            padding: 1.2rem;
        }
        
        .media-title {
            font-weight: 600;
            margin-bottom: 0.5rem;
        }
        
        .media-meta {
            display: flex;
            justify-content: space-between;
            font-size: 0.9rem;
            color: rgba(255, 255, 255, 0.7);
        }
        
        /* TikTok Section */
        .tiktok-section {
            background: var(--darker);
        }
        
        .tiktok-container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 2rem;
        }
        
        .tiktok-card {
            background: var(--card-bg);
            border: 1px solid var(--card-border);
            border-radius: 10px;
            padding: 1.5rem;
            text-align: center;
        }
        
        .tiktok-profile {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin-bottom: 1.5rem;
        }
        
        .profile-pic {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            background: var(--gradient);
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 1rem;
            font-size: 2.5rem;
        }
        
        .profile-name {
            font-size: 1.5rem;
            font-weight: 600;
            margin-bottom: 0.5rem;
        }
        
        .profile-handle {
            color: var(--secondary);
            margin-bottom: 1rem;
        }
        
        .tiktok-stats {
            display: flex;
            justify-content: center;
            gap: 2rem;
            margin-bottom: 1.5rem;
        }
        
        .stat-item {
            text-align: center;
        }
        
        .stat-value {
            font-size: 1.5rem;
            font-weight: 700;
            margin-bottom: 0.3rem;
        }
        
        .stat-label {
            font-size: 0.9rem;
            opacity: 0.8;
        }
        
        .tiktok-embed {
            margin-top: 1.5rem;
        }
        
        .tiktok-videos {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
            gap: 1.5rem;
        }
        
        /* Footer */
        footer {
            background: var(--darker);
            padding: 3rem 0 1.5rem;
            border-top: 1px solid rgba(110, 0, 255, 0.3);
        }
        
        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
        }
        
        .footer-column h3 {
            font-family: 'Orbitron', sans-serif;
            color: var(--secondary);
            margin-bottom: 1.5rem;
            font-size: 1.2rem;
        }
        
        .footer-column p {
            margin-bottom: 1rem;
            opacity: 0.8;
        }
        
        .footer-column ul {
            list-style: none;
            padding: 0;
        }
        
        .footer-column li {
            margin-bottom: 0.8rem;
        }
        
        .footer-column a {
            color: rgba(255, 255, 255, 0.7);
            text-decoration: none;
            transition: color 0.3s ease;
        }
        
        .footer-column a:hover {
            color: var(--secondary);
        }
        
        .social-links {
            display: flex;
            gap: 1rem;
            margin-top: 1rem;
        }
        
        .social-links a {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 40px;
            height: 40px;
            border-radius: 50%;
            background: rgba(255, 255, 255, 0.1);
            color: white;
            transition: all 0.3s ease;
        }
        
        .social-links a:hover {
            background: var(--gradient);
            transform: translateY(-3px);
        }
        
        .copyright {
            text-align: center;
            margin-top: 3rem;
            padding-top: 1.5rem;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            color: rgba(255, 255, 255, 0.5);
            font-size: 0.9rem;
        }
        
        /* Responsive */
        @media (max-width: 992px) {
            .about-content {
                flex-direction: column;
            }
            
            .hero h1 {
                font-size: 2.8rem;
            }
        }
        
        @media (max-width: 768px) {
            header .header-content {
                flex-direction: column;
                gap: 1rem;
            }
            
            nav ul {
                flex-wrap: wrap;
                justify-content: center;
            }
            
            .hero h1 {
                font-size: 2.2rem;
            }
            
            .hero p {
                font-size: 1rem;
            }
            
            .section-title {
                font-size: 2rem;
            }
        }
        
        @media (max-width: 576px) {
            .hero-btns {
                flex-direction: column;
            }
            
            .upload-area {
                padding: 1.5rem;
            }
            
            .link-container {
                flex-direction: column;
            }
            
            .tiktok-stats {
                flex-direction: column;
                gap: 1rem;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <div class="header-content">
                <div class="logo">GALAXY <span>SHARE</span></div>
                <nav>
                    <ul>
                        <li><a href="#about" class="active"><i class="fas fa-user"></i> About</a></li>
                        <li><a href="#file-sharing"><i class="fas fa-cloud-upload-alt"></i> Share Files</a></li>
                        <li><a href="#media"><i class="fas fa-play-circle"></i> Media</a></li>
                        <li><a href="#tiktok"><i class="fab fa-tiktok"></i> TikTok</a></li>
                    </ul>
                </nav>
                <div class="user-actions">
                    <button class="btn btn-outline"><i class="fas fa-sign-in-alt"></i> Login</button>
                    <button class="btn btn-primary"><i class="fas fa-user-plus"></i> Sign Up</button>
                </div>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="hero-content">
            <h1>SHARE FILES ACROSS THE GALAXY</h1>
            <p>Transfer any file type instantly with our secure platform. No registration required. Play videos, view images, and listen to audio directly in your browser.</p>
            <div class="hero-btns">
                <a href="#file-sharing" class="btn btn-primary"><i class="fas fa-upload"></i> Share Files Now</a>
                <a href="#media" class="btn btn-outline"><i class="fas fa-play"></i> View Media</a>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about">
        <div class="container">
            <h2 class="section-title">About the Creator</h2>
            <div class="about-content">
                <div class="about-image">
                    <img src="https://images.unsplash.com/photo-1519085360753-af0119f7cbe7?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=774&q=80" alt="Niwahereza Solomon">
                </div>
                <div class="about-text">
                    <h3>Niwahereza Solomon (Philippus)</h3>
                    <p>I'm Niwahereza Solomon, but many know me as Philippus. I'm a 17-year-old young scientist, inventor, and the founder of SLMN Galaxy Technologies. I live in Uganda, in Rukiga District, right in the heart of Mwajari Streets.</p>
                    <p>I've always been passionate about science, technology, and building things that can help others — whether it's in physics, electronics, coding, or radio broadcasting. I go to Easy High School, and before that, I studied at Little Pool School. Even while I help in my father's small shop, my mind is always focused on creating and bringing my dreams to life.</p>
                    <p>One of the biggest things I'm working on is building a highly intelligent robot called Sam — not just a machine, but a wise assistant and lifelong companion. I'm also planning to build Sam's robotic brother named Peter in the future. I'm the proud owner of 92.0 Transformation Radio, and I work hard every day to make my ideas a reality. I've even been building websites and apps, like my Galaxy Live Satellite Tracker.</p>
                    <p>I never give up, even when things are hard — because I believe I was born to create, solve, and transform this world through invention.</p>
                    
                    <div class="creator-info">
                        <div class="info-card">
                            <h4><i class="fas fa-robot"></i> Current Projects</h4>
                            <p>Sam (Intelligent Robot)</p>
                            <p>92.0 Transformation Radio</p>
                            <p>Galaxy Live Satellite Tracker</p>
                        </div>
                        <div class="info-card">
                            <h4><i class="fas fa-graduation-cap"></i> Education</h4>
                            <p>Easy High School</p>
                            <p>Little Pool School</p>
                        </div>
                        <div class="info-card">
                            <h4><i class="fas fa-map-marker-alt"></i> Location</h4>
                            <p>Mwajari Streets</p>
                            <p>Rukiga District, Uganda</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- File Sharing Section -->
    <section id="file-sharing" class="file-sharing">
        <div class="container">
            <h2 class="section-title">Share Files Instantly</h2>
            <div class="upload-container">
                <div class="upload-area" id="uploadArea">
                    <div class="upload-icon">
                        <i class="fas fa-cloud-upload-alt"></i>
                    </div>
                    <h3>Drag & Drop Files Here</h3>
                    <p>or click to browse your device</p>
                    <p class="small">Supports all file types (max 2GB)</p>
                </div>
                <input type="file" id="fileInput" style="display: none;">
                
                <div class="file-preview" id="filePreview">
                    <div class="file-info">
                        <div class="file-icon">
                            <i class="fas fa-file"></i>
                        </div>
                        <div class="file-details">
                            <div class="file-name" id="fileName">your-file-name.ext</div>
                            <div class="file-size" id="fileSize">0 MB</div>
                        </div>
                    </div>
                    
                    <div class="progress-container">
                        <div class="progress-bar" id="progressBar"></div>
                    </div>
                    
                    <button class="btn btn-primary" id="uploadBtn" style="margin-top: 1rem; width: 100%;">
                        <i class="fas fa-upload"></i> Upload File
                    </button>
                </div>
                
                <div class="share-link" id="shareLink">
                    <h3>Your file is ready to share!</h3>
                    <p>Copy the link below and share it with anyone:</p>
                    
                    <div class="link-container">
                        <input type="text" id="shareLinkInput" value="https://galaxyshare.app/file/xyz123" readonly>
                        <button class="btn btn-primary" id="copyBtn">
                            <i class="fas fa-copy"></i> Copy
                        </button>
                    </div>
                    
                    <div style="margin-top: 1.5rem;">
                        <button class="btn btn-outline" id="newUploadBtn">
                            <i class="fas fa-plus"></i> Share Another File
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Media Playback Section -->
    <section id="media" class="media-playback">
        <div class="container">
            <h2 class="section-title">Media Playback</h2>
            <div class="media-container">
                <div class="media-card">
                    <div class="media-thumbnail">
                        <img src="https://images.unsplash.com/photo-1574717024453-354056aafa98?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1074&q=80" alt="Tech Innovation">
                        <div class="play-icon">
                            <i class="fas fa-play"></i>
                        </div>
                    </div>
                    <div class="media-info">
                        <div class="media-title">The Future of Robotics</div>
                        <div class="media-meta">
                            <span><i class="fas fa-clock"></i> 12:45</span>
                            <span><i class="fas fa-eye"></i> 24.5K</span>
                        </div>
                    </div>
                </div>
                
                <div class="media-card">
                    <div class="media-thumbnail">
                        <img src="https://images.unsplash.com/photo-1518770660439-4636190af475?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1170&q=80" alt="Electronics">
                        <div class="play-icon">
                            <i class="fas fa-play"></i>
                        </div>
                    </div>
                    <div class="media-info">
                        <div class="media-title">Building Circuits 101</div>
                        <div class="media-meta">
                            <span><i class="fas fa-clock"></i> 8:22</span>
                            <span><i class="fas fa-eye"></i> 18.3K</span>
                        </div>
                    </div>
                </div>
                
                <div class="media-card">
                    <div class="media-thumbnail">
                        <img src="https://images.unsplash.com/photo-1518770660439-4636190af475?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1170&q=80" alt="Coding">
                        <div class="play-icon">
                            <i class="fas fa-play"></i>
                        </div>
                    </div>
                    <div class="media-info">
                        <div class="media-title">Coding My First App</div>
                        <div class="media-meta">
                            <span><i class="fas fa-clock"></i> 15:30</span>
                            <span><i class="fas fa-eye"></i> 32.7K</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- TikTok Section -->
    <section id="tiktok" class="tiktok-section">
        <div class="container">
            <h2 class="section-title">TikTok Integration</h2>
            <div class="tiktok-container">
                <div class="tiktok-card">
                    <div class="tiktok-profile">
                        <div class="profile-pic">
                            <i class="fas fa-user"></i>
                        </div>
                        <div class="profile-name">Solomon Galaxy</div>
                        <div class="profile-handle">@solomontech</div>
                        <p>Sharing my journey in technology, robotics, and innovation</p>
                    </div>
                    
                    <div class="tiktok-stats">
                        <div class="stat-item">
                            <div class="stat-value">24.5K</div>
                            <div class="stat-label">Followers</div>
                        </div>
                        <div class="stat-item">
                            <div class="stat-value">186</div>
                            <div class="stat-label">Videos</div>
                        </div>
                        <div class="stat-item">
                            <div class="stat-value">1.2M</div>
                            <div class="stat-label">Likes</div>
                        </div>
                    </div>
                    
                    <a href="https://www.tiktok.com/@solomontech" target="_blank" class="btn btn-primary">
                        <i class="fab fa-tiktok"></i> View Profile
                    </a>
                </div>
                
                <div class="tiktok-videos">
                    <div class="tiktok-embed">
                        <blockquote class="tiktok-embed" cite="https://www.tiktok.com/@solomontech/video/7368533691703872773" data-video-id="7368533691703872773">
                            <section></section>
                        </blockquote>
                    </div>
                    
                    <div class="tiktok-embed">
                        <blockquote class="tiktok-embed" cite="https://www.tiktok.com/@solomontech/video/7359272726350245125" data-video-id="7359272726350245125">
                            <section></section>
                        </blockquote>
                    </div>
                    
                    <div class="tiktok-embed">
                        <blockquote class="tiktok-embed" cite="https://www.tiktok.com/@solomontech/video/7348921645189762309" data-video-id="7348921645189762309">
                            <section></section>
                        </blockquote>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-column">
                    <h3>Galaxy Share</h3>
                    <p>Transfer files instantly across the web with our secure platform. No registration required. Play media directly in your browser.</p>
                    <div class="social-links">
                        <a href="https://www.tiktok.com/@solomontech" target="_blank"><i class="fab fa-tiktok"></i></a>
                        <a href="#" target="_blank"><i class="fab fa-youtube"></i></a>
                        <a href="#" target="_blank"><i class="fab fa-twitter"></i></a>
                        <a href="#" target="_blank"><i class="fab fa-github"></i></a>
                    </div>
                </div>
                
                <div class="footer-column">
                    <h3>Quick Links</h3>
                    <ul>
                        <li><a href="#about">About Creator</a></li>
                        <li><a href="#file-sharing">Share Files</a></li>
                        <li><a href="#media">Media Playback</a></li>
                        <li><a href="#tiktok">TikTok Profile</a></li>
                    </ul>
                </div>
                
                <div class="footer-column">
                    <h3>Resources</h3>
                    <ul>
                        <li><a href="#">Help Center</a></li>
                        <li><a href="#">File Limits</a></li>
                        <li><a href="#">Security</a></li>
                        <li><a href="#">API Documentation</a></li>
                    </ul>
                </div>
                
                <div class="footer-column">
                    <h3>Contact</h3>
                    <ul>
                        <li><i class="fas fa-envelope"></i> contact@galaxyshare.app</li>
                        <li><i class="fas fa-map-marker-alt"></i> Rukiga District, Uganda</li>
                        <li><i class="fas fa-building"></i> SLMN Galaxy Technologies</li>
                    </ul>
                </div>
            </div>
            
            <div class="copyright">
                &copy; 2023 Galaxy Share by SLMN Galaxy Technologies. All Rights Reserved.
            </div>
        </div>
    </footer>

    <script>
        // File upload functionality
        const uploadArea = document.getElementById('uploadArea');
        const fileInput = document.getElementById('fileInput');
        const filePreview = document.getElementById('filePreview');
        const fileName = document.getElementById('fileName');
        const fileSize = document.getElementById('fileSize');
        const progressBar = document.getElementById('progressBar');
        const uploadBtn = document.getElementById('uploadBtn');
        const shareLink = document.getElementById('shareLink');
        const shareLinkInput = document.getElementById('shareLinkInput');
        const copyBtn = document.getElementById('copyBtn');
        const newUploadBtn = document.getElementById('newUploadBtn');
        
        let selectedFile = null;
        
        // Open file browser when upload area is clicked
        uploadArea.addEventListener('click', () => {
            fileInput.click();
        });
        
        // Handle file selection
        fileInput.addEventListener('change', (e) => {
            if (e.target.files.length > 0) {
                selectedFile = e.target.files[0];
                fileName.textContent = selectedFile.name;
                fileSize.textContent = formatFileSize(selectedFile.size);
                filePreview.classList.add('active');
            }
        });
        
        // Upload simulation
        uploadBtn.addEventListener('click', () => {
            if (!selectedFile) return;
            
            // Simulate upload progress
            let progress = 0;
            const interval = setInterval(() => {
                progress += Math.floor(Math.random() * 10) + 1;
                if (progress >= 100) {
                    progress = 100;
                    clearInterval(interval);
                    
                    // Show share link after upload completes
                    setTimeout(() => {
                        filePreview.classList.remove('active');
                        shareLink.classList.add('active');
                        
                        // Generate random share link
                        const randomId = Math.random().toString(36).substring(2, 10);
                        shareLinkInput.value = `https://galaxyshare.app/file/${randomId}`;
                    }, 300);
                }
                
                progressBar.style.width = `${progress}%`;
            }, 200);
        });
        
        // Copy link to clipboard
        copyBtn.addEventListener('click', () => {
            shareLinkInput.select();
            document.execCommand('copy');
            
            // Show copied feedback
            const originalText = copyBtn.innerHTML;
            copyBtn.innerHTML = '<i class="fas fa-check"></i> Copied!';
            setTimeout(() => {
                copyBtn.innerHTML = originalText;
            }, 2000);
        });
        
        // New upload button
        newUploadBtn.addEventListener('click', () => {
            shareLink.classList.remove('active');
            fileInput.value = '';
            selectedFile = null;
            progressBar.style.width = '0%';
        });
        
        // Format file size
        function formatFileSize(bytes) {
            if (bytes === 0) return '0 Bytes';
            
            const k = 1024;
            const sizes = ['Bytes', 'KB', 'MB', 'GB'];
            const i = Math.floor(Math.log(bytes) / Math.log(k));
            
            return parseFloat((bytes / Math.pow(k, i)).toFixed(2)) + ' ' + sizes[i];
        }
        
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    window.scrollTo({
                        top: target.offsetTop - 80,
                        behavior: 'smooth'
                    });
                }
            });
        });
        
        // Initialize TikTok embeds
        document.querySelectorAll('.tiktok-embed').forEach(embed => {
            const videoId = embed.querySelector('blockquote').getAttribute('data-video-id');
            embed.innerHTML = `
                <div style="position:relative; padding-top:177.78%;">
                    <iframe src="https://www.tiktok.com/embed/v2/${videoId}" 
                        style="position:absolute; top:0; left:0; width:100%; height:100%;" 
                        frameborder="0" allowfullscreen></iframe>
                </div>
            `;
        });
    </script>
</body>
</html>
