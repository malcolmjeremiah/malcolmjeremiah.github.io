<style>
  /* Global page canvas modifications */
  html {
    scroll-behavior: smooth !important;
    background-color: #0b0f19 !important;
    font-family: -apple-system, BlinkMacSystemFont, "SF Pro Display", "Segoe UI", Roboto, Helvetica, Arial, sans-serif !important;
    color: #f1f5f9 !important;
  }
  
  /* Reset default theme restrictions to unlock full wide desktop grid space */
  body {
    max-width: 1100px !important;
    padding: 40px 20px !important;
    margin: 0 auto !important;
    background-color: #0b0f19 !important;
  }
  
  .main-content {
    max-width: 100% !important;
    padding: 0 !important;
  }

  /* Premium Header Banner Styling */
  header.page-header {
    background-image: linear-gradient(rgba(11, 15, 25, 0.85), rgba(11, 15, 25, 0.95)), url('https://github.com/malcolmjeremiah/malcolmjeremiah.github.io/blob/main/1763479411435.jpeg?raw=true') !important;
    background-size: cover !important;
    background-position: center !important;
    padding: 7rem 2rem !important;
    text-align: center !important;
    border-radius: 16px !important;
    box-shadow: 0 20px 40px -15px rgba(0, 0, 0, 0.5) !important;
    border: 1px solid rgba(255, 255, 255, 0.05) !important;
  }
  
  header.page-header h1.project-name {
    display: block !important;
    color: #ffffff !important;
    font-size: 42px !important;
    font-weight: 800 !important;
    letter-spacing: -1px !important;
    margin: 0 !important;
  }
  header.page-header h1.project-name::after {
    content: "MALCOLM JEREMIAH RICHARD";
  }
  
  header.page-header h2.project-tagline {
    display: block !important;
    color: #94a3b8 !important;
    font-size: 13px !important;
    font-weight: 600 !important;
    text-transform: uppercase !important;
    letter-spacing: 3px !important;
    margin-top: 16px !important;
  }
  header.page-header h2.project-tagline::after {
    content: "BSc (Hons) Information Technology Student | UI/UX Portfolio";
  }

  header.page-header .btn { display: none !important; }
  
  /* Premium Line Dashboard Navigation Component */
  .nav-container {
    position: -webkit-sticky;
    position: sticky;
    top: 20px;
    z-index: 999;
    display: flex;
    justify-content: center;
    background-color: rgba(15, 23, 42, 0.75);
    -webkit-backdrop-filter: blur(20px);
    backdrop-filter: blur(20px);
    padding: 4px 8px;
    border-radius: 30px;
    border: 1px solid rgba(255, 255, 255, 0.08);
    box-shadow: 0 10px 30px -10px rgba(0, 0, 0, 0.5);
    margin-bottom: 60px;
  }

  .nav-btn {
    position: relative !important;
    white-space: nowrap !important;
    color: #94a3b8 !important;
    padding: 12px 24px !important;
    border-radius: 20px !important;
    text-decoration: none !important;
    font-weight: 600 !important;
    font-size: 13px !important;
    display: inline-block !important;
    letter-spacing: 0.2px !important;
    transition: all 0.25s cubic-bezier(0.4, 0, 0.2, 1) !important;
  }
  
  .nav-btn:hover {
    color: #ffffff !important;
    background-color: rgba(255, 255, 255, 0.05) !important;
  }
  
  .nav-btn::after {
    content: '' !important;
    position: absolute !important;
    bottom: 6px !important;
    left: 50% !important;
    width: 0 !important;
    height: 2px !important;
    background-color: #f1f5f9 !important;
    transition: all 0.25s ease !important;
    transform: translateX(-50%) !important;
  }
  .nav-btn:hover::after {
    width: 40% !important;
  }

  @media (max-width: 768px) {
    .nav-container {
      justify-content: flex-start !important;
      overflow-x: auto !important;
      -webkit-overflow-scrolling: touch !important;
      border-radius: 12px !important;
      padding: 4px !important;
    }
    .nav-container::-webkit-scrollbar {
      display: none !important;
    }
    .nav-btn {
      padding: 12px 16px !important;
    }
  }

  /* Premium Interaction Cards Layout */
  .premium-card {
    background-color: #111827 !important;
    border: 1px solid rgba(255, 255, 255, 0.05) !important;
    transition: all 0.35s cubic-bezier(0.4, 0, 0.2, 1) !important;
  }
  .premium-card:hover {
    transform: translateY(-4px) !important;
    border-color: rgba(255, 255, 255, 0.15) !important;
    box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.5) !important;
  }
  
  .badge-btn {
    transition: all 0.2s cubic-bezier(0.4, 0, 0.2, 1) !important;
  }
  .badge-btn:hover {
    transform: translateY(-2px) !important;
    filter: brightness(1.1);
  }

  .section-title-wrapper {
    display: flex;
    align-items: center;
    gap: 12px;
    margin-bottom: 32px;
  }
  .section-bar {
    width: 3px;
    height: 24px;
    background: linear-gradient(#38bdf8, #818cf8);
    border-radius: 4px;
  }
</style>

<div style="margin-top: 10px;">

  <!-- Professional Slick Line Dashboard Navigation -->
  <div class="nav-container">
    <a href="#who-i-am" class="nav-btn">Profile</a>
    <a href="#projects-overview" class="nav-btn">Featured Projects</a>
    <a href="#case-study-1-ergochef" class="nav-btn">Case 1: ErgoChef+</a>
    <a href="#case-study-2-elearn-ux-audit" class="nav-btn">Case 2: eLearn Audit</a>
    <a href="#personal-challenges" class="nav-btn">Challenges</a>
    <a href="#submission" class="nav-btn">Submission</a>
  </div>

  <!-- Profile Section -->
  <div id="who-i-am" style="padding-top: 20px; margin-bottom: 60px;">
    <div class="section-title-wrapper">
      <div class="section-bar"></div>
      <h2 style="color: #ffffff; font-size: 26px; font-weight: 700; margin: 0; letter-spacing: -0.5px;">Executive Profile</h2>
    </div>
    
    <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 24px;">
      <div class="premium-card" style="flex: 2; min-width: 320px; border-radius: 16px; padding: 35px; display: flex; gap: 30px; align-items: center; flex-wrap: wrap;">
        <img src="https://raw.githubusercontent.com/malcolmjeremiah/malcolmjeremiah.github.io/main/WhatsApp%20Image%202026-07-03%20at%2010.14.22%20PM.jpeg" alt="Malcolm" style="width: 110px; height: 110px; border-radius: 50%; object-fit: cover; border: 3px solid rgba(255,255,255,0.08); box-shadow: 0 8px 24px rgba(0,0,0,0.3); flex-shrink: 0;" />
        <div style="flex: 1; min-width: 240px;">
          <p style="font-size: 15.5px; line-height: 1.75; color: #cbd5e1; margin: 0; font-weight: 400; letter-spacing: 0.1px;">
            I am an <strong>Information Technology</strong> student specializing in software automation, data extraction, and user-centered workflow optimization. My design philosophy is rooted in <strong>functional minimalism</strong>: digital interfaces should actively reduce user cognitive load, mask complex database architecture, and adapt seamlessly to a user's real-world mental model. I bridge the gap between back-end technical scripting logic and clean, empathetic front-end layout execution.
          </p>
        </div>
      </div>

      <div class="premium-card" style="flex: 1; min-width: 280px; border-radius: 16px; padding: 30px; display: flex; flex-direction: column; justify-content: center;">
        <h4 style="margin-top: 0; margin-bottom: 14px; color: #64748b; font-size: 11px; font-weight: 700; text-transform: uppercase; letter-spacing: 1.5px;">🛠️ Skill Stack</h4>
        <div style="margin-bottom: 24px; display: flex; flex-wrap: wrap; gap: 8px;">
          <span style="font-size: 12px; font-weight: 600; background-color: rgba(255,255,255,0.03); color: #e2e8f0; padding: 6px 14px; border-radius: 20px; border: 1px solid rgba(255,255,255,0.05);">Python</span>
          <span style="font-size: 12px; font-weight: 600; background-color: rgba(255,255,255,0.03); color: #e2e8f0; padding: 6px 14px; border-radius: 20px; border: 1px solid rgba(255,255,255,0.05);">PHP</span>
          <span style="font-size: 12px; font-weight: 600; background-color: rgba(255,255,255,0.03); color: #e2e8f0; padding: 6px 14px; border-radius: 20px; border: 1px solid rgba(255,255,255,0.05);">JavaScript</span>
          <span style="font-size: 12px; font-weight: 600; background-color: rgba(255,255,255,0.03); color: #e2e8f0; padding: 6px 14px; border-radius: 20px; border: 1px solid rgba(255,255,255,0.05);">GIT</span>
        </div>
        <h4 style="margin-top: 0; margin-bottom: 14px; color: #64748b; font-size: 11px; font-weight: 700; text-transform: uppercase; letter-spacing: 1.5px;">📐 Methods</h4>
        <div style="display: flex; flex-wrap: wrap; gap: 8px;">
          <span style="font-size: 12px; font-weight: 600; background-color: rgba(255,255,255,0.03); color: #94a3b8; padding: 6px 14px; border-radius: 20px; border: 1px solid rgba(255,255,255,0.05);">Heuristic Evaluation</span>
          <span style="font-size: 12px; font-weight: 600; background-color: rgba(255,255,255,0.03); color: #94a3b8; padding: 6px 14px; border-radius: 20px; border: 1px solid rgba(255,255,255,0.05);">Cognitive Walkthrough</span>
          <span style="font-size: 12px; font-weight: 600; background-color: rgba(255,255,255,0.03); color: #94a3b8; padding: 6px 14px; border-radius: 20px; border: 1px solid rgba(255,255,255,0.05);">Task Mapping</span>
        </div>
      </div>
    </div>
  </div>

  <!-- Featured Projects Overview -->
  <div id="projects-overview" style="padding-top: 20px; margin-bottom: 60px;">
    <div class="section-title-wrapper">
      <div class="section-bar"></div>
      <h2 style="color: #ffffff; font-size: 26px; font-weight: 700; margin: 0; letter-spacing: -0.5px;">Featured Case Studies</h2>
    </div>
    
    <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 24px;">
      <div class="premium-card" style="flex: 1; min-width: 300px; border-radius: 16px; padding: 32px; display: flex; flex-direction: column; justify-content: space-between;">
        <div>
          <span style="font-size: 10px; font-weight: 700; background-color: rgba(234, 88, 12, 0.1); color: #fb923c; padding: 6px 14px; border-radius: 20px; display: inline-block; margin-bottom: 20px; text-transform: uppercase; letter-spacing: 1px; border: 1px solid rgba(234, 88, 12, 0.2);">Group Case Study</span>
          <h3 style="margin: 0 0 12px 0; font-size: 20px; color: #ffffff; font-weight: 700; letter-spacing: -0.3px;">ErgoChef+: AI Ergonomic Assistant</h3>
          <p style="font-size: 14px; line-height: 1.65; color: #94a3b8; margin: 0 0 24px 0;">An AI-enabled kitchen ecosystem utilizing advanced posture-sensing technology to mitigate ergonomic stress and long-term musculoskeletal fatigue for cooks.</p>
        </div>
        <div style="border-top: 1px solid rgba(255,255,255,0.05); padding-top: 20px; display: flex; align-items: center; justify-content: space-between;">
          <div style="font-size: 12.5px; color: #cbd5e1;"><strong>Role:</strong> Lead UI Designer</div>
          <a href="#case-study-1-ergochef" style="font-size: 13.5px; font-weight: 700; color: #fb923c; text-decoration: none; display: flex; align-items: center; gap: 4px;">Explore Case →</a>
        </div>
      </div>
      
      <div class="premium-card" style="flex: 1; min-width: 300px; border-radius: 16px; padding: 32px; display: flex; flex-direction: column; justify-content: space-between;">
        <div>
          <span style="font-size: 10px; font-weight: 700; background-color: rgba(56, 189, 248, 0.1); color: #38bdf8; padding: 6px 14px; border-radius: 20px; display: inline-block; margin-bottom: 20px; text-transform: uppercase; letter-spacing: 1px; border: 1px solid rgba(56, 189, 248, 0.2);">Individual Case Study</span>
          <h3 style="margin: 0 0 12px 0; font-size: 20px; color: #ffffff; font-weight: 700; letter-spacing: -0.3px;">Learning Management UX Audit</h3>
          <p style="font-size: 14px; line-height: 1.65; color: #94a3b8; margin: 0 0 24px 0;">A comprehensive heuristic evaluation and interface restructuring of the university portal to eliminate navigation friction and multi-click journey loops for students.</p>
        </div>
        <div style="border-top: 1px solid rgba(255,255,255,0.05); padding-top: 20px; display: flex; align-items: center; justify-content: space-between;">
          <div style="font-size: 12.5px; color: #cbd5e1;"><strong>Role:</strong> Lead UX Auditor</div>
          <a href="#case-study-2-elearn-ux-audit" style="font-size: 13.5px; font-weight: 700; color: #38bdf8; text-decoration: none; display: flex; align-items: center; gap: 4px;">Explore Case →</a>
        </div>
      </div>
    </div>
  </div>

  <!-- Case Study 1: ErgoChef+ -->
  <div id="case-study-1-ergochef" style="padding-top: 40px; margin-bottom: 60px;">
    <div class="premium-card" style="border-radius: 24px; padding: 40px; box-shadow: 0 30px 60px -15px rgba(0,0,0,0.35);">
      
      <div style="display: flex; flex-wrap: wrap; justify-content: space-between; align-items: flex-start; border-bottom: 1px solid rgba(255,255,255,0.05); padding-bottom: 24px; margin-bottom: 32px; gap: 16px;">
        <div>
          <h2 style="color: #ffffff; font-size: 26px; font-weight: 800; margin: 0; letter-spacing: -0.5px;">Case Study 01: ErgoChef+</h2>
          <p style="color: #fb923c; font-size: 14px; font-weight: 600; margin: 6px 0 0 0; text-transform: uppercase; letter-spacing: 0.5px;">AI-Powered Context Cooking Ecosystem</p>
        </div>
        <span style="font-size: 12px; font-weight: 600; background-color: rgba(255,255,255,0.03); color: #cbd5e1; padding: 8px 18px; border-radius: 30px; border: 1px solid rgba(255,255,255,0.08);">Lead UI & Interaction Designer</span>
      </div>
      
      <div style="background-color: rgba(251, 146, 60, 0.03); border: 1px solid rgba(251, 146, 60, 0.1); border-radius: 12px; padding: 28px; margin-bottom: 40px;">
        <h4 style="margin-top: 0; color: #fb923c; font-size: 14px; font-weight: 700; text-transform: uppercase; letter-spacing: 1px; margin-bottom: 14px;">Project Context & Architecture</h4>
        <p style="font-size: 14.5px; line-height: 1.7; color: #cbd5e1; margin-bottom: 16px;">
          <strong>The Problem:</strong> Cooking involves highly repetitive, physically demanding actions like bending, chopping, stirring, and prolonged standing. These movements generate heavy ergonomic stress, muscle fatigue, and musculoskeletal strain. Existing smart tools automate cooking tasks but completely ignore the chef's posture and long-term joint health.
        </p>
        <p style="font-size: 14.5px; line-height: 1.7; color: #cbd5e1; margin-bottom: 0;">
          <strong>Goals & System Value:</strong> ErgoChef+ integrates AI-driven posture detection, non-intrusive reminders, and personalized ergonomic reports. The goal is to provide real-time guidance to adapt to diverse cooking contexts and establish healthy, long-term kitchen habits.
          <br><br>
          <strong>Primary Target:</strong> Busy home cooks, culinary professionals, and elderly or diverse users prone to physical kitchen fatigue.
        </p>
      </div>

      <h4 style="color: #ffffff; font-size: 13px; font-weight: 700; margin-bottom: 20px; text-transform: uppercase; letter-spacing: 1.5px;">Design Framework & Execution Pipeline</h4>
      <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 16px; margin-bottom: 40px;">
        <div style="flex: 1; min-width: 220px; background-color: rgba(255,255,255,0.02); border: 1px solid rgba(255,255,255,0.04); border-radius: 12px; padding: 24px;">
          <strong style="color: #ffffff; font-size: 14px; display: block; margin-bottom: 8px;">01. Research</strong>
          <span style="font-size: 13px; line-height: 1.6; color: #94a3b8; display: block;">Conducted quantitative user surveys and qualitative interviews to map baseline physical discomfort zones during food prep.</span>
        </div>
        <div style="flex: 1; min-width: 220px; background-color: rgba(255,255,255,0.02); border: 1px solid rgba(255,255,255,0.04); border-radius: 12px; padding: 24px;">
          <strong style="color: #ffffff; font-size: 14px; display: block; margin-bottom: 8px;">02. Ideation</strong>
          <span style="font-size: 13px; line-height: 1.6; color: #94a3b8; display: block;">Sketched low-fidelity kitchen spatial layouts and camera-to-app physical telemetry interactions on paper.</span>
        </div>
        <div style="flex: 1; min-width: 220px; background-color: rgba(255,255,255,0.02); border: 1px solid rgba(255,255,255,0.04); border-radius: 12px; padding: 24px;">
          <strong style="color: #ffffff; font-size: 14px; display: block; margin-bottom: 8px;">03. Scenarios</strong>
          <span style="font-size: 13px; line-height: 1.6; color: #94a3b8; display: block;">Mapped out contextual user flow scenarios to establish how and when the system alerts a user to change their physical posture.</span>
        </div>
        <div style="flex: 1; min-width: 220px; background-color: rgba(255,255,255,0.02); border: 1px solid rgba(255,255,255,0.04); border-radius: 12px; padding: 24px;">
          <strong style="color: #ffffff; font-size: 14px; display: block; margin-bottom: 8px;">04. Hi-Fi Build</strong>
          <span style="font-size: 13px; line-height: 1.6; color: #94a3b8; display: block;">Translated layouts into a functional, live web platform using Lovable to track real-time visual tracking data.</span>
        </div>
      </div>

      <!-- Completely Redesigned Controls Row without Poster Image Element -->
      <div style="background-color: rgba(255,255,255,0.02); border: 1px solid rgba(255,255,255,0.05); border-radius: 16px; padding: 32px; margin-bottom: 40px;">
        <div style="margin-bottom: 24px; text-align: center;">
          <h4 style="margin: 0 0 6px 0; color: #ffffff; font-size: 16px; font-weight: 700;">Design Artefacts & Interactive Gateways</h4>
          <p style="font-size: 13.5px; color: #94a3b8; margin: 0;">Access production assets and ecosystem environments executing real-time spatial analytics dashboards.</p>
        </div>
        <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 12px; justify-content: center;">
          <a href="https://ergo-chef-journey.lovable.app/" target="_blank" class="badge-btn" style="flex: 1; min-width: 240px; max-width: 280px; background-color: #ea580c; color: white; padding: 14px 24px; border-radius: 8px; text-decoration: none; font-weight: 700; font-size: 13px; text-align: center; box-shadow: 0 4px 14px rgba(234, 88, 12, 0.3);">Launch Live App Prototype</a>
          <a href="https://youtu.be/-QOms8I-tbM" target="_blank" class="badge-btn" style="flex: 1; min-width: 240px; max-width: 280px; background-color: #1f2937; color: #ffffff; padding: 14px 24px; border-radius: 8px; text-decoration: none; font-weight: 700; font-size: 13px; text-align: center; border: 1px solid rgba(255,255,255,0.08); box-shadow: 0 4px 14px rgba(0,0,0,0.3);">Watch Video Presentation</a>
          <a href="https://github.com/malcolmjeremiah/malcolmjeremiah.github.io/blob/main/ErgoChef+%20(3).png?raw=true" target="_blank" class="badge-btn" style="flex: 1; min-width: 240px; max-width: 280px; background-color: #4b5563; color: white; padding: 14px 24px; border-radius: 8px; text-decoration: none; font-weight: 700; font-size: 13px; text-align: center; box-shadow: 0 4px 14px rgba(75, 85, 99, 0.3);">View Full Project Poster</a>
        </div>
      </div>

      <div style="display: flex; flex-wrap: wrap; gap: 20px;">
        <div style="flex: 1; min-width: 280px; background-color: rgba(239, 68, 68, 0.02); border: 1px solid rgba(239, 68, 68, 0.1); border-radius: 12px; padding: 24px;">
          <h4 style="margin-top: 0; color: #ef4444; font-size: 14px; font-weight: 700; text-transform: uppercase; letter-spacing: 0.5px; margin-bottom: 12px;">Friction Zones & UX Resolves</h4>
          <p style="font-size: 13.5px; line-height: 1.65; color: #cbd5e1; margin: 0;">
            <strong>The Challenge:</strong> Ensuring prompt posture warning alerts didn't disrupt the user's active cooking workflow split focus.
            <br><br>
            <strong>The Solution:</strong> Implemented subtle, non-intrusive sound layouts and progressive visual overlay alerts that auto-dismissed once correct body calibration was recorded.
          </p>
        </div>
        <div style="flex: 1; min-width: 280px; background-color: rgba(34, 197, 94, 0.02); border: 1px solid rgba(34, 197, 94, 0.1); border-radius: 12px; padding: 24px;">
          <h4 style="margin-top: 0; color: #22c55e; font-size: 14px; font-weight: 700; text-transform: uppercase; letter-spacing: 0.5px; margin-bottom: 12px;">Metrics & Validation Loops</h4>
          <p style="font-size: 13.5px; line-height: 1.65; color: #cbd5e1; margin: 0;">
            <strong>Outcomes:</strong> Live web dashboard evaluation runs tracked an average improvement in posture alignment and high user interface satisfaction.
            <br><br>
            <strong>Feedback:</strong> Peer testers confirmed that the clean layout telemetry structure made monitoring joint habits natural and stress-free.
          </p>
        </div>
      </div>

    </div>
  </div>

  <!-- Case Study 2: UX Audit -->
  <div id="case-study-2-elearn-ux-audit" style="padding-top: 20px; margin-bottom: 60px;">
    <div class="premium-card" style="border-radius: 24px; padding: 40px; box-shadow: 0 30px 60px -15px rgba(0,0,0,0.35);">
      
      <div style="display: flex; flex-wrap: wrap; justify-content: space-between; align-items: flex-start; border-bottom: 1px solid rgba(255,255,255,0.05); padding-bottom: 24px; margin-bottom: 32px; gap: 16px;">
        <div>
          <h2 style="color: #ffffff; font-size: 26px; font-weight: 800; margin: 0; letter-spacing: -0.5px;">Case Study 02: eLearn UX Audit</h2>
          <p style="color: #38bdf8; font-size: 14px; font-weight: 600; margin: 6px 0 0 0; text-transform: uppercase; letter-spacing: 0.5px;">Learning Management Portal Optimization Study</p>
        </div>
        <span style="font-size: 12px; font-weight: 600; background-color: rgba(255,255,255,0.03); color: #cbd5e1; padding: 8px 18px; border-radius: 30px; border: 1px solid rgba(255,255,255,0.08);">Lead UX Auditor</span>
      </div>
      
      <div style="background-color: rgba(56, 189, 248, 0.03); border: 1px solid rgba(56, 189, 248, 0.1); border-radius: 12px; padding: 28px; margin-bottom: 40px;">
        <h4 style="margin-top: 0; color: #38bdf8; font-size: 14px; font-weight: 700; text-transform: uppercase; letter-spacing: 1px; margin-bottom: 14px;">Project Context & Architecture</h4>
        <p style="font-size: 14.5px; line-height: 1.7; color: #cbd5e1; margin-bottom: 16px;">
          <strong>The Problem:</strong> The existing university eLearn web interface suffers from severe navigation friction, counter-intuitive architecture, and redundant multi-click journey loops. Students routinely experience heavy cognitive fatigue trying to locate basic announcements, modular assignment submission dropboxes, and grading panels.
        </p>
        <p style="font-size: 14.5px; line-height: 1.7; color: #cbd5e1; margin-bottom: 0;">
          <strong>Goals & Value Mechanics:</strong> This project functions as an intensive UI/UX overhaul. By running rigorous heuristic audits, cognitive walkthroughs, and restructuring user navigation architecture, the primary goal was to replace convoluted nested paths with a clean, centralized dashboard directory layout.
          <br><br>
          <strong>Primary Target:</strong> University undergraduate students, academic researchers, and lecturing faculties utilizing learning management portals daily.
        </p>
      </div>

      <h4 style="color: #ffffff; font-size: 13px; font-weight: 700; margin-bottom: 20px; text-transform: uppercase; letter-spacing: 1.5px;">System Diagnostic Framework</h4>
      <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 16px; margin-bottom: 40px;">
        <div style="flex: 1; min-width: 220px; background-color: rgba(255,255,255,0.02); border: 1px solid rgba(255,255,255,0.04); border-radius: 12px; padding: 24px;">
          <strong style="color: #ffffff; font-size: 14px; display: block; margin-bottom: 8px;">01. Usability Heuristics</strong>
          <span style="font-size: 13px; line-height: 1.6; color: #94a3b8; display: block;">Evaluated the current portal against standard usability heuristics, identifying critical friction points in system visibility and consistency.</span>
        </div>
        <div style="flex: 1; min-width: 220px; background-color: rgba(255,255,255,0.02); border: 1px solid rgba(255,255,255,0.04); border-radius: 12px; padding: 24px;">
          <strong style="color: #ffffff; font-size: 14px; display: block; margin-bottom: 8px;">02. Journey Mapping</strong>
          <span style="font-size: 13px; line-height: 1.6; color: #94a3b8; display: block;">Plotted step-by-step user pathways to measure user behavior and click-counts during common tasks like accessing grades.</span>
        </div>
        <div style="flex: 1; min-width: 220px; background-color: rgba(255,255,255,0.02); border: 1px solid rgba(255,255,255,0.04); border-radius: 12px; padding: 24px;">
          <strong style="color: #ffffff; font-size: 14px; display: block; margin-bottom: 8px;">03. Compressed Wireframes</strong>
          <span style="font-size: 13px; line-height: 1.6; color: #94a3b8; display: block;">Sketched a low-fidelity card layout structure to compress the multi-layered dashboard into a unified, responsive front-end screen.</span>
        </div>
      </div>

      <div style="background-color: rgba(255,255,255,0.02); border: 1px solid rgba(255,255,255,0.05); border-radius: 16px; padding: 32px; margin-bottom: 40px;">
        <h4 style="margin-top: 0; color: #ffffff; font-size: 15px; font-weight: 700; margin-bottom: 6px;">Compiled System Blueprints</h4>
        <p style="font-size: 13.5px; color: #94a3b8; margin-bottom: 20px;">Review the wireframes, card-sorting directories, navigation matrices, and user journey optimization wireframes compiled during the heuristic audit phase.</p>
        <div style="display: flex; flex-wrap: wrap; gap: 12px;">
          <span style="background-color: rgba(255,255,255,0.03); border: 1px solid rgba(255,255,255,0.08); color: #f1f5f9; padding: 12px 20px; border-radius: 8px; font-size: 13px; font-weight: 600; display: inline-block; box-shadow: 0 4px 12px rgba(0,0,0,0.15);">📄 Usability Mapping Report.pdf</span>
          <span style="background-color: rgba(255,255,255,0.03); border: 1px solid rgba(255,255,255,0.08); color: #f1f5f9; padding: 12px 20px; border-radius: 8px; font-size: 13px; font-weight: 600; display: inline-block; box-shadow: 0 4px 12px rgba(0,0,0,0.15);">📐 Optimized Architecture Wireframes</span>
        </div>
      </div>

      <div style="display: flex; flex-wrap: wrap; gap: 20px;">
        <div style="flex: 1; min-width: 280px; background-color: rgba(239, 68, 68, 0.02); border: 1px solid rgba(239, 68, 68, 0.1); border-radius: 12px; padding: 24px;">
          <h4 style="margin-top: 0; color: #ef4444; font-size: 14px; font-weight: 700; text-transform: uppercase; letter-spacing: 0.5px; margin-bottom: 12px;">Friction Zones & UX Resolves</h4>
          <p style="font-size: 13.5px; line-height: 1.65; color: #cbd5e1; margin: 0;">
            <strong>The Challenge:</strong> Consolidating extensive, fragmented module links into a small viewport without triggering secondary layout overcrowding.
            <br><br>
            <strong>The Solution:</strong> Applied an expandable web directory system that keeps primary folders prominent while dynamically grouping inner module links until clicked.
          </p>
        </div>
        <div style="flex: 1; min-width: 280px; background-color: rgba(34, 197, 94, 0.02); border: 1px solid rgba(34, 197, 94, 0.1); border-radius: 12px; padding: 24px;">
          <h4 style="margin-top: 0; color: #22c55e; font-size: 14px; font-weight: 700; text-transform: uppercase; letter-spacing: 0.5px; margin-bottom: 12px;">Metrics & Validation Loops</h4>
          <p style="font-size: 13.5px; line-height: 1.65; color: #cbd5e1; margin: 0;">
            <strong>Outcomes:</strong> Walkthrough testing recorded a notable drop in the average time required to complete assignment lookups.
            <br><br>
            <strong>Feedback:</strong> Student peer groups reported that the simplified card framework felt significantly more modern, responsive, and intuitive.
          </p>
        </div>
      </div>

    </div>
  </div>

  <!-- Engineering Engineering Constraints -->
  <div id="personal-challenges" style="padding-top: 20px; margin-bottom: 60px;">
    <div class="section-title-wrapper">
      <div class="section-bar"></div>
      <h2 style="color: #ffffff; font-size: 26px; font-weight: 700; margin: 0; letter-spacing: -0.5px;">System Diagnostics & Problem Solving</h2>
    </div>
    
    <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 20px; margin-bottom: 20px;">
      <div class="premium-card" style="flex: 1; min-width: 320px; border-radius: 12px; padding: 28px;">
        <strong style="color: #ffffff; font-size: 15px; display: block; margin-bottom: 10px; border-bottom: 1px solid rgba(255,255,255,0.05); padding-bottom: 10px;">1. GitHub Layout Collisions</strong>
        <p style="font-size: 13.5px; line-height: 1.65; color: #94a3b8; margin: 0;">
          <strong>Problem:</strong> Root standard layout wrapping caused theme processors to strip out native Markdown header elements (like # or ##).
          <br><br>
          <strong>Resolution:</strong> Refactored structural elements into explicit inline HTML layout components using encoded wrappers to completely bypass theme build interference.
        </p>
      </div>

      <div class="premium-card" style="flex: 1; min-width: 320px; border-radius: 12px; padding: 28px;">
        <strong style="color: #ffffff; font-size: 15px; display: block; margin-bottom: 10px; border-bottom: 1px solid rgba(255,255,255,0.05); padding-bottom: 10px;">2. Theme Banner Overrides</strong>
        <p style="font-size: 13.5px; line-height: 1.65; color: #94a3b8; margin: 0;">
          <strong>Problem:</strong> Default layout headers forced rigid green gradient branding boxes on desktop viewports.
          <br><br>
          <strong>Resolution:</strong> Injected targeted style element modifications to manually reset header containers with responsive asset URLs.
        </p>
      </div>

      <div class="premium-card" style="flex: 1; min-width: 320px; border-radius: 12px; padding: 28px;">
        <strong style="color: #ffffff; font-size: 15px; display: block; margin-bottom: 10px; border-bottom: 1px solid rgba(255,255,255,0.05); padding-bottom: 10px;">3. Telemetry Warning Interfaces</strong>
        <p style="font-size: 13.5px; line-height: 1.65; color: #94a3b8; margin: 0;">
          <strong>Problem:</strong> ErgoChef+ warning windows disrupted physical user cooking flows.
          <br><br>
          <strong>Resolution:</strong> Restructured notification cycles using progressive visual overlays that clear as soon as posture metrics correct.
        </p>
      </div>
    </div>
    
    <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 20px;">
      <div class="premium-card" style="flex: 1; min-width: 320px; border-radius: 12px; padding: 28px;">
        <strong style="color: #ffffff; font-size: 15px; display: block; margin-bottom: 10px; border-bottom: 1px solid rgba(255,255,255,0.05); padding-bottom: 10px;">4. Navigation Link Nesting</strong>
        <p style="font-size: 13.5px; line-height: 1.65; color: #94a3b8; margin: 0;">
          <strong>Problem:</strong> Complex link nesting on eLearn websites increased user multi-click journey loops and cognitive loads.
          <br><br>
          <strong>Resolution:</strong> Designed a compressed, expandable grid framework to make common actions instantly accessible.
        </p>
      </div>

      <div class="premium-card" style="flex: 1; min-width: 320px; border-radius: 12px; padding: 28px;">
        <strong style="color: #ffffff; font-size: 15px; display: block; margin-bottom: 10px; border-bottom: 1px solid rgba(255,255,255,0.05); padding-bottom: 10px;">5. Navigation Snapping Friction</strong>
        <p style="font-size: 13.5px; line-height: 1.65; color: #94a3b8; margin: 0;">
          <strong>Problem:</strong> Traditional link clicks caused abrupt page snaps, lowering the overall presentation feel.
          <br><br>
          <strong>Resolution:</strong> Enabled root document scroll-behavior configurations to provide a fluid sliding transition.
        </p>
      </div>

      <div class="premium-card" style="flex: 1; min-width: 320px; border-radius: 12px; padding: 28px;">
        <strong style="color: #ffffff; font-size: 15px; display: block; margin-bottom: 10px; border-bottom: 1px solid rgba(255,255,255,0.05); padding-bottom: 10px;">6. Mobile Viewport Constraints</strong>
        <p style="font-size: 13.5px; line-height: 1.65; color: #94a3b8; margin: 0;">
          <strong>Problem:</strong> Rigid dimension styling scales skewed multi-column layout matrices on mobile interfaces.
          <br><br>
          <strong>Resolution:</strong> Standardized flex container parameters to wrap smoothly across varying devices.
        </p>
      </div>
    </div>
  </div>

  <hr style="height: 1px; border: none; background-color: rgba(255,255,255,0.05); margin: 60px 0;">

  <!-- Submission Verification -->
  <div id="submission" style="padding-top: 20px; margin-bottom: 60px;">
    <div class="premium-card" style="border-radius: 16px; padding: 35px; display: flex; align-items: center; gap: 24px; flex-wrap: wrap;">
      <div style="background-color: rgba(255,255,255,0.02); padding: 18px; border-radius: 50%; border: 1px solid rgba(255,255,255,0.05); font-size: 20px;">📋</div>
      <div style="flex: 1; min-width: 260px;">
        <h3 style="color: #ffffff; font-size: 18px; font-weight: 700; margin: 0 0 8px 0;">Academic Integrity & Submission Verification</h3>
        <p style="font-size: 14px; color: #94a3b8; line-height: 1.65; margin: 0;">
          This web portfolio is submitted in strict alignment with university academic integrity code standards. All featured layout components, script configurations, and design narratives represent authentic project work completed during the academic semester term.
        </p>
      </div>
    </div>
  </div>

</div>
