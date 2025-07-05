---
layout: page
title: Contact
sitemap: true
---

# Contact Information

<div class="contact-container">
    <div class="contact-section">
        <h2>Get in Touch</h2>
        <p>I'm always interested in discussing research collaborations, speaking opportunities, and potential projects in machine learning, graph algorithms, and high-performance computing.</p>
    </div>

    <div class="contact-details">
        <div class="contact-item">
            <div class="contact-icon">📧</div>
            <div class="contact-info">
                <h3>Email</h3>
                <p>ramki [dot] kannan [at] outlook [dot] com</p>
            </div>
        </div>

        <div class="contact-item">
            <div class="contact-icon">🏢</div>
            <div class="contact-info">
                <h3>Office Address</h3>
                <p>Oak Ridge National Laboratory<br>
                One Bethel Valley Rd<br>
                P.O. Box 2008, MS-6085<br>
                Oak Ridge, TN 37831-6086</p>
            </div>
        </div>

        <div class="contact-item">
            <div class="contact-icon">🔗</div>
            <div class="contact-info">
                <h3>Professional Links</h3>
                <p>
                    <a href="https://github.com/ramkikannan" target="_blank">GitHub</a><br>
                    <a href="https://scholar.google.com/citations?user=d59WLM4AAAAJ" target="_blank">Google Scholar</a><br>
                    <a href="https://dblp.org/pid/hd/k/Kannan:Ramakrishnan.html" target="_blank">DBLP</a>
                </p>
            </div>
        </div>

        <div class="contact-item">
            <div class="contact-icon">🎯</div>
            <div class="contact-info">
                <h3>Research Focus</h3>
                <p>Distributed machine learning, graph algorithms on HPC platforms, knowledge-guided ML, and scientific computing applications.</p>
            </div>
        </div>
    </div>

    <div class="affiliations">
        <h2>Current Affiliations</h2>
        <ul>
            <li>Distinguished R&D Staff and Group Leader for Discrete Algorithms, Oak Ridge National Laboratory</li>
            <li>Deputy Director, DOE Mathematical Multifaceted Integrated Capability Center (MMICC) - <a href="https://sparsitute.lbl.gov" target="_blank">Sparsitute</a></li>
        </ul>
    </div>
</div>

<style>
.contact-container {
    max-width: 800px;
    margin: 0 auto;
    padding: 2rem 0;
}

.contact-section {
    margin-bottom: 3rem;
    text-align: center;
}

.contact-section h2 {
    color: #2c3e50;
    margin-bottom: 1rem;
}

.contact-section p {
    font-size: 1.1rem;
    line-height: 1.6;
    color: #555;
}

.contact-details {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
    margin-bottom: 3rem;
}

.contact-item {
    display: flex;
    align-items: flex-start;
    gap: 1rem;
    padding: 1.5rem;
    background: #f8f9fa;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.contact-icon {
    font-size: 1.5rem;
    margin-top: 0.2rem;
}

.contact-info h3 {
    color: #2c3e50;
    margin: 0 0 0.5rem 0;
    font-size: 1.1rem;
}

.contact-info p {
    margin: 0;
    line-height: 1.6;
}

.contact-info a {
    color: #3498db;
    text-decoration: none;
}

.contact-info a:hover {
    text-decoration: underline;
}

.affiliations {
    background: #fff;
    padding: 2rem;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.affiliations h2 {
    color: #2c3e50;
    margin-bottom: 1rem;
}

.affiliations ul {
    list-style-type: none;
    padding: 0;
}

.affiliations li {
    padding: 0.5rem 0;
    border-bottom: 1px solid #eee;
}

.affiliations li:last-child {
    border-bottom: none;
}

@media (max-width: 768px) {
    .contact-container {
        padding: 1rem;
    }

    .contact-details {
        grid-template-columns: 1fr;
    }

    .contact-item {
        flex-direction: column;
        text-align: center;
    }
}
</style>
