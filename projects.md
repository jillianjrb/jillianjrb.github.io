---
layout: page
title: My Work
order: 2
---

<h2 class="page-title">My Work</h2>

<p class="projects-intro reveal">
  My past and present projects. Click any card to read more.
</p>

<div class="projects-grid">

  <!-- ── Card 1: LORIA ── -->
  <a href="#project-loria" class="project-card reveal" id="card-loria" onclick="openProject('loria'); return false;">
    <div class="project-card-header">
      <span class="project-card-tag">Research · Completed</span>
      <div class="project-card-title">Voice Biomarker Validation</div>
      <div class="project-card-org">LORIA, University of Lorraine</div>
      <svg class="project-card-arrow" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
        <path d="M7 17L17 7M17 7H7M17 7v10"/>
      </svg>
    </div>
    <div class="project-card-body">
      <p class="project-card-desc">
       Rigorously evaluated fundamental frequency as a depression biomarker, revealing 
       samplie-level and demographic confounding variables that limit its standalone 
       clinical robustness.
      </p>
    </div>
  </a>

  <!-- ── Card 2: Wordification ── -->
  <a href="#project-wordification" class="project-card reveal" id="card-wordification" onclick="openProject('wordification'); return false;">
    <div class="project-card-header">
      <span class="project-card-tag">EdTech · Collaborative</span>
      <div class="project-card-title">Wordification</div>
      <div class="project-card-org">ScholasTech LLC &amp; Univ. of South Carolina</div>
      <svg class="project-card-arrow" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
        <path d="M7 17L17 7M17 7H7M17 7v10"/>
      </svg>
    </div>
    <div class="project-card-body">
      <p class="project-card-desc">
        Pedagogically and linguistically driven spelling instruction for K–8 students with dialect-aware
        phonics awareness — made possible with personalized voiced synthesis.
      </p>
    </div>
  </a>

  <!-- ── Card 3: DetectErreur ── -->
  <a href="#project-detecterreur" class="project-card reveal" id="card-detecterreur" onclick="openProject('detecterreur'); return false;">
    <div class="project-card-header">
      <span class="project-card-tag">NLP Tool · Completed</span>
      <div class="project-card-title">DetectErreur</div>
      <div class="project-card-org">University of Lorraine — M1 Project</div>
      <svg class="project-card-arrow" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
        <path d="M7 17L17 7M17 7H7M17 7v10"/>
      </svg>
    </div>
    <div class="project-card-body">
      <p class="project-card-desc">
        A French writing assistant for L2 learners that detects errors, offers
        corrections, and generates pedagogically relevant feedback using symbolic AI
        and machine-learning solutions.
      </p>
    </div>
  </a>

</div>

<!-- ══════════════════════════════════════════════
     PROJECT DETAIL PANELS (hidden by default)
     ══════════════════════════════════════════════ -->

