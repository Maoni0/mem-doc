<div align="center">
    <strong><a href="README.md">English</a> | <a href="README.zh-CN.md">简体中文</a></strong>
</div>

# mem-doc
Over the years I've worked with a lot of customers to help them with analyzing GC heap related performance issues. Even though perf issues can and often vary a lot from one to the next, there's enough similarities that I thought it’s worthwhile to write a guideline document to either get folks started on the right path to be efficient at doing .NET memory performance analysis, or give those who are already quite experienced in perf more knowledge and tools to make their jobs easier.

The [.NET Memory Analysis document in this repo](./doc/.NETMemoryPerformanceAnalysis.md) includes the following –

+ How to think about performance work and how to pick the right approaches for memory analysis;
+ Enough memory fundamentals to help you assess the memory issues;
+ Know when to worry about memory issues and how to analyze them with the right tools;

It's a long document so there’s a specific “how to read this document” section to help folks avoid sections that they might already be familiar with. One of my goals is to include material that’s not easy to find elsewhere so I didn’t spend a lot of content on things that you can find quite easily on your own (eg, if you don’t know what ETW is there’s MSDN documentation and plenty of blogs that talk about it).

As we have more and better tooling I will continue updating this document. But another goal of sharing this document is to have contributors who would like to share their tips and tricks for memory analysis that don’t already exist in this doc. Your contributions are greatly appreciated. 

I also included slide decks and video recording links of talks I've done in this repo. In general when I do talks I tend to also talk about things that aren't easily found elsewhere. Currently the following talks are included -

2021 Internal talk - "A .NET Object - from allocation to collection" (talks about how memory for a .NET object is acquired all the way down to the hardware layer. Since I'm toughing many memory related things - the hardware, the OS and the GC - I had to stay very high level): [slides](./presentation/ObjectJourney.pptx)

2020 dotnext talk - "What's new in the .NET 5.0 GC" (short high level talk on new features in 5.0): [slides](./presentation/dotnext2020-new-in-5-GC.pptx)

2020 dotnetos talk - "What's so hard about pinning" (in-depth talk on how pinning is handled): [slides](./presentation/dotnetos2020-Pinning.pptx), [video](https://www.youtube.com/watch?v=troNdmHEu2g)

2019 Prague meetup talk - "What's new in the .NET Core 3.0 GC" (fairly detailed talk on new features in 3.0): [slides](./presentation/PragueMeetup2019.pptx), [video](https://www.youtube.com/watch?v=m4fddMZDceQ)

Thank you and I hope you find this material helpful.

