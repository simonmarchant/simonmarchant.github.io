---
layout: page
title: Smart Infant Monitoring System
description: A clinically-relevant metric for infant pain.
importance: 2
category: neuroimaging
related_publications: false
---

## What's the problem?

Many newborns are hospitalised, where they undergo procedures which are clinically essential but potentially painful. Almost every medical procedure is potentially a painful experience for newborns: every blood test, every vaccination and every prod with a device could be painful. Exposure to these noxious stimuli has harmful effects on infants in both the short-term and the long-term. Despite the harm from these procedures, it is generally acknowledged that infant pain is undertreated in clinical inpatient settings. This is partly because of the difficulty in identifying and measuring pain in infants. Our inability to accurately identify and measure pain in this population makes it difficult to evaluate the effect of analgesics, and difficult to identify which hospitalised infants would benefit from these analgesics.

We cannot measure pain directly. The gold standard for identifying pain in the adult population is verbal report, which is not possible in infants. In the absence of verbal report, current clinical practice relies on behavioural and physiological measures which are indirectly related to pain. Previous work has identified a template of electroencephalographic activity which is associated with potentially-painful experiences, but this is not yet used as a biomarker in clinical practice.

## What are we doing?

I am working on solving this problem together with several brilliant colleagues (Rebeccah Slater, Caroline Hartley, Aomesh Bhatt, Kirubin Pillay, Maria Cobo and Annalisa Hauck). We have developed methods which improve the reliability and simplicity of the measure, and user-friendly software which provides clinical end-users with an understandable metric for an individual baby's pain.

In particular, I have introduced measures of heartrate and of our confidence in a measure, in order to improve the reliability of the measurement when it is performed on an infant.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/5_segmod_HL.svg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Comparison of response magnitude estimate for noxious (heel lance) and non-noxious (tactile) stimuli, once the estimate has been improved using these methods. Left: Box-and-whisker plot comparing estimated response magnitudes for noxious heel lances, noxious experimental stimuli and non-noxious tactile controls. t=5.21 (heel lance to tactile). Right: ROC curve differentiating noxious heel lance from tactile control. AUROC=0.71. This is improved compared to an unmodified response magnitude estimate (t=3.93, AUROC=0.67).
</div>

## How does this help?

A patent application has been filed for these methods with the UK Patent Office, and the project is supported by Oxford University Innovation in order to produce a viable product. In the future it may give clinicians a quantitative, cotside measurement of an infant's pain, and so allow targeted interventions where needed.
