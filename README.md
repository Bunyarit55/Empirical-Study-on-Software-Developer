Author

Bunyarit Sawasdee

Paper Title

An Empirical Study on Software Developer-Related Factors and Technical Debt in Open-Source Software Projects

Abstract

Technical debt reflects hidden issues in software that arise from software developers’ activities and remains a long-standing concern in software maintenance. While existing research has primarily focused on identifying and managing technical debt, less attention has been given to the influence of developer-related factors. This study investigates the relationships between developer activeness and developer experience and the accumulation of technical debt, measured through technical debt density in open-source software projects.

Using proposed metrics—including active contributors, developer experience, technical debt density, and technical debt management performance—we conducted a statistical analysis across 116 Python open-source repositories. The results reveal no evidence that the proportion of active contributors influences technical debt density. However, levels of developer experience are associated with the improvement of technical debt management performance. Specifically, highly experienced developers show less improvement compared to those with lower experience levels. Additional influences such as project status, developers’ perception of technical debt, and project practices may also contribute to the presence of technical debt in project code.

✅ Data Summary Tables

The following tables represent the updated dataset for the thesis version.

Table 4.2 — Repository Dataset Overview
Metric	Value
Total repositories analyzed	116
Programming language	Python
Minimum active development period	2 years
Technical debt extracted using	SonarQube
Metrics computed	TD Density, Active Contributor Percent
Time window	Latest stable release
Table 4.3 — Developer Dataset Overview
Metric	Value
Total developers analyzed	91
Developer selection method	Purposive sampling from repositories
Commits analyzed per developer	40 sampled commits
Data extracted	Commit history, previous commit, TD metrics
Experience calculation	Years of contribution (start year → latest year)
Table 4.4 — Developer Experience Grouping
Developer Group	Count	Experience Range
Low-experience developers	41	≤ 5 years
High-experience developers	50	> 5 years
Total	91	—
