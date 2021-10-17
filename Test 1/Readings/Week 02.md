# Week 2

## Cognitive Engineering (Don Norman)

Cognitive Engineering 
	- Applied Cognitive Science, trying to apply what is known from science to design and construction to machines
	- Goal is to understand issues, how to make better choices when there are many, show tradeoffs when improvement in one domain leads to deficits in another

End Intention
	- To understand the fundamental principles behind human action and performance that are relevant for the development of engineering principles of design.
	- To devise systems that are pleasant to use-the goal is neither efficiency nor ease nor power, although these are all to be desired, but rather systems that are pleasant, even fun: to pro- duce what Laurel calls "pleasurable engagement" (Chapter 4).

### Analysis of Task Complexity
Sailors and Compass Example
	- The correct conceptual model can transform confus- ing, difficult tasks into simple, straightforward ones. This is an important point that forms the theme of a later section.

### Psychological Variables Differ From Physical Variables
There is a discrepancy between the person's psychologically expressed goals and the physical controls and variables of the task.
	- the person must interpret the physical variables into terms relevant to the psycho- logical goals and must translate the psychological intentions into physi- cal actions upon the mechanisms

***Examples of Problems and relationships between variables (Very Important)*** 
- Bathtub
1. Mapping problems. Which control is hot, which is cold? Which way should each control be turned to increase or decrease the flow? (Despite the appearance of universal standards for these mappings, there are sufficient variations in the standards, idiosyncratic layouts, and violations of expectations, that each new faucet poses potential problems.) 
2. Ease of control. To make the water hotter while maintaining total rate constant requires simultaneous manipulation of both faucets. 
3. Evaluation. With two spouts, it is sometimes difficult to deter- mine if the correct outcome has been reached.

- Normans Refrigirator
1. Matching the psychological variables of interest to the physical variables being controlled. Although the labels on the control mechanisms indicate some relationship to the desired psycho- logical variables, in fact, they do not control those variables directly.
2. The mapping relationships. There is clearly strong interaction between the two controls, making simple mapping between control and function or control and outcome difficult.
3. Feedback. Very slow, so that by the time one is able to deter- mine the result of an action, so much time has passed that the action is no longer remembered, making "correction" of the action difficult.
4. Conceptual model. None. The instructions seem deliberately opaque and nondescriptive of the actual operations.


### Aspects of a Task (Very Important)

- **Goals and intentions** : A goal is the state the person wishes to achieve an in- tention is the decision to act so as to achieve the goal.
- **Specification of the action sequence**: The psychological process of determining the psycho- logical representation of the actions that are to be executed by the user on the mechanisms of the system.
- **Mapping from psychological goals and intentions to action sequence**: In order to specify the action sequence, the user must translate the psychological goals and intentions into the desired system state, then determine what settings of the control mechanisms will yield that state, and then determine what physical manipulations of the mechan- isms are required. The result is the internal, mental specification of the actions that are to be executed.
- **Physical state of the system**: The physical state of the system, determined by the values of all its physical variables.
- **Control mechanisms**: The physical devices that control the physical variables.
- **Mapping between the physical mechanisms and system state**: The relationship between the settings of the mechan- isms of the system and the system state.
- **Interpretation of system state**: The relationship between the physical state of the sys- tem and the psychological goals of the user can only be determined by first translating the physical state into psychological states (perception), then interpreting the perceived system state in terms of the psychological variables of interest.
- **Evaluating the outcome**: Evaluation of the system state requires comparing the interpretation of the perceived system state with the desired goals. This often leads to a new set of goals and intentions.


### Theory of Action (Approximate version)

- **Gulf of Execution**
	- Bridging the Gulf of Execution. The gap from goals to physical sys- tem is bridged in four segments: intention formation, specifying the action sequence, executing the action, and, finally, making contact with the input mechanisms of the interface. 
		- The intention is the first step, and it starts to bridge the gulf, in part because the interaction language demanded by the physical system comes to color the thoughts of the person.
		- Specifying the action requires translating the psychological goals of the intention into the changes to be made to the physical variables actually under control of the system. 
			-This, in turn, requires following the mapping between the psychological intentions and the physical actions permitted on the mechanisms of the system, as well as the mapping between the physical mechanisms and the resulting physical state variables, and between the physical state of the system and the psychological goals and intentions
		- After an appropriate action sequence is determined, the actions must be executed. Execution is the first physical action in this sequence: Forming the goals and intentions and specifying the action sequence were all mental events. 
		- Because some physical actions are more difficult than others, the choice of input devices can affect the selection of actions, which in turn affects how well the system matches with intentions

