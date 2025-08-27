---
layout: page
title: Projects
permalink: /projects/
author_profile: true
---

<style>
    .project-category {
        margin-bottom: 3rem;
        padding-bottom: 1.5rem;
        border-bottom: 1px solid #eee;
    }
    
    .project-category h2 {
        color: #2c3e50;
        padding-bottom: 0.5rem;
        margin-bottom: 1.5rem;
        border-bottom: 2px solid #3498db;
        display: inline-block;
    }
    
    .project-item {
        background: #f9f9f9;
        border-radius: 8px;
        padding: 1.5rem;
        margin-bottom: 1.5rem;
        box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    
    .project-item:hover {
        transform: translateY(-5px);
        box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    }
    
    .project-title {
        color: #2c3e50;
        margin-top: 0;
        display: flex;
        align-items: center;
    }
    
    .project-title i {
        margin-right: 10px;
        color: #3498db;
    }
    
    .project-meta {
        color: #7f8c8d;
        font-style: italic;
        margin-bottom: 0.75rem;
    }
    
    .project-description {
        color: #34495e;
        line-height: 1.6;
    }
    
    .icon-container {
        display: flex;
        justify-content: center;
        margin: 2rem 0;
    }
    
    .category-icon {
        font-size: 2.5rem;
        color: #3498db;
        background: #eaf2f8;
        padding: 1rem;
        border-radius: 50%;
        width: 80px;
        height: 80px;
        display: flex;
        align-items: center;
        justify-content: center;
        margin: 0 auto 1rem;
    }
</style>

<div class="icon-container">
    <div class="text-center">
        <div class="category-icon">
            <i class="fas fa-project-diagram"></i>
        </div>
        <h1>Academic Projects</h1>
        <p class="project-meta">A collection of my academic work across various disciplines</p>
    </div>
</div>

<div class="project-category">
    <h2><i class="fas fa-microchip"></i> Hardware Projects</h2>
    
    <div class="project-item">
        <h3 class="project-title"><i class="fas fa-fire-extinguisher"></i> Smart Smoke Detector Using 74-Series ICs</h3>
        <div class="project-meta">Digital Electronics Laboratory</div>
        <p class="project-description">Built a 74-series IC-based system (no microcontroller) to digitize smoke sensor output, featuring adjustable alarm thresholds and a 7-second auto-reset timer.</p>
    </div>
    
    <div class="project-item">
        <h3 class="project-title"><i class="fas fa-bolt"></i> Adjustable DC Power Supply Generation</h3>
        <div class="project-meta">Power Electronics Laboratory</div>
        <p class="project-description">Designed a lab-grade buck-boost power supply with wide voltage range and current-limiting protection for stable operation.</p>
    </div>
    
    <div class="project-item">
        <h3 class="project-title"><i class="fas fa-cloud-sun"></i> Weather Station Unit</h3>
        <div class="project-meta">Communication System I Laboratory</div>
        <p class="project-description">Developed a system using Arduino and a LoRa module to transmit and receive weather sensor data from remote locations.</p>
    </div>
    
    <div class="project-item">
        <h3 class="project-title"><i class="fas fa-robot"></i> Human Following Robot</h3>
        <div class="project-meta">Control System I Lab</div>
        <p class="project-description">Developed an Arduino-based robot with IR and ultrasonic sensors to detect and follow human presence.</p>
    </div>
    
    <div class="project-item">
        <h3 class="project-title"><i class="fas fa-sun"></i> Dual Axes Solar Tracker</h3>
        <div class="project-meta">Microprocessors & Embedded Systems Lab</div>
        <p class="project-description">Developed a microcontroller based dual axis solar tracker for optimum solar power generation.</p>
    </div>
</div>

<div class="project-category">
    <h2><i class="fas fa-laptop-code"></i> Software Projects</h2>
    
    <div class="project-item">
        <h3 class="project-title"><i class="fas fa-building"></i> Electrical Design of a Building</h3>
        <div class="project-meta">Electrical Services Design</div>
        <p class="project-description">Designed the ground and typical floor plans for a 9-storey, three-unit building, including fittings and fixtures, conduit layout, switchboard and distribution board diagrams, and a lightning protection system (LPS).</p>
    </div>
    
    <div class="project-item">
        <h3 class="project-title"><i class="fas fa-gamepad"></i> Panzer Fight (Arcade Game)</h3>
        <div class="project-meta">Numerical Technique Lab</div>
        <p class="project-description">Developed a MATLAB-based multiplayer arcade game featuring panzer combat with shell-firing mechanics, dynamic barriers, and adjustable difficulty levels.</p>
    </div>
    
    <div class="project-item">
        <h3 class="project-title"><i class="fas fa-filter"></i> Audio Frequency Filters</h3>
        <div class="project-meta">Electronic Circuits II Lab</div>
        <p class="project-description">Simulated and designed active/passive bandpass/lowpass/highpass filters in Proteus, optimizing performance for precise frequency response.</p>
    </div>
    
    <div class="project-item">
        <h3 class="project-title"><i class="fas fa-brain"></i> Classification of Tumours from MRI Images</h3>
        <div class="project-meta">Digital Signal Processing I Lab</div>
        <p class="project-description">Classified four classes of tumors with the help of MATLAB image processing toolbox and Machine learning toolbox.</p>
    </div>
    
    <div class="project-item">
        <h3 class="project-title"><i class="fas fa-cogs"></i> PSO Based Load Frequency Control</h3>
        <div class="project-meta">Power Systems II Lab</div>
        <p class="project-description">Developed a Particle Swarm Optimization Based Load Frequency Control system in SIMULINK.</p>
    </div>
</div>

<script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
