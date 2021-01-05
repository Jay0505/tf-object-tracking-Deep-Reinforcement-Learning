# Action Decision Networks for Object tracking

Tensorflow Implementation of 'Action-Decision Networks for Visual Tracking with Deep Reinforcement Learning(CVPR 2017)'. This paper proposes a novel tracker which is controlled by sequentially pursuing actions learned by deep reinforce- ment learning. In contrast to the existing trackers using deep networks, the proposed tracker is designed to achieve a light computation as well as satisfactory tracking accu- racy in both location and scale. The deep network to con- trol actions is pre-trained using various training sequences and fine-tuned during tracking for online adaptation to target and background changes. The pre-training is done by utilizing deep reinforcement learning as well as super- vised learning. The use of reinforcement learning enables even partially labeled data to be successfully utilized for semi-supervised learning. 


References:

--- Action-Decision Networks for Visual Tracking with Deep Reinforcement Learning (CVPR201) : http://openaccess.thecvf.com/content_cvpr_2017/papers/Yun_Action-Decision_Networks_for_CVPR_2017_paper.pdf

--- ADNet Implmentation in Matlab : https://github.com/hellbell/ADNet/
