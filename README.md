<!-- Theme Override: Forces your image link, styles text, and unlocks hardware-accelerated smooth scrolling -->
<style>
  html {
    scroll-behavior: smooth !important;
  }
  header.page-header {
    background-image: linear-gradient(rgba(0, 0, 0, 0.55), rgba(0, 0, 0, 0.55)), url('https://github.com/malcolmjeremiah/malcolmjeremiah.github.io/blob/main/1763479411435.jpeg?raw=true') !important;
    background-size: cover !important;
    background-position: center !important;
    padding: 5rem 2rem !important;
    text-align: center !important;
  }
  
  /* Forces your Name into the main theme header element */
  header.page-header h1.project-name {
    display: block !important;
    color: #ffffff !important;
    font-size: 32px !important;
    font-weight: 700 !important;
    letter-spacing: 0.5px !important;
    text-shadow: 0 2px 5px rgba(0,0,0,0.65) !important;
    margin: 0 !important;
  }
  header.page-header h1.project-name::after {
    content: "MALCOLM JEREMIAH RICHARD";
  }
  
  /* Forces your Degree Subtitle into the main theme header element */
  header.page-header h2.project-tagline {
    display: block !important;
    color: #e1e4e8 !important;
    font-size: 15px !important;
    font-weight: 400 !important;
    text-shadow: 0 1px 3px rgba(0,0,0,0.65) !important;
    text-transform: uppercase !important;
    letter-spacing: 1px !important;
    margin-top: 10px !important;
    opacity: 1 !important;
  }
  header.page-header h2.project-tagline::after {
    content: "BSc (Hons) Information Technology Student | UI/UX Portfolio";
  }
</style>

