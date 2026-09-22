---
layout: default
title: '[2026] Spacetime Changes Can Be Counted; Photons Cannot: A No-Go Result on Photon-Object Inventory'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/spacetime-changes-can-be-counted-photons-cannot-a-no-go-result-on-photon-object-inventory/
paper: true
---
{% raw %}
# [2026] Spacetime Changes Can Be Counted; Photons Cannot: A No-Go Result on Photon-Object Inventory
* **DOI:** [10.5281/zenodo.20113982](https://doi.org/10.5281/zenodo.20113982)
* **Date:** 12 May 2026

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\PassOptionsToPackage{capitalise,nameinlink,noabbrev}{cleveref}
\documentclass[12pt,onecolumn]{article}

\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage{lmodern}
\usepackage[margin=1in]{geometry}
\usepackage{setspace}
\usepackage{microtype}
\usepackage{amsmath,amssymb,amsthm}
\usepackage{bm}
\usepackage{graphicx}
\usepackage{tikz}
\usepackage[numbers,sort&compress]{natbib}
\usepackage[colorlinks=true,linkcolor=blue,citecolor=blue,urlcolor=blue]{hyperref}

\newcommand{\doi}[1]{\href{https://doi.org/#1}{#1}}

\newtheorem{proposition}{Proposition}[section]
\newtheorem{definition}[proposition]{Definition}
\newtheorem{lemma}[proposition]{Lemma}
\newtheorem{corollary}[proposition]{Corollary}
\newtheorem{remark}[proposition]{Remark}

\usepackage{cleveref}
\usepackage{orcidlink}
\usepackage{fancyhdr}
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
\lhead{Spacetime Changes Can Be Counted; Photons Cannot}
\rhead{John C. W. McKinley}
\cfoot{\thepage}

\title{\textbf{Spacetime Changes Can Be Counted; Photons Cannot}\\
\large A No-Go Result on Photon-Object Inventory}
\author{John C. W. McKinley\,\orcidlink{0009-0005-7097-5035}}
\date{May 10, 2026}

\begin{document}

\maketitle

\blfootnote{\scriptsize This version prepared for Zenodo. DOI: \href{https://doi.org/10.5281/zenodo.20113982}{10.5281/zenodo.20113982}.}

\begin{abstract}
Spacetime-side changes are countable. Photon-objects are not. A detector may register events, an apparatus may record absorptions, and a field-state description may assign an occupation number. But these are counts of records, changes, or representation-relative quantities. They are not counts of persisting photon-objects. In standard relativistic physics, the photon has null proper time and no rest frame. The Timeless Light Model treats those standard constraints as ontologically restrictive rather than as harmless formal curiosities: no photon rest frame means no defined photon object-location, no intermediate location, no trajectory, and no transit. This paper states a narrow two-pronged no-go result: photon-object inventory is not licensed by the null constraints; and even if licensed, any closed photon-object quantity would import a census frame foreign to the null case. Ordinary photon-counting practice is preserved. Endpoint records remain countable. State-relative photon-number descriptions remain valid. What fails is the stronger claim that there exists a completed stock of photon-things in flight.
\end{abstract}

\section{Introduction}

The phrase ``one photon'' is useful. The phrase ``two detector events'' is useful. The phrase ``an \(N\)-photon state'' is useful. None of these expressions should be erased from physics.

The question is what these expressions count.

This paper argues that spacetime-side changes may be counted, but photons are not countable as persisting objects. The distinction is not semantic. It follows from taking the standard null constraints seriously. In standard relativistic physics, a photon has null proper time and no rest frame~\cite{Einstein1905,Wald1984}. TLM refuses to treat those facts as decorative formalities. If the photon has no rest frame, then no photon object-location, intermediate position, trajectory, or transit is licensed. The photon is therefore not a particle in transit, but a lawfully admissible charge-state relation whose spacetime appearance is a lawful change~\cite{McKinleyBedrock}.

The present paper does not modify Special Relativity, General Relativity, quantum mechanics, or quantum field theory. It imposes an interpretive restriction:

\begin{quote}
Do not convert countable spacetime-side changes into a completed inventory of photon-objects.
\end{quote}

The no-go result is narrow. It does not deny detections. It does not deny absorptions. It does not deny emission records. It does not deny state-relative photon-number descriptions. It denies only the extra ontology of a counted photon-stock in between.

The purpose of this note is therefore to preserve ordinary photon-counting practice while blocking a stronger ontological inference. Detector records, absorption events, source-side changes, and state-relative occupation numbers may be counted. A persisting photon-object in spacetime may not be inventoried, because standard null constraints license no such object.

\section{Definitions}

\begin{definition}[Spacetime appearance]
A spacetime appearance is the manifestation of a lawfully admissible charge-state relation as a lawful change within spacetime description.
\end{definition}

\begin{definition}[Spacetime-side change]
A spacetime-side change is the emission-side, absorption-side, detector-side, or measured transition through which the spacetime appearance is described.
\end{definition}

\begin{definition}[Spacetime-side record]
A spacetime-side record is a discrete registration of a spacetime-side change, including a detector click, absorption record, emission-side label, measured transition, or state-relative number assignment.
\end{definition}

\begin{definition}[Photon-object]
A photon-object is a supposed persisting item located in spacetime, possessing intermediate presence between emission and absorption.
\end{definition}

\begin{definition}[Photon-object inventory]
A photon-object inventory is a closed stock of persisting photon-things:
\[
|\Gamma|=N,
\]
where \(\Gamma\) is treated as a bounded set of photon-objects.
\end{definition}

\begin{definition}[Census frame]
A census frame is the standpoint required to treat a domain as a completed inventory. It supplies a boundary, an inclusion rule, an exclusion rule, and a completed count condition.
\end{definition}

\begin{definition}[Charge-state relation]
A charge-state relation is the lawful relation underlying what spacetime description renders process-wise as emission, absorption, or transfer.
\end{definition}

\section{Spacetime-Side Changes Are Countable}

\begin{proposition}[Spacetime-side changes may be counted]
Spacetime-side changes may be counted as detector records, endpoint events, or representation-relative state quantities.
\end{proposition}

\begin{proof}
A detector record is a spacetime-side event. If an apparatus records \(N\) such events, then \(N\) records have occurred within the measurement arrangement. Likewise, a specified field-state description may assign an occupation number relative to its chosen representation. In both cases, the count attaches to a spacetime-side record, change, or formal state description. Therefore spacetime-side changes may be counted.
\end{proof}

\begin{remark}
The claim is not that photon-counting language is useless. The claim is that one must identify what is being counted.
\end{remark}

\begin{proposition}[Counting spacetime-side changes does not imply counting photon-objects]
A count of spacetime-side changes does not imply a count of persisting photon-objects.
\end{proposition}

\begin{proof}
A spacetime-side change is a recorded event, measured transition, or state-relative description. A photon-object is a supposed persisting item located between endpoints. The first is supplied by spacetime-side measurement or representation. The second is an additional ontology. Therefore a count of spacetime-side changes does not imply a count of photon-objects.
\end{proof}

\section{The Null Constraint}

The central physical point is not proprietary to TLM. Standard relativistic physics already assigns the photon null proper time and no rest frame. TLM's contribution is the interpretive discipline of refusing to reinsert an object-in-flight after those constraints have removed the conditions for one.

The minimal chain is:

\[
\begin{aligned}
d\tau=0 \;&\Rightarrow\; \text{no photon rest frame} \\
&\Rightarrow\; \text{no defined photon object-location} \\
&\Rightarrow\; \text{no intermediate location} \\
&\Rightarrow\; \text{no trajectory} \\
&\Rightarrow\; \text{no transit}.
\end{aligned}
\]

The first two links are standard. The later links state the interpretive consequence enforced here. A located object requires location predicates. A persisting traveler requires intermediate states. A trajectory requires ordered occupancy. A transit story requires a carrier to be in transit. The null case supplies none of these for the photon as an object.

\begin{proposition}[No located photon-object]
The photon is not licensed as a located object in spacetime.
\end{proposition}

\begin{proof}
A located object in spacetime requires spatial predicates sufficient for location, intermediate position, and persistence across a sequence of states. In standard relativity, the photon has null proper time and no rest frame. Without a rest frame, the photon does not possess object-location predicates in the sense required for a persisting item. Without object-location predicates, no intermediate location is licensed. Without intermediate location, no trajectory is licensed. Without trajectory, no transit is licensed. Therefore the photon is not licensed as a located object in spacetime.
\end{proof}

\begin{corollary}[What has no object-location is not here]
If the photon has no defined location as an object in spacetime, then it is not a thing here, there, or halfway.
\end{corollary}

\begin{proof}
The predicates ``here,'' ``there,'' and ``halfway'' are location predicates. If location is not defined for the photon as an object, those predicates do not apply to the photon as an object. Therefore the photon is not here, there, or halfway.
\end{proof}

\begin{remark}
This does not deny that spacetime descriptions contain endpoint labels, null relations, field modes, detector records, or measured changes. It denies that such descriptions license an occupied intermediate history.
\end{remark}

\section{The First No-Go: No Photon-Object Count}

\begin{proposition}[Photon-objects cannot be counted]
Photon-objects cannot be counted because the photon-object is not licensed.
\end{proposition}

\begin{proof}
To count photon-objects, there must be photon-objects. A photon-object, as defined here, is a persisting located item in spacetime. By the preceding result, the photon is not licensed as a located object in spacetime. Therefore the required object of the count is absent. Hence photon-objects cannot be counted.
\end{proof}

\begin{corollary}[There is no photon stock]
There is no completed stock of photon-objects between emission and absorption.
\end{corollary}

\begin{proof}
A stock is an inventory of persisting items. Photon-objects are not licensed as persisting located items. Therefore no photon stock exists between emission and absorption.
\end{proof}

\begin{remark}
The point is stronger than saying that a photon stock is hard to observe. The point is that the photon-stock ontology is not licensed by the null constraints.
\end{remark}

\section{The Second No-Go: Closed Photon Quantity Imports a Census Frame}

Even if the first no-go is ignored, a second no-go remains. A completed photon quantity imports a census frame. A census frame imports temporal or quasi-temporal structure.

The problem appears whenever one says:

\[
|\Gamma|=N,
\]
where \(\Gamma\) is treated as the completed set of photon-things.

That statement is not merely a count. It is a closed inventory. A closed inventory requires one of the following hidden structures.

\subsection{Case 1: There are \(N\) photons now}

If the claim means

\[
|\Gamma(t)|=N,
\]
then the count is explicitly indexed to a time \(t\). The word ``now'' supplies a census moment.

\begin{quote}
There are \(N\) photons now.
\end{quote}

This is a time-indexed inventory. It belongs to spacetime-side accounting, not to the photon as a null charge-state relation.

\subsection{Case 2: There were \(N-1\) photons before}

If the count changes from \(N-1\) to \(N\), then the account introduces before and after:

\[
|\Gamma(t_1)|=N-1,
\qquad
|\Gamma(t_2)|=N,
\qquad
t_1<t_2.
\]

This is not timeless. It is a temporal population history.

\subsection{Case 3: There are always \(N\) photons}

If the claim is that there are always \(N\) photons, then the claim becomes:

\[
\forall t,\ |\Gamma(t)|=N.
\]

The word ``always'' is not timeless. It quantifies across time. It treats the inventory as stable throughout a temporal range.

\subsection{Case 4: A source produced \(N\) photons}

If the claim is that a source produced \(N\) photons, then the account introduces production sequence:

\[
\text{not-yet-produced}
\quad \longrightarrow \quad
\text{produced}.
\]

This is again before/after structure. It may be acceptable as source-side spacetime description, but it does not define a photon-object in the middle.

\begin{lemma}[Completed quantity imports a census frame]
A completed quantity of photon-objects requires a census frame.
\end{lemma}

\begin{proof}
A completed quantity says that the total inventory is \(N\), no more and no less. Such a claim requires a boundary around the relevant domain, an inclusion rule, an exclusion rule, and a condition under which the count is complete. These jointly form a census frame.
\end{proof}

\begin{lemma}[A census frame imports time-like structure]
A census frame imports time-like structure through a census moment, a before/after comparison, an always-condition, or a production sequence.
\end{lemma}

\begin{proof}
A completed inventory must be final relative to some standpoint. If the standpoint is ``now,'' a census moment is introduced. If the inventory changes, before/after comparison is introduced. If the inventory is said to be permanently fixed, an always-condition is introduced. If the inventory is produced, production sequence is introduced. Each route imports temporal or quasi-temporal structure.
\end{proof}

\begin{proposition}[Closed photon-object quantity is a category error]
A closed quantity of photon-objects is a category error.
\end{proposition}

\begin{proof}
A closed quantity of photon-objects requires photon-objects and a census frame. Photon-objects are not licensed, because the photon is not a persisting located item in spacetime. A census frame also imports temporal or quasi-temporal structure, which is incompatible with the photon understood as a null charge-state relation without internal time. Therefore a closed quantity of photon-objects is a category error.
\end{proof}

\section{What Is Counted Instead}

The denial of photon-object count does not erase physics. It relocates the count to the correct level.

\begin{enumerate}
    \item Detector records may be counted.
    \item Absorption-side changes may be counted.
    \item Emission-side changes may be counted.
    \item State-relative occupation numbers may be assigned.
    \item Endpoint correlations may be described.
    \item Lawful charge-state changes may be described in spacetime.
\end{enumerate}

These are all counts or descriptions of records, changes, events, or formal states. They are not inventories of photon-things.

\begin{proposition}[Photon-counting is record-counting or state-relative number assignment]
What is called photon-counting is, strictly, counting spacetime-side records or assigning state-relative photon-number quantities.
\end{proposition}

\begin{proof}
A physical count occurs through records, detections, absorptions, emissions, or representation-relative state descriptions. None of these requires a persisting photon-object in the interval. Therefore photon-counting is strictly record-counting or state-relative number assignment, not photon-object inventory.
\end{proof}

\section{Endpoint Accounting}

The clean description is endpoint accounting:

\[
\text{emission-side lawful change}
\quad \longleftrightarrow \quad
\text{absorption-side lawful change}.
\]

The photon is the name attached to the admissible charge-state relation. The relation has a spacetime appearance; the endpoint records are physical; the intermediate traveler is not added.

\begin{center}
\begin{tikzpicture}[scale=1.05, font=\footnotesize]
    % axes
    \draw[->] (-0.2,0) -- (7,0) node[right] {$x$};
    \draw[->] (0,-0.2) -- (0,4.5) node[above] {$ct$};

    % null relation
    \draw[thick,dashed] (0.9,0.7) -- (5.7,3.9);

    % endpoints
    \fill (0.9,0.7) circle (2.5pt);
    \fill (5.7,3.9) circle (2.5pt);

    \node[below right] at (0.6,0.7) {emission-side record};
    \node[above left] at (6,3.9) {absorption-side record};

    \node[above,rotate=34] at (3.2,2.25) {$ds^2=0,\ d\tau=0$};

    % no object label
    \node at (6.4,1.15) {null relation, not occupied history};
    \draw[->] (6.4,1.35) -- (3.2,2.1);
\end{tikzpicture}
\end{center}

\section{Relation to Photon Number in Quantum Theory}

Quantum theory permits photon-number language. Quantum field theory permits occupation-number language. This paper does not dispute either practice.

The restriction is ontological. A number in a specified state representation does not force a stock of tiny travelers. The formal count belongs to the formal context in which it is defined. It does not restore a photon rest frame, a photon location, a photon path, or a photon census in the middle.

\begin{proposition}[Occupation number does not restore photon-object ontology]
A photon-number state does not by itself establish a population of persisting photon-objects in spacetime.
\end{proposition}

\begin{proof}
A photon-number state is a representation-relative formal description. A population of persisting photon-objects requires located items with intermediate presence. The formal description supplies the former. It does not supply rest-frame location, internal proper time, intermediate trajectory, or object persistence. Therefore occupation number does not restore photon-object ontology.
\end{proof}

\begin{remark}
This is the same interpretive discipline applied elsewhere in the Timeless Light Model: successful formal representation does not license a forbidden middle.
\end{remark}

\section{Why the Distinction Matters}

If one treats spacetime-side records as photon-objects, pseudo-questions appear:

\begin{itemize}
    \item Where is the photon halfway?
    \item How does it know where to go?
    \item Which route did it really take?
    \item How many photon-things were in the interval?
    \item Did the photon wait, choose, update, or correct its path?
\end{itemize}

Each question assumes a located traveler. The TLM answer is not to add hidden process. The answer is to reject the premise.

The photon is not a thing traveling through spacetime. It is a lawful charge-state relation whose spacetime appearance is a lawful change. What is counted is the record, change, or representation-relative quantity, not a passenger.

\section{Main Result}

\begin{proposition}[Spacetime-side changes can be counted; photons cannot]
Spacetime-side changes can be counted as records, endpoint events, or representation-relative quantities. Photons cannot be counted as photon-objects, because no photon-object is licensed by the standard null constraints.
\end{proposition}

\begin{proof}
Spacetime-side changes are recorded or represented inside spacetime descriptions. They therefore admit counts relative to those descriptions. A photon-object would be a persisting located item in spacetime. But in standard relativistic physics, the photon has null proper time and no rest frame. Under the TLM interpretation, those constraints block photon object-location, intermediate location, trajectory, and transit. Therefore the photon-object is not licensed. Consequently spacetime-side changes can be counted, while photons cannot be counted as photon-objects.
\end{proof}

\begin{corollary}[No completed quantity for null charge-state relations]
A null charge-state relation cannot be assigned a completed quantity as a stock of things.
\end{corollary}

\begin{proof}
A completed stock of things requires countable objects. A null charge-state relation is not a persisting object in spacetime. Therefore it cannot be assigned a completed quantity as a stock of things.
\end{proof}

\section{Conclusion}

Spacetime-side changes are countable. Photons are not countable as objects.

A detector may count events. A field description may assign an occupation number. A source-side or absorption-side process may be described in ordinary spacetime language. But the photon itself is not a located item in spacetime. Standard relativity gives the photon null proper time and no rest frame. TLM takes those facts seriously: no photon rest frame means no photon object-location, no intermediate location, no trajectory, and no transit.

Therefore the photon is not a tiny thing with unusual properties. It is not here. It is not halfway. It is not in the interval. It is a lawfully admissible charge-state relation whose spacetime appearance is a lawful change.

The completed inventory question therefore fails twice. First, there is no photon-object to inventory. Second, any attempt to impose a closed photon quantity imports temporal structure through a census moment, a before/after comparison, an always-condition, or a production sequence.

The clean result is:

\[
\text{countable spacetime-side change} \neq \text{countable photon-object}.
\]

Null means null. The photon is counted only where a record, change, or state-relative quantity is available in spacetime accounting. It is not counted as a thing in flight, because there is no thing in flight.

\begin{thebibliography}{9}

\bibitem[McKinley(2026)]{McKinleyBedrock}
J.~C.~W. McKinley.
\newblock \emph{A Minimal Structural Statement of the Timeless Light Model}.
\newblock Zenodo (2026).
\newblock \doi{10.5281/zenodo.19167403}.

\bibitem[Einstein(1905)]{Einstein1905}
A.~Einstein.
\newblock Zur Elektrodynamik bewegter K{\"o}rper.
\newblock \emph{Annalen der Physik} \textbf{17}, 891--921 (1905).
\newblock \doi{10.1002/andp.19053221004}.

\bibitem[Wald(1984)]{Wald1984}
R.~M. Wald.
\newblock \emph{General Relativity}.
\newblock University of Chicago Press (1984).

\end{thebibliography}

\end{document}

```

</details>

---
{% endraw %}
