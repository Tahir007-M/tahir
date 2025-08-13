<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Mohammed Tahir Khan — Resume</title>
<style>
  :root{
    --bg:#f6f8fb;
    --card:#ffffff;
    --text:#1f2937;
    --muted:#6b7280;
    --accent:#2563eb;
    --chip:#eef2ff;
    --border:#e5e7eb;
  }
  /* Layout */
  *{box-sizing:border-box}
  html,body{height:100%}
  body{
    margin:0;
    font:16px/1.55 system-ui,-apple-system,Segoe UI,Roboto,Inter,Helvetica,Arial,sans-serif;
    color:var(--text);
    background:var(--bg);
  }
  .page{
    max-width:1000px;
    margin:32px auto;
    padding:0 16px;
  }
  .card{
    background:var(--card);
    border:1px solid var(--border);
    border-radius:16px;
    box-shadow:0 6px 20px rgba(17,24,39,.06);
    overflow:hidden;
  }
  header{
    display:grid;
    grid-template-columns:1fr;
    gap:12px;
    padding:28px 28px 14px;
    border-bottom:1px solid var(--border);
    background:linear-gradient(180deg,#ffffff 0%, #fafafa 100%);
  }
  .name{
    font-size:clamp(26px,3.4vw,36px);
    font-weight:800;
    letter-spacing:.2px;
  }
  .contact{
    display:flex;
    flex-wrap:wrap;
    gap:12px 18px;
    color:var(--muted);
    font-weight:500;
  }
  .contact a{color:inherit;text-decoration:none;border-bottom:1px dotted transparent}
  .contact a:hover{border-bottom-color:currentColor}

  /* Sections */
  .content{
    display:grid;
    grid-template-columns: 1fr 320px;
    gap:28px;
    padding:24px 28px 28px;
  }
  @media (max-width: 880px){
    .content{grid-template-columns:1fr}
  }
  section{margin-bottom:22px}
  h2{
    font-size:18px;
    margin:0 0 10px;
    letter-spacing:.4px;
    text-transform:uppercase;
    color:#111827;
    display:flex;align-items:center;gap:10px;
  }
  h2::before{
    content:"";
    width:6px;height:18px;border-radius:3px;background:var(--accent);
    display:inline-block;
  }
  p{margin:0 0 10px;color:#111827}
  .muted{color:var(--muted)}

  /* Lists & chips */
  .bullets{padding-left:18px;margin:6px 0}
  .bullets li{margin:6px 0}
  .chips{
    display:flex;flex-wrap:wrap;gap:8px;
    margin:8px 0 0;
  }
  .chip{
    background:var(--chip);
    color:#3730a3;
    border:1px solid #dfe3ff;
    padding:6px 10px;
    border-radius:999px;
    font-size:13px;
    font-weight:600;
    white-space:nowrap;
  }
  .item{
    border:1px solid var(--border);
    border-radius:12px;
    padding:12px 14px;
    margin:10px 0;
    background:#fff;
  }
  .item h3{
    margin:0 0 4px;
    font-size:16px;
  }
  .row{
    display:flex;flex-wrap:wrap;gap:10px;
    color:var(--muted);font-size:14px
  }

  /* Sidebar */
  .sidebar .box{
    border:1px solid var(--border);
    border-radius:12px;
    padding:14px;
    background:#fcfcff;
    margin-bottom:16px;
  }

  /* Print styles */
  @media print{
    :root{--bg:#fff;--card:#fff;--border:#e5e7eb}
    body{background:#fff}
    .page{margin:0;padding:0}
    .card{box-shadow:none;border:0;border-radius:0}
    header{padding:8px 0 6px;border-bottom:1px solid var(--border);background:#fff}
    .content{padding:12px 0 0;gap:18px}
    a{color:inherit;text-decoration:none}
  }
</style>
</head>
<body>
  <div class="page">
    <div class="card">
      <!-- Header -->
      <header>
        <div class="name">Mohammed Tahir Khan</div>
        <div class="contact">
          <span>📞 8217808944</span>
          <span>✉️ <a href="mailto:tahirkhan6204@gmail.com">tahirkhan6204@gmail.com</a></span>
          <!-- Add LinkedIn/GitHub later if you like -->
        </div>
      </header>

      <!-- Main content -->
      <div class="content">
        <!-- Main column -->
        <main>
          <section>
            <h2>Professional Summary</h2>
            <p>Motivated and detail-oriented college student with a strong interest in technology, efficient problem solving, and social relationships. Brings curiosity for innovative solutions, keen organizational skills, and eagerness to contribute in fast-paced, collaborative environments. Known for a proactive approach to learning and a commitment to personal and professional growth.</p>
          </section>

          <section>
            <h2>Experience</h2>

            <div class="item">
              <h3>Academic Projects &amp; Practical Learning</h3>
              <div class="row">
                <span>St. Philomena’s College, Mysuru, Karnataka</span>
                <span>•</span>
                <span>Ongoing — 2023 to Present</span>
              </div>
              <ul class="bullets">
                <li>Developed small-scale applications and programs in C, Java, Python, and R as part of coursework and lab exercises.</li>
                <li>Collaborated with peers on coding assignments, debugging, and optimizing solutions for efficiency.</li>
                <li>Applied data analysis techniques in R and Python for academic research tasks.</li>
                <li>Practiced problem-solving and logical thinking through programming challenges and project-based learning.</li>
              </ul>
            </div>
          </section>

          <section>
            <h2>Projects</h2>

            <div class="item">
              <h3>Water Dispenser using Arduino Uno</h3>
              <ul class="bullets">
                <li>Designed and built an automated water dispenser system controlled by an Arduino Uno microcontroller.</li>
                <li>Programmed the Arduino to manage water flow based on sensor inputs for efficient, user-friendly operation.</li>
                <li>Strengthened understanding of embedded systems, microcontroller programming, and sensor integration.</li>
                <li>Troubleshot hardware and software challenges throughout development.</li>
              </ul>
            </div>
          </section>
        </main>

        <!-- Sidebar -->
        <aside class="sidebar">
          <section class="box">
            <h2>Skills</h2>
            <div class="chips">
              <span class="chip">C</span>
              <span class="chip">R</span>
              <span class="chip">Java</span>
              <span class="chip">Python</span>
              <span class="chip">Problem-Solving</span>
              <span class="chip">Data Analysis (R &amp; Python)</span>
              <span class="chip">OOP (Java)</span>
              <span class="chip">Basic DBMS</span>
              <span class="chip">Debugging</span>
              <span class="chip">Teamwork &amp; Communication</span>
            </div>
          </section>

          <section class="box">
            <h2>Education</h2>
            <div class="item" style="margin:0">
              <h3 style="margin:0 0 6px">Bachelor of Computer Applications (BCA) — 5th Semester</h3>
              <div class="row">
                <span>St. Philomena’s College, Mysuru, Karnataka</span>
              </div>
              <div class="muted" style="margin-top:6px">Expected Graduation: 2026</div>
            </div>
          </section>

          <section class="box">
            <h2>Languages</h2>
            <div class="chips">
              <span class="chip">English</span>
              <span class="chip">Hindi</span>
              <span class="chip">Kannada</span>
            </div>
          </section>
        </aside>
      </div>
    </div>
  </div>
</body>
</html>

