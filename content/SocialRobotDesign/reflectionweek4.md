---
date: "2025-05-15T11:09:52+01:00"
title: "Reflective Questions Session 4: Embodiment"
ShowToc: true
TocOpen: true

---

## Embodied Agents vs Virtual Agents
The discussion on embodied agents vs virtual agens is still relevant since embodiment is still has a big influence on interaction with humans. It creates a physical appearance which people trust and gets attention. Other shapes that exist are HoloLens and Meta Quest which are avatars that move in the space around us but do not have a physical body. Next to that AR/VR and holograms are rising in which virtual agents are projected into the physical world. 

## Robotic Capabilities and Social Aspects
Robotic capabilities and social aspects are not the same since they differ in focus. Robotic/engineering capabilities focusses on what the robot is able to do and how the robot executes the functions while social aspects is more focussed on how the robot comes across to humans. Social aspects is more focussed on interaction while the focus of robotic capabilities is on performance.

Insights on dealing in a structured way with the robotic capabilities and social aspects of the design are:
- The Function–Behavior–Structure (FBS) Framework from J. S. Gero and U. Kannengiesser [1], can help to create a division between functions, behaviors and structures to map social goals to design features. 
- The Interaction Design Framework from J. Forlizzi and S. Ford [2], can help understand and design user experiences in interactive systems. It shows three perspective on experiences and components influencing the experience. Through looking at the components influencing the experience we can make a division between different part in social robot design. The components are product characteristics, user characteristics and interaction context. Next to the components there are also qualities of experience which are stated: satisfying, enjoyable, engaging and meaningful. By understanding the relationship between product attributes, user characteristics and context, designers can predict and influence the quality of the user experience. 

Yes, we can write social interaction requirements for robots in a clear and organized way, just like we do for technical or engineering tasks. This helps make social behaviors easier to understand, measure and test even though they often feel unclear or hard to define.

A template for these requirements made with chatgpt [3] can be found below.

| Requirement ID | Type                | Description                                                        | Criteria for Success               | Method of Verification            |
|----------------|---------------------|--------------------------------------------------------------------|------------------------------------|----------------------------------|
| SI-001         | Social Responsiveness | Robot must greet a person within 2 seconds of face detection       | Time ≤ 2 sec after detection        | Interaction log, real-time testing |
| SI-002         | Emotion Expression   | Robot must express “confusion” when it fails to understand a command | Visual cue (tilted head), audio cue | Observation                       |


## Examples of Conflicts and Opportunities
Examples of conflicts that arise in the function defines form vs social requirements are:
- Assistive robot for elderly care: from the functional side it must be very functional and usable while on the social side it needs to look approachable and provide a comforting feel for an elderly. The conflict is in creating a purely functional device will not work for elderly since they will not trust it.
- Industrial robot arm: from the functional side it must be very efficient, precise and work with speed while on the social side it needs to appear safe and that people can approach the robot and do not need to keep a very big distance. The conflict is mostly in that fast and powerful movements of the arm can seem unsafe and threatening for people that need to work with them.

Example of a design that is a very good match is a soft robotic in therapy for example the Paro Robot Seal. In this way the soft and cuddly appearance of the seal supports the function of it providing emotional suport and social bonding. Next to that the movement is slow and gentle which aligns the function of emotional support with the social need of comfort and trust. 

## Duffy's Embodiment Reference 
Duffy (see below) formulated a nice reference list of aspects relevant for design of embodiment. Which of these are the most relevant for your case?

The most relevant aspects for design of embodiment according to Duffy [4] are: 
| Principle                                                         | Explanation                                                                                          |
| ----------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| **Use social conventions and communication in function and form** | Design robots to communicate in ways familiar to humans, both in appearance and behavior.            |
| **Avoid the uncanny valley**                                      | Steer clear of designs that look almost but not quite human, which can cause discomfort or eeriness. |
| **Use natural (fluent) motion**                                   | Ensure robot movements are smooth and lifelike to foster better social engagement.                   |
| **Balance function and form**                                     | Make sure the robot’s appearance aligns with and supports its functional goals.                      |
| **Balance anthropomorphism and function**                         | Use human-like features thoughtfully to enhance interaction without compromising utility.            |
| **Allow the robot to portray identity**                           | Enable robots to have distinct personalities or characters to help users relate to them.             |
| **Make sure artificial emotions do not obstruct interaction**     | Avoid overly complex or inappropriate emotional expressions that confuse or hinder communication.    |

All of these principles can be very useful in the tool that we created and can be added as an extra guiding card.



## References
[1] J. S. Gero and U. Kannengiesser, "The situated function–behaviour–structure framework," Design Studies, vol. 25, no. 4, pp. 373–391, Jul. 2004, doi: 10.1016/j.destud.2003.10.010.

[2] J. Forlizzi and S. Ford, "The Building Blocks of Experience: An Early Framework for Interaction Designers," in Proceedings of the 3rd Conference on Designing Interactive Systems (DIS 2000), New York, NY, USA, 2000, pp. 419–423

[3] OpenAI, ChatGPT, https://chat.openai.com, accessed May 15, 2025, prompt: create an Engineering-Style Template for Social Interaction in the form of a table 

[4] Duffy, B. R., "Anthropomorphism and the social robot," Robotics and Autonomous Systems, vol. 42, no. 3-4, pp. 177–190, 2003