# Abstract
Deep learning techniques have become popular in land cover change detection (LCCD) with remote sensing images(RSIs). However, many existing networks mostly concentrate on learning deep features but without considering the effect of different features’ attention and fusion strategy on detection performance. In this paper, a novel hierarchical attention feature fusion (HAFF)-based network for LCCD with RSIs is proposed. In the proposed HAFF-based network, novel multi-scale convolution fusion filters (MCFFs) explore the global semantic feature of the interested targets from multi-perspectives ways. To achieve that objective, the proposed MCFFs are composed by a well-known position attention module and a novel multi-perspectives feature filter block with different kernel sizes. In addition, a compound loss function was proposed for balancing the impact from the features at different levels in terms of backpropagation error. Lastly, experiments conducted on six pairs of real RSIs, including three pairs of homogeneous images and three pairs of heterogeneous images, confirmed the superiority of the proposed NHFA over other state-of-the-art methods.
# HAFF
HAFF aims to learn and predict change maps in bi-temporal remote sensing images.
# Requirements
Python 3.6
Pytorch 1.2.0
# Q & A
For any questions, please contact  liu-jie00002023@outlook.com，Lvzhiyong_fly@hotmail.com.
