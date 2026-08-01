---
layout: w3-portfolio
title: Platform & DevOps Dashboard Portfolio
permalink: /portofolio/
---

<!-- Top container -->
<div class="w3-bar w3-top w3-black w3-large" style="z-index:4">
  <button class="w3-bar-item w3-button w3-hide-large w3-hover-none w3-hover-text-light-grey" onclick="w3_open();"><i class="fa fa-bars"></i>  Menu</button>
  <span class="w3-bar-item w3-right">Wawang Holanda</span>
</div>

<!-- Sidebar/menu -->
<nav class="w3-sidebar w3-collapse w3-white w3-animate-left" style="z-index:3;width:300px;" id="mySidebar"><br>
  <div class="w3-container w3-row">
    <div class="w3-col s4">
      <i class="fa fa-user-circle w3-text-teal" style="font-size:46px;"></i>
    </div>
    <div class="w3-col s8 w3-bar">
      <span>Welcome, <strong>Wawang</strong></span><br>
      <a href="https://github.com" target="_blank" class="w3-bar-item w3-button"><i class="fa fa-github"></i></a>
      <a href="/cv/" class="w3-bar-item w3-button"><i class="fa fa-file-text"></i></a>
      <a href="/" class="w3-bar-item w3-button"><i class="fa fa-home"></i></a>
    </div>
  </div>
  <hr>
  <div class="w3-container">
    <h5><b>Infrastruktur Menu</b></h5>
  </div>
  <div class="w3-bar-block">
    <a href="#" class="w3-bar-item w3-button w3-padding-16 w3-hide-large w3-dark-grey w3-hover-black" onclick="w3_close()" title="close menu"><i class="fa fa-remove fa-fw"></i>  Close Menu</a>
    <a href="#overview" class="w3-bar-item w3-button w3-padding w3-blue"><i class="fa fa-dashboard fa-fw"></i>  System Overview</a>
    <a href="#projects" class="w3-bar-item w3-button w3-padding"><i class="fa fa-cubes fa-fw"></i>  Core Projects</a>
    <a href="#metrics" class="w3-bar-item w3-button w3-padding"><i class="fa fa-area-chart fa-fw"></i>  SLA Metrics</a>
    <a href="#stack" class="w3-bar-item w3-button w3-padding"><i class="fa fa-gears fa-fw"></i>  Cloud Providers</a>
  </div>
</nav>

<!-- Overlay effect when opening sidebar on small screens -->
<div class="w3-overlay w3-hide-large w3-animate-opacity" onclick="w3_close()" style="cursor:pointer" title="close side menu" id="myOverlay"></div>

