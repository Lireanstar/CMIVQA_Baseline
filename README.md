# CMIVQA Baseline 🌟


欢迎来到我们的CMIVQA比赛基线代码仓库！在这里，你将找到用于解决Track 1，Track 2 和Track 3任务的基线代码。下面是仓库的内容概述和如何使用基线代码进行训练和测试的说明。
每个子项目都包含两个主要部分：环境安装和快速开始。请确保按照下面的说明正确配置环境，并使用我们提供的示例代码进行训练和测试。祝你好运！😃

### CMIVQA Track 1 Baseline
这个任务是关于视频语料库视觉答案定位（VCVAL），目标是从给定的单个医疗教学视频中使用自然语言问题定位视觉答案。为了解决这个问题，我们提出了一种新的跨模态相互知识转移跨度定位（MutualSL）来解决跨模态知识偏差。

详细的方法描述和实现可以在子目录的README.md文件中找到。[点击此处查看子目录的README.md](https://github.com/WENGSYX/CMIVQA_Baseline/tree/main/task23)



### CMIVQA Track 2/3 Baseline
这个任务是关于视频视觉答案定位（VCVAL），目标是在大量未修剪，未分段的教学视频中使用自然语言问题定位视觉答案。为了解决这个问题，我们提出了一种跨模态对比全局跨度（CCGS）方法，联合训练视频语料库检索和视觉答案定位任务。

详细的方法描述和实现可以在子目录的README.md文件中找到。[点击此处查看子目录的README.md](https://github.com/WENGSYX/CMIVQA_Baseline/tree/main/task23)


### 如果您在研究中使用了我们的代码，请引用以下论文：
```
@article{weng2022visual,
  title={Visual Answer Localization with Cross-modal Mutual Knowledge Transfer},
  author={Weng, Yixuan and Li, Bin},
  journal={arXiv preprint arXiv:2210.14823},
  year={2022}
}

@article{li2022learning,
  title={Learning to Locate Visual Answer in Video Corpus Using Question},
  author={Li, Bin and Weng, Yixuan and Sun, Bin and Li, Shutao},
  journal={arXiv preprint arXiv:2210.05423},
  year={2022}
}
```
### 祝你在CMIVQA比赛中取得好成绩！🏆🎉
