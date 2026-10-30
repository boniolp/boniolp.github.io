---
permalink: /team
hidden: true
classes: wide
# layout: single-hf
# layout: single
layout: default
title: "Team"
author_profile: true
redirect_from: 
  - /team
  - /team.html
---

<style>
/* ---------- team page (all rules scoped to .tm) ---------- */
.tm { --tm-border: rgba(127,127,127,.22); --tm-muted: #6b7378; --tm-accent: #2f6f9f; overflow-wrap: anywhere; }
.tm h1 { margin-bottom: .3em; }
.tm .tm-intro { margin: 0 0 1.4em; line-height: 1.6; }
.tm h2 { font-size: .8em; text-transform: uppercase; letter-spacing: .08em; color: var(--tm-muted); margin: 1.4em 0 .6em; }
.tm .tm-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(min(100%, 300px), 1fr)); gap: .8em; }
.tm .tm-card { display: flex; gap: .9em; align-items: flex-start; padding: .9em 1em; border: 1px solid var(--tm-border); border-radius: 10px; background: #fff; line-height: 1.45; }
.tm .tm-avatar { flex: none; width: 46px; height: 46px; border-radius: 50%; display: flex; align-items: center; justify-content: center;
                 font-weight: 700; font-size: 1em; letter-spacing: .02em; color: hsl(var(--h), 45%, 30%); background: hsl(var(--h), 55%, 90%); }
.tm .tm-info { min-width: 0; flex: 1; }
.tm .tm-head { display: flex; flex-wrap: wrap; align-items: baseline; justify-content: space-between; gap: .1em .6em; }
.tm .tm-name { font-weight: 600; font-size: 1.05em; color: #222; }
.tm a.tm-name { color: var(--tm-accent); }
.tm .tm-dates { font-size: .75em; color: var(--tm-muted); white-space: nowrap; padding: .05em .55em; border: 1px solid var(--tm-border); border-radius: 999px; }
.tm .tm-role { font-size: .9em; margin-top: .15em; }
.tm .tm-topic { font-size: .86em; color: #444; margin-top: .35em; }
.tm .tm-label { font-size: .78em; font-weight: 700; text-transform: uppercase; letter-spacing: .06em; color: var(--tm-muted); margin-right: .2em; }
.tm .tm-note { font-size: .86em; color: var(--tm-muted); margin-top: .15em; }
.tm .tm-former-title { margin-top: 1.6em; padding-top: .8em; border-top: 2px solid var(--tm-border); font-size: 1.5em; }
.tm ul.tm-rows { list-style: none; padding: 0; margin: 0; border: 1px solid var(--tm-border); border-radius: 10px; overflow: hidden; }
.tm .tm-row { display: flex; align-items: baseline; justify-content: space-between; gap: .4em 1em; padding: .55em .95em; margin: 0; border-top: 1px solid var(--tm-border); background: #fff; }
.tm .tm-row:first-child { border-top: 0; }
.tm .tm-row-main { min-width: 0; }
.tm .tm-row .tm-name { font-size: 1em; }
.tm .tm-row .tm-role, .tm .tm-row .tm-note { display: inline; font-size: .88em; color: var(--tm-muted); margin: 0; }
.tm .tm-row .tm-role::before { content: "\2014\00A0"; margin-left: .35em; }
.tm .tm-row .tm-note::before { content: "\00B7\00A0"; margin-left: .35em; }
@media (max-width: 560px) {
  .tm .tm-row { flex-direction: column; gap: .2em; }
  .tm .tm-row .tm-role, .tm .tm-row .tm-note { display: block; }
  .tm .tm-row .tm-role::before, .tm .tm-row .tm-note::before { content: none; }
}
</style>

<div class="tm">

<h1>Team and Students</h1>

<p class="tm-intro">I am a researcher at Inria and a member of the <a href="https://team.inria.fr/valda/">VALDA</a> project team, a joint team between Inria Paris, École Normale Supérieure, and CNRS.
Within VALDA, I am supervising the following students and researchers:</p>

<h2>Postdoctoral researcher</h2>
<div class="tm-grid">
<div class="tm-card">
<div class="tm-avatar" style="--h:280">RS</div>
<div class="tm-info">
<div class="tm-head"><a class="tm-name" href="https://roby46.github.io/Roberto_Stanzione/">Roberto Stanzione</a><span class="tm-dates">Jan 2026 - now</span></div>
<div class="tm-role">Postdoctoral researcher</div>
</div>
</div>
</div>

<h2>Ph.D. Students</h2>
<div class="tm-grid">
<div class="tm-card">
<div class="tm-avatar" style="--h:44">ES</div>
<div class="tm-info">
<div class="tm-head"><a class="tm-name" href="https://sylligardos.vercel.app/">Emmanouil Sylligardos</a><span class="tm-dates">Feb 2024 - now</span></div>
<div class="tm-role">PhD student (Co-advised with Pierre Senellart)</div>
<div class="tm-topic"><span class="tm-label">Topic</span> <em>Accuracy and Execution Time Trade-off in Ensembling and Model Selection for Time Series Analytics</em></div>
</div>
</div>
<div class="tm-card">
<div class="tm-avatar" style="--h:48">FC</div>
<div class="tm-info">
<div class="tm-head"><a class="tm-name" href="https://felix.chavelli.fr/">Felix Chavelli</a><span class="tm-dates">Oct 2024 - now</span></div>
<div class="tm-role">PhD student (Co-advised with Michaël Thomazo)</div>
<div class="tm-topic"><span class="tm-label">Topic</span> <em>Graph Representation for Multivariate Time Series Analytics</em></div>
</div>
</div>
<div class="tm-card">
<div class="tm-avatar" style="--h:270">MP</div>
<div class="tm-info">
<div class="tm-head"><a class="tm-name" href="https://magaliparrino.github.io/">Magali Parrino</a><span class="tm-dates">July 2025 - now</span></div>
<div class="tm-role">PhD student (CIFRE Ph.D. co-advised with Pierre Senellart)</div>
<div class="tm-topic"><span class="tm-label">Topic</span> <em>Unsupervised detection of anomalies in continuous streams of multivariate time series</em></div>
</div>
</div>
</div>

<h2>Research Engineers</h2>
<div class="tm-grid">
<div class="tm-card">
<div class="tm-avatar" style="--h:142">LC</div>
<div class="tm-info">
<div class="tm-head"><a class="tm-name" href="https://www.linkedin.com/in/louis-chanaron-b7112924b/">Louis Chanaron</a><span class="tm-dates">Oct 2025 - now</span></div>
<div class="tm-role">Inria Research Engineer</div>
</div>
</div>
</div>

<h2>Interns</h2>
<div class="tm-grid">
<div class="tm-card">
<div class="tm-avatar" style="--h:127">VM</div>
<div class="tm-info">
<div class="tm-head"><span class="tm-name">Vijay Venkatesh Murugan</span><span class="tm-dates">June 2026 - now</span></div>
<div class="tm-role">MSc student (Institut Polytechnique de Paris, France)</div>
<div class="tm-note">Collaboration with Mickaël Tharaud (IPGP)</div>
</div>
</div>
</div>

<h1 class="tm-former-title">Former Students and Researchers</h1>

<h2>Visiting Students and Researchers</h2>
<ul class="tm-rows">
<li class="tm-row"><div class="tm-row-main"><a class="tm-name" href="https://www.gssi.it/people/students/students-computer-science/item/24586-doan-thi-hoai-thu">Thi Hoai Thu Doan</a><div class="tm-role">Visiting PhD student (Gran Sasso Science Institute, Italy)</div></div><span class="tm-dates">Jan 2026 - Mar 2026</span></li>
<li class="tm-row"><div class="tm-row-main"><a class="tm-name" href="https://scalab.dimes.unical.it/lindia/">Paolo Lindia</a><div class="tm-role">Visiting PhD student (University of Calabria, Italy)</div></div><span class="tm-dates">April 2025 - Sep 2025</span></li>
<li class="tm-row"><div class="tm-row-main"><a class="tm-name" href="https://www.researchgate.net/profile/Roberto-Stanzione">Roberto Stanzione</a><div class="tm-role">Visiting PhD student (Università degli Studi di Salerno, Italy)</div></div><span class="tm-dates">Nov 2024 - May 2025</span></li>
</ul>

<h2>Interns</h2>
<ul class="tm-rows">
<li class="tm-row"><div class="tm-row-main"><a class="tm-name" href="https://www.linkedin.com/in/el-mehdi-el-kasmi-70840b291/">El Mehdi El Kasmi</a><div class="tm-role">MSc student (Mines Paris PSL, France)</div> <div class="tm-note">Co-supervision with Roberto Stanzione (Inria/ENS)</div></div><span class="tm-dates">June 2026 - August 2026</span></li>
<li class="tm-row"><div class="tm-row-main"><span class="tm-name">Vijay Venkatesh Murugan</span><div class="tm-role">MSc student (Institut Polytechnique de Paris, France)</div> <div class="tm-note">Collaboration with Mickaël Tharaud (IPGP)</div></div><span class="tm-dates">Jul 2025 - Sep 2025</span></li>
<li class="tm-row"><div class="tm-row-main"><a class="tm-name" href="https://www.linkedin.com/in/yash-krishnani-73776623b/?originalSubdomain=in">Yash Krishnani</a><div class="tm-role">BSc Student (Indian Institute of Technology Bombay, India)</div></div><span class="tm-dates">May 2025 - July 2025</span></li>
<li class="tm-row"><div class="tm-row-main"><a class="tm-name" href="https://www.linkedin.com/in/adam-rozzio-4088a1272/?originalSubdomain=fr">Adam Rozzio</a><div class="tm-role">MSc student (ENS Paris-Saclay, France)</div></div><span class="tm-dates">Feb 2025 - July 2025</span></li>
<li class="tm-row"><div class="tm-row-main"><a class="tm-name" href="https://www.linkedin.com/in/aleksander-gautier/?originalSubdomain=fr">Aleksander Gautier</a><div class="tm-role">MSc student (Telecom-Paris, France)</div></div><span class="tm-dates">Sep 2024 - Mar 2025</span></li>
<li class="tm-row"><div class="tm-row-main"><a class="tm-name" href="https://www.linkedin.com/in/haoming-lin-505099223/?originalSubdomain=ch">Haoming Lin</a><div class="tm-role">MSc student (EPFL, Switzerland)</div></div><span class="tm-dates">Apr 2024 - Sep 2024</span></li>
<li class="tm-row"><div class="tm-row-main"><a class="tm-name" href="https://www.linkedin.com/in/ashwin-k-krishna-070a57202/?originalSubdomain=in">Ashwin Krishna</a><div class="tm-role">BSc Student (IIT Madras, India)</div></div><span class="tm-dates">Apr 2023 - Jul 2023</span></li>
<li class="tm-row"><div class="tm-row-main"><a class="tm-name" href="https://www.linkedin.com/in/marine-bruel-228902250/?originalSubdomain=fr">Marine Bruel</a><div class="tm-role">BSc student (École Centrale de Lille, France)</div></div><span class="tm-dates">Feb 2023 - Apr 2023</span></li>
<li class="tm-row"><div class="tm-row-main"><a class="tm-name" href="https://www.linkedin.com/in/emmanouil-sylligardos/?originalSubdomain=gr">Emmanouil Sylligardos</a><div class="tm-role">MSc student (University of Crete, Greece)</div></div><span class="tm-dates">Sep 2022- Mar 2023</span></li>
<li class="tm-row"><div class="tm-row-main"><a class="tm-name" href="https://www.linkedin.com/in/jose-melo-costa/?originalSubdomain=br">Jose Lucas De Melo Costa</a><div class="tm-role">MSc student (CentraleSupélec, France)</div></div><span class="tm-dates">Jun 2022 - Aug 2022</span></li>
</ul>

</div>
