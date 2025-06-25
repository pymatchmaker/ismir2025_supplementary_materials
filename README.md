# Supplementary Materials for "A Systematic Evaluation of Real-Time Audio Score Following for Piano Performance"

## Abstract

Real-time music alignment, also known as **score following**, is a fundamental MIR task with a long history and is essential for many interactive applications. Despite its importance, there has not been a unified open framework for comparing models, largely due to the inherent complexity of real-time processing and the language- or system-dependent implementations. In addition, low compatibility with the existing MIR environment has made it difficult to develop benchmarks using large datasets available in recent years. While new studies based on established methods (e.g., dynamic programming, probabilistic models) have emerged, most evaluations compare models only within the same family or on small sets of test data. This paper introduces an open-source Python library for real-time music alignment that is easy to use and compatible with modern MIR libraries. Using this, we systematically compare methods along two dimensions: music representations and alignment methods. We evaluated our approach on a large test set of solo piano music from the ASAP, Batik, and Vienna4x22 datasets with a comprehensive set of metrics to ensure robust assessment. Our work aims to establish a benchmark framework for score-following research while providing a practical tool that developers can easily integrate into their applications.

## Supplementary Materials

* [Technical appendix](./technical_appendix.pdf)
* [An audio comparison of the different score followers](./comparison_examples.html)



## Demos

### Visualization

The following videos showcase the real-time visualization described in Section 8 in the paper.

* J. S. Bach: Fugue BWV 858 (performance from ASAP dataset). Score Follower `OLTWDixon`
<video width="640" height="360" controls>
  <source src="https://raw.githubusercontent.com/anonymous-conference-submission/sfismk2831/main/videos/Fugue_bwv_858_VuV01M_dixon.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

* J. S. Bach: Fugue BWV 858 (performance from ASAP dataset). Score Follower `OLTWArzt`
<video width="640" height="360" controls>
  <source src="https://raw.githubusercontent.com/anonymous-conference-submission/sfismk2831/main/videos/Fugue_bwv_858_VuV01M_arzt.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

* J. S. Bach: Fugue BWV 858 (performance from ASAP dataset). Score Follower `HMM`
<video width="640" height="360" controls>
  <source src="https://raw.githubusercontent.com/anonymous-conference-submission/sfismk2831/main/videos/Fugue_bwv_858_VuV01M_hmm.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>


### Real-time Demos

The following videos showcase score following for a live piano performance.


* Manuel Ponce: Gavota. Score Follower `OnlineTimeWarpingArzt`.
<video width="640" height="360" controls>
  <source src="https://raw.githubusercontent.com/anonymous-conference-submission/sfismk2831/main/videos/gavota_arzt_blurred_small.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

* Manuel Ponce: Gavota. Score Follower `OnlineTimeWarpingDixon`.
<video width="640" height="360" controls>
  <source src="https://raw.githubusercontent.com/anonymous-conference-submission/sfismk2831/main/videos/gavota_dixon_blurred_small.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

* Schumann: Symphonic Etudes Op. 13 Appendix Variation V. Score Follower `OnlineTimeWarpingArzt`.
<video width="640" height="360" controls>
  <source src="https://raw.githubusercontent.com/anonymous-conference-submission/sfismk2831/main/videos/schumann_demo_blurred_small.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
