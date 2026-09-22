---
layout: default
title: '[2026] An Inert Contribution Does Not Begin a Causal Chain: A Structural No-Go Result'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/an-inert-contribution-does-not-begin-a-causal-chain-a-structural-no-go-result/
paper: true
---
{% raw %}
# [2026] An Inert Contribution Does Not Begin a Causal Chain: A Structural No-Go Result

*   **DOI:** [10.5281/zenodo.20351786](https://doi.org/10.5281/zenodo.20351786)
*   **Date:** May 23, 2026

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
\usepackage{fancyhdr}

\PassOptionsToPackage{capitalise,nameinlink,noabbrev}{cleveref}
\usepackage[colorlinks=true,linkcolor=blue,citecolor=blue,urlcolor=blue]{hyperref}
\usepackage{cleveref}

\crefname{proposition}{Proposition}{Propositions}
\Crefname{proposition}{Proposition}{Propositions}
\crefname{lemma}{Lemma}{Lemmas}
\Crefname{lemma}{Lemma}{Lemmas}
\crefname{remark}{Remark}{Remarks}
\Crefname{remark}{Remark}{Remarks}
\crefname{definition}{Definition}{Definitions}
\Crefname{definition}{Definition}{Definitions}
\crefname{corollary}{Corollary}{Corollaries}
\Crefname{corollary}{Corollary}{Corollaries}
\crefname{premise}{Premise}{Premises}
\Crefname{premise}{Premise}{Premises}

\usepackage{orcidlink}

\newcommand\blfootnote[1]{%
  \begingroup
  \renewcommand\thefootnote{}\footnote{#1}%
  \addtocounter{footnote}{-1}%
  \endgroup
}

\setstretch{1.08}

\pagestyle{fancy}
\fancyhf{}
\setlength{\headheight}{14pt}
\lhead{An Inert Contribution Does Not Begin a Chain}
\rhead{John C. W. McKinley}
\cfoot{\thepage}

\newcounter{nogo}[section]
\renewcommand{\thenogo}{\thesection.\arabic{nogo}}
\newtheorem{proposition}{Proposition}
\newtheorem{lemma}{Lemma}
\newtheorem{remark}{Remark}
\newtheorem{definition}{Definition}
\newtheorem{corollary}{Corollary}
\newtheorem{premise}{Premise}
\makeatletter
\let\c@proposition\c@nogo
\let\c@lemma\c@nogo
\let\c@remark\c@nogo
\let\c@definition\c@nogo
\let\c@corollary\c@nogo
\let\c@premise\c@nogo
\makeatother

\title{\textbf{An Inert Contribution Does Not Begin a Causal Chain:\\
A Structural No-Go Result}}
\author{John C. W. McKinley\,\orcidlink{0009-0005-7097-5035}}
\date{May 23, 2026}

\begin{document}
\maketitle

\blfootnote{\scriptsize This version published at \url{https://doi.org/10.5281/zenodo.20351786}.}

\begin{abstract}
Two prior results are taken as proven \cite{mckinley_9A, mckinley_19A}: no closed physical system internally fixes the onset and direction of its own new causal chain among multiple lawful possibilities, and if such a chain nonetheless begins, then a non-internal contribution exists. The present paper states a structural no-go on candidates for that contribution. No inert candidate can satisfy the role of the non-internal contribution required for the beginning of a new causal chain. A candidate that is merely present, or otherwise established to exist, but is not among what brings the onset about, is not the contribution required by the prior result. The prior result establishes that a non-internal contribution exists; the present result excludes inert candidates from filling that role.
\end{abstract}

\section{Introduction}

Two prior results are taken as proven here. First, no closed physical system internally fixes the onset and direction of its own new causal chain among multiple lawful possibilities \cite{mckinley_9A}. Second, if such a chain nonetheless begins, then a non-internal contribution exists \cite{mckinley_19A}.

Those results establish that a contribution exists but do not settle the character of that contribution. The present paper states one constraint, as a denial: no inert candidate can satisfy the role of the non-internal contribution required for the beginning of the chain. The argument rests on two cited prior results and the definitions below; it is structural and interpretive, and alters no equation of standard physics.

\section{Definitions}

\begin{definition}[Closed physical description]
A \emph{closed physical description} is a description containing only the laws, state-terms, and causal resources internal to the causal chain under discussion.
\end{definition}

\begin{definition}[New causal chain]
A \emph{new causal chain} is a chain whose onset is the issue under discussion, rather than a process already underway and simply continuing under known laws.
\end{definition}

\begin{definition}[Non-internal contribution]
A \emph{non-internal contribution} is a contribution that is not contained within the closed physical description. This is the \emph{contribution in question}: the contribution whose existence at the onset of a new causal chain is established by the prior result \cite{mckinley_19A}.
\end{definition}

\begin{definition}[Efficacious toward the onset]
A contribution is \emph{efficacious toward the onset} if it is among what brings the onset about: among what makes the transition from not-yet-beginning to beginning occur.
\end{definition}

\begin{definition}[Inert toward the onset]
A contribution is \emph{inert toward the onset} if it is present, or is otherwise established to exist, but is not among what brings the onset about.
\end{definition}

\section{The No-Go}

\begin{proposition}[No-go on inert candidates]
\label{prop:nogo-inert-candidates}
No inert candidate can satisfy the role of the non-internal contribution required for the beginning of a new causal chain.
\end{proposition}

\begin{proof}
By \cite{mckinley_19A}, if a new causal chain begins where the closed physical description does not internally fix its onset and direction, then a non-internal contribution exists. The role of that contribution is to account for the chain's beginning. A candidate contribution that is inert toward the onset is not among what brings the onset about. It therefore cannot satisfy the role of the contribution required for the chain's beginning. Hence no inert candidate can satisfy the role of the required non-internal contribution.
\end{proof}

\section{Falsifier}

The claim fails if a new causal chain begins where the non-internal contribution required to account for its beginning is established to be inert toward the onset.

\section{Conclusion}

No inert candidate can satisfy the role of the non-internal contribution required for the beginning of a new causal chain. The prior results establish that such a contribution exists. The present result excludes a merely present or inert candidate from filling that role. The required contribution must be efficacious toward the onset.

\begin{thebibliography}{9}

\bibitem{mckinley_9A}
J. C. W. McKinley, \emph{No Closed Physical System Internally Fixes the Onset and Direction of a New Causal Chain}, Zenodo, \href{https://doi.org/10.5281/zenodo.19464780}{10.5281/zenodo.19464780} (2026).

\bibitem{mckinley_19A}
J. C. W. McKinley, \emph{If a New Causal Chain Begins, a Non-Internal Contribution Exists}, Zenodo, \href{https://doi.org/10.5281/zenodo.19752798}{10.5281/zenodo.19752798} (2026).

\end{thebibliography}

\end{document}
```

</details>

---
{% endraw %}
