# 基于卷积神经网络的绝缘子检测与识别
对绝缘子故障的例行巡检对于保障电网输电线路的安全运行十分必要。本文把无人机航拍技
术引入到日常的输电线路巡检工作中，提出了一种基于无人机航拍图像的输电线路中绝缘子的识别与
状态检测方法，可以提高输电线路巡检信息处理的实时性。绝缘子检测算法的设计是决定无人机航拍
绝缘子巡检系统的有效性的关键环节。本文首先通过选择性搜索算法对绝缘子图片进行目标建议，提
出采用卷积神经网络(CNN)进行自动特征提取结合 softmax 分类器的方法对输电线路绝缘子图片进行
绝缘子检测。其采用自制的绝缘子样本库对卷积神经网络进行了训练，并将该种方法与传统的特征提
取加分类器，以及采用 PCA 特征降维结合全连接神经网络的方法进行了比较。实验结果表明：采用
卷积神经网络的绝缘子特征提取取得了最好的绝缘子识别率，对于复杂的背景具有良好的鲁棒性。克
服了传统图像处理和传统神经网络识别方法受拍摄角度，光线照，影响的缺陷，实现了绝缘子的 86%
以上的高检测率。针对绝缘子图片中通常含有复杂背景的特点，本文在绝缘子被成功提取的基础上提
出采用已训练好的 CNN 网络通过反卷积运算来重构图片中的绝缘子信息并滤除复杂的背景信息。随
后进行超像素分割并建立绝缘子数学模型，最终实现了绝缘子串缺陷部位的精准识别。本系统为输电
线路无人机巡视中的人工智能巡视提供了借鉴。 
关键词：绝缘子；选择性搜索；分类器；神经网络；卷积神经网络；自爆缺失 
