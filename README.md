# **这是我的第一篇sci论文以及对应的代码**<br>

# A Credit Card Fraud Model Prediction Method Based on Penalty Factor Optimization AWTadaboost
**摘要**：随着网络支付的普及，信用卡盗刷，误刷的现象也越来越严重，因此近年来在信用卡欺诈检测问题中搭建一个轻便且行之有效的模型一直是个活跃的研究课题。而为了解决信用卡欺诈检测中模型训练时间和分类准确性之间的不平衡问题，本文提出了一种改进的算法（PF_AWTadaboost），以增强对噪声样本的辨别能力。首先，通过理论分析指出传统的adaboost在有噪声的情况下会出现过拟合情况导致分类精度的下降，为此引入惩罚因子来重构样本权重分配方式以避免权重过于集中在少数几个分类器中，并论证其合理性。然后，通过比较本文提出的三种不同惩罚函数的惩罚力度，选择了一个更合理的惩罚函数。 然而在adaboost基础上进行改进的AWTadaboost算法并未解决这一问题，因此将已选择的惩罚函数重新引入到AWTadaboost之中，再通过公式推导证明其算法仍然收敛，最终将其应用于信用卡欺诈检测中。最后在信用卡欺诈数据集和其他数据集上与其他传统机器学习算法进行实验对比验证，结果表明，在信用卡欺诈数据集上，PF_AWTadaboost方法比较其他方法有更好的表现，包括检测精度，模型的召回率和鲁棒性，而在其他数据集上，PF_AWTadaboost方法表现出优秀的泛化性能，尤其在AUC值上有明显优势。因此，与传统算法相比，PF_AWTadaboost算法具有更好的分类性能 <br><br><br>


* artice<br>
西瓜书和花书<br>
* train<br>
论文所用到的各算法源码，以及训练集<br><br><br>


**联系方式：QQ。2415035764**