<div id="project-loria" class="project-detail" style="display:none;">
  <a href="#" class="project-detail-back" onclick="closeProject(); return false;">
    <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M19 12H5M12 5l-7 7 7 7"/></svg>
    Back to all projects
  </a>

  <h2 class="page-title">Voice Biomarker Validation</h2>
  <p class="page-subtitle">LORIA, University of Lorraine &nbsp;·&nbsp; January 2026 – June 2026</p>
  <hr class="divider" />

  <blockquote>
    <strong>ABSTRACT:</strong> Despite clinical interest in diagnosing depression on the basis of vocal behavior,
    little research has been done to evaluate the robustness of these features as biomarkers. 
    Previous work has found links between depressive behavior and reductions
    in mean F0 and range of the patient’s voice, though a rigorous evaluation has not
    been performed on how these trends have emerged nor their precision in identifying
    depressive traits. The present study investigated the robustness of F0 (mean
    and standard deviation) as a potential vocal biomarker of depressive traits through
    the application of the V3 framework on the Androids Corpus. This project is conducted
    in three parts: first, during verification, F0 extraction is evaluated by means of a 
    linear mixed model to ensure no part of the feature computation pipeline adds 
    variation to F0. Second, analytical validation was conducted through use of a linear 
    mixed model to assess whether biological or procedural characteristics confound F0’s 
    diagnostic capacity. Lastly, at a clinical validation stage, a classification model 
    investigated whether F0 holds any predictive potential in guiding the diagnosis of 
    depressive traits. Ultimately, the findings suggested that while F0 carries an 
    exploratory predictive signal for depression detection, its value is significantly
    affected by the means of extraction (particularly the use of toolbox). Additionally, 
    different groups categorized according to sex and age exhibited different trends 
    in F0 mean while groups formed according to speech task type exhibited different 
    trends in F0 variability. Therefore, F0 lacks the robustness required for reliable
    use as a standalone vocal biomarker in real-world conditions.
  </blockquote>

  <p>
    From January to June 2026, I participated in a project that interrogated and evaluated how research has approached vocal biomarkers.  Through this project, we performed a validation pipeline on fundamental frequency (F0) as a vocal biomarker of depression using <a href="https://www.nature.com/articles/s41746-020-0260-4">DiME’s proposed V3 framework</a>.  While much research has correlated measures of speech behavior with depression diagnoses, there has been little consideration as to if these metrics are identifying symptoms of depression or if they are recorded confounding variables related to the collection of data or underlying physical conditions of these patients.  This project was produced to evaluate and implore the application of validation frameworks in current and future biomarker research.
  </p>
  <p>
    I worked alongside my team (<a href="https://www.linkedin.com/in/ma%C3%A9-dugoua-jacques-9594102b2/">Maé Dugoua-Jacques</a>, <a href="https://www.linkedin.com/in/monicapasqualini/">Monica Pasqualini</a>, <a href="https://www.linkedin.com/in/mp0pa/en/?lipi=urn%3Ali%3Apage%3Ad_flagship3_detail_base%3BNPzE4B4uQku6ui104F8TKQ%3D%3D">Maria Popa</a>) and under our supervisors (<a href="https://www.linkedin.com/in/vincent-p-martin-139841115/?lipi=urn%3Ali%3Apage%3Ad_flagship3_detail_base%3BNPzE4B4uQku6ui104F8TKQ%3D%3D">Vincent P. Martin</a>, <a href="https://www.linkedin.com/in/elio-alex-stasica-b320b1250/?lipi=urn%3Ali%3Apage%3Ad_flagship3_detail_base%3BNPzE4B4uQku6ui104F8TKQ%3D%3D">Elio Stasica</a>) to evaluate the robustness of F0 as a biomarker through the application of linear mixed-effect models (LMMs) on speech samples from the <a href="https://www.isca-archive.org/interspeech_2023/tao23_interspeech.pdf">Androids Corpus</a> according to their available metadata.  The application of LMMs was performed to isolate each available variable and control for confounding effects.  Additionally, we fine-tuned a logistic regressor to determine if depression diagnoses could be predicted on the basis of extracted F0 mean and variability data when controlled for select groups.
  </p>
  <p>
    We are pursuing the opportunity to publish our findings along with those of our supervisors’ related projects in the near future, so
    unfortunately our full report cannot be shared at this time.
  </p>
</div>

  <h3>Key areas</h3>
  <p>
    <em>Signal processing for speech feature extraction &nbsp;·&nbsp; Demographic
    confound analysis &nbsp;·&nbsp; Diagnostic pipeline development &nbsp;·&nbsp; Clinical biomarker validation &nbsp;·&nbsp; NLP in Clinical applications &nbsp;·&nbsp; Mixed-effects statistical modeling &nbsp;·&nbsp; Logistic regression modeling &nbsp;·&nbsp;</em>
  </p>

