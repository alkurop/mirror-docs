# Scientific interest

The Mirror's work falls into category of a general purpose continuous learning AI.
The process of storing poses for a vast period of time and generating complex sets of events is similar to putting a robot in a garden with ability to walk, jump, run in any direction, even hit a ball, but not telling it what exactly must done, or what is expected in terms of a goal, but necessarily  should be done something. 
Occasionally I look through articles on AI development. My particular interest is to the topic of general purpose AI.
There are some commonly discussed problems on the subject.

1. One problem is lack of continuous training data. 

Most of these machines would be trained of pre-recorded videos, that by definition are of limited amount. Training machines on surveillance cameras however and beyond ethical and legal boundaries for most researches in the field. Mirror machine will have a continuous access to new data, but with permission of those who interact with it.

2. Memory layers

The predicted poses will then be process by a non-high-precision analog of a [Giat](https://arxiv.org/pdf/2303.05234.pdf) system to identify subjects.
A challenging but interesting task is to explore how Mirror consumes and stores the decoded input.
A planned end product machine must be able to recognise general mood of the audience, the context. In an unlimited timeframe, two similar machines set up in different spots will continue to deviate and become unlike to one another. 
But storing infinite amount of data in an uncompress mode will result in running out of storage memory. This fact brings me to necessity of splitting its memory into layers.
1. Short term pattern memory - up to 10 seconds
2. Medium term session memory - up to 30 minutes
3. Long term history / personality memory - always

How does the acquired memory translate from long term to medium term, and further into long term, thus implementing the mechanism of forgetting?
I propose to introduce a mechanism of "stress", or "stressful event" - a set of events that strongly deviate from a common patter, and therefore become valid to jump over the memory threshold into a long term memory. 
The longer machine exists, the higher the stress threshold becomes, so in fact machine will only be interested in new events, that don't follow the common pattern.

Each of the memory layers will result in deviation of the machine's musical output.







