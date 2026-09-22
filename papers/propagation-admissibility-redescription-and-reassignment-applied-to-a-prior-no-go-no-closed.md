---
layout: default
title: '[2026] Propagation, Admissibility, Redescription, and Reassignment Applied to a Prior No-Go — No Closed Physical System Internally Fixes the Onset and Direction of a New Causal Chain'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/propagation-admissibility-redescription-and-reassignment-applied-to-a-prior-no-go-no-closed/
paper: true
---
{% raw %}
# [2026] Propagation, Admissibility, Redescription, and Reassignment Applied to a Prior No-Go — No Closed Physical System Internally Fixes the Onset and Direction of a New Causal Chain

*   **DOI:** [10.5281/zenodo.20253135](https://doi.org/10.5281/zenodo.20253135)
*   **Date:** May 19, 2026

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

\documentclass[12pt,onecolumn]{article}

\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage{lmodern}
\usepackage[margin=1in]{geometry}
\usepackage{microtype}
\usepackage{setspace}
\usepackage{amsmath,amssymb,amsthm}


\newcommand\blfootnote[1]{%
  \begingroup
  \renewcommand\thefootnote{}\footnote{#1}%
  \addtocounter{footnote}{-1}%
  \endgroup
}


\PassOptionsToPackage{capitalise,nameinlink,noabbrev}{cleveref}
\usepackage[colorlinks=true,linkcolor=blue,citecolor=blue,urlcolor=blue]{hyperref}
\usepackage{cleveref}
\usepackage{orcidlink}

\usepackage{fancyhdr}

\setstretch{1.08}

\pagestyle{fancy}
\fancyhf{}
\setlength{\headheight}{14pt}
\lhead{Propagation, Admissibility, Redescription, Reassignment}
\rhead{John C. W. McKinley}
\cfoot{\thepage}

\newtheorem{proposition}{Proposition}
\newtheorem{lemma}{Lemma}
\newtheorem{definition}{Definition}
\newtheorem{remark}{Remark}

\title{\textbf{Propagation, Admissibility, Redescription, and Reassignment Applied to a Prior No-Go --- No Closed Physical System Internally Fixes the Onset and Direction of a New Causal Chain}}
\author{John C. W. McKinley\,\orcidlink{0009-0005-7097-5035}}
\date{May 19, 2026}

\begin{document}
\maketitle

\begingroup
\renewcommand{\thefootnote}{}
\footnotetext{This version published at \href{https://doi.org/10.5281/zenodo.20253135}{https://doi.org/10.5281/zenodo.20253135}.}
\endgroup

\begin{abstract}
A prior result is taken as proven \cite{mckinley_9A}: no closed physical system internally fixes the onset and direction of a new causal chain among multiple lawful possibilities. The present paper develops that result. It distinguishes propagation of processes underway from onset of a new causal chain, admissibility of multiple lawful paths from determination of the path taken, and redescription of a given onset or direction from determination of that onset or direction; and it establishes a reassignment lemma: reassigning the onset or direction of a new causal chain to a prior internal step merely pushes the determination question to that prior step without discharging it.
\end{abstract}

\section{Introduction}

The prior result establishes a structural no-go: no closed physical system internally fixes the onset and direction of a new causal chain among multiple lawful possibilities \cite{mckinley_9A}. This result is taken as proven here.

The present paper develops the prior result. It distinguishes propagation, admissibility, and redescription from internal fixation, and it establishes a reassignment lemma covering both onset and direction.


\section{Definitions}

\begin{definition}[Closed physical description]
A \emph{closed physical description} is a description containing only the laws, state-terms, and causal resources internal to the causal chain under discussion.
\end{definition}

\begin{definition}[New causal chain]
A \emph{new causal chain} is a chain whose onset is the issue under discussion, rather than a process already underway and simply continuing under known laws.
\end{definition}

\begin{definition}[Onset]
The \emph{onset} of a new causal chain is the definite point at which that chain begins rather than not yet beginning.
\end{definition}

\begin{definition}[Direction]
The \emph{direction} of a new causal chain is the particular lawful path taken among multiple physically admissible alternatives.
\end{definition}

\begin{definition}[Internal fixation]
A closed physical description \emph{internally fixes} onset or direction if it determines the relevant item from within the closed description itself.
\end{definition}

\begin{definition}[Redescription]
\label{def:redescription}
A \emph{redescription} of an actual onset or direction is a re-expression of that onset or direction in alternative or finer-grained internal vocabulary within the same closed physical description, without the introduction of any further causal resource.
\end{definition}

\section{Propagation, Admissibility, and Redescription}

\begin{remark}[Propagation is not onset]
\label{remark:propagation-not-onset}
A closed physical description may govern the evolution of a process once the process is underway. That is not the same as determining the onset of a new process.
\end{remark}

\begin{remark}[Admissibility is not actual direction]
\label{remark:admissibility-not-direction}
A closed physical description may contain multiple lawful paths, and it may structure, weight, pre-order, or differentiate them. None of this is the same as determining which path is taken.
\end{remark}

\begin{remark}[Redescription is not determination]
A redescription, in the sense of \cref{def:redescription}, may express the actual onset or direction in more detailed internal vocabulary without thereby determining onset or direction from within the closed description.
\end{remark}

\section{The Reassignment Lemma}

Let $S(t)$ be a closed physical description of a new causal chain over an interval during which multiple lawful continuations remain open. Denote its onset by $t^\ast$ and its realized path by the continuation actually taken.

\begin{lemma}[Prior-step reassignment does not determine onset or direction]
\label{lemma:reassignment}
Reassigning the determination of onset or direction to a prior internal step does not supply internal fixation.
\end{lemma}

\begin{proof}
If the proposed fixing step lies on the new causal chain itself, it is not earlier than that chain's onset; it cannot fix what it is part of. If the proposed fixing step is earlier than the chain, it lies outside the closed chain under discussion and is therefore a non-internal contribution rather than internal fixation. In neither case has the onset or direction of the new causal chain been internally fixed.
\end{proof}

\section{The No-Go in Fuller Form}

\begin{proposition}[No-go for internal fixation, fuller form]
\label{prop:nogo-fuller}
Let $S(t)$ be a closed physical description of a new causal chain. Then $S(t)$ does not internally fix both the onset and direction of that chain, and reassignment to prior internal structure does not supply internal fixation.
\end{proposition}

\begin{proof}
The structural no-go is established in \cite{mckinley_9A} and is taken as proven here. The present claim adds that reassignment to prior internal structure does not supply internal fixation. By \cref{remark:propagation-not-onset}, propagation is not onset. By \cref{remark:admissibility-not-direction}, admissibility is not actual direction. By \cref{lemma:reassignment}, reassigning onset or direction to a prior internal step does not determine onset or direction. Therefore the closed description does not internally fix both the onset and direction of a new causal chain, and reassignment to prior internal structure leaves that conclusion in force.
\end{proof}

\section{Falsifier}

The fuller-form claim of this paper fails only if a closed physical description is exhibited that internally determines both the onset of a new causal chain and its actual direction among multiple lawful alternatives.

\section{Conclusion}
A closed physical description does not internally fix both the onset and direction of a new causal chain. Reassignment to prior internal structure does not supply internal fixation.


\begin{thebibliography}{9}

\bibitem{mckinley_9A}
J. C. W. McKinley, \emph{No Closed Physical System Internally Fixes the Onset and Direction of a New Causal Chain}, Zenodo, \href{https://doi.org/10.5281/zenodo.19464780}{10.5281/zenodo.19464780} (2026).

\end{thebibliography}

\end{document}
```

</details>

---
{% endraw %}
