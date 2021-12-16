<div align="center">
<strong><a href="README.md">English</a> | <a href="README.zh-CN.md">简体中文</a></strong>
</div>

# mem-doc
多年来，我与很多客户合作，帮助他们分析GC堆相关的性能问题。尽管性能问题经常有很大的不同，但有足够多的相似之处，我认为值得写一份指导性的文件，让人们在正确的道路上开始有效地进行.NET内存性能分析，或者给那些在性能方面已经有相当经验的人提供更多的知识和工具，使他们的工作更容易。

本仓库中的[.NET内存分析文档](./doc/.NETMemoryPerformanceAnalysis.zh-CN.md)包括以下内容-

+ 如何思考性能工作，如何挑选正确的方法进行内存分析。
+ 足够的内存基础知识，帮助你评估内存问题。
+ 知道什么时候该担心内存问题，以及如何用正确的工具来分析它们。

这是一份很长的文件，所以有一个专门的 "如何阅读本文件 "部分，以帮助人们避开他们可能已经熟悉的部分。我的目标之一是包括那些不容易在其他地方找到的材料，所以我没有把大量的内容花在你自己可以很容易找到的东西上（例如，如果你不知道ETW是什么，有MSDN文档和大量的博客来讨论它）。

随着我们拥有更多更好的工具，我将继续更新这个文档。但分享这个文档的另一个目的是希望有贡献者分享他们在内存分析方面的技巧和窍门，而这些技巧和窍门在这个文档中并不存在。我们非常感谢您的贡献。

我还把我做过的演讲的幻灯片和视频录制链接放在这个 repo 中。一般来说，当我做演讲时，我倾向于谈论那些不容易在其他地方找到的东西。目前包括以下演讲 -

2022年内部演讲 - "诊断内存泄漏" [幻灯片](https://github.com/Maoni0/mem-doc/blob/master/presentation/MemoryLeakDiag.pptx)([pdf](https://github.com/Maoni0/mem-doc/blob/master/presentation/MemoryLeakDiag.pdf))，[video](https://www.youtube.com/watch?v=ImeiUzbdMzc)

2021年内部演讲 - "一个.NET对象 - 从分配到收集"（讲述了一个.NET对象的内存是如何获得的，一直到硬件层。由于我正在处理许多与内存有关的事情 - 硬件、操作系统和GC - 我必须保持非常高的水平）。[幻灯片](./presentation/ObjectJourney.pptx)([pdf](https://github.com/Maoni0/mem-doc/blob/master/presentation/ObjectJourney.pdf))， [video](https://www.youtube.com/watch?v=1Qmvme70w9c)

2020年dotnext演讲 - ".NET 5.0 GC的新特性"（关于5.0新特性的简短概览性的演讲）。[幻灯片](./presentation/dotnext2020-new-in-5-GC.pptx) ([pdf](https://github.com/Maoni0/mem-doc/blob/master/presentation/dotnext2020-new-in-5-GC.pdf))

2020年dotnetos演讲 - "Pinning有什么难的"（关于如何处理Pinning的深入演讲）。[幻灯片](./presentation/dotnetos2020-Pinning.pptx)([pdf](https://github.com/Maoni0/mem-doc/blob/master/presentation/dotnetos2020-Pinning.pdf))，[视频](https://www.youtube.com/watch?v=troNdmHEu2g)

2019年Prague meetup演讲 - ".NET Core 3.0 GC中的新内容"（关于3.0中新功能的相当详细的演讲）。[幻灯片](./presentation/PragueMeetup2019.pptx)([pdf](https://github.com/Maoni0/mem-doc/blob/master/presentation/PragueMeetup2019.pdf))，[视频](https://www.youtube.com/watch?v=m4fddMZDceQ)

谢谢你，我希望这些材料对你有帮助。