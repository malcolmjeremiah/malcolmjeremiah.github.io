<style>
  /* Global page canvas modifications */
  html {
    scroll-behavior: smooth !important;
    background-color: #f8fafc !important;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif !important;
  }
  
  /* Reset default theme restrictions to unlock full wide desktop grid space */
  body {
    max-width: 1200px !important;
    padding: 20px !important;
    margin: 0 auto !important;
    background-color: #f8fafc !important;
  }
  
  .main-content {
    max-width: 100% !important;
    padding: 0 !important;
  }

  /* Header Graphic Banner Component styling */
  header.page-header {
    background-image: linear-gradient(rgba(15, 23, 42, 0.75), rgba(15, 23, 42, 0.85)), url('https://github.com/malcolmjeremiah/malcolmjeremiah.github.io/blob/main/1763479411435.jpeg?raw=true') !important;
    background-size: cover !important;
    background-position: center !important;
    padding: 6.5rem 2rem !important;
    text-align: center !important;
    border-radius: 12px !important;
    box-shadow: 0 10px 25px -5px rgba(15, 23, 42, 0.15), 0 8px 10px -6px rgba(15, 23, 42, 0.15) !important;
    border: 1px solid rgba(255, 255, 255, 0.08) !important;
  }
  
  header.page-header h1.project-name {
    display: block !important;
    color: #ffffff !important;
    font-size: 38px !important;
    font-weight: 800 !important;
    letter-spacing: -0.5px !important;
    text-shadow: 0 4px 12px rgba(0,0,0,0.4) !important;
    margin: 0 !important;
  }
  header.page-header h1.project-name::after {
    content: "MALCOLM JEREMIAH RICHARD";
  }
  
  header.page-header h2.project-tagline {
    display: block !important;
    color: #cbd5e1 !important;
    font-size: 14px !important;
    font-weight: 500 !important;
    text-shadow: 0 2px 6px rgba(0,0,0,0.4) !important;
    text-transform: uppercase !important;
    letter-spacing: 2px !important;
    margin-top: 14px !important;
    opacity: 0.95 !important;
  }
  header.page-header h2.project-tagline::after {
    content: "BSc (Hons) Information Technology Student | UI/UX Portfolio";
  }

  /* Utility classes to hide standard theme elements if necessary */
  header.page-header .btn { display: none !important; }
  
  /* Navigation Dashboard Component & Interactions */
  .nav-container {
    position: -webkit-sticky;
    position: sticky;
    top: 15px;
    z-index: 999;
    display: flex;
    justify-content: center;
    background-color: rgba(255, 255, 255, 0.9);
    -webkit-backdrop-filter: blur(16px);
    backdrop-filter: blur(16px);
    padding: 6px 16px;
    border-radius: 8px;
    border: 1px solid #e2e8f0;
    box-shadow: 0 4px 20px -2px rgba(0,0,0,0.05);
    margin-bottom: 35px;
  }

  .nav-btn {
    position: relative !important;
    white-space: nowrap !important;
    color: #475569 !important;
    padding: 10px 18px !important;
    border-radius: 6px !important;
    text-decoration: none !important;
    font-weight: 600 !important;
    font-size: 13px !important;
    display: inline-block !important;
    letter-spacing: 0.3px !important;
    transition: color 0.2s ease, background-color 0.2s ease !important;
  }
  .nav-btn::after {
    content: '' !important;
    position: absolute !important;
    bottom: 0 !important;
    left: 50% !important;
    width: 0 !important;
    height: 2px !important;
    background-color: #0f172a !important;
    transition: all 0.2s ease !important;
    transform: translateX(-50%) !important;
  }
  .nav-btn:hover {
    color: #0f172a !important;
    background-color: #f1f5f9 !important;
  }
  .nav-btn:hover::after {
    width: 80% !important;
  }

  /* Mobile Responsive Switch for Nav Dashboard */
  @media (max-width: 768px) {
    .nav-container {
      justify-content: flex-start !important;
      overflow-x: auto !important;
      -webkit-overflow-scrolling: touch !important;
      gap: 4px !important;
      padding: 6px 8px !important;
    }
    .nav-container::-webkit-scrollbar {
      display: none !important; /* Hide scrollbar for maximum screen space, intuitive swipe mechanics take over */
    }
    .nav-btn {
      padding: 10px 14px !important;
    }
  }

  .premium-card {
    transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1) !important;
  }
  .premium-card:hover {
    transform: translateY(-4px) !important;
    box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.05), 0 10px 10px -5px rgba(0, 0, 0, 0.04) !important;
    border-color: #cbd5e1 !important;
  }
  
  .badge-btn {
    transition: all 0.2s !important;
  }
  .badge-btn:hover {
    opacity: 0.9 !important;
    transform: scale(1.02) !important;
  }

  .poster-link {
    display: block !important;
    transition: transform 0.3s ease !important;
  }
  .poster-link:hover {
    transform: scale(1.03) !important;
  }
  .poster-img {
    transition: box-shadow 0.3s ease !important;
  }
  .poster-link:hover .poster-img {
    box-shadow: 0 12px 24px rgba(0,0,0,0.15) !important;
  }
