<style>
@page {
  size: A4;
  margin: 0;
}

body {
  margin: 0;
}

/* THIS is the key part */
* {
  -webkit-print-color-adjust: exact !important;
}
</style>

<div id="a4-page" style="
    width:210mm;
    height:297mm;
    margin:0 auto;
    background:#f5f5f5;
    font-family:sans-serif;
    padding:10mm;
    box-sizing:border-box;
">
    <!-- Black header with bullets -->
    <div id="header" style="
        display:flex;
        justify-content:space-between;
        align-items:center;
        background:black;
        color:white;
        font-size:1.5rem; /* starting font size */
        padding:1rem 2rem;
        width:100%;
        box-sizing:border-box;
        white-space:nowrap;
    ">
      <div class="text">Francesco Hernicsh</div>
      <div style="flex:0; margin:0 0.5rem; color:FloralWhite;">•</div>
      <div class="text">618 409 1278</div>
      <div style="flex:0; margin:0 0.5rem; color:FloralWhite;">•</div>
      <div class="text">chnerichs0822@gmail.com</div>
    </div>


  <div style="display:flex; align-items:flex-start; gap:1rem; margin-top:50px;  width:100%;">
      <!-- Heading (no underline or dash) -->
      <h1 style="
          margin:0; 
          white-space:nowrap; 
          color:black; 
          text-decoration:none; 
          border:none;   /* remove any border underlines */
          font-size:1.2rem;
          margin-right:75px;
      ">
        Summery
      </h1>
      <p style="margin-top:0; line-height:1.4; color:black; text-align: justify;">
        Computer Science student with experience in software development and graphical pipelines. Skilled in C++ and Rust, with strong abilities in writing maintainable code and designing overall system architecture. Looking for gainful employment where I can continue developing my software skills in a professional ollaborativeteam environment
      </p>
  </div>


<div style="font-family:sans-serif; color:black; padding:20px; width:100%;">

  <!-- ROW 1 -->
  <div style="display:flex; gap:20px; align-items:flex-start;">
    <div style="width:180px;">
      <h1 style="margin:0; font-size:1.4rem; line-height:1.2; border: none;"> Professional Experience</h1>
    </div>
    <div style="display:flex; flex-direction:column; align-items:center;">
      <!-- thick near left heading -->
      <div style="width:6px; height:40px; background:black;"></div>
      <!-- thin continuous line extending to next row -->
      <div style="width:2px; height:200px; background:black;"></div>
    </div>
    <div style="width:400px;">
      <h2 style="margin:0; font-size:1.1rem;border: none;">Voxidizer</h2>
      <h3 style="margin-top:6px; font-size:1rem;">3D Voxel rendering Engine</h3>
      <ul style="margin-top:10px; padding-left:24px; font-size:0.95rem; line-height:1.4;">
        <li>Wgsl shader programing</li>
        <li>Graphics pipelining</li>
        <li>Creating design documents</li>
        <li>Programming in Rust</li>
        <li>Developing an internal team organization</li>
      </ul>
    </div>

<div style="
    position:relative;
    width:0; 
    flex-shrink:0;
">
    <div style="
        position:absolute;
        right:-10px;
        top:0;
        white-space:nowrap;
        font-size:0.95rem;
        display:flex;
        gap:12px;
    ">
        <div><strong>Start:</strong> Jan 2025</div>
        <div><strong>Stop:</strong> May 2026</div>
    </div>
</div>


  </div>

  <!-- ROW 2 -->
  <div style="display:flex; gap:20px; align-items:flex-start; margin-top:0px;">
    <div style="width:180px;"></div>
    <div style="display:flex; flex-direction:column; align-items:center;">
      <!-- thick near right heading -->
      <div style="width:6px; height:40px; background:black;"></div>
      <!-- thin continuous line extending downward -->
      <div style="width:2px; height:200px; background:black;"></div>
    </div>
    <div style="width:400px;">
      <h2 style="margin:0; font-size:1.1rem; border: none;">Organizational Management</h2>
      <h3 style="margin-top:6px; font-size:1rem;"> Advised Expansion</h3>
      <ul style="margin-top:10px; padding-left:24px; font-size:0.95rem; line-height:1.4;">
        <li>Developing strategies for outreach to inceares members</li>
        <li>Developing strategies to retain members</li>
        <li>Organizing interorganizational events</li>  <li>Hosting Competitive events</li>
        <li>Raising funds and Security sponsors</li>
      </ul>
    </div>

<div style="
    position:relative;
    width:0; 
    flex-shrink:0;
">
    <div style="
        position:absolute;
        right:-10px;
        top:0;
        white-space:nowrap;
        font-size:0.95rem;
        display:flex;
        gap:12px;
    ">
        <div><strong>Start:</strong> Jan 2025</div>
        <div><strong>Stop:</strong> May 2026</div>
    </div>
</div>

  </div>

  

</div>

<div style="
    display:flex;
    flex-direction:column;
    gap:40px;
    padding:20px 40px;
    font-family:sans-serif;
    color:black;
">
    <!-- ===================== EDUCATION SECTION ===================== -->
    <div style="display:flex; gap:30px;">
        <!-- LEFT TITLE -->
        <div style="width:200px;">
            <h1 style="margin:0; font-size:1.35rem;">Education</h1>
        </div>
        <!-- DEGREE INFO -->
        <div style="display:flex; gap:15px;">
            <div style="width:280px;">
                <div style="font-weight:bold; font-size:1.05rem;">Bachelors of Computer Science</div>
                <div style="margin-top:2px;">Southern Illinois University Edwardsville</div>
                <div style="height:20px;"></div>
                <div style="font-weight:bold; font-size:1.05rem;">Associates of Science</div>
                <div style="margin-top:2px;"> Southwestern Illinois College</div>
            </div>
        </div>
        <!-- Completion Years (Bachelors + Associates) -->
        <div style="margin-left:auto; white-space:nowrap; font-size:0.95rem; display:flex; flex-direction:column; gap:50px;">
            <div><strong>Completion Year:</strong> 2026</div>
            <div><strong>Completion Year:</strong> 2023</div>
        </div>
    </div>
    <!-- ===================== SKILLS SECTION ===================== -->
    <div style="display:flex; gap:30px;">
        <!-- LEFT TITLE -->
        <div style="width:200px;">
            <h1 style="margin:0; font-size:1.35rem;">Additional Skills</h1>
        </div>
        <!-- BULLETS -->
        <div style="width:320px;">
            <ul style="margin:0; padding-left:18px; line-height:1.3; font-size:0.95rem;">
        <li>JavaScript</li>
        <li>Node.js</li>
        <li>Python</li>
        <li>HTML/CSS</li>
        <li>Git & GitHub</li>
        <li>Problem Solving</li>
        <li>Basic AI / Reinforcement Learning concepts</li>
        <li>Debugging & Testing</li>
            </ul>
        </div>
        <!-- Empty right column -->
        <div style="width:150px;"></div>
    </div>

</div>


</div>

<script>
  // Shrink text to fit the header width
  const header = document.getElementById('header');
  const texts = header.querySelectorAll('.text');

  function shrinkText() {
    let fontSize = 15; // starting font size in px
    texts.forEach(t => t.style.fontSize = fontSize + 'px');
    
    while(header.scrollWidth > header.clientWidth && fontSize > 8) {
      fontSize -= 1;
      texts.forEach(t => t.style.fontSize = fontSize + 'px');
    }
  }

  shrinkText();
  window.addEventListener('resize', shrinkText);
</script>