- **Gulf of Evaluation**
	- The gap from sys- tem to user is bridged in four segments: 
		- starting with the output displays of the interface, 
		- moving to the perceptual processing of those displays, 
		- to its interpretation, and 
		- finally, to the evaluation - the comparison of the interpretation of system state with the original goals and intention. 
	- But in doing all this, there is one more problem, one just beginning to be understood, and one not assisted by the usual forms of displays: the problem of level. There may be many levels of outcomes that must be matched with different levels of intentions

### Stages in User Activities

Summary of the analysis of tasks is that the process of performing and evaluating an action can be approximated by seven stages of user activity
	- Establishing the Goal
	- Forming the Intention
	- Specifying the Action Sequence
	- Executing the Action
	- Perceiving the System State 
	- Interpreting the State 
	- Evaluating the System State with respect to the Goals and Intentions

*Note - Read page 43 complex activity*

### Conceptual Models and System Image

*Note - This section is bit ambigous*

-  We change the interface at the system side through proper design. We change the interface at the human side through training and experience. 
- In the ideal case, no psychological effort is required to bridge the gulfs. But such a situation occurs only either with simple situations or with experienced, expert users. 
- With complex tasks or with nonexpert users, the user must engage in a plan- ning process to go from intentions to action sequence. 

- Conceptual model of the system as providing a scaffold- ing upon which to build the bridges across the gulfs. The scaffoldings provided by these conceptual models are probably only important dur- ing learning and trouble-shooting.

	- Design(er) Model
		- The Design Model is the conceptual model of the system to be built. Ideally, this conceptualization is based on the user's task, requirements, and capabilities. The conceptualization must also consider the user's background, experience, and the powers and limitations of the user's information processing mechanisms, most especially processing resources and short-term memory limits. 
	- User model
		- The user develops a mental model of the system-the User's Model. Note that the user model is not formed from the Design Model: It results from the way the user interprets the System Image. 
		- Thus, in many ways, the primary task of the designer is to construct an appropri- ate System Image, realizing that everything the user interacts with helps to form that image
			- Examples - the physical knobs, dials, keyboards, and displays, and the documentation, including instruction manuals, help facilities, text input and output, and error messages.


### ON Quality of HCI
- The details of the interaction matter, ease of use matters, but I want more than correct details, more than a system that is easy to learn or to use: I want a system that is enjoyable to use. This is an important, dominating design philosophy, easier to say than to do.
	- This means tools that reveal their under- lying conceptual model and allow for interaction, tools that emphasize comfort, ease, and pleasure of use
	- A major factor in this debate is the feeling of control that the user has over the operations that are being performed. 
	- A "powerful," "intelligent" system can lead to the well documented problems of "overautomation," causing the user to be a passive observer of operations, no longer in control of either what operations take place, or of how they are done. 
- Overall the critical aspect is "pleasurable engagement," by which it means the complete and full engagement of the person in pursuit of the "end cause" of the activity.

**Example of Issue in Tool** - Pinball set : Much as I enjoy manipulating the parts of the pinball sets, much as my 4-year-old son could learn to work it with almost no training or bother, neither of us are any good at constructing pinball sets. I can't quite get the parts in the right places:
	- When I stretch a part to change its shape, I usually end up with an unworkable part. Balls get stuck in weird corners. The action is either too fast or too slow. Yes, it is easy to change each problem as it is discovered, but the number seems endless. I wish the tools were more intelligent

### Revisiting the GULFs

Theory suggests that two of the mappings play critical roles: 
	- the mapping from the psychological variables in which the goals are stated to the physical variables upon which the control is actually exerted
	- the mapping from the physical variables of the system to psychological variables. The easier and more direct these two mappings, the easier and more pleasant the learning and use of the interface, at least so goes the theory

