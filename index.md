---
title: Home
layout: home
---
# Guardians of Gaia

## Problem Statement

### Target Learning Audience
The target learning audience for Guardians of Gaia is **middle and high school science students**.

### Identified Learning Need
Science instruction and simulations can often feel boring to many students as they can lack **engagement** and student **collaboration**. From my personal experiences, science labs and simulations can often feel as though they lack true discovery, limiting student motivation, engagement, and memory. As such, it is necessary to explore ways to increase engagement and collaboration in students, as well as a sense of discovery. Guardians of Gaia aims to combine these needs through a Tabletop Roleplaying Game (TTRPG) approach, using Dungeons and Dragons-based mechanics run by a multi-agent AI framework. This approach has been utilized in many disciplines such as history (e.g. Petousi, et al., 2025) and English (e.g. Ortolani and Ortolani, 2021), however I have yet to find examples of this approach being adapted at scale. This is most likely due to the nature of these types of games: they require a lot of work to maintain, create, and develop, most of which would fall to the teacher. As such, AI has an opportunity to fill the gap needed to alleviate this learning need.

### Rationale for AI Use
AI here will help with making the content engaging for students, as well as facilitating collaboration between students. Here AI will serve as a facilitator of the learning content as opposed to a creator of information. It should be noted here as well that to my knowledge there have yet to be platforms designed for learning where AI acts as the game master; there are platforms that can do this, however, they are not tailored towards education so there is an opportunity to create a platform for this need.

## Needfinding