<!-- !PAGE CONTENT! -->
<div class="w3-main" style="margin-left:300px;margin-top:43px;">

  <!-- Header -->
  <header class="w3-container" id="overview" style="padding-top:22px">
    <h5><b><i class="fa fa-dashboard"></i> Infrastructure Control Panel</b></h5>
  </header>

  <!-- METRIK UTAMA (4 Kotak Atas) -->
  <div class="w3-row-padding w3-margin-bottom">
    <div class="w3-quarter">
      <div class="w3-container w3-red w3-padding-16 w3-round">
        <div class="w3-left"><i class="fa fa-heartbeat w3-xxxlarge"></i></div>
        <div class="w3-right">
          <h3>99.99%</h3>
        </div>
        <div class="w3-clear"></div>
        <h4>Uptime SLA</h4>
      </div>
    </div>
    <div class="w3-quarter">
      <div class="w3-container w3-blue w3-padding-16 w3-round">
        <div class="w3-left"><i class="fa fa-code-fork w3-xxxlarge"></i></div>
        <div class="w3-right">
          <h3>1,420</h3>
        </div>
        <div class="w3-clear"></div>
        <h4>Automated Builds</h4>
      </div>
    </div>
    <div class="w3-quarter">
      <div class="w3-container w3-teal w3-padding-16 w3-round">
        <div class="w3-left"><i class="fa fa-cloud w3-xxxlarge"></i></div>
        <div class="w3-right">
          <h3>48</h3>
        </div>
        <div class="w3-clear"></div>
        <h4>Cloud Clusters</h4>
      </div>
    </div>
    <div class="w3-quarter">
      <div class="w3-container w3-orange w3-text-white w3-padding-16 w3-round">
        <div class="w3-left"><i class="fa fa-shield w3-xxxlarge"></i></div>
        <div class="w3-right">
          <h3>0</h3>
        </div>
        <div class="w3-clear"></div>
        <h4>SecOps Vulnerabilities</h4>
      </div>
    </div>
  </div>

  <!-- BAGIAN PROYEK UTAMA -->
  <div class="w3-panel" id="projects">
    <div class="w3-row-padding" style="margin:0 -16px">
      
      <!-- Kolom Kiri: Ilustrasi Topology / Diagram -->
      <div class="w3-third">
        <h5><b>Architecture Overview</b></h5>
        <div class="w3-container w3-padding-32 w3-center w3-light-grey w3-border w3-round">
          <i class="fa fa-sitemap w3-text-teal" style="font-size: 90px;"></i>
          <p class="w3-small w3-text-grey">Highly Available & Scalable Microservices Infrastructure Topology</p>
        </div>
      </div>
      
      <!-- Kolom Kanan: Daftar Detail Proyek dalam Bentuk Tabel Log -->
      <div class="w3-twothird">
        <h5><b>Production-Grade Projects Log</b></h5>
        <table class="w3-table w3-striped w3-white w3-border w3-card-2">
          <tr class="w3-teal">
            <th>Project Domain</th>
            <th>Technical Impact Summary</th>
            <th>Repository</th>
          </tr>
          <tr>
            <td><i class="fa fa-cloud w3-text-blue w3-large"></i> <b>Infrastructure as Code</b></td>
            <td>Automated AWS multi-region setups using modular Terraform, saving 90% manual setup times.</td>
            <td><a href="https://github.com" target="_blank" class="w3-tag w3-small w3-dark-grey w3-round" style="text-decoration:none;">Code <i class="fa fa-github"></i></a></td>
          </tr>
          <tr>
            <td><i class="fa fa-cubes w3-text-orange w3-large"></i> <b>Container Orchestration</b></td>
            <td>Migrated legacy setups into modern Amazon EKS and leveraged ArgoCD for GitOps deployment rules.</td>
            <td><a href="https://github.com" target="_blank" class="w3-tag w3-small w3-dark-grey w3-round" style="text-decoration:none;">Case Study</a></td>
          </tr>
          <tr>
            <td><i class="fa fa-refresh w3-text-green w3-large"></i> <b>CI/CD Pipeline Design</b></td>
            <td>Engineered complex GitHub Actions jobs including automated testing, static scanning, and cloud syncs.</td>
            <td><a href="https://github.com" target="_blank" class="w3-tag w3-small w3-dark-grey w3-round" style="text-decoration:none;">Pipeline</a></td>
          </tr>
          <tr>
            <td><i class="fa fa-area-chart w3-text-red w3-large"></i> <b>Observability Stack</b></td>
            <td>Deployed enterprise-level cluster tracking metrics using Prometheus and beautiful Grafana dashboards.</td>
            <td><a href="https://github.com" target="_blank" class="w3-tag w3-small w3-dark-grey w3-round" style="text-decoration:none;">Dashboard</a></td>
          </tr>
        </table>
      </div>
    </div>
  </div>
  <hr>

  <!-- BAGIAN METRIK PERFORMA (SLA) -->
  <div class="w3-container" id="metrics">
    <h5><b>System Performance Optimization Stats</b></h5>
    
    <p>Provisioning Automation Speedup</p>
    <div class="w3-grey w3-round-large">
      <div class="w3-container w3-center w3-padding w3-green w3-round-large" style="width:95%">95% Faster</div>
    </div>

    <p>Deployment Error Reduction Rate</p>
    <div class="w3-grey w3-round-large">
      <div class="w3-container w3-center w3-padding w3-orange w3-round-large" style="width:80%">80% Lower</div>
    </div>

    <p>Cloud Spending Cost Reduction</p>
    <div class="w3-grey w3-round-large">
      <div class="w3-container w3-center w3-padding w3-teal w3-round-large" style="width:35%">35% Saved</div>
    </div>
  </div>
  <hr>

  <!-- BAGIAN PROVDIER CLOUD YANG DIKUASAI -->
  <div class="w3-container" id="stack">
    <h5><b>Cloud Distribution Traffic & Experience</b></h5>
    <table class="w3-table w3-striped w3-bordered w3-border w3-hoverable w3-white">
      <tr class="w3-dark-grey">
        <th>Cloud Provider / Platform</th>
        <th>Proficiency Level & System Load Share</th>
      </tr>
      <tr>
        <td>Amazon Web Services (AWS)</td>
        <td><b>75%</b> - Multi-region networking, IAM, EKS, EC2, Lambda, CloudWatch</td>
      </tr>
      <tr>
        <td>Google Cloud Platform (GCP)</td>
        <td><b>15%</b> - Google Kubernetes Engine (GKE), Cloud Run, Cloud Storage</td>
      </tr>
      <tr>
        <td>On-Premises Hypervisors (Proxmox / VMware)</td>
        <td><b>10%</b> - Private lab management, bare-metal operations, storage pools</td>
      </tr>
    </table><br>
  </div>
  <hr>

  <!-- Footer -->
  <footer class="w3-container w3-padding-16 w3-light-grey w3-center">
    <h4>Wawang Holanda | Platform Engineering Portfolio</h4>
    <p>Powered by <a href="https://w3schools.com" target="_blank" class="w3-text-teal">w3.css dashboard template</a></p>
  </footer>

  <!-- End page content -->
</div>

<!-- JavaScript bawaan template untuk mengontrol Sidebar di Mobile -->
<script>
// Ambil elemen Sidebar
var mySidebar = document.getElementById("mySidebar");

// Ambil elemen Overlay effect
var overlayBg = document.getElementById("myOverlay");

// Fungsi buka menu
function w3_open() {
  if (mySidebar.style.display === 'block') {
    mySidebar.style.display = 'none';
    overlayBg.style.display = "none";
  } else {
    mySidebar.style.display = 'block';
    overlayBg.style.display = "block";
  }
}

// Fungsi tutup menu
function w3_close() {
  mySidebar.style.display = "none";
  overlayBg.style.display = "none";
}
</script>
