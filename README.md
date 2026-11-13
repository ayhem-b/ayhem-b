<h1 align="center">Ayhem Belkhamsa</h1>
<p align="center"><b>Industrial Automation Engineer &amp; Machine Builder</b> — Bizerte · Menzel Bourguiba · Tunisia</p>

<p align="center">
  <a href="https://ayhem-b.github.io/Ayhem-portfolio/"><img src="https://img.shields.io/badge/Portfolio-ayhem--b.github.io-FF7A1A?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio"></a>
  <a href="mailto:belkhamsaayhem09@gmail.com"><img src="https://img.shields.io/badge/Email-belkhamsaayhem09%40gmail.com-4FD1E8?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>
<p align="center">
  <a href="https://tn.linkedin.com/in/ayhem-belkhamsa-976b50333"><img src="https://img.shields.io/badge/LinkedIn-ayhem--belkhamsa-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://www.instagram.com/ayhem_belkhamsa/"><img src="https://img.shields.io/badge/Instagram-ayhem__belkhamsa-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"></a>
  <a href="https://www.facebook.com/ayhem.belkh/"><img src="https://img.shields.io/badge/Facebook-ayhem.belkh-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook"></a>
  <img src="https://komarev.com/ghpvc/?username=ayhem-b&label=Profile%20views&color=5C6A70&style=for-the-badge" alt="Profile views">
</p>

<p align="center">
  <img src="assets/vision-inspection-reel.gif" alt="Vision inspection station running on a production line" width="720">
  <br>
  <sub>Vision inspection station I built for a production line — camera bracket designed in CAD, inspection logic in VisionMaster + C#.</sub>
</p>

I retrofit, build and commission special machines for factories in northern Tunisia — from PLC cabinets rewired from scratch to vision-guided robots running in production. Independent operator: the person who diagnoses the line, quotes the job and builds it is the same person.

**What I do**

| ⏚ PLC &amp; cabinet retrofits | ⚙ Custom machines | ◎ Vision &amp; robotics | &gt;_ HMI &amp; data |
|---|---|---|---|
| Trace undocumented wiring, rebuild the cabinet, reprogram from a known-good baseline. Mitsubishi FX / Coolmay, Siemens S7. | Test rigs and one-off equipment sized to the real process, with an interface operators can run on day one. | Pick &amp; place, 6-axis arms, Delta robots, machine vision QC (VisionMaster, OpenCV), edge AI on Jetson. | C# (.NET / WinForms / WPF) HMIs, live logging, PDF reporting, Django back-ends, MQTT / Modbus / Snap7. |

## Featured projects

<table>
<tr>
<td width="50%" valign="top">
<img src="https://raw.githubusercontent.com/ayhem-b/Ayhem-portfolio/main/assets/images/tensile-rig-finished.jpg" alt="Tensile testing rig" width="100%"><br>
<b>Material tensile testing machine</b> · <a href="https://github.com/ayhem-b/Stress-Machine-Machine-de-traction">overview</a> · 🔒 source on request<br>
<sub>Built the rig and wrote its C# WinForms HMI: Mitsubishi FX PLC over MX Component, live stress/strain curve, servo speed control, PDF test reports (iTextSharp). .NET Framework 4.7.2.</sub>
</td>
<td width="50%" valign="top">
<img src="assets/machine-retrofit-reel.gif" alt="Machine retrofit in progress" width="100%"><br>
<b>ILLIG RV74 thermoformer retrofit</b> · 🔒 private (client project)<br>
<sub>Full control retrofit of a 1993 ILLIG RV74: Coolmay M302 (FX3U-compatible) PLC, GX Works2 structured project, 128 DI / 64 DO / 64 TC I/O allocation rebuilt from the original wiring diagrams, 14 heater zones. In progress.</sub>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<img src="https://raw.githubusercontent.com/ayhem-b/Ayhem-portfolio/main/assets/images/vision-inspection-bench.jpg" alt="Vision inspection bench" width="100%"><br>
<b>SIMEF vision detection system</b> · 🔒 private (client project)<br>
<sub>Hikrobot VisionMaster inspection with C# scripts: marking detection, OK/NG decision, per-product counters, two operating modes. 3D-printed camera, lighting and baffle supports designed in SolidWorks.</sub>
</td>
<td width="50%" valign="top">
<img src="https://raw.githubusercontent.com/ayhem-b/Ayhem-portfolio/main/assets/images/pick-and-place-cell.jpg" alt="Programming a pick and place cell" width="100%"><br>
<b>GMAO — maintenance management web app</b> · <a href="https://github.com/ayhem-b/GMAO">repo</a><br>
<sub>Django CMMS with work orders, interventions, spare parts and a live machine-status dashboard fed by a Siemens S7-1200 over Snap7. Capstone project at Lear Corporation Tunisia (ISET Bizerte).</sub>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<b>Smart home IoT stack</b> · 🔒 private (academic project)<br>
<sub>Mosquitto → Node-RED rule engine → InfluxDB → Grafana, all in Docker Compose, with a Python sensor simulator that runs an accelerated "day" and an ESP32 path for real sensors. 8 rule families (air quality, temperature, humidity, smoke, pool level, presence, soil moisture, rain).</sub>
</td>
<td width="50%" valign="top">
<b>Titanic survival prediction</b> · <a href="https://github.com/ayhem-b/Ttitanic_predicton">repo</a><br>
<sub>KNN and logistic regression in Orange and Python (scikit-learn), up to 83 % accuracy on the held-out set, with a Typst report.</sub>
</td>
</tr>
</table>

