
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kristian Alikaj</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300&display=swap');
    :root {
      --main-background: #0b0c0f;
      --main-fonts-color: #fff;
      --main-decor-color: #00a9e2;
      --main-header-background: #21252e;
      --main-font-family: 'Poppins', sans-serif;
    }

    * {
      margin: 0;
      padding: 0;
      scroll-behavior: smooth;
      box-sizing: content-box;
    }

    body {
      font-family: var(--main-font-family);
      background-image: url(https://get.wallhere.com/photo/programmers-hacking-code-computer-dark-minimalism-ASCII-art-1161344.jpg);
      background-color: rgb(3, 14, 19);
      color: var(--main-fonts-color);
    }

    main {
      padding-top: 70px;
    }

    header {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 70px;
      display: flex;
      align-items: center;
      justify-content: space-around;
      background:transparent;
      z-index: 1000;
    }

    .logo img {
      padding-top: 5px;
      height: 50px;
      cursor: pointer;
    }

    .active {
      background: var(--main-decor-color);
    }

    #home {
      margin: auto;
      padding: 20px;
      display: flex;
      flex-direction: column;
      align-items: normal;
      justify-content: space-evenly;
    }

    .intro {
      text-align: center;
      margin: auto;
      text-shadow: #0b0c0f;
      text-size-adjust: var(--main-font-family);
      padding: 0 20px;
    }

    .intro-content {
      margin: 20px 0;
    }

    .intro-box {
      background-color: rgba(3, 20, 23, 0.5);
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0px 0px  var(--main-decor-color);
      text-align: left;
      font-size: 18px;
      max-width: 900px;
      margin: 20px auto;
    }

    .intro a {
      text-decoration-line: none;
      color: var(--main-decor-color);
    }

    h2 {
      padding-bottom: 15px;
      letter-spacing: normal;
      font-size: 60px;
      color: var(--main-fonts-color);
      text-shadow: 0px 0px 40px var(--main-decor-color);
    }

    strong {
      font-size: 20px;
      color: var(--main-fonts-color);
    }

   
    
    /* Social media */
    .social-media a {
      margin: 10px;
      font-size: 2rem;
      text-align: center;
      color: var(--main-fonts-color);
    }

    .social-media a:not(:last-child) {
      margin-right: 20px;
    }

    .social-media a:hover {
      color: var(--main-decor-color);
      text-shadow: 0 0 50px var(--main-decor-color);
    }

    .social-media a[href*="mailto"] {
      font-size: 1.2rem;
      color: var(--main-fonts-color);
      text-decoration: none;
    }

    .social-media a[href*="mailto"]:hover {
      color: var(--main-decor-color);
      text-shadow: none;
    }

    /* Projects */
    #projects h3 {
      text-align: center;
      letter-spacing: normal;
      font-size: 60px;
      color: var(--main-fonts-color);
      text-shadow: 0px 0px 40px var(--main-decor-color);
    }

    .project-list {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 0 20px;
    }

    .project-card {
      width: calc(33.33% - 40px);
      margin: 20px;
      padding: 20px;
      background-color: rgba(2, 14, 17, 0.4);
      border-radius: 10px;
      box-shadow: 0px 0px  var(--main-decor-color);
      text-align: left;
    }

    .project-card h4 {
      font-size: 25px;
      margin-bottom: 10px;
      color: var(--main-fonts-color);
    }

    .project-card p {
      font-size: 17px;
      margin-bottom: 10px;
      color: var(--main-fonts-color);
    }

    .project-card a {
      font-size: 20px;
      color: var(--main-decor-color);
      text-decoration: none;
    }

    .project-card a:hover {
      color: var(--main-fonts-color);
    }

    /* Contact */
    #contact h3 {
      text-align: center;
      letter-spacing: normal;
      font-size: 60px;
      color: var(--main-fonts-color);
      text-shadow: 0px 0px 40px var(--main-decor-color);
    }

    .contact-box {
      background-color: rgba(2, 14, 17, 0.4);
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0px 0px  var(--main-decor-color);
      text-align: left;
      max-width: 900px;
      margin: 20px auto;
    }

    #contact p {
      font-size: 1.2rem;
    }

    /* Media Queries */
    @media screen and (max-width: 768px) {
      .project-card {
        width: calc(50% - 40px);
      }
    }

    @media screen and (max-width: 480px) {
      .project-card {
        width: calc(100% - 40px);
      }
    }
  </style>
 <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.13.0/css/all.css">
 <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script></head>
