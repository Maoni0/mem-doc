# mem-doc
Over the years I've worked with a lot of customers to help them with analyzing GC heap related performance issues. Even though perf issues can and often vary a lot from one to the next, there's enough similarities that I thought it’s worthwhile to write a guideline document to either get folks started on the right path to be efficient at doing .NET memory performance analysis, or give those who are already quite experienced in perf more knowledge and tools to make their jobs easier.

This document includes the following material –

+ How to think about performance work and how to pick the right approaches for memory analysis;
+ Enough memory fundamentals to help you assess the memory issues;
+ Know when to worry about memory issues and how to analyze them with the right tools;

It's a long document so there’s a specific “how to read this document” section to help folks avoid sections that they might already be familiar with. One of my goals is to include material that’s not easy to find elsewhere so I didn’t spend a lot of content on things that you can find quitely easily on your own (eg, if you don’t know what ETW is there’s MSDN documentation and plenty of blogs that talk about it).

As we have more and better tooling I will continue updating this document. But another goal of sharing this document is to have contributors who would like to share their tips and tricks for memory analysis that don’t already exist in this doc. Your contributions are greatly appreciated. 

Thank you and I hope you find this document helpful.

