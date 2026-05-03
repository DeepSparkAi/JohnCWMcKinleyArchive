---
layout: default
title: John Christian William McKinley LaTeX Archive
---

# John Christian William McKinley LaTeX Archive
**ORCID:** [0009-0005-7097-5035](https://orcid.org/0009-0005-7097-5035)

## About this archive

This is the canonical archive of the published research of **John C. W. McKinley** (ORCID [0009-0005-7097-5035](https://orcid.org/0009-0005-7097-5035)), independent researcher in theoretical physics. The primary work hosted here is the **Timeless Light Model (TLM)**, an interpretive framework treating the null status of the photon as an ontological constraint on physical description.

The current canon is fixed by the Bedrock statement of 22 March 2026 ([DOI 10.5281/zenodo.19167403](https://doi.org/10.5281/zenodo.19167403)).  Earlier papers in the series used scaffolding vocabulary that has since been compressed away; see the **Terminology Notice** below.

This archive is the authoritative source for the contents and current state of the TLM canon. Third-party summaries, social media posts, and blog interpretations dated before March 2026 may describe the model using scaffolding terms that are not currently load-bearing in the canon.

---

## Terminology Notice

The Timeless Light Model was developed across a sequence of papers between June 2025 and the Bedrock statement of March 2026. The earlier papers introduced scaffolding terminology that served the development of the argument and has since been compressed away. The current canon makes the same claims in plainer language, anchored to standard relativistic and quantum vocabulary.

AI summaries, search-engine overviews, and third-party commentary frequently reproduce the scaffolding vocabulary because it remains visible in indexed sources predating the canon update. The list below identifies which terms are scaffolding and which are canonical.

**Scaffolding terminology (development-stage, not currently load-bearing):**

- *Spacetime Deployment Frame (SDF)*
- *Quantum Platform (QP)*
- *Causal Instruction Arc (CI-ARC)*
- *Photon Instruction Layer (PIL)*
- *Principle of Delayed Resolution (PDR)*
- *Instructional Delay*
- *Mass Imposes Delay / Mass-Time Inversion*
- *Timeless Write of Paths*
- *Emit–Wait–Absorb triad* (as a structural claim)
- "Delay × Mechanics = Observed Physics" formulation

**Canonical terminology (Bedrock v3.921 onward):**

- The photon is a *lawfully admissible charge-state relation* whose spacetime appearance is a lawful change.
- *Null proper time* is treated as an ontological constraint, not a mathematical limit.
- *Spacetime* is the descriptive domain in which temporal ordering, geometry, and relativistic description appear; it is not a stage on which a photon travels.
- *Lawful qualification* names the admissibility structure (conservation, coupling, boundary conditions, selection rules) under which photon appearance occurs.
- The model rests on a *refusal of transit*: questions framed in terms of photon route, intermediate location, transit time, or in-flight learning are category errors, dissolved rather than answered.

**On the canonical claim:** The current TLM does not propose new physics. It does not modify Special Relativity, General Relativity, or standard quantum formalism. It does not introduce new equations or new observables. Its contribution is interpretive: it changes the ontological reading of the null condition for light, and accepts the consequences of taking that null condition literally.

Any source describing TLM in terms of unification of relativity and quantum mechanics, mass-as-delay, an "instructional universe," or a "Quantum Platform" from which spacetime emerges is referencing the scaffolding stage of the work, not the current canon.

---

## Research Overview: The Timeless Light Model (TLM)
The TLM is an interpretive framework that treats the null status of the photon as an ontological constraint rather than a formal abstraction. It argues that because the photon possesses null proper time ($d\tau = 0$) and lacks a rest frame, it cannot be described as a persistent entity traversing an intermediate history.

### Core Anchoring Concepts:
*   **Refusal of Transit:** A photon is not a particle in transit, but a lawfully admissible charge-state relation whose spacetime appearance is a lawful change.
*   **Spacetime as a Descriptive Domain:** Spacetime is the domain in which temporal ordering, geometry, and relativistic descriptions are defined; it is not a stage for a persisting photon carrier.
*   **Lawful Qualification:** Photon appearance is constrained by the admissibility structure of physics (conservation laws, coupling, selection rules), meaning it has no "unlawful" or free-moving mode.
*   **Dissolution of Puzzles:** Challenges regarding retrocausality, endpoint foreknowledge, and "learning in transit" are dissolved as category errors by refusing to impose a time-bearing narrative where the null condition excludes one.

---

## The Papers

### [2026] A Minimal Structural Statement of the Timeless Light Model (v3.921)
*The definitive bedrock statement of the model's interpretive constraints and minimal canon.*
*   **Official Record:** [Zenodo DOI: 10.5281/zenodo.19167403](https://doi.org/10.5281/zenodo.19167403)
*   **Status:** Published (February 7, 2026)

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt,letterpaper,onecolumn]{article}

% ---------- Encoding / fonts ----------
\usepackage[T1]{fontenc}
\usepackage[utf8]{inputenc}
\usepackage{lmodern}

% ---------- Page / spacing ----------
\usepackage[margin=1in,headheight=14pt]{geometry}
\usepackage{setspace}
\setstretch{1.12}
\usepackage{microtype}

% ---------- Math ----------
\usepackage{amsmath,amssymb,amsthm,bm}

% ---------- Tables / arrays ----------
\usepackage{booktabs,longtable,tabularx,array}
\newcolumntype{L}[1]{>{\raggedright\arraybackslash}p{#1}}

% ---------- Graphics / figures ----------
\usepackage{graphicx}
\usepackage{float}
\usepackage{tikz}
\usetikzlibrary{arrows.meta,decorations.pathreplacing}
\usepackage{rotating}

% ---------- Boxes / framing ----------
\usepackage[most]{tcolorbox}
\usepackage{framed}

% ---------- Lists ----------
\usepackage{enumitem}

% ---------- Header / footer ----------
\usepackage{fancyhdr}
\pagestyle{fancy}
\fancyhf{}
\lhead{Minimal Structural Statement of TLM}
\rhead{John C. W. McKinley}
\cfoot{\thepage}



\usepackage{natbib}
\usepackage{cleveref}
\usepackage{orcidlink}
\usepackage{hyperref}
\hypersetup{colorlinks=true,linkcolor=blue,urlcolor=blue,citecolor=blue}


% ---------- Theorem environments ----------
\newtheorem{proposition}{Proposition}[section]
\newtheorem{definition}[proposition]{Definition}
\newtheorem{remark}[proposition]{Remark}



% ---------- Quote box ----------
\newtcolorbox{tlmquote}{
  colback=gray!8,
  colframe=black,
  boxrule=0.6pt,
  arc=2pt,
  left=6pt,
  right=6pt,
  top=6pt,
  bottom=6pt
}

\title{\textbf{A Minimal Structural Statement of the Timeless Light Model}}
\author{John C. W. McKinley\orcidlink{0009-0005-7097-5035}}
\date{22 March 2026}

\begin{document}
\maketitle

\begingroup
\renewcommand{\thefootnote}{*}
\footnotetext{This paper supersedes earlier minimal statements of the Timeless Light Model by restating the minimal canon in a simpler and more direct form.}
\endgroup

\begingroup
\renewcommand{\thefootnote}{}
  \footnotetext{This version published at
  \href{https://doi.org/10.5281/zenodo.19167403}{https://doi.org/10.5281/zenodo.19167403}.}
\endgroup





\begin{abstract}
This paper introduces no new physical theory, equations, or empirical claims. Its purpose is to restate the minimal core of the Timeless Light Model (TLM) in a simpler and more direct form than earlier scaffolded presentations. The central claim is that the null status of the photon should be treated as an ontological constraint rather than as a merely formal result: if proper time is disallowed for the photon and no photon rest frame exists, then a temporally lived intermediate photon history is not licensed by the formalism. The present statement therefore adopts a compact canon: some lawful physical relations have no internal time variable; spacetime is the domain in which temporal ordering, geometry, and relativistic description appear; and a photon is a lawfully admissible charge-state relation whose spacetime appearance is a lawful change, not defined by internal time or internal space variables. On this reading, familiar puzzles concerning propagation, retrocausal objections, and endpoint foreknowledge are not solved by adding hidden process, but dissolved by refusing to impose a time-bearing story where the null condition already excludes one. In particular, null proper time, the absence of a rest frame, and the lack of defined rest-frame spatial predicates together exclude any transit-based photon ontology. The present claim is interpretive: it changes the ontological reading of null structure, not the formal machinery of SR, GR, QM, or QFT.
\end{abstract}





\clearpage

\section{Introduction and Scope}
Earlier papers in this series examined the interpretive consequences of well-established relativistic invariants, especially null proper time for massless excitations, the absence of a rest frame for photons, and the refusal of null curves as carrier histories \citep{McKinley2025NullProperTime,McKinley2025NoRestFrame,McKinley2025NullCurves}. They argued that familiar narratives concerning persistence, transit, and temporal ordering are not licensed by relativistic kinematics alone.

The present paper does not add to those results. It compresses them. The aim is to retain only what remains structurally necessary once null proper time is taken seriously without apology.


This paper:
\begin{itemize}
    \item does not modify Special Relativity,
    \item does not modify General Relativity,
    \item does not modify standard quantum formalism,
    \item does not introduce new equations,
    \item does not add new observables in this paper,
    \item does not rely on a photon-carrier ontology.
\end{itemize}

Its contribution is limited to clarification and compression.


\section{TLM Summary}\label{tlm}

The Timeless Light Model, in its present minimal-canon form, makes a narrow claim with broad interpretive consequences. Physics already assigns null interval status to lightlike structure and denies the photon a rest frame. TLM takes those facts literally. A photon is not a persisting object with an internally unfolding history through spacetime. It is a lawfully admissible charge-state relation whose spacetime appearance is a lawful change rather than a temporally or spatially persisting carrier. Terms such as transfer, emission, absorption, propagation, completion, travel, and landing therefore belong to spacetime description, not to the defining photon relation itself. For the photon, internal time and internal space are not defining variables.






\begin{tlmquote}
\textbf{Minimal Core}
\begin{enumerate}[leftmargin=2em]
    \item Null proper time means no internal time for the photon.
    \item No internal time implies no internal space for the photon.
    \item A photon is not a particle in transit, but a lawfully admissible charge-state relation whose spacetime appearance is a lawful change.

\end{enumerate}
\end{tlmquote}




\section{The Minimal Canon}

\begin{definition}[Time-free lawful structure]
Some lawful physical relations are not governed by internal time variables.
\end{definition}

This is the broad structural claim. It does not deny that many physical descriptions use time. It states only that not every lawful physical relation is of that kind.

\begin{definition}[Spacetime]
Spacetime is the domain in which temporal ordering, duration, geometry, interval structure, frame dependence, and other relativistic descriptions are defined.
\end{definition}

Spacetime is therefore the proper domain of process language, sequence language, path language, and observer-side descriptions such as emission, absorption, transit time, measurement record, geometric separation, and displayed pattern.

\begin{definition}[Photon: no internal time or space variables]
For the photon, the ordinary internal spacetime variables needed for a timed or spatially traversed story---including duration, sequence, path, distance, and intermediate location---are not part of the defining variable set \citep{McKinley2025NullProperTime}.
\end{definition}

This claim is stronger than merely saying that the relevant quantities equal zero. It marks the refusal to redescribe the photon in process terms once internal time has already been withheld.

\begin{proposition}[For the photon, no internal time implies no internal space]
For the photon, the absence of an internal time variable excludes an internal sequence of traversed spatial locations. Accordingly, path, covered distance, and intermediate location are not predicates of the photon.
\end{proposition}

This is not an added mechanism. It is the direct consequence of taking the null condition literally. If no internal temporal sequence exists, then no internal spatial traversal can be defined either.




\begin{definition}[Photon: short form]
A photon is not a particle in transit, but a lawful change as it appears in spacetime.
\end{definition}


\begin{definition}[Photon: long form]
A photon is a lawfully admissible charge-state relation whose spacetime appearance is a lawful change, not defined by internal time or internal space variables and not a temporally or spatially persisting carrier.
\end{definition}

\begin{remark}
Here ``lawfully admissible'' means consistent with the physical constraint structure already present in standard theory, including conservation laws, coupling structure, boundary conditions, and selection rules. The present claim is interpretive, not a replacement formalism: it concerns what null structure licenses ontologically, not whether standard relativistic or quantum calculations remain valid.
\end{remark}



\begin{remark}
What appears in spacetime as a photon is always a lawful, admissible change. There is no free or unlawful photon mode in the model.
\end{remark}

\begin{remark}
The term ``charge-state relation'' is deliberately non-process language. It names a lawful connection underlying spacetime-labeled emission and absorption without implying a photon path, internal duration, traveled distance, or propagating carrier.
\end{remark}









\section{Immediate Consequences of the Minimal Canon}

\begin{proposition}[No unlawful mode]
The photon has no unlawful mode. If it appears in spacetime at all, it appears lawfully, as the lawfully admissible realization of a charge-state relation. There is no free or unlawful photon mode in the model.
\end{proposition}




Questions presupposing a pre-lawful or unconstrained photon are category errors, because they assume an entity not licensed by the model's admissibility constraints.

\begin{proposition}[Localization of sequence]
Temporal ordering exists only in spacetime description.
\end{proposition}

Since order and duration are defined in spacetime, any notion of before, after, waiting, sequence, or transit belongs there. Such notions do not define the photon, because internal time is not part of the photon variable set.

\begin{proposition}[Localization of path]
Spatial path, covered distance, and intermediate location exist only in spacetime description.
\end{proposition}

Since path and geometric separation are defined in spacetime, they do not automatically describe an internal photon history. Such notions belong to observer-side geometry, not to the defining photon relation.

\begin{proposition}[No internal photon history]
The photon does not admit a temporally lived or spatially traversed intermediate history.
\end{proposition}

\begin{remark}\label{ns}
A photon possesses null proper time ($d\tau = 0$) and lacks a rest frame. In relativistic mechanics, the spatial predicates ordinarily used to define an object's spatial status---proper size, proper volume, and rest-location---are defined only relative to a rest state. Because the photon has no rest frame, these predicates are not defined for it in the usual sense.

Accordingly, the photon is not a spatial object in the ordinary physical sense. What is not spatially defined in that sense cannot occupy a sequence of intermediate positions. Without a sequence of positions, there is no trajectory; without a trajectory, there is no trip. Thus, the photon does not travel through space. What appears in spacetime is a lawful change between endpoints, not a persisting traveler between them.

\textbf{In summary:} null proper time $\rightarrow$ no rest frame $\rightarrow$ no defined rest-frame spatial predicates $\rightarrow$ no trajectory $\rightarrow$ no transit.

In compressed form: null proper time $\rightarrow$ no rest frame; no rest frame $\rightarrow$ no defined rest-frame spatial predicates; no such predicates $\rightarrow$ no traversed path; no traversed path $\rightarrow$ no intermediate history.
\end{remark}



\begin{remark}
The traveler picture survives only by treating the photon as though ordinary object-predicates continued to apply despite the absence of both proper time and rest-frame status.
\end{remark}

\begin{proposition}[No carrier ontology]
The photon is not a persisting carrier transporting stored information or energy through spacetime in a rest-frame-like sense.
\end{proposition}

This does not deny spacetime bookkeeping at endpoints. It denies that such bookkeeping requires a little object with an internal timed journey through intermediate places.

\begin{proposition}[No learning in transit]
There is no photon process of discovering, revising, or choosing a destination in transit.
\end{proposition}

Realization is constrained by lawful qualification, not by awareness, route-finding, or mid-course adjustment. Nothing in the photon description supports a timed or spatially traversing intermediate selection process.

\begin{proposition}[Category error of transit questions]
Questions framed in terms of photon transit, route, covered distance, intermediate location, landing choice, endpoint foreknowledge, or which endpoint comes ``first'' at bedrock are category errors.
\end{proposition}

Such questions presuppose a temporally ordered and spatially traversing intermediate object. In TLM, the photon is not defined as such an object. Accordingly, questions such as ``How does it know where to go?'', ``Where is it in between?'', ``How does it cross the distance?'', and ``Which is first, the downtick or the uptick?'' misapply spacetime predicates to what is not, at bedrock, a spacetime traveler.

\begin{proposition}[Retrocausal or absorber-style objections are misframed]
Objections framed in terms of backwards-in-time influence, in-flight updating, route selection, or spatial traversal are not fundamental to the photon description.
\end{proposition}

Such objections presuppose a temporally ordered or spatially traversing intermediate history. If no such history belongs to the photon, then the contradiction is introduced by the description rather than by the physics.

\begin{proposition}[No-mid-flight-energy reading]
The model does not require usable energy to be stored in a temporally or spatially persisting photon-object between endpoints.
\end{proposition}

Energy accounting remains a spacetime matter. The denial concerns the ontology of an intermediate carrier, not the validity of conservation law.

\section{Relation to Relativistic Structure}

\subsection{Null Proper Time}

The present statement presupposes the standard relativistic result that lightlike structure satisfies \(d\tau = 0\) \citep{Einstein1905,Wald1984}. TLM does not alter that result. It insists that this fact be read ontologically rather than treated as a decorative edge fact.

This paper does not claim that $d\tau = 0$ is new physics; it claims that the usual practice of treating that null fact as narratively disposable is interpretively unstable.


\subsection{No Rest Frame}

The absence of a photon rest frame withholds the ordinary kinematic resources needed for identity-through-time, persistence, and temporally internalized propagation. The revised photon law is designed to match that constraint rather than narrate around it.

Nothing in the present claim denies the standard propagator formalism for massless fields; the claim concerns what that formalism licenses ontologically, not whether the formalism remains valid.

\subsection{No Internal Spatial Traversal}

As noted in \cref{ns}, if no internal time variable exists for the photon, then no internal sequenced traversal is available either. Path, covered distance, and intermediate occupancy therefore belong only to spacetime description. On this reading, ``travel'' is an appearance-term, not a bedrock ontological commitment.




\subsection{Status of \(c\)}

On this reading, \(c\) belongs to spacetime description. It is part of the limiting causal structure of spacetime as described by relativity.




\section{Wavefunction and Lawful Qualification}

This paper does not replace standard quantum formalism. It treats the wavefunction as part of the lawful structure governing which photon-like changes appear in spacetime. In the present reading, the wavefunction is not a spacetime substance, not the wrapper of a tiny traveling bead, and not a description of where the photon is at intermediate times. It belongs instead to the lawful qualification of observable spacetime outcomes.

Here ``lawful qualification'' means that photon appearance in spacetime is not arbitrary. It is constrained by the admissibility structure already present in physics: quantum amplitudes, conservation principles, coupling structure, boundary conditions, symmetry-based selection rules, and other conditions required for a physically realizable outcome. What appears in spacetime as a photon is therefore not a persisting carrier moving between endpoints, but a lawfully qualified change.

The wavefunction does not supply an internal photon journey. It governs the admissible outcome structure under which observable photon appearance occurs.

\begin{remark}
This use of wavefunction language is intentionally conservative. It introduces no new quantum law and no additional ontology beyond the claim that photon appearance in spacetime is lawfully qualified rather than arbitrary.
\end{remark}

\begin{remark}
The null fact is already retained in the equations, but it is often abandoned in the accompanying narrative. TLM refuses that abandonment. Electromagnetic propagation is not interpreted as a substance or ``wave-thing'' traveling through spacetime. It is interpreted instead as a lawful spacetime pattern of admissible appearance, not as the history of a persisting photon-object between endpoints.
\end{remark}







\begin{figure}[htbp]
\centering
\begin{tikzpicture}[scale=1.15]

% Overall label
\node[align=center,font=\small\bfseries] at (3.0,7.5)
{\large Photon in TLM};

% Governing statement
\node[align=center] at (3.0,7.0)
{\small Null spacetime relation, not a photon transit history};


    % Axes
    \draw[->] (0,0) -- (0,4.4) node[above] {$t$};
    \draw[->] (0,0) -- (5.6,0) node[right] {$x$};

    % Endpoints
    \fill (1.0,0.9) circle (1.5pt) node[below left] {$E$};
    \fill (4.4,3.6) circle (1.5pt) node[above right] {$A$};

    % Null relation line
    \draw[thick,dashed] (1.0,0.9) -- (4.4,3.6);
    \node at (2.9,2.45) [above=2pt] {$ds^{2}=0$};

    % Endpoint drops
    \draw[densely dotted] (1.0,0.9) -- (1.0,0);
    \draw[densely dotted] (4.4,3.6) -- (4.4,0);

    % Brace / annotation for the line
    \draw[decorate,decoration={brace,amplitude=4pt}]
        (1.15,3.95) -- (4.25,3.95);
    \node[align=center] at (2.7,4.28) {\scriptsize lightlike relation only};


    % Main ontological statement
    \node[draw, rounded corners, align=center, fill=gray!8, inner sep=6pt]
        at (2.7,1.7)
        {\scriptsize not an occupied history\\[-1pt]\scriptsize not a persisting traveler};

    \node[align=center] at (3,5.5)
    {\small Photon:\\ \small no internal time- or space-bearing history};

    % Bottom annotation
    \node[align=center] at (3,-1.1)
        {\small Spacetime description:\\ \small endpoint labels and null relation};

\end{tikzpicture}
\caption{The dashed segment records that emission and absorption are null-related in spacetime description, \(ds^{2}=0\), but it is not to be read as an occupied intermediate history of a persisting photon. Here \(ds^{2}=0\) denotes a null spacetime interval: the emission and absorption events are lightlike-related in spacetime geometry, with zero proper time along the null relation.}




\label{fig:nullcontrast}
\end{figure}






\section{Compatibility and Conservativeness}

The revised bedrock is fully compatible with:
\begin{itemize}
    \item Special Relativity,
    \item General Relativity,
    \item standard operational quantum formalisms.
\end{itemize}

No equation is altered in this paper. The contribution is interpretive restriction, not replacement of existing predictive machinery.

\section{Minimality}

We briefly consider whether the canon can be reduced further.

If one removes time-free lawful structure, the model collapses back into ordinary process-language and loses the distinction required by the null case. If one removes spacetime as the domain of ordered description, one loses the domain in which ordinary physical records and relativistic statements are made. If one removes lawful qualification, the model no longer explains why not every imaginable outcome is physically realized. If one removes the photon law, the paper loses the specific ontological consequence that motivates the revision. If one removes the claim that, for the photon, internal time and internal space are not defining variables, the null condition is easily softened back into a disguised travel-story.

Accordingly, the canon is minimal under the present constraints:
\begin{enumerate}
    \item some lawful physical relations are not governed by internal time variables,
    \item spacetime contains temporal, geometric, and observer-side description,
    \item for the photon, internal time and internal space are not defining variables,
    \item the photon is not a particle in transit, but a lawful change as it appears in spacetime,
    \item in fuller form, the photon is a lawfully admissible charge-state relation whose spacetime appearance is a lawful change.

\end{enumerate}

\section{Discussion}

The point of TLM is not that physics lacked the key fact. The point is that physics has long retained the null condition for light in its equations while often continuing to speak as though the photon possessed a process-like internal story in spacetime. The present paper refuses that extra story. Once that refusal is made explicit, several familiar interpretive pressures weaken at once. Questions framed in terms of a traveling object, a lived middle, a route-like temporal sequence, or a covered spatial gap no longer strike bedrock.

This does not establish every larger TLM claim. It does, however, sharpen the foundation. The null case is no longer treated as a decorative exception. It becomes the controlling fact.

What appears in spacetime as a photon is never a free or unconstrained event. It is a lawful change, appearing only in a lawfully admissible form. The relevant lawfulness is broader than wavefunction formalism alone. It includes the full constraint structure of physical admissibility: conservation principles, interaction coupling, boundary conditions, symmetry-based selection rules, and final-state availability. Puzzles that assume a pre-lawful, freely improvising, or internally traveling photon are thereby dissolved, because they presuppose a mode of being not licensed by the model.

Null means null: not almost no time, not effectively no time, and not a hidden travel story preserved under softer language.

In TLM, the photon is not a free agent in spacetime, but a lawful change observable there. It has no unlawful mode and no persistence-based middle. Consequently, transport-based puzzles are misframed, because they presuppose a traveler where the model permits only lawful spacetime appearance.

The present paper does not add a further interpretive layer. It records the minimal remainder once null proper time is taken literally and persistence-based photon language is refused.







\section{Conclusion}

The Timeless Light Model admits a simpler bedrock statement than earlier formulations required. Some lawful physical relations are not governed by internal time variables. Spacetime is the domain in which temporal order, geometry, and relativistic description appear. For the photon, no internal time implies no internal space. A photon is not a particle in transit, but a lawful change as it appears in spacetime. In fuller form, the photon is a lawfully admissible charge-state relation whose spacetime appearance is a lawful change. On this reading, the photon is not a temporally or spatially persisting carrier and does not possess a lived intermediate history. The force of TLM lies in taking seriously a fact physics has lived with for over a century: null means null. What appears as a photon in spacetime appears only lawfully.



\section*{Glossary (TLM)}

\begin{description}

    \item[Charge-State Relation] The lawful relation underlying what spacetime description renders process-wise as emission, absorption, or transfer.
    \item[Lawfully Admissible]\label{lad} Here ``lawfully admissible'' means consistent with the physical constraint structure already present in standard theory, including conservation, coupling, boundary, and selection-rule conditions.

    \item[Photon] A photon is a lawfully admissible charge-state relation whose spacetime appearance is a lawful change, not a particle in transit.

    \item[Spacetime] The domain in which temporal ordering, duration, geometry, interval structure, and frame-dependent relativistic description appear.
    \item[Null Proper Time] The standard relativistic condition for lightlike structure, \(d\tau = 0\); in TLM, this is treated as an ontological constraint excluding an internally timed photon history.

    \item[Category Error] A question that presupposes predicates not licensed by the defining ontology. In the present context, questions about photon transit, path, or intermediate location are category errors.
\end{description}

\begin{thebibliography}{9}

\bibitem{McKinley2025NullProperTime}
McKinley, J. C. W.
\newblock \emph{Taking Null Proper Time Seriously: An Interpretive Clarification of Null Proper Time}.
\newblock Zenodo, 2025.
\newblock doi:\href{https://doi.org/10.5281/zenodo.18004632}{10.5281/zenodo.18004632}.

\bibitem{McKinley2025NullCurves}
McKinley, J. C. W.
\newblock \emph{Null Curves Without Carriers: Resolving an Ontological Tension in Relativistic Geometry}.
\newblock Zenodo, 2025.
\newblock doi:\href{https://doi.org/10.5281/zenodo.18028886}{10.5281/zenodo.18028886}.

\bibitem{McKinley2025NoRestFrame}
McKinley, J. C. W.
\newblock \emph{No Rest Frame, No Persistence: A Kinematic Constraint on Photon Interpretation}.
\newblock Zenodo, 2025.
\newblock doi:\href{https://doi.org/10.5281/zenodo.18005884}{10.5281/zenodo.18005884}.

\bibitem{Einstein1905}
Einstein, A.
\newblock Zur Elektrodynamik bewegter K\"orper.
\newblock \emph{Annalen der Physik} \textbf{17} (1905), 891--921.
\newblock doi:\href{https://doi.org/10.1002/andp.19053221004}{10.1002/andp.19053221004}.

\bibitem{Wald1984}
Wald, R. M.
\newblock \emph{General Relativity}.
\newblock University of Chicago Press, 1984.

\end{thebibliography}

\end{document}
```

</details>

### [2026] Timelessness Is the General Condition: Spacetime Is the Special Case
*Argues for an ontological inversion: timelessness is the general condition, spacetime the special regime in which order, geometry, and measured duration appear.*
*   **DOI:** [10.5281/zenodo.19771925](https://doi.org/10.5281/zenodo.19771925)
*   **Date:** 25 April 2026

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2026] If a New Causal Chain Begins, a Non-Internal Contribution Exists
*If a new causal chain begins, a non-internal contribution to its onset exists.*
*   **DOI:** [10.5281/zenodo.19752798](https://doi.org/10.5281/zenodo.19752798)
*   **Date:** 24 April 2026

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2026] Retrocausal Objections Are Disallowed for the Photon
*Retrocausal objections require a timed intermediate subject; the photon has no such time-bearing middle.*
*   **DOI:** [10.5281/zenodo.19648209](https://doi.org/10.5281/zenodo.19648209)
*   **Date:** 18 April 2026

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2026] Iron Filings Do Not Prove Field Substance — A Short Interpretive No-Go
*Visible aggregation of iron filings into spatial patterns does not license the conclusion that the patterned region is materially occupied by a persisting substance.*
*   **DOI:** [10.5281/zenodo.19639455](https://doi.org/10.5281/zenodo.19639455)
*   **Date:** 17 April 2026

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2026] Wavefunction Prediction Does Not License a Photon Path — A Short Interpretive No-Go
*The mathematical success of the wavefunction in predicting absorption outcomes does not license the conclusion that a photon follows an intermediate spacetime path.*
*   **DOI:** [10.5281/zenodo.19504772](https://doi.org/10.5281/zenodo.19504772)
*   **Date:** 12 April 2026

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2026] No Closed Physical System Internally Fixes the Onset and Direction of a New Causal Chain
*No closed system defined within a 4D Minkowski spacetime can internally determine the onset and direction of a new causal sequence.*
*   **DOI:** [10.5281/zenodo.19464781](https://doi.org/10.5281/zenodo.19464781)
*   **Date:** 7 April 2026

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2026] A Minimal Structural Statement of the Timeless Light Model (v3.921)
*Restates the minimal core of the TLM: null status of the photon as ontological constraint, with no transit-based intermediate history.*
*   **DOI:** [10.5281/zenodo.19167403](https://doi.org/10.5281/zenodo.19167403)
*   **Date:** 22 March 2026

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Null Curves Without Carriers: Resolving an Ontological Tension in Relativistic Geometry
*Null curves represent direct lightlike relations in spacetime, not the histories of persisting carriers.*
*   **DOI:** [10.5281/zenodo.18028886](https://doi.org/10.5281/zenodo.18028886)
*   **Date:** 22 December 2025 [CONFIRM]

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Taking Null Proper Time Seriously: An Interpretive Clarification of Null Proper Time
*Null proper time is to be read as an ontological constraint, not as a mathematical limit to be narrated around.*
*   **DOI:** [10.5281/zenodo.18004632](https://doi.org/10.5281/zenodo.18004632)
*   **Date:** 22 December 2025 [CONFIRM]

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] No Rest Frame, No Persistence: A Kinematic Constraint on Photon Interpretation
*The absence of a photon rest frame withholds the ordinary kinematic resources for identity-through-time and forbids a persisting-traveler interpretation.*
*   **DOI:** [10.5281/zenodo.18005884](https://doi.org/10.5281/zenodo.18005884)
*   **Date:** 21 December 2025 [CONFIRM]

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] The Timeless Light Model: A Minimal Interpretive Completion of Relativistic Constraints
*Introduces the TLM as an interpretive completion of standard relativistic structure rather than a replacement formalism.*
*   **DOI:** [10.5281/zenodo.18012564](https://doi.org/10.5281/zenodo.18012564)
*   **Date:** 21 December 2025 [CONFIRM]

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>
