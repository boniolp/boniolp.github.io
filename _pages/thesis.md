---
permalink: /thesis
hidden: true
classes: wide
# layout: single-hf
# layout: single
layout: default
title: "Detection of Anomalies and Identification of their Precursors in Large Data Series Collections"
author_profile: true
redirect_from: 
  - /thesis
  - /thesis.html
---

<style>
/* ---------- thesis page (all rules scoped to .th) ---------- */
.th { --th-border: rgba(127,127,127,.22); --th-muted: #6b7378; --th-accent: #2f6f9f; --th-soft: rgba(47,111,159,.08); overflow-wrap: anywhere; }
.th hr { display: none; }
.th > h1 { line-height: 1.25; margin-bottom: .2em; }
.th > h3:first-of-type { font-weight: 400; color: var(--th-muted); font-size: 1em; margin: 0 0 1.2em; text-transform: none; letter-spacing: 0; }
.th h2 { font-size: 1.3em; margin: 0 0 .6em; padding-bottom: .25em; border-bottom: 2px solid var(--th-border); }
.th h3 { font-size: .8em; text-transform: uppercase; letter-spacing: .08em; color: var(--th-muted); margin: 1em 0 .4em; }
.th img { max-width: 100%; height: auto; }
.th .th-sec { margin: 0 0 2em; }
/* jury */
.th .th-jury ul { list-style: none; padding: 0; margin: 0; display: grid; grid-template-columns: repeat(auto-fill, minmax(min(100%, 280px), 1fr)); gap: .5em; }
.th .th-jury li { margin: 0; padding: .55em .85em; border: 1px solid var(--th-border); border-radius: 8px; background: #fff; font-size: .9em; line-height: 1.45; color: #555; }
.th .th-jury li strong { display: block; font-size: 1.05em; }
/* abstract, pdf and video */
.th .th-abstract p { line-height: 1.65; }
.th .th-pdf { display: block; margin: 1em 0; padding: .7em .95em; border-radius: 8px; background: var(--th-soft); border-left: 3px solid var(--th-accent); }
.th .th-video img { display: block; width: 100%; max-width: 480px; border-radius: 10px; border: 1px solid var(--th-border); margin-top: .5em; }
/* chapters */
.th .th-ch { display: flow-root; padding: 1em 1.1em; border: 1px solid var(--th-border); border-radius: 10px; background: #fff; }
.th .th-ch h2 { border-bottom: 0; padding-bottom: 0; margin-bottom: .5em; }
.th .th-ch .th-fig { float: right; width: 280px; max-width: 40%; margin: 0 0 .6em 1.2em !important; }
.th .th-ch .th-fig img { width: 100%; border-radius: 8px; }
.th .th-ch p { line-height: 1.6; }
.th .th-ch ul { list-style: none; padding: 0; margin: 0; clear: both; }
.th .th-ch ul li { margin: .45em 0; padding: .55em .85em; border: 1px solid var(--th-border); border-left: 3px solid var(--th-accent); border-radius: 8px; font-size: .9em; line-height: 1.5; }
.th .th-ch ul li p { margin: 0; text-align: left !important; }
.th .th-back { display: inline-block; padding: .35em .9em; border: 1px solid var(--th-border); border-radius: 999px; text-decoration: none; }
@media (max-width: 640px) {
  .th .th-ch .th-fig { float: none; width: auto; max-width: 100%; margin: 0 0 .8em 0 !important; }
  .th .th-ch { padding: .8em .85em; }
}
</style>

<div class="th" markdown="1">

# Detection of Anomalies and Identification of their Precursors in Large Data Series Collections

### Presented by Paul Boniol on November 29 2021

***

## Jury
* **[Karine Zeitouni](https://pages.david.uvsq.fr/kzeitouni/)**, Professor, Université de Versailles - DAVID
* **[Germain Forestier](https://germain-forestier.info/)**, Professor, Université Haute-Alsace - ENSISA
* **[Bernd Amann](https://www.lip6.fr/actualite/personnes-fiche.php?ident=P200)**, Professor, Sorbonne Université - LIP6 
* **[Michalis Vazirgiannis](http://www.lix.polytechnique.fr/Labo/Michalis.Vazirgiannis/)**, Professeur, Ecole Polytechnique - LIX
* **[Themis Palpanas](https://helios2.mi.parisdescartes.fr/~themisp/home.html)**, Professor, Université de Paris, LIPADE
* **[Mohammed Meftah](https://www.linkedin.com/in/meftahdatascientist/?originalSubdomain=fr)**, Research engineer, EDF R&D
* **Emmanuel Remy**, Research engineer, EDF R&D

***

## Abstract
<p style='text-align: justify;'>
Extensive collections of data series are becoming a reality in a large number of scientific and social domains. There is, therefore, a growing interest and need to elaborate efficient techniques to analyze and process these data, such as in finance, environmental sciences, astrophysics, neurosciences, engineering. Informally, a data series is an ordered sequence of points or values. Once these series are collected and available, users often need to query them. These queries can be simple, such as the selection of time interval, but also complex, such as the similarities search or the detection of anomalies, often synonymous with malfunctioning of the system under study, or sudden and unusual evolution likely undesired. This last type of analysis represents a crucial problem for applications in a wide range of domains, all sharing the same objective: to detect anomalies as soon as possible to avoid critical events. Therefore, in this thesis, we address the following three objectives: (i) retrospective unsupervised subsequence anomaly detection in data series. (ii) unsupervised detection of anomalies in data streams. (iii) classification explanation of known anomalies in data series in order to identify possible precursors. This manuscript first presents the industrial context that motivated this thesis, fundamental definitions, a taxonomy of data series, and state-of-the-art anomaly detection methods. We then present our contributions along the three axes mentioned above. First, we describe two original solutions, NormA (that aims to build a weighted set of subsequences that represent the different behaviors of the data series) and Series2Graph (that transform the data series in a directed graph), for the task of unsupervised detection of anomalous subsequences in static data series. Secondly, we present the SAND (inspired from NormA) method for unsupervised detection of anomalous subsequences in data streams. Thirdly, we address the problem of the supervised identification of precursors. We subdivide this task into two generic problems: the supervised classification of time series and the explanation of this classification’s results by identifying discriminative subsequences. Finally, we illustrate the applicability and interest of our developments through an application concerning the identification of undesirable vibration precursors occurring in water supply pumps in the French nuclear power plants of EDF.
</p>
**Thesis (pdf)**: [Detection of Anomalies and Identification of their Precursors in Large Data Series Collections](https://helios2.mi.parisdescartes.fr/~themisp/publications/PaulBoniol-PhdThesis-2021.pdf)

This interview gives you a brief overview of my work during my Ph.D.
[![An overview of my work during my Ph.D.](https://img.youtube.com/vi/DEihnx9Sa48/0.jpg)](https://www.youtube.com/watch?v=DEihnx9Sa48)

***

## Chapter 2: Background and Related Work
<p align="center">
<img src="https://boniolp.github.io/assets/img/illustration_2.jpg" alt="Chapter2" width="300"/>
</p>
### Summary
<p style='text-align: justify;'>
In this chapter, we define the relevant taxonomy related to data series and anomaly detection methods. We then formally define the problem of subsequence anomaly detection in data series tackled in this manuscript. We finally study state-of-the-art methods to perform unsupervised anomaly detection and supervised identification of anomaly precursors in data series. Thus, the chapter is structured as follows. We first underline the preliminary definitions and the context of anomaly detection in data series. We describe the fundamental differences between point and subsequence anomalies and argue our choice of subsequence anomalies as our primary focus. We then formally describe the problem of subsequence anomaly detection in data series. As previously outlined, we inferred two variants of the problem. On the one hand, the anomalies are unknown, and a fully unsupervised framework has to be adopted. On the other hand, anomalies are known, and precursors of these anomalies have to be found. We finally enumerate state-of-the-art methods that could solve the problems mentioned above.
</p>

***

## Chapter 3: Unsupervised Subseqence Anomaly Detection
<p align="center">
<img src="https://boniolp.github.io/assets/img/illustration_3.jpg" alt="Chapter3" width="300"/>
</p>
### Summary
<p style='text-align: justify;'>
Unsupervised subsequence anomaly (or outlier) detection in long sequences is an important problem with applications in many domains. However, the approaches that have been proposed so far in the literature have severe limitations: they either require prior domain knowledge or become cumbersome and expensive to use in situations with recurrent anomalies of the same type. This chapter addresses these problems and proposes two generic approaches, NormA and Series2Graph, two novel approaches suitable for domain-agnostic anomaly detection. NormA is based on a new data series primitive, which permits to detect anomalies based on their (dis)similarity to a model that represents normal behavior. Series2Graph aims to embed the data series into a directed graph that emphasizes the unusual and potentially abnormal subsequences. The experimental results on several real datasets demonstrate that the proposed approaches correctly identify both single and recurrent anomalies of various types, with no prior knowledge of the characteristics of these anomalies (except for their length). Moreover, it outperforms the current state-of-the-art algorithms in terms of accuracy (up to 0.98 Precision@k) while being faster in execution time (for instance, one order of magnitude faster for NormA-smpl).
</p>

### Related Publications

* Paul Boniol, Michele Linardi, Federico Roncallo, Themis Palpanas, Mohammed Meftah. Emmanuel Remy. **Unsupervised and Scalable Subsequence Anomaly Detection in Large Data Series**. International Journal on Very Large Data Bases (VLDBJ), 2021. [More info...](https://boniolp.github.io/norma)

* Paul Boniol, Themis Palpanas. **Series2Graph: Graph-based Subsequence Anomaly Detection for Time Series**. Proceedings of the VLDB Endowment (PVLDB) Journal 13(11), 2020. [More info...](https://boniolp.github.io/s2g)

* Paul Boniol, Michele Linardi, Federico Roncallo, Themis Palpanas. **Automated Anomaly Detection in Large Sequences**. IEEE International Conference on Data Engineering (ICDE), Dallas, TX, USA, April 2020. [More info...](https://boniolp.github.io/norma)

* Paul Boniol, Michele Linardi, Federico Roncallo, Themis Palpanas. **SAD: An Unsupervised System for Subsequence Anomaly Detection**. IEEE International Conference on Data Engineering (ICDE), Dallas, TX, USA, April 2020. [More info...](https://boniolp.github.io/norma)

* Paul Boniol, Themis Palpanas, Mohammed Meftah, Emmanuel Remy. **GraphAn: Graph-based Subsequence Anomaly Detection**. Proceedings of the VLDB Endowment (PVLDB) Journal, 2020. [More info...](https://boniolp.github.io/s2g)

* Paul Boniol (supervised by Themis Palpanas, Mohammed Meftah, Emmanuel Remy). **Unsupervised Subsequence Anomaly Detection in Large Sequences**. Very Large Data Bases (VLDB) PhD Workshop, Tokyo, Japan, August 2020.

***

## Chapter 4: Streaming Subseqence Anomaly Detection
<p align="center">
<img src="https://boniolp.github.io/assets/img/illustration_4.jpg" alt="Chapter4" width="370"/>
</p>
### Summary
<p style='text-align: justify;'>
In the previous chapter, we tackled the unsupervised subsequence anomaly detection method for static data series. However, with the increasing demand for real-time analytics and decision-making, anomaly detection methods need to operate over streams of values and handle drifts in data distribution. Moreover, subsequence anomaly detection methods usually require access to the entire dataset and are not able to learn and detect anomalies in streaming settings. This chapter tackles the above-mentioned issues and proposes SAND, a novel online method suitable for domain-agnostic anomaly detection. SAND aims to detect anomalies based on their distance to a model that represents normal behavior. SAND relies on a novel streaming methodology to incrementally update such a model, which adapts to distribution drifts and omits obsolete data. The experimental results on several real-world and simulated datasets demonstrate that SAND correctly identifies single and recurrent anomalies without prior knowledge of the characteristics of these anomalies (up to 0.10 Precision@k improvement compared to previous approaches).
</p>

### Related Publications

* Paul Boniol, John Paparrizos, Themis Palpanas, Michael J. Franklin. **SAND: Streaming Subsequence Anomaly Detection**. Proceedings of the VLDB Endowment (PVLDB) Journal, 2021. [More info...](https://boniolp.github.io/sand)

* Paul Boniol, John Paparrizos, Themis Palpanas, Michael J. Franklin. **SAND in Action: Subsequence Anomaly Detection for Streams**. Proceedings of the VLDB Endowment (PVLDB) Journal, 2021. [More info...](https://boniolp.github.io/sand)

***

## Chapter 5: Supervised Identification of precursors of anomaly
<p align="center">
<img src="https://boniolp.github.io/assets/img/illustration_5.jpg" alt="Chapter5" width="370"/>
</p>
### Summary
<p style='text-align: justify;'>
In the previous chapter, anomalies were considered unknown. However, one can consider that experts precisely know which event he wants to detect and has a collection of data series that corresponds to these anomalies. In that case, we have a database of anomalies at our disposal. As a consequence, one can decide to adopt supervised methods. A question that naturally arises is the following one: is it possible to detect subsequences that happened before the known anomaly that might lead to an explanation of the anomaly (and potentially predict it). If the supervised model is trained to classify anomalies from normal data series, the features and subsequences that discriminate the anomaly from the normal class can be seen as symptoms or precursors (if these subsequences happened before the anomaly). Thus precursors detection for known anomalies can be tackled as a discriminant features identification for a classification model. For some Convolutional Neural Network-based models, the Class Activation Map (CAM) can be used as an explanation for the classification result. CAM has been used for highlighting the parts of an image that contribute the most to a given class prediction, and has also been adapted to data series. Nevertheless, CAM for data series suffers from one important limitation. Since CAM is a univariate time series with high values aligned with the subsequences of the input that contribute the most for a given class identification, in the specific case of multivariate data series as input, no information can be retrieved from CAM on the level of contribution of specific dimensions. In this Chapter, we describe a novel approach, dCAM, based on convolutional neural networks, enabling us to detect the discriminant subsequences within individual dimensions of a multivariate data series. In order to apply dCAM, we provide a transformation to the network architecture that we call dCNN (for the usual CNN architecture) dResNet and dInceptionTime (for the ResNet and the InceptionTime architectures). The experimental evaluation with synthetic and real datasets demonstrates our approach’s benefits and superiority in discriminant feature discovery and classification explanation in multivariate time series. Moreover, we evaluated the influences between several important parameters in order to give the user all the keys to estimate the accuracy of dCNN and dCAM.
</p>

### Related Publications

* Paul Boniol, Mohammed Meftah, Emmanuel Remy, Themis Palpanas. **dCAM: Dimension-wise Class Activation Map for Explaining Multivariate Data Series Classification**. In Proceedings of the 2022 International Conference on Management of Data (SIGMOD’22), 2022. [More info...](https://www.researchgate.net/publication/361416963_dCAM_Dimension-wise_Class_Activation_Map_for_Explaining_Multivariate_Data_Series_Classification)

***

## Chapter 6: Pump Vibration Case
<p align="center">
<img src="https://boniolp.github.io/assets/img/illustration_6.jpg" alt="Chapter6" width="370"/>
</p>
### Summary
<p style='text-align: justify;'>
In this chapter, we illustrate the applicability and the interest of our developed methods in a real-world application. We study the detection precursors of unwanted vibrations occurring in turbine-driven feed-water pump systems inside EDF nuclear power plants. We first describe the dataset and the industrial context. We then explore two scenarios: we first tackle the task as if the experts had provided no label and apply NormA and Series2Graph. We evaluate their accuracy using the labels of the experts. We then tackle the task as a supervised problem (using the label provided by the experts) and apply dCNN/dCAM. We first compare the accuracy of both unsupervised and supervised methods. We then investigate the precursors detected by dCAM and discuss the validity of these results compared to expert knowledge.
</p>

### Related Publications

* Paul Boniol, Mohammed Meftah, Emmanuel Remy, Bruno Didier, Themis Palpanas. **dCNN/dCAM: Anomaly Precursors Discovery in Multivariate Time Series with Deep Convolutional Neural Networks**. Data-Centric Engineering (DCE) Journal, 2023. [More info...](https://boniolp.github.io/dcam)

***

[Back to main page](https://boniolp.github.io/)

</div>

<script>
/* Groups each "## ..." part of the page into its own block (jury, abstract, chapters) so that it can be styled.
   The text itself is not modified. Without JavaScript the page is shown as before, with lighter styling. */
(function () {
  var root = document.querySelector('.th');
  if (!root) return;
  var kids = Array.prototype.slice.call(root.children), sec = null;
  kids.forEach(function (el) {
    if (el.tagName === 'H2') {
      sec = document.createElement('section');
      var t = el.textContent.trim();
      sec.className = 'th-sec ' + (/^chapter/i.test(t) ? 'th-ch' : /^jury/i.test(t) ? 'th-jury' : /^abstract/i.test(t) ? 'th-abstract' : '');
      root.insertBefore(sec, el);
    } else if (el.tagName === 'HR') { sec = null; return; }
    if (sec) sec.appendChild(el);
  });
  // jury: "**Name**, role" -> name on its own line, without the leading comma
  root.querySelectorAll('.th-jury li').forEach(function (li) {
    var box = li.querySelector('p') || li, s = box.querySelector('strong');
    if (s && s.nextSibling && s.nextSibling.nodeType === 3) s.nextSibling.textContent = s.nextSibling.textContent.replace(/^[\s,]+/, '');
  });
  root.querySelectorAll('.th-ch > p').forEach(function (p) {
    if (p.querySelector('img') && !p.textContent.trim()) p.classList.add('th-fig');
  });
  root.querySelectorAll('p').forEach(function (p) {
    var s = p.querySelector('strong');
    if (s && /thesis \(pdf\)/i.test(s.textContent)) p.classList.add('th-pdf');
    if (p.querySelector('a[href*="youtube"] img')) p.classList.add('th-video');
    var a = p.querySelector('a');
    if (a && /back to main page/i.test(p.textContent) && p.textContent.trim() === a.textContent.trim()) a.classList.add('th-back');
  });
})();
</script>
