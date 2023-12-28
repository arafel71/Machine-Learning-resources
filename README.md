Image segmentation :
-------------------
YOLOV8
underwater trashcan
https://learnopencv.com/train-yolov8-instance-segmentation/


Ultralytics YOLO V8 python training guide :
https://docs.ultralytics.com/modes/train/#usage-examples

Ultralytics YOLO V8 python segmentation guide :
https://docs.ultralytics.com/tasks/segment/#models

Ultralytics YOLO dataset guide :
https://docs.ultralytics.com/datasets/segment/#coco-dataset-format-to-yolo-format


Ultralytics real world project :
https://docs.ultralytics.com/guides/#real-world-projects

Ultralytics YOLO with DOCKER :
https://docs.ultralytics.com/guides/docker-quickstart/


YOLO object isolation after segmentation:
https://docs.ultralytics.com/guides/isolating-segmentation-objects/#isolate-with-transparent-pixels-sub-options

Youtube Binary mask custom segmentation
https://www.youtube.com/watch?v=udR6SwojYXo


segmentation image (french):
-----------------------------
https://www.imaios.com/fr/ressources/blog/annotations-des-images-medicales-pour-l-apprentissage-deep-learning

carie dentaire :
https://github.com/Momotoculteur/Tooth-decay-semantic-segmentation
https://deeplylearning.fr/cours-pratiques-deep-learning/segmentation-semantique-dimages/

https://www.imaios.com/fr/ressources/blog/annotations-des-images-medicales-pour-l-apprentissage-deep-learning
les types d'annotation : masque binaire, bounding box, carte de saillance, points de repère (en anglais, landmarks), 
Quelles architectures utilisent les annotations ?
Les architectures à propositions de régions de pixels (en anglais, Region Proposal networks - RPN), telles que Faster R-CNN et Mask R-CNN, utilisent des annotations permettant de réduire le nombre de propositions de régions par le réseau. Les annotations telles que les boîtes englobantes, les masques binaires, les points de repère et les cartes de saillance y contribuent, c’est pourquoi elles sont adaptées à ce type d’algorithmes. Ces annotations peuvent également être combinées pour faciliter davantage la convergence du réseau, comme avec Mask R-CNN combinant boîtes englobantes et masques binaires.

Les architectures à étape unique (en anglais, one-stage methods), comme YOLO et SDD, privilégieront les annotations de type boîtes englobantes et masques binaires.

Les architectures basées sur les cartes de saillances utilisent bien sûr les annotations du type du même nom. Elles peuvent également utiliser les annotations de types boîtes englobantes, masques binaires et points de repère, lors des approches dites “descendante” pour limiter les régions d’analyse de l’image qui seront par la suite analysées par un réseau de neurones convolutionnel (e.g. U-Net) pour terminer la tâche de segmentation.


segment everything:
https://larevueia.fr/comment-faire-de-la-segmentation-dimages-avec-python/

Dataset:
------------

Underwater TrashCan 1.0
https://conservancy.umn.edu/handle/11299/214865
