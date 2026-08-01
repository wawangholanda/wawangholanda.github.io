---
layout: w3-portfolio
title: DevOps & Platform Engineering Portfolio
permalink: /portofolio/
---

<!-- Container Utama -->
<div class="w3-content w3-padding-64" style="max-width:1200px">

  <!-- Header Halaman -->
  <header class="w3-container w3-center w3-padding-32">
    <h1 class="w3-text-white"><b>PROJECT PORTFOLIO</b></h1>
    <p class="w3-text-grey">Automasi Infrastruktur, Pipeline CI/CD, dan Arsitektur Cloud Berbasis Metrik</p>
    <hr style="width:200px; margin:auto;" class="w3-opacity">
  </header>

  <!-- Grid Proyek (3 Kolom pada Desktop, 1 Kolom pada Mobile) -->
  <div class="w3-row-padding w3-margin-top">
    
    <!-- KARTU PROYEK 1: Infrastructure as Code -->
    <div class="w3-col l4 m6 w3-margin-bottom">
      <div class="w3-card-4 w3-dark-grey w3-round-large">
        <div class="w3-container w3-padding-16">
          <div class="w3-right w3-text-teal"><i class="fa fa-cloud fa-2x"></i></div>
          <h4 class="w3-text-white"><b>AWS Multi-Region Infrastructure</b></h4>
          <p class="w3-text-light-grey" style="min-height: 80px;">
            Membangun arsitektur AWS multi-region yang highly available menggunakan Terraform. Mengurangi waktu provisioning dari hitungan hari menjadi menit.
          </p>
          <div class="w3-padding-small">
            <span class="w3-tag w3-small w3-black w3-round">Terraform</span>
            <span class="w3-tag w3-small w3-black w3-round">AWS</span>
            <span class="w3-tag w3-small w3-black w3-round">Terragrunt</span>
          </div>
          <hr class="w3-opacity" style="margin: 12px 0;">
          <a href="https://github.com" target="_blank" class="w3-button w3-block w3-teal w3-round">View Repository <i class="fa fa-github"></i></a>
        </div>
      </div>
    </div>

    <!-- KARTU PROYEK 2: Containerization & Orchestration -->
    <div class="w3-col l4 m6 w3-margin-bottom">
      <div class="w3-card-4 w3-dark-grey w3-round-large">
        <div class="w3-container w3-padding-16">
          <div class="w3-right w3-text-blue"><i class="fa fa-cubes fa-2x"></i></div>
          <h4 class="w3-text-white"><b>Kubernetes Cluster Migration</b></h4>
          <p class="w3-text-light-grey" style="min-height: 80px;">
            Memigrasikan aplikasi monolitik ke microservices di dalam cluster EKS. Mengimplementasikan ArgoCD untuk strategi deployment GitOps yang aman.
          </p>
          <div class="w3-padding-small">
            <span class="w3-tag w3-small w3-black w3-round">Kubernetes</span>
            <span class="w3-tag w3-small w3-black w3-round">ArgoCD</span>
            <span class="w3-tag w3-small w3-black w3-round">Docker</span>
          </div>
          <hr class="w3-opacity" style="margin: 12px 0;">
          <a href="https://github.com" target="_blank" class="w3-button w3-block w3-blue w3-round">View Case Study <i class="fa fa-external-link"></i></a>
        </div>
      </div>
    </div>

    <!-- KARTU PROYEK 3: CI/CD & Automation -->
    <div class="w3-col l4 m6 w3-margin-bottom">
      <div class="w3-card-4 w3-dark-grey w3-round-large">
        <div class="w3-container w3-padding-16">
          <div class="w3-right w3-text-green"><i class="fa fa-refresh fa-2x"></i></div>
          <h4 class="w3-text-white"><b>Automated CI/CD Pipeline</b></h4>
          <p class="w3-text-light-grey" style="min-height: 80px;">
            Merancang alur kerja GitHub Actions untuk otomatisasi testing, security scanning (Trivy), dan deployment otomatis ke Google Cloud Run.
          </p>
          <div class="w3-padding-small">
            <span class="w3-tag w3-small w3-black w3-round">GitHub Actions</span>
            <span class="w3-tag w3-small w3-black w3-round">GCP</span>
            <span class="w3-tag w3-small w3-black w3-round">Security</span>
          </div>
          <hr class="w3-opacity" style="margin: 12px 0;">
          <a href="https://github.com" target="_blank" class="w3-button w3-block w3-green w3-round">View Pipeline <i class="fa fa-code-fork"></i></a>
        </div>
      </div>
    </div>

  </div> <!-- Akhir Grid Baris 1 -->

  <!-- Grid Baris 2: Observability & Log Management -->
  <div class="w3-row-padding">
    
    <div class="w3-col l4 m6 w3-margin-bottom">
      <div class="w3-card-4 w3-dark-grey w3-round-large">
        <div class="w3-container w3-padding-16">
          <div class="w3-right w3-text-orange"><i class="fa fa-area-chart fa-2x"></i></div>
          <h4 class="w3-text-white"><b>Observability Stack Setup</b></h4>
          <p class="w3-text-light-grey" style="min-height: 80px;">
            Implementasi monitoring dan alerting system terpusat menggunakan Prometheus dan Grafana untuk mendeteksi downtime infrastruktur < 30 detik.
          </p>
          <div class="w3-padding-small">
            <span class="w3-tag w3-small w3-black w3-round">Prometheus</span>
            <span class="w3-tag w3-small w3-black w3-round">Grafana</span>
            <span class="w3-tag w3-small w3-black w3-round">Alerting</span>
          </div>
          <hr class="w3-opacity" style="margin: 12px 0;">
          <a href="https://github.com" target="_blank" class="w3-button w3-block w3-orange w3-round">View Dashboard <i class="fa fa-eye"></i></a>
        </div>
      </div>
    </div>

  </div> <!-- Akhir Grid Baris 2 -->

  <!-- Tombol Kembali ke Halaman Utama -->
  <div class="w3-container w3-center w3-padding-32">
    <a href="/" class="w3-button w3-light-grey w3-round-large"><i class="fa fa-arrow-left"></i> Kembali ke Beranda</a>
  </div>

</div>
