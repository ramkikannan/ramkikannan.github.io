---
layout: page
title: About
sitemap: true
---

<div class="about-container">
    <div class="about-header">
        <img src="../figs/ramki-frontier.jpg" alt="Ramki Kannan" class="about-image">
        <div class="about-intro">
            <h1>About Me</h1>
            <p class="lead">Distinguished R&D Staff and Group Leader for Discrete Algorithms at Oak Ridge National Laboratory</p>
        </div>
    </div>

    <div class="about-content">
        <section class="about-section">
            <h2>Biography</h2>
            <p>Ramki Kannan is the Distinguished R&D Staff and group leader for Discrete Algorithms at Oak Ridge National Laboratory. His research expertise are in distributed machine learning and graph algorithms on HPC platforms and their application to scientific data with a focus on accelerating scientific discovery by reducing computation time from weeks to seconds.</p>

            <p>He was the lead for DSNAPSHOT for a COVID-19 project, which is a finalist for the esteemed Association of Computing Machinery's Gordon Bell Award in 2020 and 2022, and listing Summit in 3rd place on Graph500 benchmark using the fewest resources; this is the first time an OLCF system has ranked in Graph500.</p>

            <p>He led the team that demonstrated 1 ExaFLOPS on a KnowledgeGraph AI application for the first time in Frontier and this project was recognized with UT-Battelle Research Accomplishment Award in 2023.</p>
        </section>

        <section class="about-section">
            <h2>Research Interests</h2>
            <div class="research-grid">
                <div class="research-item">
                    <h3>🔬 Scalable Machine Learning</h3>
                    <p>Machine learning and graph algorithms on HPC systems and big data architectures</p>
                </div>
                <div class="research-item">
                    <h3>🧠 Knowledge Guided ML</h3>
                    <p>Integrating domain knowledge with machine learning approaches</p>
                </div>
                <div class="research-item">
                    <h3>📊 Dimensionality Reduction</h3>
                    <p>Matrix & tensor factorization, autoencoders, factor models and low rank approximation</p>
                </div>
                <div class="research-item">
                    <h3>🔗 Graph Algorithms</h3>
                    <p>Distributed graph processing and analysis on high-performance computing platforms</p>
                </div>
            </div>
        </section>

        <section class="about-section">
            <h2>Leadership & Recognition</h2>
            <ul class="achievements">
                <li>Deputy Director for the DOE Mathematical Multifaceted Integrated Capability Center (MMICC) <a href="https://sparsitute.lbl.gov" target="_blank">Sparsitute</a></li>
                <li>Awarded over $35M in research funding from various agencies</li>
                <li>Project lead for over $1 million in Department of Defense projects</li>
                <li>24+ patents issued in USPTO</li>
                <li>Former IBM Master Inventor</li>
                <li>Co-author of "Knowledge-guided Machine Learning" (2022)</li>
            </ul>
        </section>

        <section class="about-section">
            <h2>Education</h2>
            <div class="education-item">
                <h3>Ph.D. in Computer Science</h3>
                <p>Georgia Institute of Technology</p>
                <p><em>Advisor: Professor Haesun Park</em></p>
            </div>
            <div class="education-item">
                <h3>M.Sc (Engg)</h3>
                <p>Indian Institute of Science</p>
                <p><em>Advisor: Professor Y. Narahari</em></p>
            </div>
        </section>

        <section class="about-section">
            <h2>Principal Investigator</h2>
            <p><a href="https://ramkikannan.github.io/planc-api" target="_blank">Parallel Low Rank Approximation with Non-negative Constraints (PLANC)</a></p>
        </section>
    </div>
</div>

<style>
.about-container {
    max-width: 900px;
    margin: 0 auto;
    padding: 2rem 1rem;
}

.about-header {
    display: flex;
    align-items: center;
    gap: 2rem;
    margin-bottom: 3rem;
    flex-wrap: wrap;
}

.about-image {
    width: 400px;
    height: 300px;
    object-fit: cover;
    border-radius: 8px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

.about-intro {
    flex: 1;
    min-width: 300px;
}

.about-intro h1 {
    font-size: 2.5rem;
    margin: 0 0 1rem 0;
    color: #2d3748;
}

.lead {
    font-size: 1.3rem;
    color: #4a5568;
    margin: 0;
    line-height: 1.5;
}

.about-section {
    margin-bottom: 3rem;
}

.about-section h2 {
    color: #2d3748;
    border-bottom: 2px solid #e2e8f0;
    padding-bottom: 0.5rem;
    margin-bottom: 1.5rem;
}

.research-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 1.5rem;
    margin-top: 1.5rem;
}

.research-item {
    background: #f8f9fa;
    padding: 1.5rem;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.research-item h3 {
    color: #2d3748;
    margin: 0 0 0.5rem 0;
    font-size: 1.1rem;
}

.research-item p {
    color: #4a5568;
    margin: 0;
    line-height: 1.5;
}

.achievements {
    list-style: none;
    padding: 0;
}

.achievements li {
    padding: 0.5rem 0;
    border-bottom: 1px solid #e2e8f0;
    position: relative;
    padding-left: 1.5rem;
}

.achievements li:before {
    content: "✓";
    position: absolute;
    left: 0;
    color: #3182ce;
    font-weight: bold;
}

.achievements li:last-child {
    border-bottom: none;
}

.education-item {
    margin-bottom: 1.5rem;
    padding: 1rem;
    background: #f8f9fa;
    border-radius: 6px;
}

.education-item h3 {
    color: #2d3748;
    margin: 0 0 0.5rem 0;
}

.education-item p {
    margin: 0.25rem 0;
    color: #4a5568;
}

.education-item em {
    color: #718096;
    font-style: italic;
}

@media (max-width: 768px) {
    .about-header {
        flex-direction: column;
        text-align: center;
    }

    .about-image {
        width: 300px;
        height: 225px;
    }

    .about-intro h1 {
        font-size: 2rem;
    }

    .research-grid {
        grid-template-columns: 1fr;
    }
}
</style>
