---
permalink: /
title: "BIOGRAPHY"
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---

<style>
  /* =========================================
     1. STATIC LIGHT THEME VARIABLES (Locked)
     ========================================= */
  :root {
    --port-primary: #2c3e50;    /* Dark Academic Blue */
    --port-text: #3b3b3b;       /* Dark Gray for readability */
    --port-muted: #64748b;      /* Muted gray for subtitles */
    --port-bg: #fdfdfd;         /* Almost white for cards */
    --port-border: #eaeaea;     /* Light gray borders */
    --accent-color: #f0f7ff;    /* Soft blue for milestones */
  }

  /* =========================================
     2. GLOBAL HEADER FIXES (Matches Portfolio)
     ========================================= */
  .masthead, 
  .masthead__inner-wrap, 
  .masthead__menu, 
  .masthead__menu ul, 
  .greedy-nav {
    background-color: #ffffff !important;
    background: #ffffff !important;
  }
  
  .masthead {
    border-bottom: 1px solid var(--port-border) !important;
  }

  .masthead a, 
  .masthead__menu-item,
  .masthead__menu-item a,
  .greedy-nav a, 
  .greedy-nav .visible-links,
  .greedy-nav .visible-links li,
  .greedy-nav .visible-links a {
    background-color: transparent !important;
    background: transparent !important;
    color: var(--port-text) !important;
  }

  .masthead a:hover,
  .greedy-nav a:hover,
  .greedy-nav .visible-links a:hover,
  .greedy-nav .visible-links li.masthead__menu-item--current a,
  .greedy-nav .visible-links li.masthead__menu-item--current a:hover {
    background-color: transparent !important;
    background: transparent !important;
    color: var(--port-primary) !important;
  }

  h1.page__title, .page__title {
    color: var(--port-primary) !important;
    font-weight: 700 !important;
  }

  /* =========================================
     3. BIOGRAPHY LAYOUT STYLES
     ========================================= */
  /* Standardized Section Titles */
  .section-title {
    margin-top: 45px; 
    border-bottom: 1px solid var(--port-border); 
    padding-bottom: 8px; 
    text-transform: uppercase; 
    color: var(--port-primary) !important;
    font-size: 1.15em !important; 
    letter-spacing: 0.1em;
    font-weight: 700;
  }

  /* Standardized Text Style for Bio */
  .content-text {
    text-align: justify !important; 
    text-justify: inter-word !important;
    font-size: 0.95em; 
    line-height: 1.7; 
    margin-bottom: 20px; 
    color: var(--port-text);
  }

  /* Collaboration Alert */
  .collab-box {
    background-color: var(--accent-color);
    border-left: 4px solid var(--port-primary);
    padding: 14px 18px;
    font-size: 0.95em;
    color: var(--port-primary);
    font-weight: 500;
    margin: 30px 0;
    border-radius: 0 4px 4px 0;
    box-shadow: 0 1px 3px rgba(0,0,0,0.03);
    line-height: 1.6;
  }

  /* Research Interest Badges */
  .interest-pills {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    margin-top: 15px;
    margin-bottom: 30px;
  }
  
  .pill {
    background-color: var(--port-primary); 
    color: #ffffff; 
    font-size: 0.85em; 
    font-weight: 600;
    padding: 6px 14px;
    border-radius: 4px; 
    letter-spacing: 0.03em;
    box-shadow: 0 2px 4px rgba(0,0,0,0.05);
  }

  /* News Timeline Styling */
  .news-scroll-container {
    max-height: 500px; 
    overflow-y: auto; 
    margin-top: 20px;
    padding-right: 15px;
  }
  
  .news-scroll-container::-webkit-scrollbar { width: 5px; }
  .news-scroll-container::-webkit-scrollbar-track { background: var(--port-bg); }
  .news-scroll-container::-webkit-scrollbar-thumb { background: #d1d5db; border-radius: 10px; }
  .news-scroll-container::-webkit-scrollbar-thumb:hover { background: #9ca3af; }

  .timeline-item {
    display: flex; 
    margin-bottom: 14px; 
    font-size: 0.9em; 
    line-height: 1.5;
    padding: 4px 0;
    align-items: baseline; 
  }
  
  .timeline-date {
    min-width: 95px; 
    font-weight: 700; 
    color: var(--port-muted); 
  }
  
  .timeline-content {
    flex: 1; 
    color: var(--port-text);
    word-wrap: break-word; /* Prevents text cutoff */
  }

  /* Highlighted Milestones */
  .timeline-item.milestone {
    background-color: var(--accent-color); 
    border-radius: 4px;
    padding: 8px 12px; /* Added horizontal padding to prevent cutoff */
    margin-left: -12px; /* Offsets the padding to align visually */
    margin-top: 2px;
    margin-bottom: 12px;
  }

  /* Mobile & Tablet Responsiveness */
  @media (max-width: 768px) {
    .timeline-item { 
      flex-direction: column; 
      margin-bottom: 18px;
    }
    .timeline-date { 
      margin-bottom: 4px; 
      font-size: 0.85em; 
      color: var(--port-primary);
    }
    .timeline-item.milestone { 
      margin-left: 0; 
      padding: 10px 12px;
    }
  }
</style>

<div class="content-text">
    <p>
      <strong>Dr. Nadeem Tariq Beigh</strong> is an interdisciplinary researcher and technology developer specialising in intelligent flexible electronics,
      wearable sensing, printed devices, multifunctional nanocomposites, MEMS/NEMS, and self-powered systems. He is currently a <strong>Visiting Researcher at the Indian Institute of Technology Delhi</strong>, where he continues his work on intelligent microsystems, nonlinear devices, energy harvesting, and advanced sensing technologies. Before returning to IIT Delhi, he completed his postdoctoral research at the Smart and Intelligent Sensors Laboratory, Khalifa University, Abu Dhabi.
    </p>
    <p>
      At Khalifa University, Dr. Beigh developed a range of low-cost and scalable sensing technologies, including porous graphene–polymer pressure sensors,
      electrohydrodynamically printed MXene-based devices, wearable respiratory-monitoring platforms, multifunctional tactile–thermal composites, and flexible IoT systems. His research also explored nonlinear PMUT dynamics and physical reservoir computing. Several of these technologies progressed to TRL-4 prototypes, patent applications, and
      commercialisation pathways in healthcare, robotics, and AgriTech.
    </p>
    <p>
      Previously, he worked at Nanyang Technological University, Singapore, on the integration of MEMS with terahertz switching and reconfigurable
      high-frequency systems. He received his Ph.D. in Electrical Engineering from IIT Delhi, where he developed photopatternable multifunctional
      nanocomposites with combined piezoelectric and triboelectric behaviour for mechanical energy harvesting and self-powered sensing. His research is distinguished by a complete technology-development approach: from materials design and microfabrication to device characterisation, embedded integration, AI-assisted interpretation, and real-world prototyping.
    </p>
    </div>
   <i class="fas fa-lightbulb" style="color: #64748b; margin-right: 8px;"></i>
      His long-term ambition is to create intelligent, autonomous, and
      sustainable sensing platforms for healthcare, human–machine interaction,
      precision agriculture, environmental monitoring, and Industry 5.0.
      </div>
  


<h2 class="section-title">Research Interests</h2>
<div class="interest-pills">
  <span class="pill">MEMS/NEMS</span>
  <span class="pill">Wearables</span>
  <span class="pill">Piezo/Tribo/Resistive Sensing</span>
  <span class="pill">Self-Powered System</span>
  <span class="pill">Smart Sensors</span>
</div>

<h2 class="section-title">Recent News</h2>
<div class="news-scroll-container">
  
  <div class="timeline-item milestone">
    <div class="timeline-date">July 2026</div>
    <div class="timeline-content">Dr. Nadeem delivered a talk at Global Conference on Graphene & 2D Advanced Materials, Paris, on " From Flakes to Functions- Translating 2D materials into marketable technologies.</div>
  </div>
  
  <div class="timeline-item">
    <div class="timeline-date">Jun 2026</div>
    <div class="timeline-content">Our review paper accepted in Sensors and Actuator Reports.</div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">July 2024</div>
    <div class="timeline-content">Microclimate temperature analysis paper accepted in <strong>Sustainable Cities and Society</strong>.</div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Jun 2024</div>
    <div class="timeline-content">Urban Heat Island forecasting paper published in the <strong>Journal of Environmental Informatics</strong>.</div>
  </div>

  <div class="timeline-item milestone">
    <div class="timeline-date">Aug 2023</div>
    <div class="timeline-content">Joined the <strong>Department of Urban Development</strong> as a <strong>Climate Data Scientist</strong>.</div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Jul 2023</div>
    <div class="timeline-content">Book chapter accepted in the <strong>Handbook of Computational Sustainability</strong> (Springer).</div>
  </div>

  <div class="timeline-item milestone">
    <div class="timeline-date">Dec 2022</div>
    <div class="timeline-content">Graduated with an <strong>M.Sc. in Geospatial Analytics</strong> (CGPA: 4.0).</div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Aug 2021</div>
    <div class="timeline-content">Joined the <strong>Institute of Earth Sciences</strong> as a <strong>Graduate Research Assistant</strong>.</div>
  </div>

</div>
