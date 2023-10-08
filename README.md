>REPs* are clearly defined cookbooks allowing us to scale & measure the implementation of reliability practices

*REP: Reliability Enhancing Procedures

# REPs create clear delivables for the engineers
You cannot ask hundreds/thousand of engineers to implement SRE, chaos engineering, or other practices. You would get hundreds/thousand of different incompatible interpretations. The REPs, no matter how you define them, allow everyone to speak the same language, to understand the requirements, and to read the deliverables provides by others.

When we started our journey at Swisscom, we had quite many interpretation of SRE for all type of things. Let's take SLO as a case study.
What is a service the SLO refer to ? Is than a agregation of many smaller user journeys (SLI) into a bigger chunk called SLO ? No. Do we have plenty of "SLO" for every services for all the user journeys they serve ? All the above and more (SLA=SLO ?!?) was in used. Speaking the same language is really key here. Hence a unified service modeling (REP1) and SLO implementation (REP5).

REPs a a way to align through the large enterprise on key aspects tied to reliability.

Everyone has now the **same definition of SLO**: An SLO informed in real time the health of a specific user journey and can be mesure by one or more indicator (SLI). A service is a bundle of user journeys grouped in different features. So Service 1:n features 1:n **user journey 1:1 SLO** 1:n SLI
When you work on SLO, you speak about implement REP5 with its clear structure, its training, and the links to the tools that support you!
