# 虚拟数据集动作生成

该部分旨在为基于对抗生成网络（GAN）的跨视角动作序列生成模型提供更丰富的数据集。采集一些游戏(例如GTAV)内的虚拟数据集(即视频)，赋予视频中的人物新的动作序列，以达到生成新数据集的做法。

目前我们选用的工具为apple公司开发的ml-neuman。该项目利用nerf技术将视频中的背景和人物分离，赋予人物新的动作序列后和背景组合重新渲染出新的视频。

## 以下是使用探索的结果以及结论：

### 之前的工作：

对现实场景的训练后赋予新动作序列




https://user-images.githubusercontent.com/56157591/221800815-8ca89423-b127-4626-bd64-020a63946951.mp4



https://user-images.githubusercontent.com/56157591/221800862-1d54f139-e1d7-41a1-acab-92a918b9fab0.mp4



https://user-images.githubusercontent.com/56157591/221800883-fb8f515a-125d-494f-933f-04e741c1e059.mp4



https://user-images.githubusercontent.com/56157591/221800909-ce2c6362-7e04-40a3-b202-a80d034419e9.mp4