### Design Issues
- Any real system is the result of a series of tradeoffs that balance one design decision against another, that take into account time, effort, and expense. Almost always the benefits of a design decision along one dimension lead to deficits along some other dimension. 
- The designer must consider the wide class of users, the physical limitations, the con- straints caused by time and economics, and the limitations of the tech- nology. Moreover, the science and engineering disciplines necessary for a proper design of the interface do not yet exist. 
	- Approximate Models in Design
		* Although the approximate model is clearly wrong in all its details, in most practical applications the details of STM do not matter: This approximate model can be very valuable. Other approximate models are easy to find. 
	- Tradeoffs
		* Design is a series of tradeoffs: Assistance for one stage is apt to inter- fere with another. Any single design technique is apt to have its vir- tues along one dimension compensated by deficiencies along another. Each technique provides a set of tradeoffs
		* **The prototypical tradeoff: information versus time**.
			- Factors that increase informative- ness tend to decrease the amount of available workspace and system respon- siveness. On the one hand, the more informative and complete the display, the more useful when the user has doubts or lacks understand- ing. On the other hand, the more complete the display, the longer it takes to be displayed and the more space it must occupy physically.
		* **First- and second-order issues**
			- One major tradeoff concerns just which aspects of the system will be worked on. With limited time and people, the design team has to make decisions: Some parts of the sys- tem will receive careful attention, others will not. Each different aspect of the design takes time, energy, and resources, none of which is apt to be readily available. Therefore, it is important to be able to distinguish the first order effects from the secondary effects-the big issues from the little issues.


### Prescriptions for Design Principles
- **Create a science of user-centered design** 
	- For this, we need prin- ciples that can be applied at the time of the design, principles that get the design to a pretty good state the first time around.
- **Take interface design seriously as an independent and important problem** 
	- It takes at least three kinds of special knowledge to design an interface: first, knowledge of design, of program- ming and of the technology, second, knowledge of people, of the principles of mental computation, of communication, and of interaction and third, expert knowledge of the task that is to be accomplished.
	-  We need either especially trained interface special- ists or teams of designers, some members expert in the topic domain of the device, some expert in the mechanics of the device, and some expert about people. 
- **Separate the design of the interface from the design of the system**
	- This is the principle of modularization in design. It allows the previous point to work. Today, in most systems, everyone has access to control of the screen or mouse
- **Do user-centered system design: Start with the needs of the user** 
	- From the point of view of the user, the interface is the system. Concern for the nature of the interaction and for the user- these are the things that should force the design. 
	- Let the requirements for the interaction drive the design of the inter- face, let ideas about the interface drive the technology. 


## THE PSYCHOLOGY OF EVERYDAY ACTIONS

> Norman, D. (2013). Chapter 2: The Psychology of Everyday Actions. In The Design of Everyday Things: Revised and Expanded Edition. (pp. 37-73). Arizona: Basic Books.


**Agenda** - First, how do people do things? why do they do things? But what happens when things go wrong? How do we detect that they aren’t working, and then how do we know what to do? To help understand this, I first delve into human psychology and a simple conceptual model of how people select and then evaluate their actions


### How People Do Things: The Gulfs of Execution and Evaluation

- The role of the designer is to help people bridge the
two gulfs.
- The Gulf of Evaluation reflects the amount of effort that the person must make to interpret the physical satte of the device and to determine how well the expectations
and intentions have been met. 
- What are the major design elements that help bridge the
Gulf of Evaluation? Feedback and a good conceptual mode.
- The difficulties reside in their design, not in the people attempting to use them.

- **Basic Tools** : We bridge the Gulf of Execution through the use of signifiers, constraints, mappings, and a conceptual model. We bridge the Gulf of Evaluation through the use of feedback and a conceptual model.

### Seven Stages of Action

1. Goal (form the goal) 
2. Plan (the action) 
3. Specify (an action sequence) 
4. Perform (the action sequence)
5. Perceive (the state of the world)
6. Interpret (the perception)
7. Compare (the outcome with the goal)

* It has proven to be helpful in designing interaction. Not all of the activity in the stages is conscious. Goals tend to be, but even they may be subconscious. 
* Most behavior does not require going through all stages in sequence; however, most activities will not be satisfied by single actions.

