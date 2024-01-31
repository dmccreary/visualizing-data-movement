# About the Visualizing Data Movement Project

Let's face it.  Static architectural diagrams suck.

To be specific:

1. The often don't explain what is happening in a system.
2. They don't help users understand where bottlenecks occur in systems.
3. They don't show us where single-point-of-failures occur.
4. They are not good at helping us understand architectural tradeoffs.

In short, we can do better.  Much better!

It used to cost considerable time and effort to build
simulations of working systems that show how data flows through architectures.  But with the rise of low-cost generative AI systems, this is all starting to change.  Now, even teachers are building simulations customized to each lesson, each group and each student.

Our goal in this project is to build a foundation of architecture simulations that span many levels of abstraction.  At the bottom of these abstractions are digital logic gates.  At the top level, we have complete applications.  And there are many layers in between.

We have used generative AI, specifically OpenAI's ChatGPT and GPT-4 to generate the first pass at many of these simulations.  We have then manually adjusted the simulations to make them correct, consistent and reusable.  You should be able to use generative AI to
quickly customize them for new tasks.

Speaking of reuse, all of the content on this site is
licensed under [Creative Commons](license.md).  This means you can use the simulations in your classrooms without charge, but you can't resell these programs for profit.  We hope you give this site the appropriate attribution.

## Acknowledgments

We are indebted to many open-source developers who helped build the foundations upon which these simulations are created.

We especially want to acknowledge the work that the [Processing Foundation](https://processingfoundation.org/) has
done to create the p5.js JavaScript libraries and tools that these systems are created with.

We also want to acknowledge the work that [Code Savvy](https://www.codesavvy.org/) has done promoting [MicroSims](https://dmccreary.github.io/microsims/).  Many of the visualizations on this site are inspired by their early work.

