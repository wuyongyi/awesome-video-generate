# awesome-video-generate
A curated list of awesome Video generate resources and projects

## manim：

用于数学类的教学小视频生成，基于python3, 注意：在mac、linux上安装有个小坑，需要apt-get安装libcairo2

传送门：https://github.com/3b1b/manim

## video-automation

根据.yaml文件中的一些数据和模板生成一系列视频。文件呈现为MP4文件(使用ffmpeg)。主要目标是减少录制会议视频的后期制作成本。

传送门：https://github.com/abourget/video-automation

## videogan

一个使用场景动态生成很短视频的实现，Carl Vondrick, Hamed Pirsiavash, Antonio Torralba, at NIPS 2016. 

传送门：https://github.com/cvondrick/videogan

## dvd-gan
DeepMind 提出的模型叫作 Dual Video Discriminator GAN (DVD-GAN)，可以利用计算高效的判别器分解，扩展到时间更长、分辨率更高的视频。该研究建立在biggan之上，是迈向逼真视频生成的一次探索， Ian Goodfellow 也转推了这篇论文。

论文名称：Efficient Video Generation on Complex Datasets
论文地址：https://arxiv.org/pdf/1907.06571.pdf

## Phenaki
Phenaki是一个能够在给定一系列文本提示的情况下进行逼真的视频合成的模型。由于计算成本、高质量的文本视频数据数量有限以及视频长度可变，从文本生成视频尤其具有挑战性。为了解决这些问题，我们引入了一个新的学习视频表示因果模型，该模型将视频压缩为离散令牌的小表示。这个令牌器在时间上使用因果注意力，这允许它与可变长度的视频一起工作。为了从文本中生成视频令牌，我们使用以预计算文本令牌为条件的双向屏蔽变压器。生成的视频令牌随后被去令牌化以创建实际视频。为了解决数据问题，我们演示了对大型图像文本对语料库以及少量视频文本示例的联合培训如何导致超出视频数据集中可用的泛化。与之前的视频生成方法相比，Phenaki可以在开放域中根据一系列提示（即时间变量文本或故事）生成任意长视频。据我们所知，这是论文研究首次从时间变量提示生成视频。此外，在时空质量和每个视频的令牌数量方面，拟议的视频编码器解码器的性能优于文献中目前使用的所有每帧基线。

传送门：https://phenaki.github.io
开源代码：tbd