- The action cycle can start from the top, by establishing a new goal, in which case we call it goal-driven behavior
- But the action cycle can also start from the bottom, triggered by some event in the world, in which case we
call it either data-driven or event-driven behavior
- Opportunistic actions are those in which the behavior takes advantage of circumstances. Rather than engage in extensive planning and analysis, we go about the day’s activities and do things as opportunities arise
- The seven stages provide a guideline for developing new products or services. The gulfs are obvious places to start, for either gulf, whether of execution or evaluation, is an opportunity for product enhancement. The trick is to develop observational skills to detect them. Most innovation is done as an incremental enhancement of
existing products.

### Human Thought: Mostly Subconscious
- The mind is more difficult to comprehend than actions. Most of us start by believing we already understand both human behavior and the human mind.
- The human mind is immensely complex, having evolved over
a long period with many specialized structures. The study of the mind is the subject of multiple disciplines, including the behavioral and social sciences, cognitive science, neuroscience, philosophy, and the information and computer sciences. - Finger Move Experiments
- Conscious attention is necessary to learn most things, but after the initial learning, continued practice and study, sometimes for thousands of hours over a period of years, produces what psychologists call “overlearning,


- The earlier questions were memory for factual information, what is called declarative memory. - Phone number of Friend

- The last question could have been answered factually, but is usually most easily answered by recalling the activities performed to open the door. This is called procedural memory. - Door knob location

- Cognition and emotion cannot be separated. Cognitive thoughts lead to emotions: emotions drive cognitive thoughts. The brain is structured to act upon the world, and every action carries with it expectations, and these expectations drive emotions

***Subconscious and Conscious Systems of Cognition***

Subconscious->Conscious
Fast->Slow
Automatic->Controlled
Multiple resources->Limited resources
Controls skilled behavior->Invoked for novel situations: when learning, when in danger, when things go wrong

### Human Cognition and Emotion
Useful approximate model of human cognition and emotion
is to consider three levels of processing: visceral, behavioral, and reflective.

**Visceral**
- The visceral system allows us to respond quickly and subconsciously, without conscious awareness or control
- Visceral responses are fast and automatic.
They give rise to the startle reflex for novel, unexpected events; for such genetically programmed behavior as fear of heights, dislike of the dark or very noisy environments, dislike of bitter tastes and the liking of sweet tastes, and so on.
- It simply assesses the situation: no cause is assigned, no blame, and no credit
- Visceral responses are fast and completely subconscious. They are sensitive only to the current state of things. Most scientists do not call these emotions: they are precursors to emotion.
- For designers, the visceral response is about immediate perception: the pleasantness of a mellow, harmonious sound or the jarring, irritating scratch of fingernails on a rough surface.

**Behavioral**
- The behavioral level is the home of learned skills, triggered by situations that match the appropriate patterns. Actions and analyses at this level are largely subconscious. Even though we are usually aware of our actions, we are often unaware of the details
- Pick up a cup, and then with the
same hand, pick up several more items. You automatically adjust the fingers and the hand’s orientation to make the task possible


**Reflective**
- The reflective level is the home of conscious cognition. As a consequence, this is where deep understanding develops, where reasoning and conscious decision-making take place. 
-  Reflection is cognitive, deep, and slow. It often occurs after the events have happened. It is a reflection or looking back over them, evaluating the circumstances,
actions, and outcomes, often assessing blame or responsibility. 
- Adding causal elements to experienced events leads to
such emotional states as guilt and pride (when we assume ourselves to be the cause) and blame and praise (when others are thought to be the cause)

* Design must take place in all 3 levels

* **Levels of Processing and the
Stages of the Action Cycle** - Visceral response is at the lowest level: the control of simple muscles and sensing the state of the world and body. The behavioral level is about expectations, so it is sensitive to the expectations of the action sequence and then the interpretations of the feedback. The reflective level is a part of the goal- and plan-setting activity as well as affected by the comparison
of expectations with what has actually happened

**Csikszentmihalyi’s work** - An easy task, far below our skill level, makes it so easy to meet expectations that there is no challenge. Very little or no processing effort is required, which leads to apathy or boredom. A difficult task, far above our skill, leads to so many failed expectations that it causes frustration, anxiety, and helplessness. The flow state occurs when the challenge of the activity just slightly exceeds our skill level, so full attention is continually required.


