# OpenWorld-Recognition-in-Image-Classification
Implementation of fine-tuning, Learning Without Forgetting and iCaRL framework for image classification in open world recognition task

The proposed work is meant as an exploration of incremental learning techniques. We start from the implementation of three baselines: fine-tuning, Learning Without Forgetting, iCaRL framework. Furthermore, different ablation studies are carried, analysing variations in losses and classifiers.
We then tested models able to reject samples, labelling them as unknown class: this scenario is tested in both open and closed world, with and without the rejection capability. In the last part a modification in the nearestmean- of-exemplars classifier is proposed, accounting for the different spreads of the classes in the feature space.
