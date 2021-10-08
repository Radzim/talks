---
title: "Access, Assess and Address: A Pipeline for (Automated?) Data Science"
abstract: |
  Data Science is an emerging discipline that is being promoted as a universal panacea for the world’s desire to make better informed decisions based on the wealth of data that is available in our modern interconnected society. In practice data science projects often find it difficult to deliver. In this talk we will review efforts to drive data informed in real world examples, e.g., the UK’s early Covid19 pandemic response. We will introduce a framework for categorising the stages and challenges of the data science pipeline and relate it to the challenges we see when giving data driven answers to real world questions. We will speculate on where automation may be able to help but emphasise that automation in this landscape is challenging when so many issues remain for getting humans to do the job well.
author:
- family: Lawrence
  given: Neil D.
  gscholar: r3SJcvoAAAAJ
  institute: University of Cambridge
  twitter: lawrennd
  url: http://inverseprobability.com
blog: 
date: 2021-09-13
venue: "ECML Workshop on Automating Data Science"
transition: None
---


\include{_data-science/includes/lies-damned-lies.md}

\include{_delve/includes/delve-overview.md}

\subsection{What is Machine Learning?}

$$ \text{data} + \text{model} \stackrel{\text{compute}}{\rightarrow} \text{prediction}$$




\include{_data-science/includes/big-data-paradox.md}
\include{_data-science/includes/big-model-paradox.md}
\include{_policy/includes/diane-coyle-fitzwilliam-lecture.md}

\include{_policy/includes/data-as-a-convener.md}

\section{Delve}

\include{_delve/includes/delve-report-list.md}

\notes{There is lots of hope for the role data science and AI could play, but we’re still a way off from being AI-ready. Further attention is needed on some of the foundational issues around data use – access, skills, culture – before we can begin to talk in earnest about deploying AI. [link here to data readiness]}

\include{_delve/includes/delve-data-report.md}
\include{_delve/includes/data-report-recommendations.md}

\notes{Delivering a rapid response requires the ability to quickly convene teams from across disciplines (and often institutions) around a key question. To facilitate this, we also used ideas from \addblog{open data science}{2014/07/01/open-data-science} to facilitate communication and understanding.}

\include{_data-science/includes/access-assess-address.md}

\subsection{Conclusions}

\slides{* Bandwidth constraints of humans
* Big Data Paradox
* Big Model Paradox
* Data as a Convener
* Decomposition of Complex Models
}

\notes{The particular circumstances of the Covid-19 pandemic have highlighted the challenges of integrating scientific ideas to answer policy questions. In this talk, we've given a formal introduction to the problem, the difficulty of communicating between individuals (particularly from different domains) and reviewed the ideas and solutions we used in the Delve initiative.}

\notes{Recommendations from the DELVE Data report suggest that more effort needs to be placed into working in this manner in normal circumstances, so that when an emergency occurs we are better prepared to deal with the questions we face.}

\notes{When we combine these difficult challenges with complex models, we need to put more effort into decomposing our models so that they may be calibrated and re-integrated at appropriate fidelities.}

\thanks

\references