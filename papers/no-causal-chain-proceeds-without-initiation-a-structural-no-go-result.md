---
layout: default
title: '2026 No Causal Chain Proceeds Without Initiation: A Structural No-Go Result'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/no-causal-chain-proceeds-without-initiation-a-structural-no-go-result/
paper: true
---
{% raw %}
# 2026 No Causal Chain Proceeds Without Initiation: A Structural No-Go Result

* **DOI:** [10.5281/zenodo.20263606](https://doi.org/10.5281/zenodo.20263606)

* **Date:** May 17, 2026

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
\lhead{No Causal Chain Proceeds Without Initiation}
\rhead{John C. W. McKinley}
\cfoot{\thepage}

\newtheorem{proposition}{Proposition}
\newtheorem{definition}{Definition}

\title{\textbf{No Causal Chain Proceeds Without Initiation:\\ A Structural No-Go Result}}
\author{John C. W. McKinley\,\orcidlink{0009-0005-7097-5035}}
\date{May 17, 2026}

\begin{document}
\maketitle

\blfootnote{\scriptsize This version published at \url{https://doi.org/10.5281/zenodo.20263607}.}

\begin{abstract}
This note states a structural no-go. No causal chain proceeds without an initiation: an occurrence within the chain that is not derived from any prior occurrence within the chain. Derivation transmits occurrence; it does not generate it. A chain in which every occurrence is derived supplies no occurrence to derive from.
\end{abstract}

\section{Definitions}

\begin{definition}[Causal chain]
A \emph{causal chain} is a sequence of events in which each event's occurrence is derived from the occurrence of its predecessor in the chain.
\end{definition}

\begin{definition}[Derivation]
An event's occurrence is \emph{derived} from a prior event's occurrence when the prior event's occurrence brings the later event's occurrence about. Derivation transmits occurrence; it does not generate it.
\end{definition}

\begin{definition}[Initiation]
The \emph{initiation} of a causal chain is an occurrence within the chain that is not derived from any prior occurrence within the chain.
\end{definition}

\begin{definition}[Proceed]
A causal chain \emph{proceeds} when its events occur in sequence.
\end{definition}

\section{The Structural Claim}

\begin{quote}
\textbf{Core Thesis.} No causal chain proceeds without initiation.
\end{quote}

\begin{proposition}[No-go on uninitiated chains]
No causal chain proceeds without an initiation.
\end{proposition}

\begin{proof}
Assume for contradiction that a causal chain proceeds without an initiation. Then every occurrence in the chain is derived from a prior occurrence within the chain.

Derivation transmits occurrence; it does not generate it. Each occurrence therefore presupposes a prior occurrence from which it is derived, and that prior occurrence is itself derived from a further prior occurrence, without end.

Every occurrence in the chain is therefore a derivation, with no underived occurrence at any point. A totality composed only of derivations supplies no underived occurrence from which any derivation can begin. The chain supplies no occurrence to derive from, contradicting the assumption that it proceeds as a causal chain without initiation.

Therefore no causal chain proceeds without an initiation.
\end{proof}

\section{Falsifier}
The claim fails only if a causal chain is exhibited whose events occur in sequence, each occurrence derived from a prior occurrence within the chain, yet no occurrence in the chain is underived.

\section{Conclusion}

No causal chain proceeds without an initiation. A chain of pure transmission supplies no occurrence to transmit.
\end{document}
```

</details>

---
{% endraw %}