### Context Description
The context examined was a large middle school science classroom with approximately 30 students and one teacher. Students are currently taking part in a unit about ecosystems. Students in this unit are expected to learn about ecosystem dynamics (e.g. population, food, biodiversity); the teacher is following New York State’s P-12 Learning Standards (https://www.nysed.gov/sites/default/files/programs/standards-instruction/ms-science-learning-standards.pdf) for the following learning goals:
- MS-LS2-2. Construct an explanation that predicts patterns of interactions among organisms in a variety of ecosystems.
- MS-LS2-5. Evaluate competing design solutions for maintaining biodiversity and protecting ecosystem stability.

The teacher has run this unit before, however struggled to maintain student interest in the subject, especially when it comes to running ecosystem simulations. In these simulations, students often work together in groups to explore how population changes in an ecosystem occur. These simulations are often done fairly quickly (~20 minutes) and are done on a computer. Students have an accompanying worksheet to complete with the simulation.

### Needfinding Method
To assess the problem an artifact analysis was conducted with simulations aimed at teaching ecosystem related concepts. A total of three resources were assessed:
- OpenSciEd 7.5 Ecosystem Dynamics (https://openscied.org/instructional-materials/7-5-ecosystem-dynamics/) 
- LS2. Ecosystems Lab (https://www.funsciencetools.org/middle-school-science/ls2-ecosystems)
- Forest Ecosystem (https://gizmos.explorelearning.com/find-gizmos/launch-gizmo?resourceId=639)

These resources were analyzed for the following criteria:
- Opportunity for collaboration
- Engagement
- Visuals
- Science Content (e.g. what aspects of science are used?)

### Key Findings
1. **Little to no collaboration**: While these resources can be used collaboratively, there is nothing about these resources that deliberately support collaboration. If these resources are to be used collaboratively, work is needed to be done by the teacher to adapt these materials for student collaboration. Additionally, if done collaboratively, these resources can create conditions for “free riders” where one or two students are doing the work.
1. **Not very engaging**: By themselves these simulations are pretty boring; engagement can be increased with an accompanying worksheet or storyline, such as in the case of OpenSciEd’s Orangutan themed case study and worksheet, but by themselves they are very unengaging. The visuals are pretty uninteresting and (at least to me) there is little reason for students to care. 
1. **Replicates scientific practices**: All three of the artifacts try to replicate scientific practices, such as graphing, changing variables, and running experiments. These are built into the simulations, and show the importance of the scientific method in these types of lessons.
1. **Guided**: These simulations are very heavily guided or it is assumed that there is a specific goal attached to these simulations. This means that there is no opportunity for exploration or experimentation.
1. **Simple**: All three simulations are very simple with limited interaction. Typically, there are one to four variables that the students can control. This is not necessarily a bad thing, but limits exploration and experimentation.

### Revised Need Statement
While the original need statement still holds true, there is a need for refinement as there are more nuanced reasons for the issues. 

Science simulations are often unengaging science; they are simple, guided, lack discovery, and lack collaboration.


## Literature Review

### Sources Reviewed
A total of four papers were reviewed, sourced from Consensus. The first paper (Smetana & Bell, 2012) is a literature focused on the effectiveness of computer simulations for science education. While an older paper, the findings highlight how the effectiveness of simulations in science education is dependent on the context in which they are used and the design of the simulation. More specifically Smetana and Bell (2012) argue that computer simulations are most effective when they supplement instruction, include support systems (e.g. animations, background information), and promote conceptual change (e.g. cognitive dissonance). This relates to my project by providing design directions for creating an effective AI-enhanced simulation. 

The second paper reviewed for this project was on using LLMs for the rapid development of physics simulations (Ben-Zion, et al., 2025). Here the authors present an approach for leveraging Claude to quickly create physics simulations and tested the effectiveness of the created simulations. This paper was selected because it presents an alternative AI solution to the one proposed for this project; it is effective however they still may exhibit the same limitations as existing science simulations. Here AI is not challenging the existing simulation space, just making the creation of simulations easier and more accessible.

The third paper reviewed presented a role-playing simulation game for increasing engagement in science-policy (van Beek, et al., 2022). The authors found that by making the situation more “real,” through role-playing games, there was higher engagement with the presented content. This is important as it can provide evidence for the role-play approach that I plan on employing for the project; role-playing games can assist with making students care about the material they are being presented with. It should be noted though that this paper focuses primarily on science-policy (e.g. climate change) rather than science instruction, so the applicability of this study to Guardians of Gaia may be limited. 

The final paper reviewed for this project reported findings for an experiment where students interacted with an LLM assisted science game (Chen & Chang, 2024). The study found that students who had access to the LLM while playing the game had lower cognitive load, higher intrinsic motivation, and higher performance than those without the AI tool. This is important to consider because it shows how LLMs when partnered with role playing games can enhance game-based learning in science education.

### Key Ideas from Literature
Across the different sources a total of three key themes emerged that are relevant to Guardians of Gaia. The first theme that emerged was the importance of instruction. Science simulations should be a supplement to instruction, not a replacement (Smetana & Bell, 2012). This was a noted limitation in Ben-Zion, et al. 's, approach (2025), as by themselves the generated simulations are fairly limited and lack embedded pedagogical content knowledge (p. 424).

The second theme that emerged was the need for support systems and scaffolding. Similar to the first theme, simulations are enhanced when there exists appropriate scaffolding (Smetana & Bell, 2012); simulations should be enhanced by including background information or context, conceptual development guidance (Ben-Zion, et al., 2025), feedback (Chen & Chang, 2024), etc. 

The final theme that emerged was role-playing as a way to increase engagement. As noted by Ben-Zion, et al., (2025), a limitation of their developed simulations is that they lack structured student engagement. Role-playing elements may provide a solution to that, as found with van Beek, et al., (2022), as using role-playing elements in their climate change simulation made the problems feel more real and in turn increased learner engagement with the material.

### Existing Solutions and Their Limitations
The main gap that was identified with the reviewed literature is that the use of AI in science simulations is rather limited. For one, searching for literature and tools in this space was rather difficult as there are not a lot of existing resources available; I believe this may have to do with the rather new nature of the topic. Additionally, the use of AI that I was able to find either had to do with the creation of simulations (e.g. Ben-Zion, et al., 2025) or were used as a supplement to existing science simulations (e.g. Chen & Chang, 2024). There were no resources that I identified that truly leveraged the transformational nature of AI and utilized its capabilities for supporting effective simulation design.

Another gap that I identified is the lack of teacher support. As noted by Smetana & Bell (2012), teacher preparedness is a common gap in science simulation literature; teachers have a huge impact on the effectiveness of simulations, so care must be taken to support their use and understanding of created tools. While, some implied care is taken by Ben-Zion, et al., (2025) as their work is about the creation of science simulations, the same care is not taken by the other studies, as teachers and classroom implementation are not discussed. 

### Implications for Project
Two design implications have been identified from the literature. The first is the need for support materials; to better scaffold and support this project, I believe that there will be a need to develop materials to structure and scaffold the system. An initial idea I have that may meet this is to create and provide an accompanying worksheet that the learners will need to complete while using the system. 

The second implication that has been identified is the need for teacher support. Ideally, the system should provide a lot of teacher control, but should not be difficult to use in a classroom. 


## Works Cited
Ben-Zion, Y., Zarzecki, R. E., Glazer, J., & Finkelstein, N. D. (2025). Leveraging AI for rapid generation of physics simulations in education: Building your own virtual lab. The Physics Teacher, 63(6), 424-427.

Chen, C. H., & Chang, C. L. (2024). Effectiveness of AI-assisted game-based learning on science learning outcomes, intrinsic motivation, cognitive load, and learning behavior. Education and Information Technologies, 29(14), 18621-18642.

Ortolani, K., & Ortolani, A. (2021). GAMES-BASED LEARNING: AN EXPERIENCE REPORT IN TEACHING ENGLISH DURING THE PANDEMIC. Matraga - Revista do Programa de Pós-Graduação em Letras da UERJ, 28.

Petousi, D., Katifori, A., Sakellariadis, P., Servi, K., Kougioumtzian, L., Koutiva, G., Roussou, M., & Ioannidis, Y. (2025). The Intersection of Play and History: Integrating Historical Content in Tabletop Role-Playing Games for Education. Proceedings of the 20th International Conference on the Foundations of Digital Games. https://doi.org/10.1145/3723498.3723811.

Smetana, L. K., & Bell, R. L. (2012). Computer simulations to support science instruction and learning: A critical review of the literature. International Journal of Science Education, 34(9), 1337-1370.

van Beek, L., Milkoreit, M., Prokopy, L., Reed, J. B., Vervoort, J., Wardekker, A., & Weiner, R. (2022). The effects of serious gaming on risk perceptions of climate tipping points. Climatic Change, 170(3), 31.
--

Guardians of Gaia is created by Jaycee Sansom

[Just the Docs]: https://just-the-docs.github.io/just-the-docs/
[GitHub Pages]: https://docs.github.com/en/pages
[README]: https://github.com/just-the-docs/just-the-docs-template/blob/main/README.md
[Jekyll]: https://jekyllrb.com
[GitHub Pages / Actions workflow]: https://github.blog/changelog/2022-07-27-github-pages-custom-github-actions-workflows-beta/
[use this template]: https://github.com/just-the-docs/just-the-docs-template/generate
