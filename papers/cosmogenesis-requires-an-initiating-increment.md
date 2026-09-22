---
layout: default
title: '[2026] Cosmogenesis Requires an Initiating Increment'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/cosmogenesis-requires-an-initiating-increment/
paper: true
---
{% raw %}
# [2026] Cosmogenesis Requires an Initiating Increment

*   **DOI:** [10.5281/zenodo.20405016](https://doi.org/10.5281/zenodo.20405016)
*   **Date:** May 27, 2026

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

\crefname{proposition}{Proposition}{Propositions}
\Crefname{proposition}{Proposition}{Propositions}
\crefname{definition}{Definition}{Definitions}
\Crefname{definition}{Definition}{Definitions}
\crefname{remark}{Remark}{Remarks}
\Crefname{remark}{Remark}{Remarks}

\setstretch{1.08}

\pagestyle{fancy}
\fancyhf{}
\setlength{\headheight}{14pt}
\lhead{Cosmogenesis Requires an Initiating Increment}
\rhead{John C. W. McKinley}
\cfoot{\thepage}

\newcounter{nogo}[section]
\renewcommand{\thenogo}{\thesection.\arabic{nogo}}
\newtheorem{proposition}{Proposition}
\newtheorem{definition}{Definition}
\newtheorem{remark}{Remark}
\makeatletter
\let\c@proposition\c@nogo
\let\c@definition\c@nogo
\let\c@remark\c@nogo
\makeatother

\title{\textbf{Cosmogenesis Requires an Initiating Increment}}
\author{John C. W. McKinley\,\orcidlink{0009-0005-7097-5035}}
\date{May 27, 2026}

\begin{document}
\maketitle

\blfootnote{\scriptsize This version published at \url{https://doi.org/10.5281/zenodo.20405016}.}

\begin{abstract}
Two prior results are taken as proven \cite{mckinley_9A, mckinley_1AC}: that no closed physical description internally fixes the onset of its own new causal chain; and that if a new causal chain begins, then its beginning requires an actual added increment of energy, denoted $\Delta E_{\mathrm{init}}$. The present paper applies those results to the limit case. If the closed physical description of the universe has a beginning, then its beginning required an actual added initiating increment. The argument is structural, not cosmological. It does not depend on any particular cosmological model and does not identify the ontology of the contributor. It states only that wherever the closed physical description has a beginning, the beginning required $\Delta E_{\mathrm{init}}$.
\end{abstract}

\section{Introduction}

Two prior results are taken as proven here. First, no closed physical description internally fixes the onset of its own new causal chain \cite{mckinley_9A}. Second, if a new causal chain begins, then its beginning requires an actual added increment of energy $\Delta E_{\mathrm{init}}$ \cite{mckinley_1AC}.

The present paper does not re-argue either claim. It applies them to a single case: the onset of the universe.

The claim defended here is narrow. If the closed physical description of the universe has a beginning---under any cosmological model that admits one---then by the prior results, that beginning required an actual added initiating increment. The argument does not require a particular interpretation of cosmogenesis. It applies to any onset at which the closed physical description does not yet contain anything earlier.

\section{Definitions}

\begin{definition}[Closed physical description]
A \emph{closed physical description} is a description containing only the laws, state-terms, and causal resources internal to the causal chain under discussion.
\end{definition}

\begin{definition}[Onset of the universe]
The \emph{onset of the universe} is the definite point at which the closed physical description of the universe begins, rather than not yet beginning. The present paper takes no position on which cosmological model identifies that onset; the claim applies to any model in which one exists.
\end{definition}

\begin{definition}[Initiating increment]
The \emph{initiating increment}, denoted $\Delta E_{\mathrm{init}}$, is the minimal actual added increment of energy required for the beginning of a new causal chain.
\end{definition}

\section{The Argument}

\begin{proposition}[The onset of the universe is not internally fixed]
\label{prop:cosmo-not-fixed}
The closed physical description of the universe does not internally fix the onset of its own beginning.
\end{proposition}

\begin{proof}
By prior result \cite{mckinley_9A}, no closed physical description internally fixes the onset of its own new causal chain. The closed physical description of the universe is a closed physical description. Its beginning is the onset of a new causal chain. Therefore the closed physical description of the universe does not internally fix the onset of its own beginning.
\end{proof}

\begin{proposition}[Cosmogenesis requires an initiating increment]
\label{prop:cosmo-increment}
If the universe has an onset, then that onset required an actual added initiating increment $\Delta E_{\mathrm{init}}$.
\end{proposition}

\begin{proof}
By \cref{prop:cosmo-not-fixed}, the closed physical description of the universe does not internally fix the onset of its own beginning. By prior result \cite{mckinley_1AC}, if a new causal chain begins, then its beginning requires an actual added increment of energy $\Delta E_{\mathrm{init}}$ not contained in the closed physical description of the chain. The onset of the universe is the beginning of such a chain. Therefore the onset of the universe required an actual added initiating increment $\Delta E_{\mathrm{init}}$.
\end{proof}

\section{Scope and Clarifications}

\begin{remark}[Model-independence]
The argument does not depend on any particular cosmological model. It applies to any model in which the closed physical description of the universe has an onset, including standard Big Bang cosmology, inflationary cosmology with a beginning, and any other model in which the closed physical description does not extend indefinitely backward. The argument does not apply to models in which the closed physical description has no onset at all.
\end{remark}

\begin{remark}[No ontology of the contributor is identified]
The present paper does not identify the ontology of whatever supplies $\Delta E_{\mathrm{init}}$ at cosmogenesis. It does not characterize the contributor, its persistence, its further properties, or any interpretation of its nature. Those are downstream questions. The result here is structural: wherever the closed physical description has a beginning, the beginning required an actual added initiating increment.
\end{remark}

\begin{remark}[Boundary of applicability]
The claim here is not that ordinary physics fails within already-running cosmological evolution. The claim is narrower. The closed physical description of the universe does not account for its own onset, and if that onset occurred, an actual added increment was required.
\end{remark}

\section{Falsifier}

The claim of this paper fails only if the universe has an onset and that onset occurred without any actual added increment of energy.

\section{Conclusion}

The prior results stand. Closed physical descriptions do not internally fix the onset of new causal chains; and if such a chain begins, then its beginning requires an actual added increment of energy $\Delta E_{\mathrm{init}}$. The present paper applies those results to the limit case. The closed physical description of the universe does not internally fix the onset of its own beginning. If the universe has an onset, then that beginning required an actual added initiating increment $\Delta E_{\mathrm{init}}$.

\begin{thebibliography}{9}

\bibitem{mckinley_9A}
J. C. W. McKinley, \emph{No Closed Physical System Internally Fixes the Onset and Direction of a New Causal Chain}, Zenodo, \href{https://doi.org/10.5281/zenodo.19464780}{10.5281/zenodo.19464780} (2026).

\bibitem{mckinley_1AC}
J. C. W. McKinley, \emph{The Initiating Increment: Why the Beginning of a New Causal Chain Requires an Actual Added Increment of Energy}, Zenodo, \href{https://doi.org/10.5281/zenodo.20369221}{10.5281/zenodo.20369221} (2026).

\end{thebibliography}

\end{document}
```

</details>

---
{% endraw %}
