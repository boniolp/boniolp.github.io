---
permalink: /talks
hidden: true
classes: wide
# layout: single-hf
# layout: single
layout: default
title: "Talks"
author_profile: true
redirect_from: 
  - /talks
  - /talks.html
---

<style>
/* ---------- talks page (all rules scoped to .tk) ---------- */
.tk { --tk-border: rgba(127,127,127,.22); --tk-muted: #6b7378; --tk-accent: #2f6f9f; overflow-wrap: anywhere; }
.tk h1 { margin-bottom: .3em; }
.tk .tk-summary { display: none; }
.tk .tk-legend { display: flex; flex-wrap: wrap; gap: .3em 1em; font-size: .82em; color: var(--tk-muted); margin: 0 0 .4em; }
.tk .tk-legend span::before { content: ""; display: inline-block; width: .8em; height: .8em; border-radius: 2px; margin-right: .35em; vertical-align: -1px; background: var(--tk-kind); }
.tk .tk-years { font-size: .85em; color: var(--tk-muted); margin: 0 0 1em; }
.tk .tk-years a { margin-right: .7em; }
.tk h4 { font-size: 1.3em; margin: 1.5em 0 .4em; padding-bottom: .25em; border-bottom: 2px solid var(--tk-border); scroll-margin-top: 70px; }
.tk h4 .tk-count { font-size: .55em; font-weight: 600; color: var(--tk-muted); margin-left: .5em; vertical-align: middle; }
.tk ul { list-style: none; padding: 0; margin: 0; }
.tk li { margin: .5em 0; padding: .7em .95em; border: 1px solid var(--tk-border); border-left: 3px solid var(--tk-kind, var(--tk-accent)); border-radius: 8px; line-height: 1.5; background: #fff; }
.tk li p { margin: 0; }
.tk .tk-title { font-weight: 600; color: #222; }
.tk .tk-event { font-size: .9em; color: var(--tk-muted); margin-top: .15em; }
.tk .tk-links { display: flex; flex-wrap: wrap; gap: .35em; margin-top: .45em; }
.tk .tk-btn { font-size: .78em; padding: .12em .65em; border: 1px solid var(--tk-border); border-radius: 999px; color: #333; text-decoration: none; background: #fafafa; }
.tk .tk-btn:hover { border-color: var(--tk-accent); color: var(--tk-accent); }
.tk .keynote { --tk-kind: #d08a2c; }
.tk .invited { --tk-kind: #2f6f9f; }
.tk .seminar { --tk-kind: #2a8a5b; }
</style>

<div class="tk" markdown="1">

# Invited Talks and Seminars

#### 2026

- **The (very long) road to truly automatic time series anomaly detection**, Seminar at KU Leuven Bruges campus. [More info](https://set.kuleuven.be/phd/seminars/schafer-boniol).


#### 2025
- **Time Series Anomaly Detection: The Road to Automatic Solutions**, Invited Speaker at the 3rd Macau Symposium on Data Science.
- **Anomaly Detection in Time Series: Overview and New Trends**, Invited speaker at Orange Innovation, [Slides](https://inriafr-my.sharepoint.com/:b:/g/personal/paul_boniol_inria_fr/EdxWO0aQzA5EunhAeY0H6oABeI-Ge6VrK8CNKBhzP4RuWA?e=MBbmhV).
- **An introduction to Time series anomaly detection (a data-driven perspective)**, Invited speaker for SIDOS at EGC 2025. [More Info](https://sites.google.com/view/sidos2025/home), [Slides](https://inriafr-my.sharepoint.com/:b:/g/personal/paul_boniol_inria_fr/EVaUZdWPfW5Lq4g537toVPkBHkemnMw0bf6BUP4Ks8us9Q). 

#### 2024

- **Time Series Anomaly Detection: Overview and New Trends**, Keynote for ML4Jets International Conference (November 2024). [More Info](https://indico.cern.ch/event/1386125/), [Slides](https://inriafr-my.sharepoint.com/:b:/g/personal/paul_boniol_inria_fr/Ee_QyfkiTNZNqX4W1G-XBIoBSfncOW0PE7JvmtnFi-P8fw?e=bXhFjq), [Video](https://indico.cern.ch/event/1386125/contributions/6209715/attachments/2959820/5224750/08ML4Jets24_BoniolPaul.mp4).
- **Anomaly Detection in Time Seires**, keynote for AALTD workshop at ECML / PKDD 2024 (September 2024). [More info](https://ecml-aaltd.github.io/aaltd2024/invitedtalk.html), [Slides](https://inriafr-my.sharepoint.com/:b:/g/personal/paul_boniol_inria_fr/EVgVym7YIuZDplH6M-pWXhQBbzymeUGk296LNZ56_kITYw).

#### 2023

- **Dimension-wise Class Activation Map for Explaining Multivariate Data Series Classification**, Invited talk for GDR CNRS MaDICS Symposium (May 2023)
- **Detection of Anomalies and Identification of their Precursors in Large Data Series Collections**, Invited talk for GDR CNRS MaDICS Symposium (May 2023)
- **From Anomaly Detection to Precursors Discovery in Time Series**, MLMDA Seminar at ENS Paris Saclay, Centre Borelli (January 2023)

#### 2022

- **Unsupervised Subsequences Anomaly Detection and Precursors Identification for Very Large Time Series**, Seminar at VALDA team, INRIA (November 2022)
- **Automated Anomaly Detection for Very Large Time Series**, Invited talk for Forum ORAP : Le PEPR Numpex « Numérique pour l’Exascale » (November 2022)
- **Detection of Anomalies and Identification of their Precursors in Large Data Series Collections**, Seminar at CEDAR team, INRIA, (November 2022)
- **Unsupervised Detection of Abnormal Subsequences in the Context of Large Data Series Collections**, Seminar at BD team, LIP6 (September 2022)
- **Abnormal Subsequence Detection for Large Collections of Time Series**, Seminar at ZENITH team, INRIA (September 2022)
- **Anomalies Detection and Prediction for Very Large Data Series**, Invited talk for INFORSID PhD prize (May 2022)

#### 2021

- **Easy, Accurate, and Fast Complex Analytics on Big Data Series Collections: Similarity Search and Subsequence Anomaly Detection**, Seminar at DEWA R&D (May 2021)

</div>

<script>
/* Turns each "**Title**, event. [links]" item into a card, colours it by kind (keynote / invited talk / seminar),
   and adds per-year counts and a year index. Without JavaScript the plain (styled) list is shown. */
(function () {
  var root = document.querySelector('.tk');
  if (!root) return;
  function esc(s) { return s.replace(/&/g, '&amp;').replace(/</g, '&lt;').replace(/>/g, '&gt;'); }
  var years = [], total = 0, year = '';
  Array.prototype.forEach.call(root.children, function (el) {
    if (el.tagName === 'H4') { year = el.textContent.trim(); el.id = 'y' + year; years.push(el); el._n = 0; }
    if (el.tagName === 'UL') Array.prototype.forEach.call(el.children, function (li) {
      total++; if (years.length) years[years.length - 1]._n++;
      var box = li.querySelector('p') || li, title = box.querySelector('strong');
      if (!title) return;
      var event = '', links = [], seen = false, inLinks = false;
      Array.prototype.slice.call(box.childNodes).forEach(function (n) {
        if (n === title) { seen = true; return; }
        if (!seen) return;
        if (n.tagName === 'A') { inLinks = true; links.push('<a class="tk-btn" href="' + n.getAttribute('href') + '">' + esc(n.textContent) + '</a>'); return; }
        if (!inLinks) event += n.nodeType === 1 ? n.outerHTML : esc(n.textContent);
      });
      event = event.replace(/^[\s,.]+/, '').replace(/[\s,.]+$/, '');
      var kind = /keynote/i.test(event) ? 'keynote' : /seminar/i.test(event) ? 'seminar' : 'invited';
      li.classList.add(kind);
      li.innerHTML = '<div class="tk-title">' + esc(title.textContent) + '</div>' +
                     (event ? '<div class="tk-event">' + event + '</div>' : '') +
                     (links.length ? '<div class="tk-links">' + links.join('') + '</div>' : '');
    });
  });
  years.forEach(function (h) { var c = document.createElement('span'); c.className = 'tk-count'; c.textContent = h._n + (h._n > 1 ? ' talks' : ' talk'); h.appendChild(c); });
  var h1 = root.querySelector('h1'), anchor = h1 ? h1.nextSibling : root.firstChild;
  var s = document.createElement('p'); s.className = 'tk-summary'; s.textContent = total + ' talks';
  var lg = document.createElement('div'); lg.className = 'tk-legend';
  lg.innerHTML = '<span class="keynote">Keynote</span><span class="invited">Invited talk</span><span class="seminar">Seminar</span>';
  var ix = document.createElement('div'); ix.className = 'tk-years';
  ix.innerHTML = 'Jump to: ' + years.map(function (h) { return '<a href="#' + h.id + '">' + h.id.slice(1) + '</a>'; }).join('');
  root.insertBefore(s, anchor); root.insertBefore(lg, anchor); root.insertBefore(ix, anchor);
})();
</script>
