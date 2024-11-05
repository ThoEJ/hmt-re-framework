Checklists/Questions for Phase 1
================================

Activity 1.2 &ndash; Questions to help with the identification of behavior bundles and communication flows based on use case context as candidates for subjects and message exchanges:

| Identification of Behavior Bundles, Communication Flows, and Human/Machine Agents |
| -------- | 
| What activities are generally needed to accomplish the use case? | 
| Considering existing systems that should be replaced, what activities did they perform? | 
| Considering other systems that the CPS should interact with, what activities do/should they perform? | 
| Considering the previously identified stakeholders, what activities do/should they perform? |
| Which functionalities/features could the CPS provide and which corresponding activities are necessary? |
| How could relevant activities be organized to form distinct bundles of thematically related behavior needed to accomplish the use case? |
| What types information/physical resources are needed to provide these behavior bundles? |
| What types information/physical resources need to be exchanged between different behavior bundles? |
| What kind of physical/digital components could the CPS be composed of? |

Activity 1.4 &ndash; Questions to guide the refinement of subject-oriented models, while determining different automation level and task allocation possibilities, as well as model validation:

| Iterative Model Refinement \& HMT Considerations &ndash; Automation Level, Task Allocation |
| -------- | 
| Considering each subject in a SID to be refined, should the subject behavior in the future be assigned to a machine agent (CPS component, other system) or a human agent (CPS stakeholder identified previously)? |
| What would the respective advantages and disadvantages of using a human or machine agent for this subject behavior be? |
| Could the subject behavior be assigned to multiple agents for collaborative execution (i.e., part of the behavior is done by a human agent and the other part by a machine agent)? *(If yes, then break it down into multiple subjects that interact through message exchanges)* |
| Are multiple alternative subject behavior assignment possibilities of potential interest? (i.e., subject behavior could be done by either a human or a machine agent)? *(If yes, then create multiple model variants)* |
| Considering each subject in the SID, which tasks need to be carried out as part of this behavior? |
| What is the required temporal/causal order of these tasks? |
| Can these tasks be arranged in a single sequence without any parallel paths? *(If yes, then the SBD can be defined; If no, then the parallel paths have to become their own subjects)* |

| Model Validation |
| -------- | 
| Can all possible paths in the process models be traversed to their respective, specified end states during execution? |
| Does the flow of states arising from the execution of the models correspond to what was envisioned by the design session participants during modeling? |
| Are any critical steps in the behavior missing? |
| Are there any superfluous steps in the behavior that can potentially be cut? |
