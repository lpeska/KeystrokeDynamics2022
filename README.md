# TYVIZER: Visual Representations of Keyboard Typing Dynamics
Repository for the paper "Person Authentication using Visual Representations of Keyboard Typing Dynamics" published in DSEA@SNAMS2022
- by: Ladislav Peska, Patrik Vesely, Tomas Skopal and Krisztian Buza
- contact: ladislav.peska@matfyz.cuni.cz

### Abstract:
In this paper, we focus on the problem of user’s
authentication through typing dynamics patterns. We specifically
focus on small-sized problems, where it is difficult to fully
train corresponding machine (deep) learning algorithms from
scratch. Instead, we propose a different approach based on the
visualization of the typing patterns and subsequent usage of pre-
trained feature extractors from the computer vision domain. We
evaluated the approach on a publicly-available dataset and results
indicate that this is a viable solution capable to improve over
several baselines. Moreover, the proposed visual representation
of the data contributes to the explainability of AI.

### Instructions:
In order to construct visualizations of individual keystroke series, please consult the "visualizations" folder. In order to generate feature embeddings from visualizations, please consult "embeddings" folder. For running the evaluation pipeline, including class label predictions, consult the "evaluation" folder.
- for more info on utilized dataset, please refer to http://www.biointelligence.hu/typing-challenge/task2/index.php
