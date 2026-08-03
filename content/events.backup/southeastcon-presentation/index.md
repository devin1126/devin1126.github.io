---
title: "Neural Process-based Reactive Controller for Autonomous Racing"
event: "IEEE SoutheastCon 2026"
date: 2026-03-05

summary: >
  Conference presentation on a novel architecture, PI-AttNP, applied for end-to-end, reactive-based autonomous racing in a simulated F1Tenth racing environment.
featured: true
---
This presentation introduces a neural process-based reactive control framework for autonomous racing using an Attentive Neural Process (AttNP) and a physics-informed extension, the PI-AttNP. The proposed approach learns a Follow-The-Gap (FTG) navigation policy directly from LiDAR and vehicle dynamics data while incorporating an approximate FTG-derived control prior to improve convergence, prediction accuracy, and generalization in high-speed racing environments.

Experimental validation was performed in a simulated F1TENTH Ackermann steering racing environment, demonstrating improved control prediction performance and reduced collision frequency relative to AttNP and residual MLP baselines. The framework additionally incorporates a Control Barrier Function (CBF)-based safety filter that provides real-time collision avoidance guarantees while maintaining competitive lap completion performance.

<iframe
  src="https://drive.google.com/file/d/1T35U8MIq75fXG8MhfEymr2KyGmLGpZQg/preview"
  width="100%"
  height="600"
  allow="autoplay"
  allowfullscreen>
</iframe>