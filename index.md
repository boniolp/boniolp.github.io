<style>
/* ---------- home page (all rules scoped to .ix) ---------- */
.ix { --ix-border: rgba(127,127,127,.22); --ix-muted: #6b7378; --ix-accent: #2f6f9f; --ix-soft: rgba(47,111,159,.08); overflow-wrap: anywhere; }
.ix h2 { font-size: 1.3em; margin: 1.6em 0 .6em; padding-bottom: .25em; border-bottom: 2px solid var(--ix-border); }
.ix h2:first-of-type { margin-top: 0; }
.ix > p { line-height: 1.7; }
/* research interests */
.ix > ul:first-of-type { list-style: none; padding: 0; margin: .4em 0 0; display: grid; grid-template-columns: repeat(auto-fill, minmax(min(100%, 220px), 1fr)); gap: .5em; }
.ix > ul:first-of-type > li { margin: 0; padding: .65em .85em; border: 1px solid var(--ix-border); border-top: 3px solid var(--ix-accent); border-radius: 8px; background: #fff; font-size: .92em; line-height: 1.45; color: #333; }
/* open positions */
.ix > h2:nth-of-type(2) + p { margin: 0; padding: .8em 1em; border-radius: 8px; background: var(--ix-soft); border-left: 3px solid var(--ix-accent); line-height: 1.6; }
.ix > h2:nth-of-type(2) + p a { font-weight: 600; }
/* news */
.ix > ul:last-of-type { list-style: none; padding: 0; margin: 0; }
.ix > ul:last-of-type > li { position: relative; margin: 0; padding: 0 0 .95em 1.4em; border-left: 2px solid var(--ix-border); margin-left: .4em; line-height: 1.55; }
.ix > ul:last-of-type > li::before { content: ""; position: absolute; left: -6px; top: .35em; width: 10px; height: 10px; border-radius: 50%; background: #fff; border: 2px solid var(--ix-accent); box-sizing: border-box; }
.ix .ix-date { display: inline-block; font-size: .75em; font-weight: 700; color: var(--ix-accent); background: var(--ix-soft); padding: .05em .55em; border-radius: 999px; margin-right: .35em; vertical-align: 1px; }
.ix .ix-hidden { display: none; }
.ix .ix-more { font: inherit; font-size: .85em; margin: .2em 0 0 1.8em; padding: .3em .9em; border: 1px solid var(--ix-border); border-radius: 999px; background: #fff; color: var(--ix-accent); cursor: pointer; }
</style>

<div class="ix" markdown="1">

## Short bio

I am a researcher at [Inria](https://www.inria.fr) and a member of the [VALDA](https://team.inria.fr/valda/) project team, a joint team between [Inria Paris](https://www.inria.fr/centre/paris), [École Normale Supérieure](https://www.ens.fr), and [CNRS](https://www.cnrs.fr). Since September 2026, I have been a Joint Faculty Professor (Professeur Attaché) at [École Normale Supérieure](https://www.ens.fr) and Paris Sciences & Lettres University (PSL).

Before that, I was a Postdoctoral researcher at École Normale Supérieure (ENS) Paris-Saclay (Center Borelli) in the team of [Prof. Laurent Oudre](http://www.laurentoudre.fr/). I completed my Ph.D. at the University of Paris and EDF R&D, working with [Prof. Themis Palpanas](http://helios.mi.parisdescartes.fr/~themisp/), Emmanuel Remy, and Mohammed Meftah. During my Ph.D., I did an internship at the University of Chicago under the supervision of [Prof. Michael J. Franklin](https://cs.uchicago.edu/people/michael-franklin/) and [Prof. John Paparrizos](https://www.paparrizos.org/). Before that, I got my bachelor’s and master’s degrees in computer science and applied mathematics from Grenoble INP ENSIMAG engineering school. Finally, before starting my Ph.D., I worked as a research engineer at the computer science lab of École Polytechnique in [Prof. Michalis Vazirgiannis](http://www.lix.polytechnique.fr/Labo/Michalis.Vazirgiannis/)'s team.

My research interests lie in the intersections between:
-  Massive time series analytics and management systems. 
-  Unsupervised and supervised anomaly detection methods for large time series.
-  Machine learning for time series analytics.

## Open Positions!

I am currently looking for an **Intern** to join my group/projects. You may find [Here](https://boniolp.github.io/topics) the list of open positions.


## News
- **[Oct. 2026]** Our papers [TSB-SEG](https://github.com/fchavelli/TSB-SEG) (Time Series Segmentation Benchmark), [SHAD](https://arxiv.org/abs/2610.01168) (A novel dataset for time series anomaly detection, explanation, and interpretation), and [RAMSAD](https://arxiv.org/abs/2610.20243) (TSFM-based model selection with similarity search) have been accepted and will be presented at [NeurIPS 2026](https://neurips.cc/).
- **[May 2026]** Thanks to the [SPACERAISE](https://spaceraise.academy/) organizers for inviting me to give a lecture on Time Series Analytics. You may find the slides [here](https://boniolp.github.io/GSSI-2026).
- **[Dec. 2025]** Thanks to the [3rd Macau Symposium on Data Science](https://dss.cds.ici.um.edu.mo/2025-landing-page/invited-speakers/) organizers for inviting me to give a talk on Automatic solutions for time series anomaly detection.
- **[Oct. 2025]** Thanks to the [TwinODIS](https://sites.google.com/view/twinodis-summerschool1/home) organizers for inviting me to give three lectures on time series anomaly detection. You may find the slides [here](https://boniolp.github.io/TwinODIS).
- **[Aug. 2025]** We have released an interactive taxonomy on time series anomaly detection. Explore it on [GitHub](https://github.com/boniolp/TSADtaxonomy) or directly via the [webpage](https://boniolp.github.io/TSADtaxonomy/)
- **[May. 2025]** Thanks to the [SPACERAISE](https://spaceraise.academy/) organizers for inviting me to give two lectures on Time Series Analytics. You may find the slides [here](https://boniolp.github.io/GSSI-2025).
- **[Jan. 2025]** Thanks to the [SIDOS workshop](https://sites.google.com/view/sidos2025/home) organizers for inviting me to give a talk on Time Series Anomaly Detection. You may find the slides [here](https://inriafr-my.sharepoint.com/:b:/g/personal/paul_boniol_inria_fr/EVaUZdWPfW5Lq4g537toVPkBHkemnMw0bf6BUP4Ks8us9Q).
- **[Nov. 2024]** Thanks to the [ML4Jets 2024](https://indico.cern.ch/event/1386125/) organizers for inviting me to give a talk on [Model selection and Time Series Anomaly Detection](https://indico.cern.ch/event/1386125/timetable/?view=standard). You may find the slides [here](https://inriafr-my.sharepoint.com/:b:/g/personal/paul_boniol_inria_fr/Ee_QyfkiTNZNqX4W1G-XBIoBSfncOW0PE7JvmtnFi-P8fw) and a video [here](https://indico.cern.ch/event/1386125/contributions/6209715/attachments/2959820/5224750/08ML4Jets24_BoniolPaul.mp4).
- **[Sep. 2024]** Thanks to the [AALTD 2024](https://ecml-aaltd.github.io/aaltd2024/people.html) organizers for inviting me to give a talk on [Time Series Anomaly Detection](https://ecml-aaltd.github.io/aaltd2024/invitedtalk.html). You may find the slides [here](https://inriafr-my.sharepoint.com/:b:/g/personal/paul_boniol_inria_fr/EVgVym7YIuZDplH6M-pWXhQBbzymeUGk296LNZ56_kITYw).

</div>

<script>
/* News: "[May 2026]" becomes a date tag; only the 5 most recent items are shown, the others behind a button.
   Without JavaScript all the news are shown as a timeline. */
(function () {
  var root = document.querySelector('.ix');
  if (!root) return;
  var lists = root.querySelectorAll(':scope > ul'), news = lists[lists.length - 1];
  if (!news || lists.length < 2) return;
  var SHOW = 5, items = Array.prototype.slice.call(news.children);
  items.forEach(function (li, i) {
    var box = li.querySelector('p') || li, s = box.querySelector('strong');
    if (s && box.firstElementChild === s && /^\[.*\]$/.test(s.textContent.trim())) {
      s.textContent = s.textContent.trim().replace(/^\[|\]$/g, '');
      s.className = 'ix-date';
    }
    if (i >= SHOW) li.classList.add('ix-hidden');
  });
  if (items.length > SHOW) {
    var b = document.createElement('button'); b.type = 'button'; b.className = 'ix-more';
    b.textContent = 'Show older news (' + (items.length - SHOW) + ')';
    b.onclick = function () {
      var open = b.dataset.open !== '1';
      items.forEach(function (li, i) { if (i >= SHOW) li.classList.toggle('ix-hidden', !open); });
      b.dataset.open = open ? '1' : '0';
      b.textContent = open ? 'Show fewer news' : 'Show older news (' + (items.length - SHOW) + ')';
    };
    news.parentNode.insertBefore(b, news.nextSibling);
  }
})();
</script>
