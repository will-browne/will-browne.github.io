# Postgraduate Research Information
This is a collection of useful hints and tips for postgraduate research, such as doctoral or masters study. Over the last 20+ years I've been fortunate enough to guide amazing people through their research journey, so here are my thoughts to help people in the early stages of their journey. This includes people considering collaborative research with me, so lists areas of potential mutual interest.

## Things you need for the research journey:

1. Prerequisite knowledge in the research domain.
This is usually a high-class undergraduate degree in a relevant discipline (high GPA from a good university ~top 500 world ranked). This can be complemented by on-line courses and self-study when switching disciplines.
2. English language communication in written, oral and comprehension.
Academic discourse is commonly in English (it is arguable whether this is the best language, but it has become the de facto standard), so obtaining a high level  (~IELTS 7.0 or equivalent) and continuing to work on this aspect is required throughout the study is an unavoidable necessity.
3. 'Stickability', especially for doctorate studies. 
Research is difficult, which also makes it highly rewarding. The ability to keep going through tough times, and seek help as required, is needed.

There is one other criteria I look for when committing to guide/supervise an emerging researcher for over three years: 'Do they make me think?'
I'm interested in someone with an enquiring mind, who naturally asks the difficult questions.

There have been a few things that have made the journey more difficult, such as lack of finances, part-time study, starting a family, illness, but none of these have been impregnable barriers to completion.
I can only recall two actual barriers: money as the motivator (entrepreneurship is to be celebrated, but rarely a good basis for research) and drugs (even soft drugs impair intellectual ability).

## Hints for contacting a potential supervisor 
Academics receive hundreds of enquiries per year, so please do not be disheartened if an enquiry goes unanswered as it's not personal. Thus, 
The first hint is to make the email personal, i.e. Dear Prof Will Browne rather than Dear Professor, (BTW the title can be left off for me). 
The second hint is to show that you have looked into the research of the supervisor, e.g. I read your paper on ... [and have actually read it!]. 
The third hint is to show how your research interests overlap with the supervisor's current interests, e.g. This matches my interest in ..., which I developed from ...
Finally, it is good to show the direction of the joint research, e.g. Would you be interested in guiding my research on ... ?

Commenting on the latest research trends, areas of future investigation, pertinent research questions and hypotheses to address open questions, will also get the interest of potential supervisors.

CVs should be quantifiable, e.g. put your grades in relevant subjects, overall GPA and English-language test scores. If your university is not in the same country, then it's good to cite its world ranking and how it compares nationally. Published papers are often important, so state the impact factor of the venue and its number of citations. Academic CVs do not have to be restricted to one-page, but they do have to be nicely formatted and free of typographical/grammar/spelling errors.

## Available Research Areas and Projects 
This is not an exhaustive list, but is indicative of my research plans. It's also not in a priority order as it's more important to find areas of mutual interest rather than adapt to a supervisor's area of interest that is not motivating to you.

My overall research area is: _Artificial Cognitive Systems_

That is, how to get artificial systems (software and/or robots) to perceive, represent, reason, learn and effect an interaction with an environment to continually improve its task solving ability.

### Continual Learning Systems
AI that is pre-programmed is limited on its tasks and human bias. Learning systems offer rich behaviour, where collaborators and I have created the following that need developing (projects bulleted)

A symbolic system that works in Boolean and Integer domains without noise
* Need to translate this to real-valued, noisy domains.
Code exists, but the data sets do not and integration is still uncertain. Most intriguing is how future use can influence current learning, i.e. "will this be useful in the future?"

A lateralized system exists that enables a provident to be considered at the local level and the holistic level simultaneously.
* How lateralization functions in continual learning is an open question, e.g. can we learn the concept of a leg, wheel, etc., so that we can readily identify and differentiate forms of locomotion?

A compaction algorithm exists that can remove redundant and irrelevant learnt knowledge, where it is unknown how this works for continual learning. What happens with almost duplicate knowledge from different sources, how to forget (without catastrophic forgetting), how to learn economically and so forth.
* How to learn in a distributed/federated manner continuously is an open question, but recent advances in networked learning are promising.

### Abstract reasoning
This is the ability to learn the underlying patterns within an environment to interactive observation within it. This goes beyond generalisation, i.e. the ability to identify and ignore irrelevant/redundant knowledge. Instead, it is the ability to identify building blocks of knowledge that can be recombined into more complex patterns that are useful to solve tasks in the domain.

The continual learning system developed as a basic form of abstract reasoning in terms of recombining solutions from small problems to help solve larger-scale problems in the same or related domain.
* Research questions remaining on how abstraction adapts to inductive, deductive and abductive reasoning in adaptive learning.
Chollet’s Abstraction Reasoning Corpus is a most interesting and open challenge in this research field.

Robots are often required to produce maps of unknown areas or navigate through dynamic environments but use a static map of fixed scale. Humans and other animals appear to be able to switch scales in a map to reason at the best scale for the problem they are tackling currently, e.g. local scale to move around an obstacle or more globally the best path to achieve multiple objectives.
* How reasoning utilising multiple scales can happen concurrently for a robot to successfully accomplish multiple objectives coherently.
An interesting aside is whether humans store the world in 3D or 2 ½ D (information such as height, slope, angle, …, is stored on a two-dimensional planar map), which could be explored using robotic analogies.

### Neurosymbolic Learning
Reasoning using symbols is powerful when describing innate patterns of features in a domain. It can also form the basis of eXplainable AI (XAI), which will become an essential topic for adoption of AI in every day decision-making. However, presenting such systems with raw data, e.g. pixels in an image, phonemes in sound, characters in a sentence and so forth overwhelms symbolic reasoners as there are simply too many potential patterns to consider for the computational resources available.
Instead, connectionist approaches, especially deep neural networks, have been shown to be excellent at determining important features and their relationships to environmental targets. Such end-to-end reasoning is impressive but has also been described as a locality sensitive hashing table. It doesn’t understand the underlying patterns.
* Neurosymbolic learning seeks to combine the ability to identify features from neuro-inspired connectionist techniques with the ability to learn about patterns using symbolic learning, but there are many questions in this nascent field on how best to achieve this fusion in a variety of domains.
* eXplainable AI (XAI) for real-world data, where data mining using symbolic learning needs to be made accessible for business and industry.

### Affective Robotics
Marvin Minsky, a pioneer in AI, raises the question whether a machine can be intelligent without emotions rather than having an intelligent machine expressing emotions. Affective robotics considers how analogues of emotion can be used to improve performance, especially in uncertain, unknown, dynamic and noisy domains where look up-table type approaches are likely to fail to discover identical previous experience.
It is noted that this field is controversial as the neuroscience basis for emotion itself still requires much research. Previous research has developed ‘hidden latent variables’ that that can be adaptively learnt to enable functionality equivalent to that considered useful in emotions
*This research would consider emotions as a warehouse to sort incoming signals based on their past, present and future values, cf an equivalence to PID controllers.

### Stroke Rehabilitation Robotics
Much of my research is forward-looking, blue-sky ideas, so it is worthwhile to consider a beneficial application. Namely, intelligent orthotics for stroke rehabilitation that learn the best strategies to help people affected by stroke. A prototype hardware system has been constructed, which ironically will take time to develop for medical approval.
* Design, mechatronics and manufacturing is needed to move the prototype up from TRL5, plus research to generate the AI to optimise rehabilitation programs.