<body>
    <div class="container">
      <header>
        <a class="logo" href="#home"></a>
      </header>
      
      <main>
        <div id="home">
          <section class="intro">
            <h2>Kristian Alikaj<hr></h2>
            <div class="intro-content">
              <strong>Bioinformatics | <a href="https://www.mi.fu-berlin.de/en/bioinf/stud/bachelor/index.html" target="_blank" style="color: #00a9e2;">Freie Universität Berlin</a></strong>
              <div class="intro-box">
                <p>During my studies for Bioinformatics at Freie Universität Berlin/Charité – Universitätsmedizin Berlin, I have developed expertise in omics analysis, bioinformatics software development, and the application of machine learning to biological data.<br> I am proficient in C++, Python, R, and SQL, and have some experience with Julia, and Haskell.<br> The projects and web applications listed below showcase my skills, and you can also find my work on my GitHub profile.</p>
              </div>
            </div>
          </section>
        </div>
    

        <div id="projects">
          <section class="projects-section">
            <h3>Projects<hr></h3>
            <div class="project-list">
              <div class="project-card">
                <h4>Bioinformatics & C++</h4>
                <p>C++ : Global Alignment, Horspool Algorithm, Aho-Corasick- and Q-Gram Index Search, BLAST Neighborhood, RNA Structure Prediction, Suffix Array & BWT including a web app 'WEB SEQ' to deploy them.</p>
                <p><a href="https://github.com/kris96tian/dsa_cpp" target="_blank">View Repository</a> <br><a href="https://vine-mirage-roquefort.glitch.me/" target="_blank">WEB APP</a></p>
              </div>
              
              <div class="project-card">
                <h4>Pytorch: ECG Silent Heart attacks</h4>
                <p>A machine learning project using Pytorch for health in AI. Skills gained during an Internship at the Berlin Institute of Health.</p>
                <a href="https://github.com/kris96tian/machine_learning_ecg" target="_blank">View Project</a>
              </div>
               <div class="project-card">
    <h4>SNP/Variant Calling Analysis</h4>
                <p>Experience with <strong>fastQC, bwa, samtools, bedtools, bcf/vcftools, or gatk</strong> in bash/Unix, as well as automatization with PyScripts (PyVCF) or workflow management systems like Snakemake</p>
              </div>

              <div class="project-card">
                <h4>scRNA-Analysis</h4>
                <p>Experience performing analysis using R (Seurat), Python (Scanpy), a little bit of Julia.</p>
                <a href="https://github.com/kris96tian/sc-RNAseq_analysis" target="_blank">Repository with my Notebooks</a>
              </div>

<div class="project-card">
                <h4>App: Phylogenetic Trees</h4>
                <p>A Python application built using Streamlit that provides functionalities for constructing phylogenetic trees using various clustering methods and algorithms.</p>
                <a href="https://phylogenetictreegenerator.streamlit.app/" target="_blank">Visit Web-App</a>
             </div>
 
              <div class="project-card">
                <h4>Diabetes Prediction</h4>
                <p>A web app to predict the risk of diabetes being trained on patient data. Backend with Python [Maschine Learning] and Frontend with HTML/CSS via Flask.</p>
                <a href="https://diabetesp.pythonanywhere.com/" target="_blank">View Web-App</a>
              </div>
              
 <div class="project-card">
                <h4>Bioinformatics Tools</h4>
                <p>A web app showcasing some bioinformatics tools for generating suffix arrays, Burrows-Wheeler transforms, and FM indices for input strings, and translate DNA sequences into their corresponding protein sequences</p>
                <a href="https://bioinfotools.streamlit.app/" target="_blank">View Web-App</a>
              </div>

 <div class="project-card">
                <h4>Genomic Analysis of COVID Variants</h4>
                <p>COVID-19 sequence analysis: data exploration, metadata parsing, sequence download, alignment, mutation identification, amino acid translation, and storage.</p>
                <a href="https://github.com/kris96tian/corona_mutations_analysis" target="_blank">View Repository</a>
              </div>
					 <div class="project-card">
                <h4>Haskell & Bioinformatics</h4>
                <p>Re-Diving into Haskell & the benefits of functional programming.</p>
                <a href="https://github.com/kris96tian/HASKELL" target="_blank">Repository</a>
              </div>
                   
            
	<div class="project-card">
                <h4>Rain forest</h4>
                <p>A website developed with HTML & CSS</p>
                <a href="https://userpage.fu-berlin.de/kristiaa96/forest" target="_blank">View Website</a>
             		     </div>
              </div>
            </div>
          </section>
        </div>
      </main>
      
      <div id="contact">
        <h3>Contact me<hr></h3>
        <div class="contact-box">
          <p>I am actively seeking internship or job opportunities in the field of bioinformatics or related areas. Please feel free to contact me if you have any openings or would like to discuss potential collaborations.</p>
          <div class="social-media">
            <a href="https://github.com/kris96tian" target="_blank" class="social-media"><i class='fab fa-github'></i></a>
<a href="https://www.linkedin.com/in/kristianalikaj/" target="_blank" class="social-media"><i class='fab fa-linkedin-in'></i></a>

            <a href="mailto:kristian.alikaj@fu-berlin.de">Email</a>
          </div>
        </div>
      </div>
      
      </div>
      </body>
      </html>
