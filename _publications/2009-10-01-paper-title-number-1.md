---
title: "Enhancing face recognition via additional facial attributes"
collection: publications
category: manuscripts
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: ''
date: 2026-05-29
venue: 'Multimedia Systems'
# slidesurl: 'https://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://link.springer.com/article/10.1007/s00530-026-02386-8'
# bibtexurl: 'https://academicpages.github.io/files/bibtex1.bib'
citation: 'Shin, J., Kim, M. & Park, S. Enhancing face recognition via additional facial attributes. Multimedia Systems 32, 320 (2026). https://doi.org/10.1007/s00530-026-02386-8'
---
Recent advancements in deep learning have significantly enhanced face recognition technology. However, its performance degrades considerably in real-world environments where subject identification is challenging due to factors like occlusion, poor illumination, and non-frontal poses. To address these limitations, this paper proposes a practical and model-agnostic method that improves face recognition by utilizing some facial attributes as auxiliary semantic information. Our approach combines the conventional facial similarity score obtained from the DeepFace framework with an additional attribute score calculated from five auxiliary facial attributes. The core of our proposed model lies in a final similarity calculation that differentially assigns weights based on temporal stability and confidence in the detected attributes. Using a weighted sum controlled by an arbitrary weight, α, our method dynamically adjusts the contributions to the final score for visual similarity and attribute consistency. Experiments conducted on a challenging dataset constructed from six different films demonstrate that the proposed method achieves significant performance improvements, enhancing Rank-1 accuracy by an average of 10.69% above the baseline, and by up to 36.25% in specific cases. Furthermore, an ablation study confirms that even though temporal attributes do not always increase the absolute number of correct matches, they enhance the model’s stability by broadening the range of alpha values that yield improved performance. This research substantiates that integrating semantic attribute information is an effective strategy for building more robust and reliable face recognition systems for real-world applications.