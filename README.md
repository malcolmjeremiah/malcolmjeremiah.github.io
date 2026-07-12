<style>
  /* Global Page Canvas & Premium Typography System */
  html {
    scroll-behavior: smooth !important;
    background-color: #030712 !important;
    font-family: -apple-system, BlinkMacSystemFont, "SF Pro Display", "-apple-system-body", "Segoe UI", Roboto, sans-serif !important;
    color: #f8fafc !important;
    letter-spacing: -0.1px;
  }
  
  body {
    max-width: 1140px !important;
    padding: 60px 20px !important;
    margin: 0 auto !important;
    background-color: #030712 !important;
    /* Ambient multi-axis mesh lighting background */
    background-image: 
      radial-gradient(at 0% 0%, rgba(56, 189, 248, 0.04) 0px, transparent 50%),
      radial-gradient(at 100% 0%, rgba(139, 92, 246, 0.03) 0px, transparent 50%),
      radial-gradient(at 50% 100%, rgba(15, 23, 42, 0.9) 0px, transparent 70%) !important;
    background-attachment: fixed !important;
  }
  
  .main-content {
    max-width: 100% !important;
    padding: 0 !important;
  }

  /* Executive Header Hero Panel Component */
  header.page-header {
    background-image: linear-gradient(rgba(2, 6, 23, 0.9), rgba(2, 6, 23, 0.97)), url('https://github.com/malcolmjeremiah/malcolmjeremiah.github.io/blob/main/1763479411435.jpeg?raw=true') !important;
    background-size: cover !important;
    background-position: center !important;
    padding: 9rem 2rem !important;
    text-align: center !important;
    border-radius: 28px !important;
    box-shadow: 0 40px 100px -30px rgba(0, 0, 0, 0.9) !important;
    border: 1px solid rgba(255, 255, 255, 0.03) !important;
    margin-bottom: 50px !important;
  }
  
  header.page-header h1.project-name {
    display: block !important;
    color: #ffffff !important;
    font-size: 48px !important;
    font-weight: 800 !important;
    letter-spacing: -1.5px !important;
    margin: 0 !important;
    background: linear-gradient(180deg, #ffffff 0%, #cbd5e1 100%) !important;
    -webkit-background-clip: text !important;
    -webkit-text-fill-color: transparent !important;
  }
  header.page-header h1.project-name::after {
    content: "MALCOLM JEREMIAH RICHARD";
  }
  
  header.page-header h2.project-tagline {
    display: block !important;
    color: #e2e8f0 !important;
    font-size: 12px !important;
    font-weight: 700 !important;
    text-transform: uppercase !important;
    letter-spacing: 5px !important;
    margin-top: 24px !important;
    text-shadow: 0 2px 10px rgba(0, 0, 0, 0.4) !important;
  }
  header.page-header h2.project-tagline::after {
    content: "BSc (Hons) Information Technology Student | UI/UX Portfolio";
  }

  header.page-header .btn { display: none !important; }
  
  /* Next-Gen Ultra-Thin Floating Navigation */
  .nav-container {
    position: -webkit-sticky;
    position: sticky;
    top: 24px;
    z-index: 999;
    display: flex;
    justify-content: center;
    background-color: rgba(3, 7, 18, 0.6);
    -webkit-backdrop-filter: blur(30px);
    backdrop-filter: blur(30px);
    padding: 5px;
    border-radius: 40px;
    border: 1px solid rgba(255, 255, 255, 0.05);
    box-shadow: 0 30px 60px -15px rgba(0, 0, 0, 0.8), inset 0 1px 0 rgba(255,255,255,0.05);
    margin-bottom: 100px;
  }

  .nav-btn {
    position: relative !important;
    white-space: nowrap !important;
    color: #94a3b8 !important;
    padding: 12px 28px !important;
    border-radius: 30px !important;
    text-decoration: none !important;
    font-weight: 600 !important;
    font-size: 13px !important;
    display: inline-block !important;
    letter-spacing: 0.2px !important;
    transition: all 0.3s cubic-bezier(0.25, 1, 0.5, 1) !important;
  }
  
  .nav-btn:hover {
    color: #ffffff !important;
    background-color: rgba(255, 255, 255, 0.04) !important;
  }
  
  .nav-btn::after {
    content: '' !important;
    position: absolute !important;
    bottom: 4px !important;
    left: 50% !important;
    width: 0 !important;
    height: 2px !important;
    background: linear-gradient(90deg, #38bdf8, #818cf8) !important;
    transition: all 0.3s ease !important;
    transform: translateX(-50%) !important;
  }
  .nav-btn:hover::after {
    width: 25% !important;
  }

  @media (max-width: 768px) {
    .nav-container {
      justify-content: flex-start !important;
      overflow-x: auto !important;
      -webkit-overflow-scrolling: touch !important;
      border-radius: 16px !important;
      padding: 6px !important;
      margin-bottom: 40px;
    }
    .nav-container::-webkit-scrollbar {
      display: none !important;
    }
    .nav-btn {
      padding: 12px 18px !important;
    }
  }

  /* Next-Gen Frosted Card Framework */
  .premium-card {
    background: linear-gradient(135deg, rgba(15, 23, 42, 0.3) 0%, rgba(30, 41, 59, 0.2) 100%) !important;
    backdrop-filter: blur(16px) !important;
    -webkit-backdrop-filter: blur(16px) !important;
    border: 1px solid rgba(255, 255, 255, 0.03) !important;
    box-shadow: 0 20px 40px -15px rgba(0, 0, 0, 0.5) !important;
    transition: all 0.45s cubic-bezier(0.16, 1, 0.3, 1) !important;
  }
  
  /* Micro-Highlight Project Specific Glow Maps */
  .premium-card.glow-orange:hover {
    transform: translateY(-6px) !important;
    border-color: rgba(249, 115, 22, 0.25) !important;
    box-shadow: 0 30px 60px -15px rgba(249, 115, 22, 0.15) !important;
  }
  
  .premium-card.glow-blue:hover {
    transform: translateY(-6px) !important;
    border-color: rgba(56, 189, 248, 0.25) !important;
    box-shadow: 0 30px 60px -15px rgba(56, 189, 248, 0.15) !important;
  }
  
  .badge-btn {
    transition: all 0.3s cubic-bezier(0.16, 1, 0.3, 1) !important;
    cursor: pointer !important;
  }
  .badge-btn:hover {
    transform: translateY(-2px) !important;
    filter: brightness(1.15);
  }

  .section-title-wrapper {
    display: flex;
    align-items: center;
    gap: 16px;
    margin-bottom: 36px;
  }
  .section-bar {
    width: 4px;
    height: 28px;
    background: linear-gradient(to bottom, #60a5fa, #3b82f6);
    border-radius: 10px;
  }
  
  .pill-metric {
    font-size: 11px;
    font-weight: 700;
    text-transform: uppercase;
    letter-spacing: 1px;
    padding: 6px 14px;
    border-radius: 20px;
    display: inline-block;
  }

  /* Robust and Clean Responsive Table Wrapper */
  .audit-table-wrapper {
    width: 100% !important;
    overflow-x: auto !important;
    -webkit-overflow-scrolling: touch !important;
    border-radius: 12px !important;
    background: rgba(15, 23, 42, 0.15) !important;
    border: 1px solid rgba(255, 255, 255, 0.05) !important;
    margin-top: 20px !important;
  }

  .audit-table {
    width: 100% !important;
    min-width: 700px !important;
    border-collapse: collapse !important;
    font-size: 13.5px !important;
    color: #cbd5e1 !important;
  }
  .audit-table th {
    text-align: left !important;
    padding: 14px 16px !important;
    background: rgba(255, 255, 255, 0.03) !important;
    color: #ffffff !important;
    font-weight: 600 !important;
    border-bottom: 1px solid rgba(255, 255, 255, 0.08) !important;
  }
  .audit-table td {
    padding: 14px 16px !important;
    border-bottom: 1px solid rgba(255, 255, 255, 0.04) !important;
    line-height: 1.5 !important;
  }

  /* Fixed Pop-up Overlay CSS Framework */
  .custom-modal-overlay {
    position: fixed !important;
    top: 0 !important;
    left: 0 !important;
    width: 100% !important;
    height: 100% !important;
    background-color: rgba(3, 7, 18, 0.94) !important;
    backdrop-filter: blur(24px) !important;
    -webkit-backdrop-filter: blur(24px) !important;
    z-index: 10000 !important;
    display: none !important;
    align-items: center !important;
    justify-content: center !important;
    opacity: 0 !important;
    transition: opacity 0.3s cubic-bezier(0.16, 1, 0.3, 1) !important;
  }
  
  .custom-modal-overlay.is-active {
    display: flex !important;
    opacity: 1 !important;
  }
  
  .custom-modal-window {
    position: relative !important;
    width: 90vw !important;
    height: 85vh !important;
    display: flex !important;
    align-items: center !important;
    justify-content: center !important;
    overflow: hidden !important;
    cursor: grab !important;
    border-radius: 16px !important;
  }
  .custom-modal-window:active {
    cursor: grabbing !important;
  }
  .custom-modal-content {
    max-width: 100% !important;
    max-height: 100% !important;
    object-fit: contain !important;
    user-select: none !important;
    -webkit-user-drag: none !important;
    transition: transform 0.25s cubic-bezier(0.16, 1, 0.3, 1) !important;
    box-shadow: 0 25px 70px rgba(0, 0, 0, 0.6) !important;
  }
  
  /* Report PDF Lightbox Modal Window Configurations */
  .report-modal-window {
    width: 85vw !important;
    height: 85vh !important;
    background-color: #111827 !important;
    border-radius: 16px !important;
    border: 1px solid rgba(255, 255, 255, 0.08) !important;
    box-shadow: 0 25px 70px rgba(0, 0, 0, 0.8) !important;
    overflow: hidden !important;
    display: flex !important;
    flex-direction: column !important;
  }
  .report-frame {
    width: 100% !important;
    height: 100% !important;
    border: none !important;
    background: #111827 !important;
  }

  .custom-modal-close-btn {
    position: fixed !important;
    top: 25px !important;
    right: 35px !important;
    background: rgba(15, 23, 42, 0.7) !important;
    border: 1px solid rgba(255,255,255,0.08) !important;
    backdrop-filter: blur(8px) !important;
    -webkit-backdrop-filter: blur(8px) !important;
    color: #94a3b8 !important;
    font-size: 24px !important;
    width: 44px !important;
    height: 44px !important;
    border-radius: 50% !important;
    cursor: pointer !important;
    display: flex !important;
    align-items: center !important;
    justify-content: center !important;
    transition: all 0.2s ease !important;
    z-index: 10001 !important;
  }
  .custom-modal-close-btn:hover {
    color: #ffffff !important;
    background: rgba(15, 23, 42, 0.9) !important;
    transform: scale(1.05) !important;
  }
</style>

<div style="margin-top: 10px;">

  <div class="nav-container">
    <a href="#who-i-am" class="nav-btn">Profile</a>
    <a href="#projects-overview" class="nav-btn">Featured Projects</a>
    <a href="#case-study-1-ergochef" class="nav-btn">Case 1: ErgoChef+</a>
    <a href="#case-study-2-elearn-ux-audit" class="nav-btn">Case 2: eLearn Audit</a>
    <a href="#personal-challenges" class="nav-btn">Diagnostics</a>
    <a href="#submission" class="nav-btn">Submission</a>
  </div>

  <div id="who-i-am" style="padding-top: 20px; margin-bottom: 80px;">
    <div class="section-title-wrapper">
      <div class="section-bar" style="background: linear-gradient(#38bdf8, #818cf8);"></div>
      <h2 style="color: #ffffff; font-size: 28px; font-weight: 700; margin: 0; letter-spacing: -0.5px;">Introduction</h2>
    </div>
    
    <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 28px;">
      <div class="premium-card glow-blue" style="flex: 2; min-width: 320px; border-radius: 24px; padding: 40px; display: flex; gap: 35px; align-items: center; flex-wrap: wrap;">
        <div style="position: relative; flex-shrink: 0;">
          <div style="position: absolute; top: -5px; left: -4px; right: -4px; bottom: -4px; background: linear-gradient(135deg, #38bdf8, #818cf8); border-radius: 50%; z-index: 0; opacity: 0.3; filter: blur(4px);"></div>
          <img src="https://raw.githubusercontent.com/malcolmjeremiah/malcolmjeremiah.github.io/main/WhatsApp%20Image%202026-07-03%20at%2010.14.22%20PM.jpeg" alt="Malcolm" style="position: relative; width: 110px; height: 110px; border-radius: 50%; object-fit: cover; border: 4px solid #020617; z-index: 1;" />
        </div>
        <div style="flex: 1; min-width: 240px;">
          <p style="font-size: 16px; line-height: 1.8; color: #cbd5e1; margin: 0; font-weight: 400; letter-spacing: 0.2px;">
            I am an <strong>Information Technology</strong> student specializing in software automation, data extraction, and user-centered workflow optimization. My design philosophy is rooted in <strong>functional minimalism</strong>: digital interfaces should actively reduce user cognitive load, mask complex database architecture, and adapt seamlessly to a user's real-world mental model. I bridge the gap between back-end technical scripting logic and clean, empathetic front-end layout execution.
          </p>
        </div>
      </div>

      <div class="premium-card glow-blue" style="flex: 1; min-width: 280px; border-radius: 24px; padding: 35px; display: flex; flex-direction: column; justify-content: center;">
        <h4 style="margin-top: 0; margin-bottom: 16px; color: #475569; font-size: 11px; font-weight: 700; text-transform: uppercase; letter-spacing: 2px;">Core Architecture Stack</h4>
        <div style="margin-bottom: 28px; display: flex; flex-wrap: wrap; gap: 8px;">
          <span style="font-size: 12px; font-weight: 600; background-color: rgba(255,255,255,0.03); color: #38bdf8; padding: 6px 14px; border-radius: 20px; border: 1px solid rgba(56, 189, 248, 0.15);">Python</span>
          <span style="font-size: 12px; font-weight: 600; background-color: rgba(255,255,255,0.03); color: #e2e8f0; padding: 6px 14px; border-radius: 20px; border: 1px solid rgba(255,255,255,0.05);">PHP</span>
          <span style="font-size: 12px; font-weight: 600; background-color: rgba(255,255,255,0.03); color: #e2e8f0; padding: 6px 14px; border-radius: 20px; border: 1px solid rgba(255,255,255,0.05);">JavaScript</span>
          <span style="font-size: 12px; font-weight: 600; background-color: rgba(255,255,255,0.03); color: #e2e8f0; padding: 6px 14px; border-radius: 20px; border: 1px solid rgba(255,255,255,0.05);">GIT</span>
        </div>
        <h4 style="margin-top: 0; margin-bottom: 16px; color: #475569; font-size: 11px; font-weight: 700; text-transform: uppercase; letter-spacing: 2px;">Methodologies</h4>
        <div style="display: flex; flex-wrap: wrap; gap: 8px;">
          <span style="font-size: 12px; font-weight: 600; background-color: rgba(255,255,255,0.03); color: #a5b4fc; padding: 6px 14px; border-radius: 20px; border: 1px solid rgba(129, 140, 248, 0.12);">Heuristic Evaluation</span>
          <span style="font-size: 12px; font-weight: 600; background-color: rgba(255,255,255,0.03); color: #94a3b8; padding: 6px 14px; border-radius: 20px; border: 1px solid rgba(255,255,255,0.05);">Cognitive Walkthrough</span>
          <span style="font-size: 12px; font-weight: 600; background-color: rgba(255,255,255,0.03); color: #94a3b8; padding: 6px 14px; border-radius: 20px; border: 1px solid rgba(255,255,255,0.05);">Task Mapping</span>
        </div>
      </div>
    </div>
  </div>

  <div id="projects-overview" style="padding-top: 20px; margin-bottom: 80px;">
    <div class="section-title-wrapper">
      <div class="section-bar" style="background: linear-gradient(#f97316, #ef4444);"></div>
      <h2 style="color: #ffffff; font-size: 28px; font-weight: 700; margin: 0; letter-spacing: -0.5px;">Featured Projects</h2>
    </div>
    
    <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 28px;">
      <div class="premium-card glow-orange" style="flex: 1; min-width: 300px; border-radius: 24px; padding: 36px; display: flex; flex-direction: column; justify-content: space-between; border-left: 3px solid #f97316 !important;">
        <div>
          <span class="pill-metric" style="background-color: rgba(249, 115, 22, 0.08); color: #fdba74; border: 1px solid rgba(249, 115, 22, 0.15);">Group Case Study</span>
          <h3 style="margin: 20px 0 14px 0; font-size: 22px; color: #ffffff; font-weight: 700; letter-spacing: -0.5px;">ErgoChef+: AI Ergonomic Assistant</h3>
          <p style="font-size: 14.5px; line-height: 1.7; color: #94a3b8; margin: 0 0 30px 0;">An AI-enabled kitchen ecosystem utilizing advanced posture-sensing technology to mitigate ergonomic stress and long-term musculoskeletal fatigue for cooks.</p>
        </div>
        <div style="border-top: 1px solid rgba(255,255,255,0.05); padding-top: 24px; display: flex; align-items: center; justify-content: space-between;">
          <div style="font-size: 13px; color: #cbd5e1;"><strong>Role:</strong> Lead UI Designer</div>
          <a href="#case-study-1-ergochef" style="font-size: 14px; font-weight: 700; color: #fdba74; text-decoration: none; display: flex; align-items: center; gap: 4px;">Explore Case →</a>
        </div>
      </div>
      
      <div class="premium-card glow-blue" style="flex: 1; min-width: 300px; border-radius: 24px; padding: 36px; display: flex; flex-direction: column; justify-content: space-between; border-left: 3px solid #38bdf8 !important;">
        <div>
          <span class="pill-metric" style="background-color: rgba(56, 189, 248, 0.08); color: #7dd3fc; border: 1px solid rgba(56, 189, 248, 0.15);">Individual Case Study</span>
          <h3 style="margin: 20px 0 14px 0; font-size: 22px; color: #ffffff; font-weight: 700; letter-spacing: -0.5px;">Learning Management Portal UX Audit</h3>
          <p style="font-size: 14.5px; line-height: 1.7; color: #94a3b8; margin: 0 0 30px 0;">A comprehensive heuristic evaluation and interface restructuring of the university portal to eliminate navigation friction and multi-click journey loops for students.</p>
        </div>
        <div style="border-top: 1px solid rgba(255,255,255,0.05); padding-top: 24px; display: flex; align-items: center; justify-content: space-between;">
          <div style="font-size: 13px; color: #cbd5e1;"><strong>Role:</strong> Lead UX Auditor</div>
          <a href="#case-study-2-elearn-ux-audit" style="font-size: 14px; font-weight: 700; color: #7dd3fc; text-decoration: none; display: flex; align-items: center; gap: 4px;">Explore Case →</a>
        </div>
      </div>
    </div>
  </div>

  <div id="case-study-1-ergochef" style="padding-top: 40px; margin-bottom: 80px;">
    <div class="premium-card glow-orange" style="border-radius: 28px; padding: 45px; box-shadow: 0 40px 80px -20px rgba(0,0,0,0.6);">
      
      <div style="display: flex; flex-wrap: wrap; justify-content: space-between; align-items: flex-start; border-bottom: 1px solid rgba(255,255,255,0.05); padding-bottom: 28px; margin-bottom: 36px; gap: 16px;">
        <div>
          <h2 style="color: #ffffff; font-size: 28px; font-weight: 800; margin: 0; letter-spacing: -0.5px;">Case Study 1: ErgoChef+</h2>
          <p style="color: #f97316; font-size: 13px; font-weight: 700; margin: 8px 0 0 0; text-transform: uppercase; letter-spacing: 1px;">AI-Powered Context Cooking Ecosystem</p>
        </div>
        <span style="font-size: 12px; font-weight: 600; background-color: rgba(255,255,255,0.03); color: #cbd5e1; padding: 8px 20px; border-radius: 30px; border: 1px solid rgba(255,255,255,0.08);">Lead UI & Interaction Designer</span>
      </div>
      
      <div style="background: linear-gradient(135deg, rgba(249, 115, 22, 0.02) 0%, rgba(234, 88, 12, 0.05) 100%); border: 1px solid rgba(249, 115, 22, 0.12); border-radius: 16px; padding: 32px; margin-bottom: 45px;">
        <h4 style="margin-top: 0; color: #fdba74; font-size: 13px; font-weight: 700; text-transform: uppercase; letter-spacing: 1.5px; margin-bottom: 16px;">Project Overview & Context</h4>
        <p style="font-size: 15px; line-height: 1.75; color: #cbd5e1; margin-bottom: 20px;">
          <strong>The Problem:</strong> Cooking involves highly repetitive, physically demanding actions like bending, chopping, stirring, and prolonged standing. These movements generate heavy ergonomic stress, muscle fatigue, and musculoskeletal strain. Existing smart tools automate cooking tasks but completely ignore the chef's posture and long-term joint health.
        </p>
        <p style="font-size: 15px; line-height: 1.75; color: #cbd5e1; margin-bottom: 0;">
          <strong>Project Goals & Value Proposition:</strong> ErgoChef+ integrates AI-driven posture detection, non-intrusive reminders, and personalized ergonomic reports. The goal is to provide real-time guidance to adapt to diverse cooking contexts and establish healthy, long-term kitchen habits.
          <br><br>
          <strong>Target Audience:</strong> Busy home cooks, culinary professionals, and elderly or diverse users prone to physical kitchen fatigue.
        </p>
      </div>

      <h4 style="color: #ffffff; font-size: 12px; font-weight: 700; margin-bottom: 24px; text-transform: uppercase; letter-spacing: 2px;">Design Process & Iterative Framework</h4>
      <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 20px; margin-bottom: 45px;">
        <div style="flex: 1; min-width: 220px; background-color: rgba(255,255,255,0.01); border: 1px solid rgba(255,255,255,0.03); border-radius: 16px; padding: 28px;">
          <strong style="color: #ffffff; font-size: 14px; display: block; margin-bottom: 10px;">Research & Discovery</strong>
          <span style="font-size: 13px; line-height: 1.65; color: #94a3b8; display: block;">Conducted quantitative user surveys and qualitative interviews to map baseline physical discomfort zones during food prep.</span>
        </div>
        <div style="flex: 1; min-width: 220px; background-color: rgba(255,255,255,0.01); border: 1px solid rgba(255,255,255,0.03); border-radius: 16px; padding: 28px;">
          <strong style="color: #ffffff; font-size: 14px; display: block; margin-bottom: 10px;">Ideation & Sketches</strong>
          <span style="font-size: 13px; line-height: 1.65; color: #94a3b8; display: block;">Sketched low-fidelity kitchen spatial layouts and camera-to-app physical telemetry interactions on paper.</span>
        </div>
        <div style="flex: 1; min-width: 220px; background-color: rgba(255,255,255,0.01); border: 1px solid rgba(255,255,255,0.03); border-radius: 16px; padding: 28px;">
          <strong style="color: #ffffff; font-size: 14px; display: block; margin-bottom: 10px;">Storyboarding</strong>
          <span style="font-size: 13px; line-height: 1.65; color: #94a3b8; display: block;">Mapped out contextual user flow scenarios to establish how and when the system alerts a user to change their physical posture.</span>
        </div>
        <div style="flex: 1; min-width: 220px; background-color: rgba(255,255,255,0.01); border: 1px solid rgba(255,255,255,0.03); border-radius: 16px; padding: 28px;">
          <strong style="color: #ffffff; font-size: 14px; display: block; margin-bottom: 10px;">High-Fi Prototyping</strong>
          <span style="font-size: 13px; line-height: 1.65; color: #94a3b8; display: block;">Translated layouts into a functional, live web platform using Lovable to track real-time visual tracking data.</span>
        </div>
      </div>

      <div style="background-color: rgba(255,255,255,0.01); border: 1px solid rgba(255,255,255,0.03); border-radius: 20px; padding: 40px; margin-bottom: 45px; text-align: center;">
        <h4 style="margin: 0 0 8px 0; color: #ffffff; font-size: 18px; font-weight: 700; letter-spacing: -0.3px;">Design Artefacts & Live Media</h4>
        <p style="font-size: 14px; color: #64748b; margin: 0 0 32px 0;">Explore the production-ready application layout interface running spatial computer vision logic live from your system dashboard.</p>
        <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 16px; justify-content: center;">
          <a href="https://ergo-chef-journey.lovable.app/" target="_blank" class="badge-btn" style="flex: 1; min-width: 240px; max-width: 280px; background: linear-gradient(135deg, #f97316 0%, #ea580c 100%); color: white; padding: 16px 28px; border-radius: 10px; text-decoration: none; font-weight: 700; font-size: 13.5px; text-align: center; box-shadow: 0 10px 25px -5px rgba(234, 88, 12, 0.4);">Launch Live App Prototype</a>
          <a href="https://youtu.be/-QOms8I-tbM" target="_blank" class="badge-btn" style="flex: 1; min-width: 240px; max-width: 280px; background-color: #111827; color: #ffffff; padding: 16px 28px; border-radius: 10px; text-decoration: none; font-weight: 700; font-size: 13.5px; text-align: center; border: 1px solid rgba(255,255,255,0.08); box-shadow: 0 10px 25px -5px rgba(0,0,0,0.4);">Watch Video Presentation</a>
          <div onclick="openPosterModal()" class="badge-btn" style="flex: 1; min-width: 240px; max-width: 280px; background-color: #374151; color: #e5e7eb; padding: 16px 28px; border-radius: 10px; font-weight: 700; font-size: 13.5px; text-align: center; border: 1px solid rgba(255,255,255,0.05); box-shadow: 0 10px 25px -5px rgba(0,0,0,0.2);">View Full Project Poster</div>
        </div>
      </div>

      <div style="display: flex; flex-wrap: wrap; gap: 24px;">
        <div style="flex: 1; min-width: 280px; background: linear-gradient(135deg, rgba(239, 68, 68, 0.01) 0%, rgba(239, 68, 68, 0.02) 100%); border: 1px solid rgba(239, 68, 68, 0.06); border-radius: 16px; padding: 28px;">
          <h4 style="margin-top: 0; color: #ef4444; font-size: 13px; font-weight: 700; text-transform: uppercase; letter-spacing: 1px; margin-bottom: 14px;">Challenges & UX Solutions</h4>
          <p style="font-size: 14px; line-height: 1.7; color: #cbd5e1; margin: 0;">
            <strong>The Challenge:</strong> Ensuring prompt posture warning alerts didn't disrupt the user's active cooking workflow split focus.
            <br><br>
            <strong>The Solution:</strong> Implemented subtle, non-intrusive sound layouts and progressive visual overlay alerts that auto-dismissed once correct body calibration was recorded.
          </p>
        </div>
        <div style="flex: 1; min-width: 280px; background: linear-gradient(135deg, rgba(34, 197, 94, 0.01) 0%, rgba(34, 197, 94, 0.02) 100%); border: 1px solid rgba(34, 197, 94, 0.06); border-radius: 16px; padding: 28px;">
          <h4 style="margin-top: 0; color: #22c55e; font-size: 13px; font-weight: 700; text-transform: uppercase; letter-spacing: 1px; margin-bottom: 14px;">Project Results & Feedback</h4>
          <p style="font-size: 14px; line-height: 1.7; color: #cbd5e1; margin: 0;">
            <strong>Outcomes:</strong> Live web dashboard evaluation runs tracked an average improvement in posture alignment and high user interface satisfaction.
            <br><br>
            <strong>Feedback:</strong> Peer testers confirmed that the clean layout telemetry structure made monitoring joint habits natural and stress-free.
          </p>
        </div>
      </div>

    </div>
  </div>

  <div id="case-study-2-elearn-ux-audit" style="padding-top: 20px; margin-bottom: 80px;">
    <div class="premium-card glow-blue" style="border-radius: 28px; padding: 45px; box-shadow: 0 40px 80px -20px rgba(0,0,0,0.6);">
      
      <div style="display: flex; flex-wrap: wrap; justify-content: space-between; align-items: flex-start; border-bottom: 1px solid rgba(255,255,255,0.05); padding-bottom: 28px; margin-bottom: 36px; gap: 16px;">
        <div>
          <h2 style="color: #ffffff; font-size: 26px; font-weight: 800; margin: 0; letter-spacing: -0.5px;">Case Study 2: Institutional eLearn UX Audit</h2>
          <p style="color: #38bdf8; font-size: 13px; font-weight: 700; margin: 8px 0 0 0; text-transform: uppercase; letter-spacing: 1px;">Learning Management Portal Optimization Study</p>
        </div>
        <span style="font-size: 12px; font-weight: 600; background-color: rgba(255,255,255,0.03); color: #cbd5e1; padding: 8px 20px; border-radius: 30px; border: 1px solid rgba(255,255,255,0.08);">Lead UX Auditor</span>
      </div>
      
      <div style="background: linear-gradient(135deg, rgba(56, 189, 248, 0.02) 0%, rgba(56, 189, 248, 0.03) 100%); border: 1px solid rgba(56, 189, 248, 0.08); border-radius: 16px; padding: 32px; margin-bottom: 40px;">
        <h4 style="margin-top: 0; color: #7dd3fc; font-size: 13px; font-weight: 700; text-transform: uppercase; letter-spacing: 1.5px; margin-bottom: 16px;">Project Overview & Context</h4>
        <p style="font-size: 15px; line-height: 1.75; color: #cbd5e1; margin-bottom: 20px;">
          <strong>The Problem:</strong> The existing university eLearn web interface suffers from severe navigation friction, counter-intuitive architecture, and redundant multi-click journey loops. Students routinely experience heavy cognitive fatigue trying to locate basic announcements, modular assignment submission dropboxes, and grading panels.
        </p>
        <p style="font-size: 15px; line-height: 1.75; color: #cbd5e1; margin-bottom: 0;">
          <strong>Project Goals & Value Proposition:</strong> This project functions as an intensive UI/UX overhaul. By running rigorous heuristic audits, cognitive walkthroughs, and restructuring user navigation architecture, the primary goal was to replace convoluted nested paths with a clean, centralized dashboard directory layout.
          <br><br>
          <strong>Target Audience:</strong> University undergraduate students, academic researchers, and lecturing faculties utilizing learning management portals daily.
        </p>
      </div>

      <h4 style="color: #ffffff; font-size: 12px; font-weight: 700; margin-bottom: 24px; text-transform: uppercase; letter-spacing: 2px;">Design Process & Audit Framework</h4>
      <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 20px; margin-bottom: 45px;">
        <div style="flex: 1; min-width: 220px; background-color: rgba(255,255,255,0.01); border: 1px solid rgba(255,255,255,0.03); border-radius: 16px; padding: 28px;">
          <strong style="color: #ffffff; font-size: 14px; display: block; margin-bottom: 10px;">Heuristic Evaluation</strong>
          <span style="font-size: 13px; line-height: 1.65; color: #94a3b8; display: block;">Evaluated the current portal against standard usability heuristics, identifying critical friction points in system visibility and consistency.</span>
        </div>
        <div style="flex: 1; min-width: 220px; background-color: rgba(255,255,255,0.01); border: 1px solid rgba(255,255,255,0.03); border-radius: 16px; padding: 28px;">
          <strong style="color: #ffffff; font-size: 14px; display: block; margin-bottom: 10px;">User Task Mapping</strong>
          <span style="font-size: 13px; line-height: 1.65; color: #94a3b8; display: block;">Plotted step-by-step user pathways to measure user behavior and click-counts during common tasks like accessing grades.</span>
        </div>
        <div style="flex: 1; min-width: 220px; background-color: rgba(255,255,255,0.01); border: 1px solid rgba(255,255,255,0.03); border-radius: 16px; padding: 28px;">
          <strong style="color: #ffffff; font-size: 14px; display: block; margin-bottom: 10px;">Wireframing & Layouts</strong>
          <span style="font-size: 13px; line-height: 1.65; color: #94a3b8; display: block;">Sketched a low-fidelity card layout structure to compress the multi-layered dashboard into a unified, responsive front-end screen.</span>
        </div>
      </div>

      <div style="background-color: rgba(255,255,255,0.01); border: 1px solid rgba(255,255,255,0.03); border-radius: 20px; padding: 35px; margin-bottom: 45px;">
        <div style="border-bottom: 1px solid rgba(255,255,255,0.05); padding-bottom: 16px; margin-bottom: 20px;">
          <h4 style="margin: 0; color: #ffffff; font-size: 17px; font-weight: 700; letter-spacing: -0.3px;">Empirical Usability Diagnostic Log</h4>
          <p style="font-size: 13px; color: #64748b; margin: 4px 0 0 0;">Comprehensive architectural defects tracked across the production system environment.</p>
        </div>
        
        <div class="audit-table-wrapper">
          <table class="audit-table">
            <thead>
              <tr>
                <th>Violation ID</th>
                <th>Heuristic Target</th>
                <th>Real-World Failure Mechanics</th>
                <th>Severity</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td style="color: #38bdf8; font-weight: 600;">V01</td>
                <td>H2: System & Real World</td>
                <td>System-facing database keys and strings leaked into prominent header templates.</td>
                <td><span style="background: rgba(245, 158, 11, 0.1); color: #f59e0b; padding: 2px 8px; border-radius: 4px; font-size: 11px;">Severity 2</span></td>
              </tr>
              <tr>
                <td style="color: #38bdf8; font-weight: 600;">V02</td>
                <td>H5: Error Prevention</td>
                <td>Intake information strings hard-coded into legal name entries, blocking user flexibility controls.</td>
                <td><span style="background: rgba(245, 158, 11, 0.1); color: #f59e0b; padding: 2px 8px; border-radius: 4px; font-size: 11px;">Severity 2</span></td>
              </tr>
              <tr>
                <td style="color: #38bdf8; font-weight: 600;">V03</td>
                <td>H4: Consistency Standards</td>
                <td>Directory filtration systems return blank screens for active upper-tier student accounts.</td>
                <td><span style="background: rgba(239, 68, 68, 0.1); color: #ef4444; padding: 2px 8px; border-radius: 4px; font-size: 11px;">Severity 3</span></td>
              </tr>
              <tr>
                <td style="color: #38bdf8; font-weight: 600;">V04</td>
                <td>H7: Efficiency of Use</td>
                <td>Workspace directories flooded with static, expired course cells with no archival triggers.</td>
                <td><span style="background: rgba(239, 68, 68, 0.1); color: #ef4444; padding: 2px 8px; border-radius: 4px; font-size: 11px;">Severity 3</span></td>
              </tr>
              <tr>
                <td style="color: #38bdf8; font-weight: 600;">V08</td>
                <td>H1: Visibility of Status</td>
                <td>Global generic `Messages 99+` notification badges combine urgent lecturer notes with basic student club logs.</td>
                <td><span style="background: rgba(245, 158, 11, 0.1); color: #f59e0b; padding: 2px 8px; border-radius: 4px; font-size: 11px;">Severity 2</span></td>
              </tr>
            </tbody>
          </table>
        </div>
      </div>

      <div style="background-color: rgba(255,255,255,0.01); border: 1px solid rgba(255,255,255,0.03); border-radius: 20px; padding: 40px; margin-bottom: 45px; text-align: center;">
        <h4 style="margin: 0 0 8px 0; color: #ffffff; font-size: 18px; font-weight: 700; letter-spacing: -0.3px;">Design Artefacts & Audited Layouts</h4>
        <p style="font-size: 14px; color: #64748b; margin: 0 0 28px 0;">Access the complete unedited usability assessment report mapping out system constraints and data triangulations.</p>
        <div style="display: flex; justify-content: center;">
          <div onclick="openReportModal()" class="badge-btn" style="flex: 1; min-width: 260px; max-width: 320px; background: linear-gradient(135deg, #38bdf8 0%, #0284c7 100%); color: #020617 !important; padding: 16px 28px; border-radius: 10px; font-weight: 700; font-size: 14px; text-align: center; box-shadow: 0 10px 25px -5px rgba(56, 189, 248, 0.3);">📋 View the Report Here</div>
        </div>
      </div>

      <div style="display: flex; flex-wrap: wrap; gap: 24px;">
        <div style="flex: 1; min-width: 280px; background: linear-gradient(135deg, rgba(239, 68, 68, 0.01) 0%, rgba(239, 68, 68, 0.02) 100%); border: 1px solid rgba(239, 68, 68, 0.08); border-radius: 16px; padding: 28px;">
          <h4 style="margin-top: 0; color: #ef4444; font-size: 13px; font-weight: 700; text-transform: uppercase; letter-spacing: 1px; margin-bottom: 14px;">Challenges & UX Solutions</h4>
          <p style="font-size: 14px; line-height: 1.7; color: #cbd5e1; margin: 0;">
            <strong>The Challenge:</strong> Consolidating extensive, fragmented module links into a small viewport without triggering secondary layout overcrowding.
            <br><br>
            <strong>The Solution:</strong> Applied an expandable web directory system that keeps primary folders prominent while dynamically grouping inner module links until clicked.
          </p>
        </div>
        <div style="flex: 1; min-width: 280px; background: linear-gradient(135deg, rgba(34, 197, 94, 0.01) 0%, rgba(34, 197, 94, 0.02) 100%); border: 1px solid rgba(34, 197, 94, 0.08); border-radius: 16px; padding: 28px;">
          <h4 style="margin-top: 0; color: #22c55e; font-size: 13px; font-weight: 700; text-transform: uppercase; letter-spacing: 1px; margin-bottom: 14px;">Project Results & Feedback</h4>
          <p style="font-size: 14px; line-height: 1.7; color: #cbd5e1; margin: 0;">
            <strong>Outcomes:</strong> Empirical validation runs recorded an immediate drop in manual task processing loops and execution delays.
            <br><br>
            <strong>Feedback:</strong> Student peer focus group checks confirmed that a contextual dashboard matrix feels more intuitive under high data volumes.
          </p>
        </div>
      </div>

    </div>
  </div>

  <div id="personal-challenges" style="padding-top: 20px; margin-bottom: 80px;">
    <div class="section-title-wrapper">
      <div class="section-bar" style="background: linear-gradient(#6366f1, #a855f7);"></div>
      <h2 style="color: #ffffff; font-size: 28px; font-weight: 700; margin: 0; letter-spacing: -0.5px;">Personal Challenges & Problem Solving</h2>
    </div>
    
    <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 24px; margin-bottom: 24px;">
      <div class="premium-card glow-blue" style="flex: 1; min-width: 320px; border-radius: 16px; padding: 32px;">
        <strong style="color: #ffffff; font-size: 15px; display: block; margin-bottom: 12px; border-bottom: 1px solid rgba(255,255,255,0.05); padding-bottom: 12px;">GitHub Layout Processing Collisions</strong>
        <p style="font-size: 14px; line-height: 1.7; color: #94a3b8; margin: 0;">
          <strong>Problem:</strong> Root standard layout wrapping caused theme processors to strip out native Markdown header elements (like # or ##).
          <br><br>
          <strong>Resolution:</strong> Refactored structural elements into explicit inline HTML layout components using encoded wrappers to completely bypass theme build interference.
        </p>
      </div>

      <div class="premium-card glow-blue" style="flex: 1; min-width: 320px; border-radius: 16px; padding: 32px;">
        <strong style="color: #ffffff; font-size: 15px; display: block; margin-bottom: 12px; border-bottom: 1px solid rgba(255,255,255,0.05); padding-bottom: 12px;">Theme Layout Banner Overrides</strong>
        <p style="font-size: 14px; line-height: 1.7; color: #94a3b8; margin: 0;">
          <strong>Problem:</strong> Default layout headers forced rigid green gradient branding boxes on desktop viewports.
          <br><br>
          <strong>Resolution:</strong> Injected targeted style element modifications to manually reset header containers with responsive asset URLs.
        </p>
      </div>

      <div class="premium-card glow-blue" style="flex: 1; min-width: 320px; border-radius: 16px; padding: 32px;">
        <strong style="color: #ffffff; font-size: 15px; display: block; margin-bottom: 12px; border-bottom: 1px solid rgba(255,255,255,0.05); padding-bottom: 12px;">Non-Intrusive Telemetry Alerts</strong>
        <p style="font-size: 14px; line-height: 1.7; color: #94a3b8; margin: 0;">
          <strong>Problem:</strong> ErgoChef+ warning windows disrupted physical user cooking flows.
          <br><br>
          <strong>Resolution:</strong> Restructured notification cycles using progressive visual overlays that clear as soon as posture metrics correct.
        </p>
      </div>
    </div>
    
    <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 24px;">
      <div class="premium-card glow-blue" style="flex: 1; min-width: 320px; border-radius: 16px; padding: 32px;">
        <strong style="color: #ffffff; font-size: 15px; display: block; margin-bottom: 12px; border-bottom: 1px solid rgba(255,255,255,0.05); padding-bottom: 12px;">Learning Portal Navigation Friction</strong>
        <p style="font-size: 14px; line-height: 1.7; color: #94a3b8; margin: 0;">
          <strong>Problem:</strong> Complex link nesting on eLearn websites increased user multi-click journey loops and cognitive loads.
          <br><br>
          <strong>Resolution:</strong> Designed a compressed, expandable grid framework to make common actions instantly accessible.
        </p>
      </div>

      <div class="premium-card glow-blue" style="flex: 1; min-width: 320px; border-radius: 16px; padding: 32px;">
        <strong style="color: #ffffff; font-size: 15px; display: block; margin-bottom: 12px; border-bottom: 1px solid rgba(255,255,255,0.05); padding-bottom: 12px;">Anchor Link Navigation Shifts</strong>
        <p style="font-size: 14px; line-height: 1.7; color: #94a3b8; margin: 0;">
          <strong>Problem:</strong> Traditional link clicks caused abrupt page snaps, lowering the overall presentation feel.
          <br><br>
          <strong>Resolution:</strong> Enabled root document scroll-behavior configurations to provide a fluid sliding transition.
        </p>
      </div>

      <div class="premium-card glow-blue" style="flex: 1; min-width: 320px; border-radius: 16px; padding: 32px;">
        <strong style="color: #ffffff; font-size: 15px; display: block; margin-bottom: 12px; border-bottom: 1px solid rgba(255,255,255,0.05); padding-bottom: 12px;">Viewport Adaptability Constraints</strong>
        <p style="font-size: 14px; line-height: 1.7; color: #94a3b8; margin: 0;">
          <strong>Problem:</strong> Rigid dimension styling scales skewed multi-column layout matrices on mobile interfaces.
          <br><br>
          <strong>Resolution:</strong> Standardized flex container parameters to wrap smoothly across varying devices.
        </p>
      </div>
    </div>
  </div>

  <hr style="height: 1px; border: none; background-color: rgba(255,255,255,0.05); margin: 60px 0;">

  <div id="submission" style="padding-top: 20px; margin-bottom: 60px;">
    <div class="premium-card glow-blue" style="border-radius: 20px; padding: 40px; display: flex; align-items: center; gap: 28px; flex-wrap: wrap;">
      <div style="background-color: rgba(255,255,255,0.02); padding: 20px; border-radius: 50%; border: 1px solid rgba(255,255,255,0.05); font-size: 22px;">📋</div>
      <div style="flex: 1; min-width: 260px;">
        <h3 style="color: #ffffff; font-size: 20px; font-weight: 700; margin: 0 0 10px 0;">Academic Integrity & Submission Verification</h3>
        <p style="font-size: 14.5px; color: #94a3b8; line-height: 1.7; margin: 0;">
          This web portfolio is submitted in strict alignment with university academic integrity code standards. All featured layout components, script configurations, and design narratives represent authentic project work completed during the academic semester term. Artificial intelligence assistive tooling was deployed exclusively to optimize grammatical layout properties.
        </p>
      </div>
    </div>
  </div>

  <div id="posterModal" class="custom-modal-overlay" onclick="closePosterModalFromOverlay(event)">
    <button class="custom-modal-close-btn" onclick="closePosterModal()">&times;</button>
    <div class="custom-modal-window" id="modalWindow">
      <img id="posterImg" class="custom-modal-content" src="https://github.com/malcolmjeremiah/malcolmjeremiah.github.io/blob/main/ErgoChef+%20(3).png?raw=true" alt="ErgoChef+ Project Poster" />
    </div>
  </div>

  <div id="reportModal" class="custom-modal-overlay" onclick="closeReportModalFromOverlay(event)">
    <button class="custom-modal-close-btn" onclick="closeReportModal()">&times;</button>
    <div class="report-modal-window">
      <iframe class="report-frame" src="22078778_Assignment1.pdf#toolbar=1&navpanes=1&scrollbar=1"></iframe>
    </div>
  </div>

</div>

<script>
  const posterModal = document.getElementById('posterModal');
  const reportModal = document.getElementById('reportModal');
  const modalWindow = document.getElementById('modalWindow');
  const posterImg = document.getElementById('posterImg');

  let isZoomed = false;
  let isDragging = false;
  let startX, startY;
  let translateX = 0, translateY = 0;

  /* Poster Modal Controls */
  function openPosterModal() {
    posterModal.classList.add('is-active');
    document.body.style.overflow = 'hidden'; 
    resetZoom();
  }

  function closePosterModal() {
    posterModal.classList.remove('is-active');
    document.body.style.overflow = ''; 
    resetZoom();
  }

  function closePosterModalFromOverlay(event) {
    if (event.target.id === 'posterModal') {
      closePosterModal();
    }
  }

  /* PDF Report Modal Controls */
  function openReportModal() {
    reportModal.classList.add('is-active');
    document.body.style.overflow = 'hidden';
  }

  document.addEventListener('keydown', (event) => {
    if (event.key === 'Escape') {
      closePosterModal();
      closeReportModal();
    }
  });

  function closeReportModal() {
    reportModal.classList.remove('is-active');
    document.body.style.overflow = '';
  }

  function closeReportModalFromOverlay(event) {
    if (event.target.id === 'reportModal') {
      closeReportModal();
    }
  }

  /* Zoom Mechanics Code Blueprint */
  modalWindow.addEventListener('click', (event) => {
    if (event.target.classList.contains('custom-modal-close-btn') || event.target.tagName === 'BUTTON') return;
    
    if (!isZoomed) {
      isZoomed = true;
      posterImg.style.cursor = 'zoom-out';
      
      const rect = modalWindow.getBoundingClientRect();
      const clickX = (event.clientX - rect.left) / rect.width;
      const clickY = (event.clientY - rect.top) / rect.height;
      
      posterImg.style.transformOrigin = `${clickX * 100}% ${clickY * 100}%`;
      posterImg.style.transform = 'scale(2.5)';
    } else {
      resetZoom();
    }
  });

  modalWindow.addEventListener('mousedown', (event) => {
    if (!isZoomed) return;
    isDragging = true;
    startX = event.clientX - translateX;
    startY = event.clientY - translateY;
  });

  window.addEventListener('mousemove', (event) => {
    if (!isDragging || !isZoomed) return;
    event.preventDefault();
    
    translateX = event.clientX - startX;
    translateY = event.clientY - startY;
    
    posterImg.style.transform = `scale(2.5) translate(${translateX / 2.5}px, ${translateY / 2.5}px)`;
  });

  window.addEventListener('mouseup', () => {
    isDragging = false;
  });

  modalWindow.addEventListener('touchstart', (event) => {
    if (!isZoomed || event.touches.length > 1) return;
    isDragging = true;
    startX = event.touches[0].clientX - translateX;
    startY = event.touches[0].clientY - translateY;
  });

  window.addEventListener('touchmove', (event) => {
    if (!isDragging || !isZoomed) return;
    translateX = event.touches[0].clientX - startX;
    translateY = event.touches[0].clientY - startY;
    posterImg.style.transform = `scale(2.5) translate(${translateX / 2.5}px, ${translateY / 2.5}px)`;
  });

  window.addEventListener('touchend', () => {
    isDragging = false;
  });

  function resetZoom() {
    isZoomed = false;
    isDragging = false;
    translateX = 0;
    translateY = 0;
    posterImg.style.cursor = 'zoom-in';
    posterImg.style.transform = 'scale(1)';
    posterImg.style.transformOrigin = 'center center';
  }
</script>