</style>

<div style="margin-top: 30px;">

  <!-- Professional Slick Line Dashboard Navigation (With Mobile Overflow Prevention) -->
  <div class="nav-container">
    <a href="#who-i-am" class="nav-btn">Profile</a>
    <a href="#projects-overview" class="nav-btn">Featured Projects</a>
    <a href="#case-study-1-ergochef" class="nav-btn">Case 1: ErgoChef+</a>
    <a href="#case-study-2-elearn-ux-audit" class="nav-btn">Case 2: eLearn Audit</a>
    <a href="#personal-challenges" class="nav-btn">Challenges</a>
    <a href="#submission" class="nav-btn">Submission</a>
  </div>

  <div id="who-i-am" style="padding-top: 40px; margin-bottom: 20px;">
    <div style="display: flex; align-items: center; gap: 10px; margin-bottom: 20px;">
      <div style="width: 4px; height: 24px; background-color: #0f172a; border-radius: 2px;"></div>
      <h2 style="color: #0f172a; font-size: 24px; font-weight: 700; margin: 0; letter-spacing: -0.5px;">Who I Am</h2>
    </div>
    
    <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 24px;">
      <div class="premium-card" style="flex: 2; min-width: 320px; background-color: #ffffff; border: 1px solid #e2e8f0; border-radius: 12px; padding: 30px; box-shadow: 0 1px 3px rgba(0,0,0,0.02); display: flex; gap: 24px; align-items: center; flex-wrap: wrap;">
        <img src="https://raw.githubusercontent.com/malcolmjeremiah/malcolmjeremiah.github.io/main/WhatsApp%20Image%202026-07-03%20at%2010.14.22%20PM.jpeg" alt="Malcolm" style="width: 110px; height: 110px; border-radius: 50%; object-fit: cover; border: 4px solid #ffffff; box-shadow: 0 4px 14px rgba(15,23,42,0.12); flex-shrink: 0;" />
        <div style="flex: 1; min-width: 240px;">
          <p style="font-size: 15px; line-height: 1.7; color: #334155; margin: 0; font-weight: 400;">
            I am an <strong>Information Technology</strong> student specializing in software automation, data extraction, and user-centered workflow optimization. My design philosophy is rooted in <strong>functional minimalism</strong>: digital interfaces should actively reduce user cognitive load, mask complex database architecture, and adapt seamlessly to a user's real-world mental model. I bridge the gap between back-end technical scripting logic and clean, empathetic front-end layout execution.
          </p>
        </div>
      </div>

      <div class="premium-card" style="flex: 1; min-width: 260px; background-color: #ffffff; border: 1px solid #e2e8f0; border-radius: 12px; padding: 24px; box-shadow: 0 1px 3px rgba(0,0,0,0.02); display: flex; flex-direction: column; justify-content: center;">
        <h4 style="margin-top: 0; margin-bottom: 12px; color: #64748b; font-size: 11px; font-weight: 700; text-transform: uppercase; letter-spacing: 1px;">🛠️ Skill Stack</h4>
        <div style="margin-bottom: 20px; display: flex; flex-wrap: wrap; gap: 6px;">
          <span style="font-size: 12px; font-weight: 600; background-color: #f1f5f9; color: #334155; padding: 6px 12px; border-radius: 6px; border: 1px solid #e2e8f0;">Python</span>
          <span style="font-size: 12px; font-weight: 600; background-color: #f1f5f9; color: #334155; padding: 6px 12px; border-radius: 6px; border: 1px solid #e2e8f0;">PHP</span>
          <span style="font-size: 12px; font-weight: 600; background-color: #f1f5f9; color: #334155; padding: 6px 12px; border-radius: 6px; border: 1px solid #e2e8f0;">JavaScript</span>
          <span style="font-size: 12px; font-weight: 600; background-color: #f1f5f9; color: #334155; padding: 6px 12px; border-radius: 6px; border: 1px solid #e2e8f0;">GIT</span>
        </div>
        <h4 style="margin-top: 0; margin-bottom: 12px; color: #64748b; font-size: 11px; font-weight: 700; text-transform: uppercase; letter-spacing: 1px;">📐 Methods</h4>
        <div style="display: flex; flex-wrap: wrap; gap: 6px;">
          <span style="font-size: 12px; font-weight: 600; background-color: #f8fafc; color: #475569; padding: 6px 12px; border-radius: 6px; border: 1px solid #e2e8f0;">Heuristic Evaluation</span>
          <span style="font-size: 12px; font-weight: 600; background-color: #f8fafc; color: #475569; padding: 6px 12px; border-radius: 6px; border: 1px solid #e2e8f0;">Cognitive Walkthrough</span>
          <span style="font-size: 12px; font-weight: 600; background-color: #f8fafc; color: #475569; padding: 6px 12px; border-radius: 6px; border: 1px solid #e2e8f0;">Task Mapping</span>
        </div>
      </div>
    </div>
  </div>

  <div id="projects-overview" style="padding-top: 50px;">
    <div style="display: flex; align-items: center; gap: 10px; margin-bottom: 20px;">
      <div style="width: 4px; height: 24px; background-color: #0f172a; border-radius: 20px;"></div>
      <h2 style="color: #0f172a; font-size: 24px; font-weight: 700; margin: 0; letter-spacing: -0.5px;">Featured Projects</h2>
    </div>
    
    <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 24px;">
      <div class="premium-card" style="flex: 1; min-width: 300px; background-color: #ffffff; border: 1px solid #e2e8f0; border-radius: 12px; padding: 28px; box-shadow: 0 1px 3px rgba(0,0,0,0.02); display: flex; flex-direction: column; justify-content: space-between;">
        <div>
          <span style="font-size: 10px; font-weight: 700; background-color: #fff7ed; color: #c2410c; padding: 6px 12px; border-radius: 20px; display: inline-block; margin-bottom: 16px; text-transform: uppercase; letter-spacing: 0.5px; border: 1px solid #ffedd5;">Group Case Study</span>
          <h3 style="margin: 0 0 10px 0; font-size: 19px; color: #0f172a; font-weight: 700; letter-spacing: -0.3px;">ErgoChef+: AI Ergonomic Assistant</h3>
          <p style="font-size: 13.5px; line-height: 1.6; color: #475569; margin: 0 0 20px 0;">An AI-enabled kitchen ecosystem utilizing advanced posture-sensing technology to mitigate ergonomic stress and long-term musculoskeletal fatigue for cooks.</p>
        </div>
        <div style="border-top: 1px solid #f1f5f9; padding-top: 16px; display: flex; align-items: center; justify-content: space-between;">
          <div style="font-size: 12.5px; color: #334155;"><strong>Role:</strong> Lead UI & Interaction Designer</div>
          <a href="#case-study-1-ergochef" style="font-size: 13.5px; font-weight: 700; color: #ea580c; text-decoration: none;">Explore Case →</a>
        </div>
      </div>
      
      <div class="premium-card" style="flex: 1; min-width: 300px; background-color: #ffffff; border: 1px solid #e2e8f0; border-radius: 12px; padding: 28px; box-shadow: 0 1px 3px rgba(0,0,0,0.02); display: flex; flex-direction: column; justify-content: space-between;">
        <div>
          <span style="font-size: 10px; font-weight: 700; background-color: #f0f9ff; color: #0366d6; padding: 6px 12px; border-radius: 20px; display: inline-block; margin-bottom: 16px; text-transform: uppercase; letter-spacing: 0.5px; border: 1px solid #e0f2fe;">Individual Case Study</span>
          <h3 style="margin: 0 0 10px 0; font-size: 19px; color: #0f172a; font-weight: 700; letter-spacing: -0.3px;">Institutional eLearn UX Audit</h3>
          <p style="font-size: 13.5px; line-height: 1.6; color: #475569; margin: 0 0 20px 0;">A comprehensive heuristic evaluation and interface restructuring of the university portal to eliminate navigation friction and multi-click journey loops for students.</p>
        </div>
        <div style="border-top: 1px solid #f1f5f9; padding-top: 16px; display: flex; align-items: center; justify-content: space-between;">
          <div style="font-size: 12.5px; color: #334155;"><strong>Role:</strong> Lead UX Auditor</div>
          <a href="#case-study-2-elearn-ux-audit" style="font-size: 13.5px; font-weight: 700; color: #0284c7; text-decoration: none;">Explore Case →</a>
        </div>
      </div>
    </div>
  </div>

  <div id="case-study-1-ergochef" style="padding-top: 60px;">
    <div style="background-color: #ffffff; border: 1px solid #e2e8f0; border-radius: 14px; padding: 35px; box-shadow: 0 4px 6px -1px rgba(0,0,0,0.02);">
      
      <div style="display: flex; flex-wrap: wrap; justify-content: space-between; align-items: flex-start; border-bottom: 1px solid #f1f5f9; padding-bottom: 20px; margin-bottom: 24px; gap: 12px;">
        <div>
          <h2 style="color: #0f172a; font-size: 24px; font-weight: 800; margin: 0; letter-spacing: -0.5px;">🍳 Case Study 1: ErgoChef+</h2>
          <p style="color: #64748b; font-size: 14px; margin: 4px 0 0 0;">AI-Powered Context Cooking Ecosystem</p>
        </div>
        <span style="font-size: 12px; font-weight: 600; background-color: #f8fafc; color: #334155; padding: 8px 16px; border-radius: 8px; border: 1px solid #e2e8f0; box-shadow: 0 1px 2px rgba(0,0,0,0.02);">Role: Lead UI & Interaction Designer</span>
      </div>
      
      <div style="background-color: #fdf8f5; border: 1px solid #f9ebe2; border-radius: 10px; padding: 24px; margin-bottom: 30px;">
        <h4 style="margin-top: 0; color: #c2410c; font-size: 15px; font-weight: 700; margin-bottom: 10px;">📋 Project Overview & Context</h4>
        <p style="font-size: 14px; line-height: 1.6; color: #334155; margin-bottom: 12px;">
          <strong>The Problem:</strong> Cooking involves highly repetitive, physically demanding actions like bending, chopping, stirring, and prolonged standing. These movements generate heavy ergonomic stress, muscle fatigue, and musculoskeletal strain. Existing smart tools automate cooking tasks but completely ignore the chef's posture and long-term joint health.
        </p>
        <p style="font-size: 14px; line-height: 1.6; color: #334155; margin-bottom: 0;">
          <strong>Project Goals & Value Proposition:</strong> ErgoChef+ integrates AI-driven posture detection, non-intrusive reminders, and personalized ergonomic reports. The goal is to provide real-time guidance to adapt to diverse cooking contexts and establish healthy, long-term kitchen habits.
          <br><br>
          <strong>Target Audience:</strong> Busy home cooks, culinary professionals, and elderly or diverse users prone to physical kitchen fatigue.
        </p>
      </div>

      <h4 style="color: #0f172a; font-size: 15px; font-weight: 700; margin-bottom: 16px; text-transform: uppercase; letter-spacing: 0.5px;">📐 Design Process & Iterative Framework</h4>
      <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 16px; margin-bottom: 30px;">
        <div style="flex: 1; min-width: 220px; background-color: #f8fafc; border: 1px solid #e2e8f0; border-radius: 8px; padding: 20px;">
          <strong style="color: #0f172a; font-size: 14px; display: block; margin-bottom: 8px;">1. Research & Discovery</strong>
          <span style="font-size: 13px; line-height: 1.6; color: #475569; display: block;">Conducted quantitative user surveys and qualitative interviews to map baseline physical discomfort zones during food prep.</span>
        </div>
        <div style="flex: 1; min-width: 220px; background-color: #f8fafc; border: 1px solid #e2e8f0; border-radius: 8px; padding: 20px;">
          <strong style="color: #0f172a; font-size: 14px; display: block; margin-bottom: 8px;">2. Ideation & Sketches</strong>
          <span style="font-size: 13px; line-height: 1.6; color: #475569; display: block;">Sketched low-fidelity kitchen spatial layouts and camera-to-app physical telemetry interactions on paper.</span>
        </div>
        <div style="flex: 1; min-width: 220px; background-color: #f8fafc; border: 1px solid #e2e8f0; border-radius: 8px; padding: 20px;">
          <strong style="color: #0f172a; font-size: 14px; display: block; margin-bottom: 8px;">3. Storyboarding</strong>
          <span style="font-size: 13px; line-height: 1.6; color: #475569; display: block;">Mapped out contextual user flow scenarios to establish how and when the system alerts a user to change their physical posture.</span>
        </div>
        <div style="flex: 1; min-width: 220px; background-color: #f8fafc; border: 1px solid #e2e8f0; border-radius: 8px; padding: 20px;">
          <strong style="color: #0f172a; font-size: 14px; display: block; margin-bottom: 8px;">4. High-Fi Prototyping</strong>
          <span style="font-size: 13px; line-height: 1.6; color: #475569; display: block;">Translated layouts into a functional, live web platform using Lovable to track real-time visual tracking data.</span>
        </div>
      </div>

      <!-- Updated Media Area with Clickable Poster and Dynamic Layout -->
      <div style="background-color: #f8fafc; border: 1px solid #e2e8f0; border-radius: 10px; padding: 24px; margin-bottom: 30px; display: flex; flex-wrap: wrap; justify-content: space-between; align-items: center; gap: 24px;">
        <div style="flex: 1; min-width: 280px; max-width: 480px;">
          <h4 style="margin-top: 0; color: #0f172a; font-size: 15px; font-weight: 700; margin-bottom: 6px;">🎨 Design Artefacts & Live Media</h4>
          <p style="font-size: 13px; color: #475569; margin-bottom: 20px;">Explore the production-ready application layout interface running spatial computer vision logic live from your system dashboard.</p>
          <div style="display: flex; flex-direction: column; gap: 10px;">
            <a href="https://ergo-chef-journey.lovable.app/" target="_blank" class="badge-btn" style="background-color: #ea580c; color: white; padding: 12px 20px; border-radius: 6px; text-decoration: none; font-weight: 700; font-size: 13px; text-align: center; box-shadow: 0 4px 6px -1px rgba(234, 88, 12, 0.2);">🌐 Launch Live App Prototype</a>
            <a href="https://youtu.be/-QOms8I-tbM" target="_blank" class="badge-btn" style="background-color: #0f172a; color: white; padding: 12px 20px; border-radius: 6px; text-decoration: none; font-weight: 700; font-size: 13px; text-align: center; box-shadow: 0 4px 6px -1px rgba(15, 23, 42, 0.2);">📺 Watch Video Presentation</a>
            <a href="https://github.com/malcolmjeremiah/malcolmjeremiah.github.io/blob/main/ErgoChef+%20(3).png?raw=true" target="_blank" class="badge-btn" style="background-color: #475569; color: white; padding: 12px 20px; border-radius: 6px; text-decoration: none; font-weight: 700; font-size: 13px; text-align: center; box-shadow: 0 4px 6px -1px rgba(71, 85, 105, 0.2);">📄 View Full Project Poster</a>
          </div>
        </div>
        <div style="flex: 1; min-width: 240px; display: flex; justify-content: center;">
          <a href="https://github.com/malcolmjeremiah/malcolmjeremiah.github.io/blob/main/ErgoChef+%20(3).png?raw=true" target="_blank" class="poster-link" title="Click to view high-resolution version">
            <img class="poster-img" src="https://github.com/malcolmjeremiah/malcolmjeremiah.github.io/blob/main/ErgoChef+%20(3).png?raw=true" alt="ErgoChef+ Project Poster" style="width: 100%; max-width: 240px; height: auto; border-radius: 8px; border: 1px solid #cbd5e1; box-shadow: 0 4px 6px rgba(0,0,0,0.05);" />
          </a>
        </div>
      </div>

      <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 20px;">
        <div style="flex: 1; min-width: 280px; background-color: #fef2f2; border: 1px solid #fee2e2; border-radius: 10px; padding: 24px;">
          <h4 style="margin-top: 0; color: #991b1b; font-size: 15px; font-weight: 700; margin-bottom: 12px;">⚠️ Challenges & UX Solutions</h4>
          <p style="font-size: 13.5px; line-height: 1.6; color: #374151; margin: 0;">
            <strong>The Challenge:</strong> Ensuring prompt posture warning alerts didn't disrupt the user's active cooking workflow split focus.
            <br><br>
            <strong>The Solution:</strong> Implemented subtle, non-intrusive sound layouts and progressive visual overlay alerts that auto-dismissed once correct body calibration was recorded.
          </p>
        </div>
        <div style="flex: 1; min-width: 280px; background-color: #f0fdf4; border: 1px solid #dcfce7; border-radius: 10px; padding: 24px;">
          <h4 style="margin-top: 0; color: #166534; font-size: 15px; font-weight: 700; margin-bottom: 12px;">🚀 Project Results & Feedback</h4>
          <p style="font-size: 13.5px; line-height: 1.6; color: #374151; margin: 0;">
            <strong>Outcomes:</strong> Live web dashboard evaluation runs tracked an average improvement in posture alignment and high user interface satisfaction.
            <br><br>
            <strong>Feedback:</strong> Peer testers confirmed that the clean layout telemetry structure made monitoring joint habits natural and stress-free.
          </p>
        </div>
      </div>

    </div>
  </div>

  <div id="case-study-2-elearn-ux-audit" style="padding-top: 40px;">
    <div style="background-color: #ffffff; border: 1px solid #e2e8f0; border-radius: 14px; padding: 35px; box-shadow: 0 4px 6px -1px rgba(0,0,0,0.02);">
      
      <div style="display: flex; flex-wrap: wrap; justify-content: space-between; align-items: flex-start; border-bottom: 1px solid #f1f5f9; padding-bottom: 20px; margin-bottom: 24px; gap: 12px;">
        <div>
          <h2 style="color: #0f172a; font-size: 24px; font-weight: 800; margin: 0; letter-spacing: -0.5px;">📚 Case Study 2: Institutional eLearn UX Audit</h2>
          <p style="color: #64748b; font-size: 14px; margin: 4px 0 0 0;">Learning Management Portal Optimization Study</p>
        </div>
        <span style="font-size: 12px; font-weight: 600; background-color: #f8fafc; color: #334155; padding: 8px 16px; border-radius: 8px; border: 1px solid #e2e8f0; box-shadow: 0 1px 2px rgba(0,0,0,0.02);">Role: Lead UX Auditor</span>
      </div>
      
      <div style="background-color: #f0f7ff; border: 1px solid #e0f2fe; border-radius: 10px; padding: 24px; margin-bottom: 30px;">
        <h4 style="margin-top: 0; color: #0366d6; font-size: 15px; font-weight: 700; margin-bottom: 10px;">📋 Project Overview & Context</h4>
        <p style="font-size: 14px; line-height: 1.6; color: #334155; margin-bottom: 12px;">
          <strong>The Problem:</strong> The existing university eLearn web interface suffers from severe navigation friction, counter-intuitive architecture, and redundant multi-click journey loops. Students routinely experience heavy cognitive fatigue trying to locate basic announcements, modular assignment submission dropboxes, and grading panels.
        </p>
        <p style="font-size: 14px; line-height: 1.6; color: #334155; margin-bottom: 0;">
          <strong>Project Goals & Value Proposition:</strong> This project functions as an intensive UI/UX overhaul. By running rigorous heuristic audits, cognitive walkthroughs, and restructuring user navigation architecture, the primary goal was to replace convoluted nested paths with a clean, centralized dashboard directory layout.
          <br><br>
          <strong>Target Audience:</strong> University undergraduate students, academic researchers, and lecturing faculties utilizing learning management portals daily.
        </p>
      </div>

      <h4 style="color: #0f172a; font-size: 15px; font-weight: 700; margin-bottom: 16px; text-transform: uppercase; letter-spacing: 0.5px;">📐 Design Process & Audit Framework</h4>
      <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 16px; margin-bottom: 30px;">
        <div style="flex: 1; min-width: 220px; background-color: #f8fafc; border: 1px solid #e2e8f0; border-radius: 8px; padding: 20px;">
          <strong style="color: #0f172a; font-size: 14px; display: block; margin-bottom: 8px;">1. Heuristic Evaluation</strong>
          <span style="font-size: 13px; line-height: 1.6; color: #475569; display: block;">Evaluated the current portal against standard usability heuristics, identifying critical friction points in system visibility and consistency.</span>
        </div>
        <div style="flex: 1; min-width: 220px; background-color: #f8fafc; border: 1px solid #e2e8f0; border-radius: 8px; padding: 20px;">
          <strong style="color: #0f172a; font-size: 14px; display: block; margin-bottom: 8px;">2. User Task Mapping</strong>
          <span style="font-size: 13px; line-height: 1.6; color: #475569; display: block;">Plotted step-by-step user pathways to measure user behavior and click-counts during common tasks like accessing grades.</span>
        </div>
        <div style="flex: 1; min-width: 220px; background-color: #f8fafc; border: 1px solid #e2e8f0; border-radius: 8px; padding: 20px;">
          <strong style="color: #0f172a; font-size: 14px; display: block; margin-bottom: 8px;">3. Wireframing & Layouts</strong>
          <span style="font-size: 13px; line-height: 1.6; color: #475569; display: block;">Sketched a low-fidelity card layout structure to compress the multi-layered dashboard into a unified, responsive front-end screen.</span>
        </div>
      </div>

      <div style="background-color: #f8fafc; border: 1px solid #e2e8f0; border-radius: 10px; padding: 24px; margin-bottom: 30px;">
        <h4 style="margin-top: 0; color: #0f172a; font-size: 15px; font-weight: 700; margin-bottom: 6px;">🎨 Design Artefacts & Audited Layouts</h4>
        <p style="font-size: 13px; color: #475569; margin-bottom: 16px;">Review the wireframes, card-sorting directories, navigation matrices, and user journey optimization wireframes compiled during the heuristic audit phase.</p>
        <div style="display: flex; flex-wrap: wrap; gap: 10px;">
          <span style="background-color: #ffffff; border: 1px solid #cbd5e1; color: #1e293b; padding: 10px 16px; border-radius: 6px; font-size: 13px; font-weight: 600; box-shadow: 0 1px 2px rgba(0,0,0,0.02); display: inline-block;">📄 Usability Mapping Report.pdf</span>
          <span style="background-color: #ffffff; border: 1px solid #cbd5e1; color: #1e293b; padding: 10px 16px; border-radius: 6px; font-size: 13px; font-weight: 600; box-shadow: 0 1px 2px rgba(0,0,0,0.02); display: inline-block;">📐 Optimized Architecture Wireframes</span>
        </div>
      </div>

      <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 20px;">
        <div style="flex: 1; min-width: 280px; background-color: #fff5f5; border: 1px solid #ffe3e3; border-radius: 10px; padding: 24px;">
          <h4 style="margin-top: 0; color: #c53030; font-size: 15px; font-weight: 700; margin-bottom: 12px;">⚠️ Challenges & UX Solutions</h4>
          <p style="font-size: 13.5px; line-height: 1.6; color: #374151; margin: 0;">
            <strong>The Challenge:</strong> Consolidating extensive, fragmented module links into a small viewport without triggering secondary layout overcrowding.
            <br><br>
            <strong>The Solution:</strong> Applied an expandable web directory system that keeps primary folders prominent while dynamically grouping inner module links until clicked.
          </p>
        </div>
        <div style="flex: 1; min-width: 280px; background-color: #f0fff4; border: 1px solid #c6f6d5; border-radius: 10px; padding: 24px;">
          <h4 style="margin-top: 0; color: #22543d; font-size: 15px; font-weight: 700; margin-bottom: 12px;">🚀 Project Results & Feedback</h4>
          <p style="font-size: 13.5px; line-height: 1.6; color: #374151; margin: 0;">
            <strong>Outcomes:</strong> Walkthrough testing recorded a notable drop in the average time required to complete assignment lookups.
            <br><br>
            <strong>Feedback:</strong> Student peer groups reported that the simplified card framework felt significantly more modern, responsive, and intuitive.
          </p>
        </div>
      </div>

    </div>
  </div>

  <div id="personal-challenges" style="padding-top: 60px;">
    <div style="display: flex; align-items: center; gap: 10px; margin-bottom: 20px;">
      <div style="width: 4px; height: 24px; background-color: #0f172a; border-radius: 20px;"></div>
      <h2 style="color: #0f172a; font-size: 24px; font-weight: 700; margin: 0; letter-spacing: -0.5px;">Personal Challenges & Problem Solving</h2>
    </div>
    
    <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 20px; margin-bottom: 20px;">
      <div class="premium-card" style="flex: 1; min-width: 320px; background-color: #ffffff; border: 1px solid #e2e8f0; border-radius: 12px; padding: 24px; box-shadow: 0 1px 3px rgba(0,0,0,0.02);">
        <strong style="color: #0f172a; font-size: 14.5px; display: block; margin-bottom: 8px; border-bottom: 1px solid #f1f5f9; padding-bottom: 8px;">1. GitHub Layout Processing Collisions</strong>
        <p style="font-size: 13.5px; line-height: 1.6; color: #475569; margin: 0;">
          <strong>Problem:</strong> Root standard layout wrapping caused theme processors to strip out native Markdown header elements (like # or ##).
          <br>
          <strong>Resolution:</strong> Refactored structural elements into explicit inline HTML layout components using encoded wrappers to completely bypass theme build interference.
        </p>
      </div>

      <div class="premium-card" style="flex: 1; min-width: 320px; background-color: #ffffff; border: 1px solid #e2e8f0; border-radius: 12px; padding: 24px; box-shadow: 0 1px 3px rgba(0,0,0,0.02);">
        <strong style="color: #0f172a; font-size: 14.5px; display: block; margin-bottom: 8px; border-bottom: 1px solid #f1f5f9; padding-bottom: 8px;">2. Theme Layout Banner Overrides</strong>
        <p style="font-size: 13.5px; line-height: 1.6; color: #475569; margin: 0;">
          <strong>Problem:</strong> Default layout headers forced rigid green gradient branding boxes on desktop viewports.
          <br>
          <strong>Resolution:</strong> Injected targeted style element modifications to manually reset header containers with responsive asset URLs.
        </p>
      </div>

      <div class="premium-card" style="flex: 1; min-width: 320px; background-color: #ffffff; border: 1px solid #e2e8f0; border-radius: 12px; padding: 24px; box-shadow: 0 1px 3px rgba(0,0,0,0.02);">
        <strong style="color: #0f172a; font-size: 14.5px; display: block; margin-bottom: 8px; border-bottom: 1px solid #f1f5f9; padding-bottom: 8px;">3. Non-Intrusive Telemetry Alerts</strong>
        <p style="font-size: 13.5px; line-height: 1.6; color: #475569; margin: 0;">
          <strong>Problem:</strong> ErgoChef+ warning windows disrupted physical user cooking flows.
          <br>
          <strong>Resolution:</strong> Restructured notification cycles using progressive visual overlays that clear as soon as posture metrics correct.
        </p>
      </div>
    </div>
    
    <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 20px;">
      <div class="premium-card" style="flex: 1; min-width: 320px; background-color: #ffffff; border: 1px solid #e2e8f0; border-radius: 12px; padding: 24px; box-shadow: 0 1px 3px rgba(0,0,0,0.02);">
        <strong style="color: #0f172a; font-size: 14.5px; display: block; margin-bottom: 8px; border-bottom: 1px solid #f1f5f9; padding-bottom: 8px;">4. Learning Portal Navigation Friction</strong>
        <p style="font-size: 13.5px; line-height: 1.6; color: #475569; margin: 0;">
          <strong>Problem:</strong> Complex link nesting on eLearn websites increased user multi-click journey loops and cognitive loads.
          <br>
          <strong>Resolution:</strong> Designed a compressed, expandable grid framework to make common actions instantly accessible.
        </p>
      </div>

      <div class="premium-card" style="flex: 1; min-width: 320px; background-color: #ffffff; border: 1px solid #e2e8f0; border-radius: 12px; padding: 24px; box-shadow: 0 1px 3px rgba(0,0,0,0.02);">
        <strong style="color: #0f172a; font-size: 14.5px; display: block; margin-bottom: 8px; border-bottom: 1px solid #f1f5f9; padding-bottom: 8px;">5. Anchor Link Navigation Jumps</strong>
        <p style="font-size: 13.5px; line-height: 1.6; color: #475569; margin: 0;">
          <strong>Problem:</strong> Traditional link clicks caused abrupt page snaps, lowering the overall presentation feel.
          <br>
          <strong>Resolution:</strong> Enabled root document scroll-behavior configurations to provide a fluid sliding transition.
        </p>
      </div>

      <div class="premium-card" style="flex: 1; min-width: 320px; background-color: #ffffff; border: 1px solid #e2e8f0; border-radius: 12px; padding: 24px; box-shadow: 0 1px 3px rgba(0,0,0,0.02);">
        <strong style="color: #0f172a; font-size: 14.5px; display: block; margin-bottom: 8px; border-bottom: 1px solid #f1f5f9; padding-bottom: 8px;">6. Viewport Adaptability Constraints</strong>
        <p style="font-size: 13.5px; line-height: 1.6; color: #475569; margin: 0;">
          <strong>Problem:</strong> Rigid dimension styling scales skewed multi-column layout matrices on mobile interfaces.
          <br>
          <strong>Resolution:</strong> Standardized flex container parameters to wrap smoothly across varying devices.
        </p>
      </div>
    </div>
  </div>

  <hr style="height: 1px; border: none; background-color: #e2e8f0; margin: 50px 0;">

  <div id="submission" style="padding-top: 20px; margin-bottom: 60px;">
    <div style="background-color: #ffffff; border: 1px solid #e2e8f0; border-radius: 12px; padding: 30px; box-shadow: 0 4px 6px -1px rgba(0,0,0,0.02); display: flex; align-items: center; gap: 20px; flex-wrap: wrap;">
      <div style="background-color: #f8fafc; padding: 15px; border-radius: 50%; border: 1px solid #e2e8f0;">📋</div>
      <div style="flex: 1; min-width: 260px;">
        <h3 style="color: #0f172a; font-size: 18px; font-weight: 700; margin: 0 0 6px 0;">Academic Integrity & Submission Verification</h3>
        <p style="font-size: 14px; color: #475569; line-height: 1.6; margin: 0;">
          This web portfolio is submitted in strict alignment with university academic integrity code standards. All featured layout components, script configurations, and design narratives represent authentic project work completed during the academic semester term.
        </p>
      </div>
    </div>
  </div>

</div>
