---
permalink: /about
hidden: true
classes: wide
# layout: single-hf
# layout: single
layout: default
title: "About me"
author_profile: true
redirect_from: 
  - /about
  - /about.html
---

<style>
/* ---------- about page (all rules scoped to .ab) ---------- */
.ab { --ab-border: rgba(127,127,127,.25); --ab-muted: #6b7378; --ab-accent: #2f6f9f; --ab-soft: rgba(47,111,159,.09); overflow-wrap: anywhere; }
.ab hr { display: none; }
.ab h1 { margin-bottom: .2em; }
.ab h2 { font-size: 1.3em; margin: 1.6em 0 .7em; padding-bottom: .25em; border-bottom: 2px solid var(--ab-border); }
.ab h2:first-of-type { margin-top: .6em; }
/* awards: grid of cards */
.ab > h2:first-of-type + ul { list-style: none; padding: 0; margin: 0; display: grid; grid-template-columns: repeat(auto-fill, minmax(min(100%, 280px), 1fr)); gap: .55em; }
.ab > h2:first-of-type + ul > li { display: flex; gap: .6em; align-items: flex-start; margin: 0; padding: .6em .85em; border: 1px solid var(--ab-border); border-radius: 8px; background: #fff; line-height: 1.4; font-size: .93em; }
.ab > h2:first-of-type + ul > li::before { content: "\1F3C6"; flex: none; font-size: 1.05em; line-height: 1.3; }
.ab > h2:first-of-type + ul > li a { color: #333; }
.ab > h2:first-of-type + ul > li a:hover { color: var(--ab-accent); }
/* education and experiences: timeline */
.ab > h2:not(:first-of-type) + ul { list-style: none; padding: 0; margin: 0 0 0 .4em; }
.ab > h2:not(:first-of-type) + ul > li { position: relative; margin: 0; padding: 0 0 1.2em 1.5em; border-left: 2px solid var(--ab-border); line-height: 1.5; }
.ab > h2:not(:first-of-type) + ul > li:last-child { padding-bottom: .2em; }
.ab > h2:not(:first-of-type) + ul > li::before { content: ""; position: absolute; left: -7px; top: .3em; width: 12px; height: 12px; border-radius: 50%; background: #fff; border: 2px solid var(--ab-accent); box-sizing: border-box; }
.ab > h2:not(:first-of-type) + ul > li > p { margin: 0; }
.ab .ab-date { display: inline-block; font-size: .78em; font-weight: 700; color: var(--ab-accent); background: var(--ab-soft); padding: .08em .6em; border-radius: 999px; }
.ab .ab-role { display: block; font-style: normal; font-weight: 600; color: #222; margin-top: .25em; }
.ab > h2:not(:first-of-type) + ul > li ul { margin: .35em 0 0; padding-left: 1.15em; font-size: .92em; color: #555; }
.ab > h2:not(:first-of-type) + ul > li ul li { margin: .2em 0; }
.ab > h2:not(:first-of-type) + ul > li ul p { margin: .2em 0; }
</style>

<div class="ab" markdown="1">

<h1>About me</h1>

## Awards
- [Listed as VLDB 2026 distinguished reviewers](https://vldb.org/2026/conference-awards.html)
- [Listed as KDD 2026 best reviewers for the research track](https://kdd2026.kdd.org/kdd-best-reviewers/#research)
- [Listed as EDBT 2025 program committee honorable mentions](https://edbticdt2025.upc.edu/?contents=honorable-mentions-EDBT.html)
- [IEEE ICDE 2024 Best Runner-Up Demo Award](https://icde2024.github.io/awards.html)
- [Paul Caseau 2022 award](https://www.edf.fr/groupe-edf/innover/rd-un-savoir-faire-mondial/notre-communaute-scientifique/prix-et-trophees-de-la-rd/2022-qui-sont-les-laureats-du-prix-de-these-paul-caseau)
- [Lambdamu congress "research and industry" 2022 prize](https://www.imdr-lambdamu.eu/lambda-mu-dor23)
- [BDA 2022 Ph.D. prize](https://bdav.irisa.fr/prix/)
- [INFORSID 2022 Ph.D. prize](http://inforsid.fr/laureatprixthese.php)


***

## Education

- **2019-2021**: *Ph.D. student, University of Paris, EDF R&D*
  - Analysis of very large multivariate time series using unsupervised learning methods in order to detect anomalies and support predictive maintenance. Collaboration with the National French Electricity Company (EDF).
  - Advisors: 
    - [Prof. Themis Palpanas](http://helios.mi.parisdescartes.fr/~themisp/) 
    - Emmanuel Remy
    - Mohammed Meftah

- **2020**: *Visiting PH.D. student, University of Chicago*
  - Evaluating a possible extension of subsequence clustering and anomaly detection methods for streaming data series.
  - Advisors:
    - [Prof. Michael J. Franklin](https://cs.uchicago.edu/people/michael-franklin/)
    - [Prof. John Paparrizos](https://www.paparrizos.org/)

- **2014-2017:** *Master and Bachelor degree, Grenoble INP, ENSIMAG*
  - Engineering and Computer Science School 

- **2016-2017:** *Exchange Program (Master), Trinity College Dublin, SCSS*
  - School of Computer Science and Statistics 
  - (First Honor grade for First and Second Semester)

***


## Experiences

- **December 2023 - Present:** *Inria Researcher (ISFP), Inria (Paris Research Center), VALDA project-team*

- **September 2026 - Present:** *Joint Faculty Professor (Professeur Attaché), École Normale Supérieure (PSL), DI-ENS*

- **2023:** *Postdoctoral researcher, École Normale Supérieurs (ENS) Paris-Saclay, Centre Borelli*

- **October 2022:** *Visiting Researcher, European Gravitational Observatory (EGO), the VIRGO collaboration*
  - Research project:
     - Geo-localization of noises using data series from fiber-acoustic sensors positioned at one of the buildings of the VIRGO interferometer. Collaboration with Dr. Stamatios Gkaitatzis and Prof. Stavros Katsanevas.

- **2022-2023:** *Postdoctoral researcher, Université Paris Cité, LIPADE*
  - Research projects:
    - Benchmarking and large-scale evaluation of anomaly detection methods for univariate time series. Collaboration with Dr. John Paparrizos and Prof. Michael J. Franklin from the University of Chicago.
    - Precursor detection and time series classification for the prediction of the Piton de la Fournaise volcano. Collaboration with the Institut de Physique du Globe de Paris (IPGP).
    - Ensembling unsupervised anomaly detection methods with a supervised model selection method. Evaluation on large univariate time series benchmark.
 

- **2017-2018:** *Research engineer, Ecole Polytechnique, LIX*
  - Research projects:
    - **COM4U**:  Analysis of retail data using unsupervised learning techniques in order to discover causality links between external events and web behaviors. Collaboration with start-up Realytics. Graph mining, URL clustering, time series clustering. Implementation in Python. 

    - **SMARTLAW**: Analysis of textual law data using unsupervised techniques in order to estimate the difficulty and the type of trial in the Court of Justice of France. Collaboration with the law faculty at HEC Paris Business School. Text mining, Graph modeling, Graph mining, k-core analysis. Implementation in Python.
  - Supervision:
    - [Prof. Michalis Vazirgiannis](http://www.lix.polytechnique.fr/Labo/Michalis.Vazirgiannis/)

- **2017:** *Research intern, Paris Descartes University, LIPADE*
  - Development of machine learning algorithms to detect and predict subsequence anomalies in sensor data of electric power plants. Time series similarity/clustering/classification, Matrix Profile (MP). Implementation in C and Python. 
  - Supervision:
    - [Prof. Themis Palpanas](http://helios.mi.parisdescartes.fr/~themisp/) 

- **2016:** *Research intern, IRT Saint-Exupery*
  - Implementation of an avoidance rover protection system (ARP) in C from an Event-B model. Formal verification of the code using frama-c, why3-based ACSL language.

***

</div>

<script>
/* Timeline: "**2019-2021**: *Role*" becomes a date tag above the role (the ": " between them is dropped).
   Without JavaScript the same content is shown, slightly less polished. */
(function () {
  var root = document.querySelector('.ab');
  if (!root) return;
  root.querySelectorAll(':scope > h2:not(:first-of-type) + ul > li').forEach(function (li) {
    var box = li.firstElementChild && li.firstElementChild.tagName === 'P' ? li.firstElementChild : li;
    var date = box.querySelector(':scope > strong'), role = box.querySelector(':scope > em');
    if (!date) return;
    date.classList.add('ab-date');
    date.textContent = date.textContent.replace(/[\s:]+$/, '');
    var n = date.nextSibling;
    if (n && n.nodeType === 3) n.textContent = n.textContent.replace(/^[\s:]+/, '');
    if (role) role.classList.add('ab-role');
  });
})();
</script>
