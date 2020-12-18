# cheatsheet
cheatsheet code

Disable tensorflow GPU:
import os
os.environ["CUDA_VISIBLE_DEVICES"] = "-1"

Show username and GPU usage in commands:
ps -up `nvidia-smi |tee /dev/stderr |tail -n +16 | head -n -1 | sed 's/\s\s*/ /g' | cut -d' ' -f3`
or 
nvidia-smi

# Cartoon Face Recognition Related Data and Paper
Image dataset zoo
https://github.com/deepinsight/insightface/wiki/Dataset-Zoo

The IIIT-CFW dataset
https://cvit.iiit.ac.in/research/projects/cvit-projects/cartoonfaces

Simposons character data
https://www.kaggle.com/alexattia/the-simpsons-characters-dataset

Danbooru Dataset Information
https://www.gwern.net/Danbooru2019#possible-uses

Subset of Dabnboru
https://www.kaggle.com/mylesoneill/tagged-anime-illustrations/kernels
https://www.kaggle.com/alamson/safebooru

Anime Face Dataset
https://github.com/bchao1/Anime-Face-Dataset

lbpcascade_animeface
https://github.com/nagadomi/lbpcascade_animeface

iCartoon Dataset -- iQiyi
http://challenge.ai.iqiyi.com/detail?raceId=5def71b4e9fcf68aef76a75e

# Paper

DeepLearningAnimePapers
https://github.com/deeppomf/DeepLearningAnimePapers#anime-papers

Cartoon Face Recognition: A Benchmark Dataset
https://arxiv.org/pdf/1907.13394.pdf

iCartoonFace: A Benchmark of Cartoon Person Recognition
https://www.arxiv-vanity.com/papers/1907.13394/ 

Simpson characters detection - Keras CNN - Acc 97%
https://www.dsimb.inserm.fr/~ghouzam/personal_projects/Simpson_character_recognition.html

A Multi-Label Convolutional Neural Network for Automatic Image Annotation
https://www.jstage.jst.go.jp/article/ipsjjip/23/6/23_767/_article 

Bringing Cartoons to Life: Towards Improved Cartoon Face Detection and Recognition Systems
https://arxiv.org/abs/1804.01753

Simpsons face recognition
https://medium.com/alex-attia-blog/the-simpsons-character-recognition-using-keras-d8e1796eae36

Cartoon Sentiment
https://www.gwern.net/docs/www/pdfs.semanticscholar.org/b965e51a588e85ee112ed61ff4aab12cc5d586b0.pdf

Illustration2Vec: A Semantic Vector Representation of Illustrations
https://www.gwern.net/docs/anime/2015-saito.pdf

# Tools
pixiv crawler
https://pypi.org/project/pixiv-crawler/



# Non-Cartoon related multilabel dataset 

The PASCAL Visual Object Classes Challenge 2007
http://host.robots.ox.ac.uk/pascal/VOC/voc2007/index.html



# Interview/OA questions
Will Cross Validation overfit?
https://stats.stackexchange.com/questions/416553/can-k-fold-cross-validation-cause-overfitting
https://stats.stackexchange.com/questions/9053/how-does-cross-validation-overcome-the-overfitting-problem

Handling Missing Values
https://analyticsindiamag.com/5-ways-handle-missing-values-machine-learning-datasets/

Undrstand if name==main
https://medium.com/python-features/understanding-if-name-main-in-python-a37a3d4ab0c3


# DS Related Positions Info
https://github.com/pittcsc/NewGrad-2021
https://github.com/jxucoder/2021-new-grads

# Algorithm DP
https://zhuanlan.zhihu.com/p/91582909