### People as Storytellers

- Conceptual models are a form of story, resulting from our predisposition to find explanations. These models are essential in helping us understand our experiences, predict the outcome of our actions, and handle unexpected occurrences.
- One commonly held folk theory of the working of a
thermostat is that it is like a valve: the thermostat controls how much heat (or cold) comes out of the device. Hence, to heat or cool something most quickly, set the thermostat so that the device is on maximum. The theory is reasonable, and there exist devices that operate like this, but neither the heating or cooling equipment for a
home nor the heating element of a traditional oven is one of them.
- The information provided misleads people into forming the wrong, quite inappropriate model - Don Normans fridge.
- It is that everyone forms stories (conceptual models) to explain what they have observed. In the absence of external
information, people can let their imagination run free as long as the conceptual models they develop account for the facts as they perceive them.

### Blaming Wrong things
- People try to find causes for events. They tend to assign a causal relation whenever two things occur in succession. If some unexpected event happens in my home just after I have taken some action, I am
apt to conclude that it was caused by that action, even if there really was no relationship between the two.
- The tendency to repeat an action when the first attempt fails can be disastrous. This has led to numerous deaths when people tried to escape a burning building by attempting to push open exit doors that opened inward, doors that should have been pulled. As a result, in many countries, the law requires doors in public places to open outward, and moreover to be operated by so-called panic bars, so that they automatically open when people, in a panic to escape a fire, push their bodies against them
- Suppose I try to use an everyday thing, but I can’t. Who is at fault: me or the thing? We are apt to blame ourselves, especially if others are able to use it. Suppose the fault really lies in the device, so that lots of people have the same problems. Because everyone
perceives the fault to be his or her own, nobody wants to admit to having trouble.
- It seems natural for people to blame their own misfortunes on the environment. It seems equally natural to blame other people’s misfortunes on their personalities
- In all such cases, whether a person is inappropriately accepting blame for the inability to work simple objects or attributing behavior to environment or personality, a faulty conceptual model is at work.

### Learned Helplessness
- The phenomenon called learned helplessness might help explain the self-blame. It refers to the situation in which people experience repeated failure at a task. As a result, they decide that the task cannot be done, at least not by them: they are helpless. They stop trying.
- When people have trouble using technology, especially when they perceive (usually incorrectly) that nobody else is having the same problems, they tend to blame themselves. Worse, the more they have trouble, the more helpless they may feel, believing that they must be technically or mechanically inept


### Positive Psychology
- Just as we learn to give up after repeated failure, we can learn optimistic, positive responses to life.
- Scientists know this. Scientists do experiments to learn how the world works. Sometimes their experiments work as expected, but often they don’t. Are these failures? No, they are learning experiences. Many of the most important scientific discoveries have come from these so-called failures.

### Falsely Blaming Yourself
- The idea that a person is at fault when something goes wrong is deeply entrenched in society. That’s why we blame others and even ourselves. Unfortunately, the idea that a person is at fault is imbedded in the legal system. When major accidents occur, official courts of inquiry are set up to assess the blame. More and more often the blame is attributed to “human error.”

### HOW TECHNOLOGY CAN ACCOMMODATE HUMAN BEHAVIOR
- Microsoft excel data example

### The Seven Stages of Action: Seven Fundamental Design Principles

1. Discoverability. It is possible to determine what actions are possible
and the current state of the device.
2. Feedback. There is full and continuous information about the results
of actions and the current state of the product or service. After an
action has been executed, it is easy to determine the new state.
3. Conceptual model. The design projects all the information needed
to create a good conceptual model of the system, leading to understanding and a feeling of control. The conceptual model enhances
both discoverability and evaluation of results.
4. Affordances. The proper affordances exist to make the desired actions possible.
5. Signifiers. Effective use of signifiers ensures discoverability and that
the feedback is well communicated and intelligible.
6. Mappings. The relationship between controls and their actions follows the principles of good mapping, enhanced as much as possible
through spatial layout and temporal contiguity.
7. Constraints. Providing physical, logical, semantic, and cultural constraints guides actions and eases interpretation