<div id="project-wordification" class="project-detail" style="display:none;">
  <a href="#" class="project-detail-back" onclick="closeProject(); return false;">
    <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M19 12H5M12 5l-7 7 7 7"/></svg>
    Back to all projects
  </a>

  <h2 class="page-title">Wordification</h2>
  <p class="page-subtitle">ScholasTech LLC &amp; University of South Carolina</p>
  <hr class="divider" />

  <p>
    Wordification is a project from <strong>ScholasTech, LLC</strong> and the
    <strong>University of South Carolina</strong> to create personalized spelling
    instruction and practice for K–8 students. To teach literacy effectively, the
    platform prioritizes phonics awareness and offers <strong>dialect-enhanced
    instruction</strong>. Wordification is first of its kind in that its educational materials are
    catered and personalized to speakers of different dialects — an important
    step toward more equitable literacy education.
  </p>
  <p>
    Through this project, I have had the privilege of speaking with several educators and administrators about the state of reading and writing education in the classrooms as well as test out the current softwares made available to them.  In my research, I have observed that current applications of voice processing in computer-assisted language learning in the United States are merely designed to implement a standardized American English pronunciation--with no awareness of regional accents or lenience to natural speech behavior such as pauses and repetitions of words.  What matters most to the education of students is simple: building the skills for a lifetime of reading and writing.  
  </p>
  <p>
    The most exciting part of my work at Wordification thus far is considering applying synthetic voice technology to allow teachers to craft more personalized and linguistically aware online lessons for their students.  Many common spelling errors in young students arise from the incorrect application of spelling conventions on different productions of speech (<em>How can students learn to spell by sounding out "pin" and "pen" or "sit" and "seat" if the speaker's native accent pronounces these the same way?</em>).  Dialectally aware education will allow educators to customize the students' activities with local accents and voices through the voice cloning of a diverse group of voice actors to implement lessons that target these specific common phonic errors and personalize students' lessons with respect to their most frequent errors.
  </p>

  <a href="https://wordification.scholastechnology.com/"
    target="_blank" rel="noopener"
    class="hero-cta">
    Visit the Wordification site
    <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
      <path d="M5 12h14M12 5l7 7-7 7"/>
    </svg>
  </a>
</div>

<div id="project-detecterreur" class="project-detail" style="display:none;">
  <a href="#" class="project-detail-back" onclick="closeProject(); return false;">
    <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M19 12H5M12 5l-7 7 7 7"/></svg>
    Back to all projects
  </a>

  <h2 class="page-title">DetectErreur</h2>
  <p class="page-subtitle">Université de Lorraine — Master 1, Semester 1 Project &nbsp;·&nbsp; Completed</p>
  <hr class="divider" />

  <p>
    DetectErreur is a digital tool designed to assist <strong>learners of French
    as a second language</strong>. By encoding the rules of the French language in
    Python alongside machine learning methods, the tool detects writing errors,
    offers corrections, and provides pedagogically relevant feedback.
  </p>
  <p>
    It uses <strong>Retrieval Augmented Generation (RAG)</strong> with
    <strong>Mistral NeMo 12B</strong> to generate feedback that directly cites the
    rules of French — giving learners explanations grounded in linguistic authority
    rather than generic suggestions.
  </p>
  <p>
    Developing DetectErreur gave me hands-on experience with RAG pipelines and the
    challenges of building language tools that are both linguistically accurate and
    pedagogically sound.
  </p>

  <img src="{{ site.baseurl }}/images/detecterreur_attempt.png"
       alt="DetectErreur interface screenshot"
       class="project-detail-img" />
</div>

<script>
  function openProject(id) {
    // hide grid, show detail
    document.querySelector('.projects-grid').style.display = 'none';
    document.querySelector('.projects-intro').style.display = 'none';
    var detail = document.getElementById('project-' + id);
    detail.style.display = 'block';
    // smooth scroll to top of content
    window.scrollTo({ top: 0, behavior: 'smooth' });
    // fade in
    detail.style.opacity = '0';
    detail.style.transform = 'translateY(14px)';
    detail.style.transition = 'opacity 0.4s ease, transform 0.4s ease';
    requestAnimationFrame(function() {
      requestAnimationFrame(function() {
        detail.style.opacity = '1';
        detail.style.transform = 'translateY(0)';
      });
    });
  }

  function closeProject() {
    var details = document.querySelectorAll('.project-detail');
    details.forEach(function(d) { d.style.display = 'none'; });
    document.querySelector('.projects-grid').style.display = 'grid';
    document.querySelector('.projects-intro').style.display = 'block';
    window.scrollTo({ top: 0, behavior: 'smooth' });
  }
</script>
