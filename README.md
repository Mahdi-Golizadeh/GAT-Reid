In this paper we introduce an attention module called efficient gated channel-spatial attention (EGCSA) to address these challenges. EGCSA consists of two submodules: efficient channel-wise attention (ECAt) and efficient spatial attention (ESAt). ECAt focuses on interactions at the channel level within feature maps by generating attention weights through convolutional layers. ESAt operates at the spatial level to capture relevant information across different spatial locations. These submodules produce attention weights. A multi-stage gate mechanism selects efficient features from the generated ones in previous step, enabling the network to learn robust and discriminative features. The proposed module is integrated into the backbone network after multiple layers.