<p align="center">
  <img src="assets/work-in-progress-reel.gif" alt="Work in progress on the shop floor" height="300">
  &nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/ayhem-b/Ayhem-portfolio/main/assets/images/control-cabinet-retrofit.jpg" alt="Inside a control cabinet during a retrofit" height="300">
</p>

## Toolbox

**PLC &amp; motion** &nbsp;
![Mitsubishi](https://img.shields.io/badge/Mitsubishi_FX-GX_Works2-E60012?style=flat-square)
![Siemens](https://img.shields.io/badge/Siemens_S7-TIA_Portal-009999?style=flat-square)
![Coolmay](https://img.shields.io/badge/Coolmay-M302-2B3439?style=flat-square)
![Yaskawa](https://img.shields.io/badge/Yaskawa-VFD-1E4DA1?style=flat-square)
![Servo](https://img.shields.io/badge/Servo_%2F_stepper-PWM-5C6A70?style=flat-square)

**Vision &amp; robotics** &nbsp;
![VisionMaster](https://img.shields.io/badge/Hikrobot-VisionMaster-C8102E?style=flat-square)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Jetson](https://img.shields.io/badge/NVIDIA-Jetson-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Robots](https://img.shields.io/badge/6--DOF_%C2%B7_Delta_%C2%B7_Pick%26Place-FF7A1A?style=flat-square)

**Software** &nbsp;
![C#](https://img.shields.io/badge/C%23-.NET_%2F_WinForms_%2F_WPF-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Node-RED](https://img.shields.io/badge/Node--RED-8F0000?style=flat-square&logo=nodered&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![InfluxDB](https://img.shields.io/badge/InfluxDB-22ADF6?style=flat-square&logo=influxdb&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT_%C2%B7_Modbus_%C2%B7_Snap7-660066?style=flat-square)
![SolidWorks](https://img.shields.io/badge/SolidWorks-DA291C?style=flat-square)
![Typst](https://img.shields.io/badge/Typst-239DAD?style=flat-square&logo=typst&logoColor=white)

Currently learning **ROS 2** and going deeper on industrial communication protocols.

## GitHub activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ayhem-b&show_icons=true&theme=dark&hide_border=true&bg_color=12171A&title_color=FF7A1A&icon_color=4FD1E8&text_color=EAF0F2" alt="GitHub stats" height="165">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ayhem-b&layout=compact&theme=dark&hide_border=true&bg_color=12171A&title_color=FF7A1A&text_color=EAF0F2" alt="Top languages" height="165">
</p>

[![wakatime](https://wakatime.com/badge/user/cf8da79b-a470-449f-8b0c-f235c18b2fd3.svg)](https://wakatime.com/@cf8da79b-a470-449f-8b0c-f235c18b2fd3)
<!--START_SECTION:waka-->

```txt
From: 23 October 2026 - To: 30 October 2026

No activity tracked
```

<!--END_SECTION:waka-->

<p align="center">
  <img src="https://wakatime.com/share/@cf8da79b-a470-449f-8b0c-f235c18b2fd3/a8f6d8f6-7585-46f8-abdf-ef882af10143.svg" alt="WakaTime languages" height="300">
  <img src="https://wakatime.com/share/@cf8da79b-a470-449f-8b0c-f235c18b2fd3/e5d007f8-acb4-4d59-a4f2-da56b2a5c4d7.svg" alt="WakaTime editors" height="300">
</p>

---

<p align="center"><sub>Have a line that's down, a machine nobody documented, or a process that's still manual? <a href="https://ayhem-b.github.io/Ayhem-portfolio/#contact">Let's scope it out.</a></sub></p>
