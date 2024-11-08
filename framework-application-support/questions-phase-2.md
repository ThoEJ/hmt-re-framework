Checklists/Questions for Phase 2
================================

Activity 2.1 &ndash; What-If-Questions to help discover HMT process problems at multiple layers of analysis based on Maiden [1]. The corresponding model and scenario elements that should be examined are highlighted for each layer:

| Action (SBD states, Scenario actions) |
| -------- |
| What if this action does not complete or does not complete on time? |

| Information Manipulated (SID messages, SBD states, SBD subject data definition list, Scenario actions) |
| -------- |
| What if the information manipulated in this action is out-of-date? |
| What if the information manipulated is inappropriate for this action? |
| What if the information manipulated in this action is insufficient, incorrect or unreliable? |
| What if the information manipulated in this action is too general or detailed? |
| What if the information model is incorrect? |

| Agent (SID subject, SBD states, Scenario actions) |
| -------- |
| What if [AGENT1] is unavailable or malfunctioning during this action? |
| What if [AGENT1] is functioning incorrectly during this action? |
| What if [AGENT1] and [AGENT2] fulfil the same roles during this action? |
| What if something unusual occurs in [AGENT1]'s environment during this action? |
| What if something unusual occurs in [AGENT1]'s organisation during this action? |

| Event (SBD states, Scenario actions) |
| -------- |
| What if this event does not occur in this scenario? |
| What if this event occurs earlier or later in time than expected? |
| What if this event occurs more or less frequently than expected? |
| What if a different event occurs instead of this event in the scenario? | 

| Object (SBD states, Scenario actions) |
| -------- |
| What if [OBJECT1] is unavailable or not operational during this action? |

| Human Agent (SID subject, SBD states, Scenario actions) |
| -------- |
| What if [HUMANAGENT] has some unusual physical characteristics that affect his/her behaviour during this action? |
| What if [HUMANAGENT] is physically unable to undertake this action? |
| What if [HUMANAGENT] is unusually young or old? |
| What if [HUMANAGENT]'s gender is different to what is expected during this action? |

| Machine Agent (SID subject, SBD states, Scenario actions) |
| -------- |
| What if [MACHINEAGENT] undertakes some unusual behaviour or exhibits some unusual state during the action? |
| What if [MACHINEAGENT] has a problem with its power supply during this action? |
| What if [MACHINEAGENT] has a problem with its hardware during this action? |
| What if [MACHINEAGENT]'s peripheral device fails during this action? |
| What if [MACHINEAGENT] is interface fails during this action? | 

| Agent Communication (SID subject, SID message exchange) |
| -------- |
| What if there is a communication breakdown between [MACHINEAGENT] and [HUMANAGENT] during this action? |
| What if there is a communication failure between [MACHINEAGENT1] and [MACHINEAGENT2] during this action? |
| What if there is a communication breakdown between [HUMANAGENT1] and [HUMANAGENT2] during this action? |

Activity 2.1 &ndash; Questions to help analyse a concrete instance of a process problem according to HMT dimensions. Based on McDermott et al. [1]:

| Transparency |
| -------- |
| *Observability*: How could the problem be detected by a HA/MA? |
| *Predictability*: How well could the next intended action of the HA/MA be inferred? |

| Augmented Cognition |
| -------- |
| *Directing Attention*: How could the HA/MA be made aware of the problem? |
| *Solution Exploration*: How could the HA/MA be supported in finding candidate solutions for solving the problem? |
| *Adaptability*: How could the HA/MA select the best solutions and solve the problem? |

| Coordination |
| -------- |
| *Directability*: How well could the HA direct the resources of the MA? |
| *Calibrated Trust*: How could the level between the HA and the MA be improved? |
| *Common Ground*: How could the sharing of knowledge (beliefs, assumptions?) between the HA and the MA be improved? |

References
==========
[1] Maiden, N.A.M.: Systematic scenario walkthroughs with ART-SCENE. In: Alexander, I., Maiden, N.A.M. (eds.) Scenarios, Stories, Use Cases: Through the Systems
Development Life-Cycle, pp. 161–178. John Wiley & Sons, New York (2004)

[2] McDermott, P., Dominguez, C., Kasdaglis, N., Ryan, M., Trahan, I., Nelson, A., et al.: Human-machine teaming systems engineering guide. MITRE Corp Bedford MA Bedford United States (2018)