<div>

  <!-- Smooth Floating Navigation Buttons -->
  <div style="display: flex; flex-wrap: wrap; gap: 10px; margin-top: 25px; margin-bottom: 25px; justify-content: center;">
    <a href="#who-i-am" style="background-color: #24292e; color: white; padding: 10px 18px; border-radius: 6px; text-decoration: none; font-weight: 600; font-size: 13px; display: inline-block; box-shadow: 0 1px 3px rgba(0,0,0,0.12);">🏠 Profile</a>
    <a href="#projects-overview" style="background-color: #24292e; color: white; padding: 10px 18px; border-radius: 6px; text-decoration: none; font-weight: 600; font-size: 13px; display: inline-block; box-shadow: 0 1px 3px rgba(0,0,0,0.12);">📂 Featured Projects</a>
    <a href="#case-study-1-ergochef" style="background-color: #24292e; color: white; padding: 10px 18px; border-radius: 6px; text-decoration: none; font-weight: 600; font-size: 13px; display: inline-block; box-shadow: 0 1px 3px rgba(0,0,0,0.12);">🍳 Case 1: ErgoChef+</a>
    <a href="#case-study-2-elearn-ux-audit" style="background-color: #24292e; color: white; padding: 10px 18px; border-radius: 6px; text-decoration: none; font-weight: 600; font-size: 13px; display: inline-block; box-shadow: 0 1px 3px rgba(0,0,0,0.12);">📚 Case 2: eLearn Audit</a>
    <a href="#personal-challenges" style="background-color: #24292e; color: white; padding: 10px 18px; border-radius: 6px; text-decoration: none; font-weight: 600; font-size: 13px; display: inline-block; box-shadow: 0 1px 3px rgba(0,0,0,0.12);">⚡ Challenges</a>
    <a href="#submission" style="background-color: #24292e; color: white; padding: 10px 18px; border-radius: 6px; text-decoration: none; font-weight: 600; font-size: 13px; display: inline-block; box-shadow: 0 1px 3px rgba(0,0,0,0.12);">📋 Submission</a>
  </div>

  <hr style="height: 1px; border: none; background-color: #e1e4e8; margin: 25px 0;">

  <!-- Section: Profile -->
  <div id="who-i-am" style="padding-top: 10px;">
    <h2 style="color: #24292e; font-size: 22px; font-weight: 600; margin-bottom: 16px;">👤 Who I Am</h2>
    
    <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 20px; margin-bottom: 30px;">
      <!-- Profile Card -->
      <div style="flex: 2; min-width: 300px; background-color: #f6f8fa; border: 1px solid #e1e4e8; border-radius: 8px; padding: 24px; box-shadow: 0 1px 3px rgba(0,0,0,0.05); display: flex; gap: 20px; align-items: center; flex-wrap: wrap;">
        <img src="https://raw.githubusercontent.com/malcolmjeremiah/malcolmjeremiah.github.io/main/WhatsApp%20Image%202026-07-03%20at%2010.14.22%20PM.jpeg" alt="Malcolm" style="width: 100px; height: 100px; border-radius: 50%; object-fit: cover; border: 3px solid #ffffff; box-shadow: 0 2px 6px rgba(0,0,0,0.15); flex-shrink: 0;" />
        <div style="flex: 1; min-width: 220px;">
          <p style="font-size: 15px; line-height: 1.6; color: #24292e; margin: 0; font-weight: 400;">
            I am an <strong>Information Technology</strong> student specializing in software automation, data extraction, and user-centered workflow optimization. My design philosophy is rooted in <strong>functional minimalism</strong>: digital interfaces should actively reduce user cognitive load, mask complex database architecture, and adapt seamlessly to a user's real-world mental model. I bridge the gap between back-end technical scripting logic and clean, empathetic front-end layout execution.
          </p>
        </div>
      </div>

      <!-- Skills Card -->
      <div style="flex: 1; min-width: 240px; background-color: #ffffff; border: 1px solid #e1e4e8; border-radius: 8px; padding: 20px; box-shadow: 0 1px 3px rgba(0,0,0,0.05); display: flex; flex-direction: column; justify-content: center;">
        <h4 style="margin-top: 0; margin-bottom: 12px; color: #24292e; font-size: 14px; text-transform: uppercase; letter-spacing: 0.5px;">🛠️ Skill Stack</h4>
        <div style="margin-bottom: 16px;">
          <span style="font-size: 11px; font-weight: bold; background-color: #e2e8f0; color: #4a5568; padding: 5px 9px; border-radius: 4px; display: inline-block; margin-bottom: 5px; margin-right: 4px;">Python</span>
          <span style="font-size: 11px; font-weight: bold; background-color: #e2e8f0; color: #4a5568; padding: 5px 9px; border-radius: 4px; display: inline-block; margin-bottom: 5px; margin-right: 4px;">PHP</span>
          <span style="font-size: 11px; font-weight: bold; background-color: #e2e8f0; color: #4a5568; padding: 5px 9px; border-radius: 4px; display: inline-block; margin-bottom: 5px; margin-right: 4px;">JavaScript</span>
          <span style="font-size: 11px; font-weight: bold; background-color: #e2e8f0; color: #4a5568; padding: 5px 9px; border-radius: 4px; display: inline-block; margin-bottom: 5px; margin-right: 4px;">GIT</span>
        </div>
        <h4 style="margin-top: 4px; margin-bottom: 12px; color: #24292e; font-size: 14px; text-transform: uppercase; letter-spacing: 0.5px;">📐 Methods</h4>
        <div>
          <span style="font-size: 11px; font-weight: bold; background-color: #edf2f7; color: #2d3748; padding: 5px 9px; border-radius: 4px; display: inline-block; margin-bottom: 5px; margin-right: 4px;">Heuristic Evaluation</span>
          <span style="font-size: 11px; font-weight: bold; background-color: #edf2f7; color: #2d3748; padding: 5px 9px; border-radius: 4px; display: inline-block; margin-bottom: 5px; margin-right: 4px;">Cognitive Walkthrough</span>
          <span style="font-size: 11px; font-weight: bold; background-color: #edf2f7; color: #2d3748; padding: 5px 9px; border-radius: 4px; display: inline-block; margin-bottom: 5px; margin-right: 4px;">Task Mapping</span>
        </div>
      </div>
    </div>
  </div>

  <hr style="height: 1px; border: none; background-color: #e1e4e8; margin: 30px 0;">

  <!-- Section: Featured Projects Overview -->
  <div id="projects-overview" style="padding-top: 10px;">
    <h2 style="color: #24292e; font-size: 22px; font-weight: 600; margin-bottom: 16px;">📂 Featured Projects</h2>
    <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 20px; margin-bottom: 30px;">
      <!-- Card 1 -->
      <div style="flex: 1; min-width: 280px; background-color: #ffffff; border: 1px solid #e1e4e8; border-radius: 8px; padding: 20px; box-shadow: 0 1px 3px rgba(0,0,0,0.05); display: flex; flex-direction: column; justify-content: space-between;">
        <div>
          <span style="font-size: 10px; font-weight: bold; background-color: #ffe8d6; color: #c05621; padding: 4px 8px; border-radius: 20px; display: inline-block; margin-bottom: 12px; text-transform: uppercase;">Group Project Case Study</span>
          <h3 style="margin: 0 0 8px 0; font-size: 18px; color: #24292e;">ErgoChef+: AI Ergonomic Assistant</h3>
          <p style="font-size: 13px; line-height: 1.5; color: #586069; margin: 0 0 16px 0;">An AI-enabled kitchen ecosystem utilizing advanced posture-sensing technology to mitigate ergonomic stress and long-term musculoskeletal fatigue for cooks.</p>
        </div>
        <div style="margin-top: 15px;">
          <div style="margin-bottom: 12px; font-size: 12px; color: #24292e;"><strong>Role:</strong> Lead UI & Interaction Designer</div>
          <a href="#case-study-1-ergochef" style="font-size: 13px; font-weight: bold; color: #c05621; text-decoration: none;">Read Full Case Study →</a>
        </div>
      </div>
      <!-- Card 2 -->
      <div style="flex: 1; min-width: 280px; background-color: #ffffff; border: 1px solid #e1e4e8; border-radius: 8px; padding: 20px; box-shadow: 0 1px 3px rgba(0,0,0,0.05); display: flex; flex-direction: column; justify-content: space-between;">
        <div>
          <span style="font-size: 10px; font-weight: bold; background-color: #dbedff; color: #0366d6; padding: 4px 8px; border-radius: 20px; display: inline-block; margin-bottom: 12px; text-transform: uppercase;">Individual Case Study</span>
          <h3 style="margin: 0 0 8px 0; font-size: 18px; color: #24292e;">Institutional eLearn UX Audit</h3>
          <p style="font-size: 13px; line-height: 1.5; color: #586069; margin: 0 0 16px 0;">A comprehensive heuristic evaluation and interface restructuring of the university portal to eliminate navigation friction and multi-click journey loops for students.</p>
        </div>
        <div style="margin-top: 15px;">
          <div style="margin-bottom: 12px; font-size: 12px; color: #24292e;"><strong>Role:</strong> Lead UX Auditor & Interaction Designer</div>
          <a href="#case-study-2-elearn-ux-audit" style="font-size: 13px; font-weight: bold; color: #0366d6; text-decoration: none;">Read Full Case Study →</a>
        </div>
      </div>
    </div>
  </div>

  <hr style="height: 1px; border: none; background-color: #e1e4e8; margin: 30px 0;">

  <!-- Section: Case Study 1 -->
  <div id="case-study-1-ergochef" style="padding-top: 10px;">
    <h2 style="color: #24292e; font-size: 22px; font-weight: 600; margin-bottom: 4px;">🍳 Case Study 1: ErgoChef+</h2>
    <p style="color: #586069; font-size: 14px; margin: 0 0 16px 0;"><strong>Role:</strong> Lead UI & Interaction Designer (Group Project)</p>
    
    <div style="background-color: #ffffff; border: 1px solid #e1e4e8; border-radius: 8px; padding: 24px; box-shadow: 0 1px 3px rgba(0,0,0,0.05); margin-bottom: 24px;">
      <h4 style="margin-top: 0; color: #c05621; font-size: 16px;">📋 Project Overview & Context</h4>
      <p style="font-size: 14px; line-height: 1.6; color: #24292e; margin-bottom: 12px;">
        <strong>The Problem:</strong> Cooking involves highly repetitive, physically demanding actions like bending, chopping, stirring, and prolonged standing. These movements generate heavy ergonomic stress, muscle fatigue, and musculoskeletal strain. Existing smart tools automate cooking tasks but completely ignore the chef's posture and long-term joint health.
      </p>
      <p style="font-size: 14px; line-height: 1.6; color: #24292e; margin-bottom: 0;">
        <strong>Project Goals & Value Proposition:</strong> ErgoChef+ integrates AI-driven posture detection, non-intrusive reminders, and personalized ergonomic reports. The goal is to provide real-time guidance to adapt to diverse cooking contexts and establish healthy, long-term kitchen habits.
        <br><br>
        <strong>Target Audience:</strong> Busy home cooks, culinary professionals, and elderly or diverse users prone to physical kitchen fatigue.
      </p>
    </div>

    <h4 style="color: #24292e; font-size: 16px; margin-bottom: 12px;">📐 Design Process & Iterative Framework</h4>
    <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 16px; margin-bottom: 24px;">
      <div style="flex: 1; min-width: 200px; background-color: #f6f8fa; border: 1px solid #e1e4e8; border-radius: 6px; padding: 16px;">
        <strong style="color: #24292e; font-size: 14px; display: block; margin-bottom: 6px;">1. Research & Discovery</strong>
        <span style="font-size: 13px; line-height: 1.5; color: #586069; display: block;">Conducted quantitative user surveys and qualitative interviews to map baseline physical discomfort zones during food prep.</span>
      </div>
      <div style="flex: 1; min-width: 200px; background-color: #f6f8fa; border: 1px solid #e1e4e8; border-radius: 6px; padding: 16px;">
        <strong style="color: #24292e; font-size: 14px; display: block; margin-bottom: 6px;">2. Ideation & Sketches</strong>
        <span style="font-size: 13px; line-height: 1.5; color: #586069; display: block;">Sketched low-fidelity kitchen spatial layouts and camera-to-app physical telemetry interactions on paper.</span>
      </div>
      <div style="flex: 1; min-width: 200px; background-color: #f6f8fa; border: 1px solid #e1e4e8; border-radius: 6px; padding: 16px;">
        <strong style="color: #24292e; font-size: 14px; display: block; margin-bottom: 6px;">3. Storyboarding</strong>
        <span style="font-size: 13px; line-height: 1.5; color: #586069; display: block;">Mapped out contextual user flow scenarios to establish how and when the system alerts a user to change their physical posture.</span>
      </div>
      <div style="flex: 1; min-width: 200px; background-color: #f6f8fa; border: 1px solid #e1e4e8; border-radius: 6px; padding: 16px;">
        <strong style="color: #24292e; font-size: 14px; display: block; margin-bottom: 6px;">4. High-Fi Prototyping</strong>
        <span style="font-size: 13px; line-height: 1.5; color: #586069; display: block;">Translated layouts into a functional, live web platform using Lovable to track real-time visual tracking data.</span>
      </div>
    </div>

    <!-- Design Artefacts Block -->
    <div style="background-color: #fcf8f2; border: 1px solid #f0e4d4; border-radius: 8px; padding: 24px; margin-bottom: 24px;">
      <h4 style="margin-top: 0; color: #c05621; font-size: 15px; text-transform: uppercase; letter-spacing: 0.5px;">🎨 Design Artefacts & Live Media</h4>
      <p style="font-size: 13px; color: #586069; margin-bottom: 16px;">Explore the system architecture across low-fidelity ideation sketches, conceptual storyboards, the official video pitch, and the final high-fidelity live deployment platform.</p>
      <div style="display: flex; flex-wrap: wrap; gap: 12px;">
        <a href="https://ergo-chef-journey.lovable.app/" target="_blank" style="background-color: #c05621; color: white; padding: 10px 16px; border-radius: 6px; text-decoration: none; font-weight: bold; font-size: 13px; display: inline-block; box-shadow: 0 1px 2px rgba(0,0,0,0.05);">🌐 Launch Live App Prototype</a>
        <a href="https://youtu.be/-QOms8I-tbM" target="_blank" style="background-color: #24292e; color: white; padding: 10px 16px; border-radius: 6px; text-decoration: none; font-weight: bold; font-size: 13px; display: inline-block; box-shadow: 0 1px 2px rgba(0,0,0,0.05);">📺 Watch Project Video Presentation</a>
      </div>
    </div>

    <!-- Challenges & Results Block -->
    <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 20px; margin-bottom: 30px;">
      <div style="flex: 1; min-width: 280px; background-color: #fff5f5; border: 1px solid #ffe3e3; border-radius: 8px; padding: 20px;">
        <h4 style="margin-top: 0; color: #c53030; font-size: 15px; margin-bottom: 10px;">⚠️ Challenges & UX Solutions</h4>
        <p style="font-size: 13px; line-height: 1.6; color: #2f2f2f; margin: 0;">
          <strong>The Challenge:</strong> Ensuring prompt posture warning alerts didn't disrupt the user's active cooking workflow split focus.
          <br><br>
          <strong>The Solution:</strong> Implemented subtle, non-intrusive sound layouts and progressive visual overlay alerts that auto-dismissed once correct body calibration was recorded.
        </p>
      </div>
      <div style="flex: 1; min-width: 280px; background-color: #f0fff4; border: 1px solid #c6f6d5; border-radius: 8px; padding: 20px;">
        <h4 style="margin-top: 0; color: #22543d; font-size: 15px; margin-bottom: 10px;">🚀 Project Results & Feedback</h4>
        <p style="font-size: 13px; line-height: 1.6; color: #2f2f2f; margin: 0;">
          <strong>Outcomes:</strong> Live web dashboard evaluation runs tracked an average improvement in posture alignment and high user interface satisfaction.
          <br><br>
          <strong>Feedback:</strong> Peer testers confirmed that the clean layout telemetry structure made monitoring joint habits natural and stress-free.
        </p>
      </div>
    </div>
  </div>

  <hr style="height: 1px; border: none; background-color: #e1e4e8; margin: 30px 0;">

  <!-- Section: Case Study 2 -->
  <div id="case-study-2-elearn-ux-audit" style="padding-top: 10px;">
    <h2 style="color: #24292e; font-size: 22px; font-weight: 600; margin-bottom: 4px;">📚 Case Study 2: Institutional eLearn UX Audit</h2>
    <p style="color: #586069; font-size: 14px; margin: 0 0 16px 0;"><strong>Role:</strong> Lead UX Auditor & Interaction Designer (Individual Project)</p>
    
    <div style="background-color: #ffffff; border: 1px solid #e1e4e8; border-radius: 8px; padding: 24px; box-shadow: 0 1px 3px rgba(0,0,0,0.05); margin-bottom: 24px;">
      <h4 style="margin-top: 0; color: #0366d6; font-size: 16px;">📋 Project Overview & Context</h4>
      <p style="font-size: 14px; line-height: 1.6; color: #24292e; margin-bottom: 12px;">
        <strong>The Problem:</strong> The existing university eLearn web interface suffers from severe navigation friction, counter-intuitive architecture, and redundant multi-click journey loops. Students routinely experience heavy cognitive fatigue trying to locate basic announcements, modular assignment submission dropboxes, and grading panels.
      </p>
      <p style="font-size: 14px; line-height: 1.6; color: #24292e; margin-bottom: 0;">
        <strong>Project Goals & Value Proposition:</strong> This project functions as an intensive UI/UX overhaul. By running rigorous heuristic audits, cognitive walkthroughs, and restructuring user navigation architecture, the primary goal was to replace convoluted nested paths with a clean, centralized dashboard directory layout.
        <br><br>
        <strong>Target Audience:</strong> University undergraduate students, academic researchers, and lecturing faculties utilizing learning management portals daily.
      </p>
    </div>

    <h4 style="color: #24292e; font-size: 16px; margin-bottom: 12px;">📐 Design Process & Audit Framework</h4>
    <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 16px; margin-bottom: 24px;">
      <div style="flex: 1; min-width: 200px; background-color: #f6f8fa; border: 1px solid #e1e4e8; border-radius: 6px; padding: 16px;">
        <strong style="color: #24292e; font-size: 14px; display: block; margin-bottom: 6px;">1. Heuristic Evaluation</strong>
        <span style="font-size: 13px; line-height: 1.5; color: #586069; display: block;">Evaluated the current portal against standard usability heuristics, identifying critical friction points in system visibility and consistency.</span>
      </div>
      <div style="flex: 1; min-width: 200px; background-color: #f6f8fa; border: 1px solid #e1e4e8; border-radius: 6px; padding: 16px;">
        <strong style="color: #24292e; font-size: 14px; display: block; margin-bottom: 6px;">2. User Task Mapping</strong>
        <span style="font-size: 13px; line-height: 1.5; color: #586069; display: block;">Plotted step-by-step user pathways to measure user behavior and click-counts during common tasks like accessing grades.</span>
      </div>
      <div style="flex: 1; min-width: 200px; background-color: #f6f8fa; border: 1px solid #e1e4e8; border-radius: 6px; padding: 16px;">
        <strong style="color: #24292e; font-size: 14px; display: block; margin-bottom: 6px;">3. Wireframing & Layouts</strong>
        <span style="font-size: 13px; line-height: 1.5; color: #586069; display: block;">Sketched a low-fidelity card layout structure to compress the multi-layered dashboard into a unified, responsive front-end screen.</span>
      </div>
    </div>

    <!-- Design Artefacts Block -->
    <div style="background-color: #f2f7fc; border: 1px solid #d4e3f0; border-radius: 8px; padding: 24px; margin-bottom: 24px;">
      <h4 style="margin-top: 0; color: #0366d6; font-size: 15px; text-transform: uppercase; letter-spacing: 0.5px;">🎨 Design Artefacts & Audited Layouts</h4>
      <p style="font-size: 13px; color: #586069; margin-bottom: 16px;">Review the wireframes, card-sorting directories, navigation matrices, and user journey optimization wireframes compiled during the heuristic audit phase.</p>
      <div style="display: flex; flex-wrap: wrap; gap: 12px;">
        <span style="background-color: #ffffff; border: 1px solid #e1e4e8; color: #24292e; padding: 8px 14px; border-radius: 4px; font-size: 12px; font-weight: 600; box-shadow: 0 1px 2px rgba(0,0,0,0.02);">📄 Usability Mapping Report.pdf</span>
        <span style="background-color: #ffffff; border: 1px solid #e1e4e8; color: #24292e; padding: 8px 14px; border-radius: 4px; font-size: 12px; font-weight: 600; box-shadow: 0 1px 2px rgba(0,0,0,0.02);">📐 Optimized Architecture Wireframes</span>
      </div>
    </div>

    <!-- Challenges & Results Block -->
    <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 20px; margin-bottom: 30px;">
      <div style="flex: 1; min-width: 280px; background-color: #fff5f5; border: 1px solid #ffe3e3; border-radius: 8px; padding: 20px;">
        <h4 style="margin-top: 0; color: #c53030; font-size: 15px; margin-bottom: 10px;">⚠️ Challenges & UX Solutions</h4>
        <p style="font-size: 13px; line-height: 1.6; color: #2f2f2f; margin: 0;">
          <strong>The Challenge:</strong> Consolidating extensive, fragmented module links into a small viewport without triggering secondary layout overcrowding.
          <br><br>
          <strong>The Solution:</strong> Applied an expandable web directory system that keeps primary folders prominent while dynamically grouping inner module links until clicked.
        </p>
      </div>
      <div style="flex: 1; min-width: 280px; background-color: #f0fff4; border: 1px solid #c6f6d5; border-radius: 8px; padding: 20px;">
        <h4 style="margin-top: 0; color: #22543d; font-size: 15px; margin-bottom: 10px;">🚀 Project Results & Feedback</h4>
        <p style="font-size: 13px; line-height: 1.6; color: #2f2f2f; margin: 0;">
          <strong>Outcomes:</strong> Walkthrough testing recorded a notable drop in the average time required to complete assignment lookups.
          <br><br>
          <strong>Feedback:</strong> Student peer groups reported that the simplified card framework felt significantly more modern, responsive, and intuitive.
        </p>
      </div>
    </div>
  </div>

  <hr style="height: 1px; border: none; background-color: #e1e4e8; margin: 30px 0;">

  <!-- Section: Personal Challenges & Problem Solving (6 Challenges Matrix) -->
  <div id="personal-challenges" style="padding-top: 10px;">
    <h2 style="color: #24292e; font-size: 22px; font-weight: 600; margin-bottom: 4px;">⚡ Personal Challenges & Problem Solving</h2>
    <p style="color: #586069; font-size: 14px; margin: 0 0 20px 0;">A transparent log of advanced development bottlenecks, system failures, and the engineering frameworks utilized to resolve them.</p>
    
    <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 16px; margin-bottom: 30px;">
      
      <!-- Challenge 1 -->
      <div style="flex: 1; min-width: 280px; background-color: #ffffff; border: 1px solid #e1e4e8; border-radius: 6px; padding: 18px; box-shadow: 0 1px 2px rgba(0,0,0,0.02);">
        <strong style="color: #24292e; font-size: 14px; display: block; margin-bottom: 6px;">1. GitHub Layout Processing Collisions</strong>
        <p style="font-size: 13px; line-height: 1.5; color: #586069; margin: 0;">
          <strong>Problem:</strong> Root standard layout wrapping caused theme processors to strip out native Markdown header elements (`#`, `##`).
          <br>
          <strong>Resolution:</strong> Refactored structural elements into explicit inline HTML layout components (`<div>`) to completely bypass theme build interference.
        </p>
      </div>

      <!-- Challenge 2 -->
      <div style="flex: 1; min-width: 280px; background-color: #ffffff; border: 1px solid #e1e4e8; border-radius: 6px; padding: 18px; box-shadow: 0 1px 2px rgba(0,0,0,0.02);">
        <strong style="color: #24292e; font-size: 14px; display: block; margin-bottom: 6px;">2. Theme Layout Banner Overrides</strong>
        <p style="font-size: 13px; line-height: 1.5; color: #586069; margin: 0;">
          <strong>Problem:</strong> Default layout headers forced rigid green gradient branding boxes on desktop viewports.
          <br>
          <strong>Resolution:</strong> Injected targeted `<style>` element modifications to manually reset header containers with responsive asset URLs.
        </p>
      </div>

      <!-- Challenge 3 -->
      <div style="flex: 1; min-width: 280px; background-color: #ffffff; border: 1px solid #e1e4e8; border-radius: 6px; padding: 18px; box-shadow: 0 1px 2px rgba(0,0,0,0.02);">
        <strong style="color: #24292e; font-size: 14px; display: block; margin-bottom: 6px;">3. Non-Intrusive Telemetry Alerts</strong>
        <p style="font-size: 13px; line-height: 1.5; color: #586069; margin: 0;">
          <strong>Problem:</strong> ErgoChef+ warning windows disrupted physical user cooking flows.
          <br>
          <strong>Resolution:</strong> Restructured notification cycles using progressive visual overlays that clear as soon as posture metrics correct.
        </p>
      </div>

    </div>
    
    <div style="display: flex; flex-direction: row; flex-wrap: wrap; gap: 16px; margin-bottom: 30px;">

      <!-- Challenge 4 -->
      <div style="flex: 1; min-width: 280px; background-color: #ffffff; border: 1px solid #e1e4e8; border-radius: 6px; padding: 18px; box-shadow: 0 1px 2px rgba(0,0,0,0.02);">
        <strong style="color: #24292e; font-size: 14px; display: block; margin-bottom: 6px;">4. Learning Portal Navigation Friction</strong>
        <p style="font-size: 13px; line-height: 1.5; color: #586069; margin: 0;">
          <strong>Problem:</strong> Complex link nesting on eLearn websites increased user multi-click journey loops and cognitive loads.
          <br>
          <strong>Resolution:</strong> Designed a compressed, expandable grid framework to make common actions instantly accessible.
        </p>
      </div>

      <!-- Challenge 5 -->
      <div style="flex: 1; min-width: 280px; background-color: #ffffff; border: 1px solid #e1e4e8; border-radius: 6px; padding: 18px; box-shadow: 0 1px 2px rgba(0,0,0,0.02);">
        <strong style="color: #24292e; font-size: 14px; display: block; margin-bottom: 6px;">5. Anchor Link Navigation Jumps</strong>
        <p style="font-size: 13px; line-height: 1.5; color: #586069; margin: 0;">
          <strong>Problem:</strong> Traditional link clicks caused abrupt page snaps, lowering the overall presentation feel.
          <br>
          <strong>Resolution:</strong> Enabled root document `scroll-behavior: smooth` configurations to provide a fluid sliding transition.
        </p>
      </div>

      <!-- Challenge 6 -->
      <div style="flex: 1; min-width: 280px; background-color: #ffffff; border: 1px solid #e1e4e8; border-radius: 6px; padding: 18px; box-shadow: 0 1px 2px rgba(0,0,0,0.02);">
        <strong style="color: #24292e; font-size: 14px; display: block; margin-bottom: 6px;">6. Viewport Adaptability Constraints</strong>
        <span style="font-size: 13px; line-height: 1.5; color: #586069; display: block;">
          <strong>Problem:</strong> Rigid dimension styling scales skewed multi-column layout matrices on mobile interfaces.
          <br>
          <strong>Resolution:</strong> Standardized flex container parameters to wrap smoothly across varying devices.
        </span>
      </div>

    </div>
  </div>

  <hr style="height: 1px; border: none; background-color: #e1e4e8; margin: 30px 0;">

  <!-- Section: Submission -->
  <div id="submission" style="padding-top: 10px; margin-bottom: 50px;">
    <h2 style="color: #24292e; font-size: 22px; font-weight: 600; margin-bottom: 16px;">📋 Academic Integrity & Submission</h2>
    <div style="background-color: #ffffff; border: 1px solid #e1e4e8; border-radius: 8px; padding: 24px; box-shadow: 0 1px 3px rgba(0,0,0,0.05);">
      <p style="font-size: 14px; color: #24292e; line-height: 1.6; margin: 0;">
        This web portfolio is submitted in strict alignment with university academic integrity code standards. All featured layout components, script configurations, and design narratives represent authentic project work completed during the academic semester term.
      </p>
    </div>
  </div>

</div>
