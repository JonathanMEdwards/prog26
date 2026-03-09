We thank the reviewers for their effort and comments. The chair identified the need for four major revisions:

1. Add evidence beyond single examples for the 4 problems addressed by the work.
2. Add a systematic discussion of what is necessary to support further operations, and what the limitations are.
3. Provide a deeper explanation of the conclusions from previous study.
4. Provide more details of the evaluation with a discussion.

In response to points 1, 3, & 4 we have substantially restructured and expanded the evaluation aspects of the paper. Before there was an Evaluation section that tabulated the eight challenge problems identified in our prior paper (Schema Evolution in Interactive Programming Systems), assigning a Pass/Fail grade to each. Now we have distributed discussion of case studies throughout the paper that include more nuanced evaluations. These case studies include the four challenge problems that were deemed to have been solved and also additional cases taken from the research literature.  A combined Evaluation and Discussion section now discusses the cases of the four failed challenge problems. The extended evaluation makes it possible to understand what is currently implemented in Baseline, what is conceptually compatible with our approach, as well as what problems are incompatible with our methods.

The new discussion section also addresses the "elephant in the room" identified in point 2 above: the worrying complexity and incompleteness of the set of operations. We are forced to admit that this fact indicates our work is still preliminary and we propose future work generalizing the data model in order to distill fewer primitive operations. We hope that we have already demonstrated sufficiently valuable and novel benefits to warrant sharing them with the research community.

In response to reviewer B we have moved the Related Work section to the conventional location before the Conclusion. In response to Reviewer A we have added discussions of the benefits of our approach over CRDTs and lenses, which are the most popular competitive approaches. Specifically: CRDTs are unidirectional, and lenses are first-order. We also respond to Reviewer A's question about replication by clarifying that our approach would require a centralized primary whose order of operations decides conflict resolution for everyone consistently.

We have submitted a latexdiff showing all our changes, but it may be hard to read due to the extent of the changes and the inherent limitations of state-based diffing (ahem).

We believe these changes have made the paper more accessible and useful to the research community.

Regards,
Jonathan Edwards
Tomas Petricek