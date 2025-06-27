---
date: "2025-06-02"
title: "Session 6: Behaviour Tool"
ShowToc: true
TocOpen: true

---

### Description
The Behavior Recipe Book is a collection of pre-defined behavioral patterns, each captured on a distinct card. These cards serve as building blocks for designing robot interactions, much like design patterns in software or UI design. Each recipe outlines a common interaction goal, a sequence of robot actions, the context in which it's best used, and practical tips for implementation. By using these established patterns, designers can ensure consistency, efficiency, and effectiveness in developing new robot behaviors, moving beyond ad-hoc design to a more structured and informed approach.
![Scenario](/img/week6-tool.png) 

### SMART
Specific: The tool provides predefined, goal-driven behavior templates that help designers quickly prototype robot interactions.
Measurable: Designers can evaluate effectiveness based on user engagement, task success rate, and clarity of interaction using consistent recipes.
Achievable: The tool supports rapid ideation through modular, easy-to-follow cards and requires only low-fidelity tools (roleplay, paper prototyping) for early-stage testing.
Relevant: Encourages consistency, emotional appropriateness, and functional design in human-robot interactions.
Time-bound: Can be used throughout the design process—from ideation to testing—with structured, time-efficient prototyping and evaluation phases.

### Using the tool
Use the robot, if it is ready for the testing phase. If not, designers can roleplay the interaction using the Behavior Recipe Cards. In this roleplay, a person enacts the robot following the selected recipe. This allows iterative testing, even in early stages without a working robot prototype.

#### How it works
Designers use a physical or digital set of Behavior Recipe Cards. Each card represents a common robot behavior and is structured to provide:
- **Goal:** The primary objective of the behavior (e.g., "Show emotional intelligence," "Improve communication clarity," "Increase task success rates").
- **Sequence:** A step-by-step outline of the robot's actions and responses (e.g., "Detect user emotion -> Match tone/gesture," "Detect presence -> Greet user," "User asks questions -> Ask a question -> Wait for response").
- **Use When:** The specific scenarios or contexts where this behavior is most appropriate or effective (e.g., "When social content is emotionally charged," "Robot acts as guide or companion," "Teaching or guiding users through steps").
- **Tip:** Additional advice, best practices, or considerations for implementing the behavior (e.g., "Use only when accurate emotion detection is available," "Use soft tones and delay to avoid overwhelming the user," "Add reinforcement or suggestion").

Designers can:
- **Browse:** Explore the existing library of cards (such as "Emotional Mirror," "Follow and Observe," "Greet and Mirror," "Prompt and Clarify," "Help on Cue," "Repeat Until Clear," "Observe and Wait," "Fail Gracefully," and "Pause and Check").
- **Combine:** Select multiple cards to build complex behavioral sequences for a given scenario.
- **Remix and Modify:** Adapt existing recipe sequences or tips to fit unique challenges, or use the "Custom Mix Template" card to create entirely new behaviors following the established structure.
- **Prototype and Test:** Once a behavior sequence is assembled, designers can walk through it, act it out, or use low-fidelity tools (like the Embodied Wizard Proxy or Kitchen Timer Tester) to simulate and test the interaction flow and its perceived effect on users. 


### Evaluating the tool outcomes
Case used: A robot is instructed to pick up medication from a table and distribute it to a user.

#### POEM observation framework
Observations were recorded using the POEM framework.
![Scenario](/img/Poem-week6.png) 

**Observed behavior**
- The "Pause & Check" behavior was applied: the robot pauses before handing over medication and waits for user acknowledgment (verbal/non-verbal).
- Robot nods and recognizes user cues before proceeding.
- Initiation of the behavior was initially perceived as “strange,” highlighting a need to refine how the behavior starts.

**User Experience Insights**
- The interaction felt awkward at first, but the "pause" helped make the handover feel intentional and respectful.
- Roleplaying (even without a functioning robot) revealed how users interpret robot intention and timing.
- Non-verbal cues were crucial; users responded well to pauses and nods indicating checking or seeking consent.

### Evaluating outcomes regarding the case + literature: 
The "Pause & Check" behavior card test showed that the Behavior Recipe Book is a useful tool. Even without a real robot, using role-play gave us helpful information about how robot behaviors could be designed and how people might react to them. This supports earlier research that shows simple methods like role-playing can give strong insights during the design process [1], [2].

One thing we noticed was that the start of the interaction felt a bit awkward. This tells us that we should improve not only the main robot behavior, but also how the behavior fits into the full interaction. This idea fits with design rules that say interactions should feel smooth and natural for users [3].

We also saw that small non-verbal actions, like nodding or pausing, worked really well. These simple signals helped the robot seem more social and understandable. This matches findings in human-robot interaction research that say small social cues are just as important as the robot’s main actions [4].

### Sources
[1] J. L. Kolko, "Design Thinking Comes of Age," Harvard Business Review, vol. 93, no. 9, 2015. 

[2] P. L. Hekkert and D. J. Hekkert, "Design, Science and the Art of Human-Centered Design," Design Issues, vol. 24, no. 3, 2008. 

[3] B. Shneiderman, "Eight Golden Rules of Interface Design," in Designing the User Interface: Strategies for Effective Human-Computer Interaction, 6th ed. Boston, MA, USA: Pearson, 2016. 

[4] K. Dautenhahn, "Human-Robot Interaction Design," in The Handbook of Robotics, B. Siciliano and O. Khatib, Eds. Cham, Switzerland: Springer, 2016.