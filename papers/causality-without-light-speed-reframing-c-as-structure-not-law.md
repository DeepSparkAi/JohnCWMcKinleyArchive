---
layout: default
title: '[2025] Causality Without Light Speed: Reframing c as Structure, Not Law'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/causality-without-light-speed-reframing-c-as-structure-not-law/
paper: true
---
{% raw %}
# [2025] Causality Without Light Speed: Reframing c as Structure, Not Law
*   **DOI:** [10.5281/zenodo.15826480](https://doi.org/10.5281/zenodo.15826480)
*   **Date:** 7 July 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[11pt]{article}
\usepackage{pifont} % A
\usepackage[utf8]{inputenc}
\usepackage{amsmath, amssymb, geometry}
\usepackage{hyperref}
\usepackage{natbib}
\usepackage{graphicx}
\usepackage{booktabs}
\usepackage{titlesec}
\usepackage{fancyhdr}
\usepackage{cleveref}
\usepackage{tikz}
\usepackage[most]{tcolorbox}
\usetikzlibrary{patterns}
\usepackage{enumitem}
\usepackage[strings]{underscore}

\usepackage{tocloft}
\renewcommand{\cftsecnumwidth}{2.5em}
\renewcommand{\cftsubsecnumwidth}{3em}

% Add a period after section numbers
\renewcommand{\cftsecaftersnum}{.}
\renewcommand{\cftsubsecaftersnum}{.}
\renewcommand{\cftsubsubsecaftersnum}{.}



% Format section headings: Add space and period after number
\titleformat{\section}
  {\normalfont\Large\bfseries}
  {\thesection.}{1em}{}

\titleformat{\subsection}
  {\normalfont\large\bfseries}
  {\thesubsection.}{1em}{}

\titleformat{\subsubsection}
  {\normalfont\normalsize\bfseries}
  {\thesubsubsection.}{1em}{}

% Add vertical space before/after sections
\titlespacing*{\section}
  {0pt}{3.0ex plus 1ex minus .2ex}{2.0ex plus .2ex}

\titlespacing*{\subsection}
  {0pt}{2.5ex plus 1ex minus .2ex}{1.5ex plus .2ex}

\titlespacing*{\subsubsection}
  {0pt}{2.0ex plus 0.8ex minus .2ex}{1.0ex plus .2ex}




\newcommand{\TLMdivider}{
  \begin{center}
  \rule{0.25\textwidth}{0.4pt}
  \quad \( T \cdot C_s = 1 \) \quad
  \rule{0.25\textwidth}{0.4pt}
  \end{center}
}

\usetikzlibrary{arrows.meta, positioning, shapes.geometric}
\geometry{margin=1in}
\linespread{1.15}
\numberwithin{equation}{section}
\bibliographystyle{apsrev4-2}

\hypersetup{
    colorlinks=true,
    linkcolor=blue,
    citecolor=blue,
    urlcolor=blue,
}

\title{Causality Without Light Speed:\\Reframing \( c \) as Structure, Not Law}



\author{
John C. W. McKinley \\
Independent Researcher \\
\href{https://orcid.org/0009-0005-7097-5035}{ORCID: 0009-0005-7097-5035}
}

\begin{document}

\maketitle
\begin{center}
\textbf{DOI:} \href{https://doi.org/10.5281/zenodo.15826480}{10.5281/zenodo.15826480}
\end{center}
\vspace{2em}

\tableofcontents
\vspace{1em}




\vspace{2em}
\TLMdivider
\vspace{3em}

\begin{abstract}
The speed of light \( c \) is often described as ``preserving causality'' in both popular and academic explanations of physics. This paper challenges that phrasing, demonstrating that causality is only placed at risk in a relativistic framework where time and simultaneity are observer-dependent. \( c \) is not a universal guardian of causal order — it is a constraint introduced to maintain consistency within that specific structure. By analyzing causality in Newtonian physics, special relativity, general relativity, and quantum mechanics, we argue that \( c \) should not be treated as the origin or enforcer of causality, but rather as a consistency condition arising from the relativistic model~\cite{einstein1905}.This paper proceeds in two stages: first, it clarifies misconceptions about causality in existing theories; second, it proposes a new framework---the \textit{Timeless Light Model} (TLM)---that reframes causality as the rendered resolution of timeless instructions.This paper combines physics with metaphysical inquiry, proposing that observed spacetime arises from a timeless instruction set—bridging scientific formalism and foundational questions about causality, agency, and origin.


\end{abstract}

\section{Introduction}
\label{sec:introduction}

The speed of light \( c \) is widely regarded as one of the most fundamental constants in physics. In both popular and technical accounts, it is often said that nothing can travel faster than light because such motion would ``break causality.'' This framing, while partially valid within specific models, leads to conceptual confusion when presented as a general principle. 

\vspace{2em}
\begin{tcolorbox}[
  colback=yellow!5!white,
  colframe=yellow!60!black,
  title=Preview: A Shift in Perspective,
  fonttitle=\bfseries
]
Later in this paper, we will reframe \( c \) not as a metaphysical ceiling that enforces causality, but as a geometric consequence of the spacetime model itself — a boundary that emerges from structural assumptions, not one that governs them.
\end{tcolorbox}
\vspace{2em}



This paper argues that the idea of \( c \) ``preserving causality'' only makes sense within the formal structure of relativistic physics — where the very notion of simultaneity is relative, and causal order can vary by observer if not properly bounded \cite{einstein1905}. In contrast, classical Newtonian mechanics requires no such limit: time is absolute, simultaneity is universal, and causality is structurally unthreatened even if instantaneous influences exist.

\begin{tcolorbox}[colback=white!97!gray, colframe=purple!50!black, title=Note on Interpretation, fonttitle=\bfseries]
This model crosses the boundary between formal physics and metaphysical interpretation by design. It asserts that instructional causality and delayed resolution invite questions of origin and authorship—not as a theological claim, but as a necessary consequence of rethinking spacetime as an output, not a container.
\end{tcolorbox}


We aim to clarify what \( c \) actually does in special relativity (SR), general relativity (GR), and quantum mechanics (QM), and to show that its role is not to enforce a metaphysical law of cause and effect, but rather to uphold consistency in a specific geometrical framework of spacetime. Once that distinction is made clear, we can better understand what causality means — and how it must be qualified depending on the physical model in use.

``Causality'' should not be treated as a sacred principle that necessitates \( c \); rather, \( c \) is introduced to ensure causality remains well-defined in a relativistic universe that would otherwise undermine it.



\paragraph{Note on Broader Implications.}
While this paper remains grounded in established frameworks, its goal is not purely retrospective. Clarifying the true role of \( c \) in causality lays the conceptual groundwork for a broader model — one in which causality itself emerges from a deeper, non-spatiotemporal structure. That proposal will follow in the final section.




\begin{tcolorbox}[colback=white!98!gray, colframe=black!40!black, title=Structure of the Paper, fonttitle=\bfseries]
This paper proceeds in two stages: 
\begin{itemize}
  \item First, it clarifies misconceptions about the role of causality and the speed of light in standard physical theories, showing that \( c \) arises from the internal structure of those models rather than acting as a universal enforcer.
  \item Second, it introduces a new framework—the \textit{Timeless Light Model} (TLM)—in which observable causality is the delayed manifestation of timeless instructions, and spacetime itself is rendered rather than fundamental.
\end{itemize}
\end{tcolorbox}



\section{Causality Defined}
\label{sec:causality}

Causality, in its simplest form, is the principle that a cause must precede its effect. In classical physics, this relationship is both intuitive and absolute: time flows uniformly, and all observers agree on the sequence of events. This framework offers no ambiguity — if event A causes event B, then all observers agree that A occurred before B.

In this context, causality is not something that needs to be enforced — it is built into the structure of time itself. There is no room for disagreement about ``what happened first.'' This clarity begins to dissolve, however, in the relativistic domain.

Special relativity introduces the concept of frame-dependent simultaneity. That is, two events that are simultaneous in one frame may not be simultaneous in another. If signals could propagate faster than light, it would be possible — under certain transformations — for an observer to see an effect precede its cause.

The diagram below illustrates how two observers in relative motion can disagree on the temporal order of events connected by a hypothetical superluminal signal.

As shown in Figure~\ref{fig:causality}, if a signal exceeds the speed of light, an observer in a different inertial frame may perceive the effect before the cause.

 \vspace{2em}



\begin{figure}[h!]
\centering
\begin{tikzpicture}[scale=1.1, every node/.style={font=\small}]

% Axes
\draw[->] (-1,0) -- (5,0) node[right] {Space};
\draw[->] (0,-0.5) -- (0,5) node[above] {Time};

% Light cone
\draw[gray, dashed] (0,0) -- (4,4);
\draw[gray, dashed] (0,0) -- (-1,1);

\node[gray] at (2.2,2.2) {\( c \)};
\node[gray] at (-0.9,1.1) {\( -c \)};

% Events
\filldraw[black] (0,0) circle (2pt) node[below left] {A (cause)};
\filldraw[black] (3,1.5) circle (2pt) node[below right] {B (effect)};

% Superluminal signal
\draw[thick, red, ->] (0,0) -- (3,1.5);

% Observer worldlines
\draw[blue, thick] (1,0) -- (1,4.5) node[above] {Observer 1};
\draw[green!70!black, thick] (4,0) -- (2,4) node[above] {Observer 2};

% Event projection lines (Observer 2's time axis)
\draw[dashed, green!70!black] (3,1.5) -- (1,3.5);



\end{tikzpicture}
\caption{Superluminal signal reverses causal order in some frames. Without a speed limit, relativistic transformations can invert cause and effect.\vspace{2em}}

\label{fig:causality}
\end{figure}


\clearpage





\begin{figure}[h!]
\centering
\begin{tikzpicture}[scale=1, every node/.style={font=\small}]

% Axes
\draw[->] (-0.5,0) -- (4,0) node[right] {Space};
\draw[->] (0,-0.5) -- (0,4.5) node[above] {Time};

% Events
\filldraw[black] (0,0) circle (2pt) node[below left] {A (cause)};
\filldraw[black] (2.2,1.5) circle (2pt) node[below right] {B (effect)};

% Instantaneous signal
\draw[thick, red, ->] (0,0) -- (2.2,1.5);

% Observer worldlines (Newtonian: vertical)
\draw[blue, thick] (0.8,0) -- (0.8,4) node[above] {Obs. 1};
\draw[green!70!black, thick] (2.8,0) -- (2.8,4) node[above] {Obs. 2};

\end{tikzpicture}
\caption{Under Newtonian mechanics, time is absolute and universal. All observers agree on the sequence A → B, even if the signal travels faster than light.\vspace{10em}}
\label{fig:newtonian}
\end{figure}











\begin{tcolorbox}[colback=blue!5!white, colframe=blue!60!black, title=Sidebar: Who Enforces Causality?, fonttitle=\bfseries]

Causality — the principle that causes precede effects — is not universally enforced the same way across physical theories.

\begin{itemize}
  \item \textbf{In Newtonian physics}, causality is a given: time is absolute, and all observers agree on sequence.
  \item \textbf{In Special Relativity}, causality is threatened by observer-dependent simultaneity — and preserved only by enforcing the light-speed limit \( c \).
  \item \textbf{In General Relativity}, causality is encoded in the geometry of curved spacetime via local light cones.
\end{itemize}

Thus, \( c \) is not a metaphysical enforcer of causality — it's a structural constraint within the relativistic models where simultaneity is broken.

\end{tcolorbox}


\vspace{2em}
\vspace{2em}



\section{Why Causality Matters — And Why It Must Be Preserved}
\label{sec:whycausality}

Causality is not an arbitrary aesthetic principle — it is an observed regularity in the physical world. Across all domains of everyday and experimental experience, we see a consistent rule: effects follow causes, not the reverse. Dropped objects fall \emph{after} being released, reactions occur \emph{after} initiations, and signals are received \emph{after} transmission. This consistent directionality compels us to build physical theories that respect it.

Thus, the reason to ``protect'' causality is not metaphysical — it is empirical. If we routinely observed backward-in-time effects or inconsistent causal ordering, we might accept theories that permit them. But in the absence of such phenomena, our physical models must reflect the apparent unidirectionality of influence.

In this light, the role of \( c \) becomes clearer. In special and general relativity, time is no longer absolute, and observers can disagree about when events occur. This opens the door to paradox unless some invariant structure — like a maximum signal speed — is imposed to limit how information can propagate. The speed of light \( c \) fulfills that role, but only because the relativistic framework creates the possibility of disagreement in the first place.

Therefore, we do not protect causality for its own sake. We protect it because our physical models must match what we observe — and what we observe is consistent, one-way causal ordering. Any acceptable theory of physics must account for this regularity, whether it does so via light cones, geometric constraints, or some other mechanism entirely.


\vspace{2em}

\begin{figure}[h!]
\centering
\begin{tikzpicture}[scale=0.9, every node/.style={font=\small}]

% Axes
\draw[->] (-0.8,0) -- (3.5,0) node[right] {Space};
\draw[->] (0,-0.5) -- (0,4.5) node[above] {Proper Time};

% Light cone (curved for GR illustration)
\draw[gray, dashed, domain=0:2.2, samples=100] plot ({1.2*\x*\x},\x);
\draw[gray, dashed, domain=0:2.2, samples=100] plot ({-0.8*\x*\x},\x);

\node[gray] at (2.1,1.5) {\( +c \)};
\node[gray] at (-1.0,1.5) {\( -c \)};

% Events
\filldraw[black] (0,0) circle (2pt) node[below left] {A};
\filldraw[black] (1.6,2) circle (2pt) node[right] {B};

% Causal path within cone (allowed)
\draw[thick, blue, ->] (0,0) -- (1.6,2);

% Disallowed region (narrowed)
\path[pattern=north east lines, pattern color=red!30] (1.8,1.8) -- (2.2,2.5) -- (2.2,0.2) -- (1.8,-0.4) -- cycle;
\node[red!60!black] at (2,1) {Acausal};

\end{tikzpicture}
\caption{In general relativity, light cones may curve and tilt due to gravity, but locally they always define the causal structure. Signals cannot exit the cone without violating causality.\vspace{2em}}
\label{fig:grlightcone}
\end{figure}




\section{How Causality Breaks Without \( c \) — In Relativistic Frameworks}
\label{sec:causalitybreaks}

Once special relativity is accepted, simultaneity is no longer absolute. Two observers in relative motion may disagree on whether events A and B occurred in the same order, or even on whether they occurred at all. This disagreement only becomes problematic when information or influence can propagate between spacelike-separated events — that is, if signals can travel faster than light.

To illustrate, consider the following thought experiment:

\begin{itemize}
  \item Observer Alice emits a superluminal signal from event A to event B.
  \item In her frame, A causes B — the signal moves forward in time.
  \item But due to Lorentz transformations, a second observer Bob (moving at a high relative velocity) sees event B occur \emph{before} event A.
  \item If Bob can now send a return superluminal signal from B back to A, then from Alice’s perspective, the signal from Bob arrives \emph{before she sent hers}.
\end{itemize}

This forms a closed causal loop, violating logical consistency. In such a system, it becomes possible to receive a reply to a message before sending it — or even to prevent the message from being sent in the first place, creating paradoxes of the type associated with time travel and backward causation.

Mathematically, the breakdown arises from the structure of Minkowski spacetime. Lorentz transformations mix space and time coordinates in such a way that the temporal ordering of spacelike-separated events becomes frame-dependent. When signal velocity exceeds \( c \), the separation between ``cause'' and ``effect'' enters the spacelike region — where different observers disagree on which event came first.

Thus, within the framework of special relativity, \( c \) is not merely a limit on speed — it is a limit on causal ambiguity. It defines the light cone, separating events into:

\begin{itemize}
  \item \textbf{Timelike related}: Events can influence one another, and all observers agree on order.
  \item \textbf{Spacelike related}: Events are too far apart in space and too close in time to be causally connected — and order depends on frame.
\end{itemize}

Removing the light-speed limit in this framework allows causal paradoxes to emerge. This is the origin of the oft-repeated claim: ``\( c \) preserves causality.'' But as emphasized throughout this paper, it does so only within a structure that \emph{requires} such a limit to function consistently.

In Newtonian mechanics, where time is absolute and global, there is no such risk — faster-than-light signaling does not invert causal order. The need for a causal boundary arises uniquely from the relativistic redefinition of time and simultaneity.


\section{Causality Without \texorpdfstring{$c$}{c}: Relativity vs Newton}
\label{sec:newtonian}

Before the advent of relativity, physics operated under the assumption that time was universal and absolute. In Newtonian mechanics, every observer shares the same global clock. Events occur in a fixed order across all reference frames, and simultaneity is unambiguous. This framework naturally upholds causality — not by enforcing it through constraints, but by building it into the fabric of time itself.

In this setting, there is no conceptual barrier to instantaneous action-at-a-distance. Newton's law of universal gravitation, for example, originally assumed that gravitational forces were applied instantaneously, regardless of distance. While later developments (such as field theory and eventually general relativity) replaced this notion with finite-speed propagation, the instantaneous model never created causal paradoxes within Newtonian mechanics. The absolute time coordinate ensures that all observers agree on the order of events.

To illustrate this, consider two spatially distant observers, Alice and Bob. If Alice sends an instantaneous signal to Bob, both agree that the signal was sent before it was received. There is no disagreement about sequence, because there is no frame-dependent time distortion. No observer can ever witness an effect before its cause, no matter how fast the signal travels.

Thus, in Newtonian physics:

\begin{itemize}
  \item Time is the same for all observers.
  \item Simultaneity is globally defined.
  \item All causal relationships are invariant across frames.
  \item There is no need for a speed limit to preserve causality.
\end{itemize}

This stands in sharp contrast to the relativistic picture, where time is malleable, simultaneity is relative, and causality requires geometric enforcement via the light cone structure. The Newtonian model demonstrates that causality is structurally robust when time is absolute — and that the need for a speed constraint like \( c \) arises only when simultaneity breaks down.

In this sense, the Newtonian case serves as a clean control: a reminder that causal consistency does not inherently require a maximum signal velocity. It is only when time itself becomes a coordinate tied to motion and perspective that the risk of causal ambiguity — and the need for constraints — emerges.

\section{General Relativity and the Geometry of Causality}
\label{sec:grcausality}

General relativity (GR) extends the principles of special relativity into a dynamic, curved spacetime. Rather than treating gravity as a force acting at a distance, GR describes it as a manifestation of spacetime curvature caused by energy and mass. In this framework, the speed of light \( c \) remains locally constant, but the geometry of spacetime is no longer fixed and flat — it bends and evolves in response to matter and energy.

In GR, causality is preserved not through an invariant signal speed in flat space, but through the local structure of spacetime itself. Each point in spacetime has a light cone — a geometric object that defines the boundary between causally connected and disconnected events. The light cone tilts and narrows in the presence of strong gravitational fields, but it always remains intact locally.

\subsection{Local Light Cones and Causal Order}
\label{subsec:lightcones}

In curved spacetime, what replaces the global invariance of \( c \) is the \emph{local} causal structure defined by the metric tensor \( g_{\mu\nu} \). At each point in spacetime, the light cone delineates which directions in spacetime are:

\begin{itemize}
  \item \textbf{Timelike}: Paths slower than light — causal communication possible.
  \item \textbf{Lightlike (null)}: Paths at exactly the speed of light.
  \item \textbf{Spacelike}: Paths faster than light — not causally connected.
\end{itemize}

Even in a curved manifold, these classifications hold at every point, ensuring that causal relations respect local geometry. A signal or object cannot jump outside its light cone without violating the local structure of spacetime.

\paragraph{Coordinate-Free Viewpoint}
From a coordinate-independent perspective, general relativity enforces causal order via the local structure of the metric tensor \( g_{\mu\nu} \). The Lorentzian signature \((-,+,+,+)\) ensures that spacetime can be locally divided into timelike, null, and spacelike intervals. These distinctions are geometric and invariant, forming the basis of light cone structure without requiring any specific coordinate system. As a result, causality is not tied to observer coordinates but emerges from the intrinsic geometry of the manifold itself.


\subsection{Global Pathologies and Causality Loops}
\label{subsec:pathologies}

Despite this local rigor, general relativity admits certain exotic solutions — such as Gödel’s rotating universe or Kerr black holes — in which light cones twist and loop back on themselves, forming \emph{closed timelike curves} (CTCs). These are paths in spacetime that return to their own past, raising deep questions about determinism and consistency.

Such solutions are generally considered nonphysical or unstable. In fact, Stephen Hawking proposed the \textit{Chronology Protection Conjecture}, which asserts that the laws of physics may prevent the formation of CTCs under realistic conditions, thus “making the universe safe for historians.” While not proven in general, many semiclassical analyses suggest that quantum effects — such as vacuum polarization — might destabilize or prevent time machine-like geometries from forming in practice.

Nevertheless, these pathologies serve as a reminder: in GR, causality is not an axiom but a feature of the geometry. The existence of CTC-permitting solutions implies that causality is preserved in most — but not all — GR spacetimes. The structure of the light cone is what enforces causal order, and if that structure is distorted sufficiently, causality can, in principle, break down.

\vspace{2em}


\begin{tcolorbox}[
  colback=purple!5!white,
  colframe=purple!70!black,
  title=Sidebar: Causality Is Not Enforced — It Emerges,
  fonttitle=\bfseries,
  sharp corners=south,
  breakable
]



Once we’ve accepted that spacetime is not fixed, but curved and dynamic (bent), the role of \( c \) becomes a \emph{manifestation} of causal structure — not its enforcer.

Causality is preserved locally in general relativity because the geometry of spacetime allows it to be. The light cones at each point define the boundary between what can and cannot be causally connected — and \( c \) is simply the slope of that boundary.

Thus, \( c \) does not impose causal order from outside; it emerges \textit{within} a model where time and space have already been geometrically fused.
\end{tcolorbox}




\vspace{2em}

\subsection{The Role of \texorpdfstring{$c$}{c} in GR}
\label{subsec:roleofc}

Importantly, \( c \) remains the maximum speed of causal influence — but it is now a \emph{local} condition. There is no universal reference frame to measure speeds globally, nor is there a global concept of simultaneity. Instead, GR relies on the manifold’s geometry to enforce causal order at each point.

Thus, in general relativity, causality is preserved by:

\begin{itemize}
  \item The local invariance of \( c \) in the tangent space of each point.
  \item The global coherence of the light cone structure, dictated by the spacetime metric.
\end{itemize}

This represents a shift from the SR picture: \( c \) is no longer a flat-space horizon, but the slope of the cone that defines allowable causal paths through a curved spacetime. The need to ``protect'' causality still exists, but the mechanism now lies in geometry rather than velocity alone.





\section{Quantum Mechanics and the Boundary of Causal Constraint}
\label{sec:qmcausality}

Quantum mechanics introduces a new set of challenges to the classical concept of causality. While it does not violate the core principle that effects follow causes in observable outcomes, it does present phenomena — such as entanglement — that seem to exhibit instantaneous correlations between spacelike-separated events. This raises the question: does quantum theory respect causal structure in the relativistic sense?

The answer, supported by both theory and experiment, is yes — though in subtle ways. This phenomenon was first highlighted in the Einstein-Podolsky-Rosen (EPR) paradox~\cite{epr1935}, and later confirmed through Bell test experiments~\cite{bell1964}. Landmark modern tests, such as the loophole-free experiment by Hensen \textit{et al.}~\cite{hensen2015}, have demonstrated that entangled particles exhibit correlations that defy classical explanation, even when separated by spacelike intervals.




\subsection{Entanglement and Nonlocal Correlations}
\label{subsec:entanglement}

In entangled systems, measurements performed on one particle appear to instantaneously influence the outcome of measurements on another particle, even when the two are separated by distances that preclude any light-speed communication. This phenomenon was first highlighted in the Einstein-Podolsky-Rosen (EPR) paradox~\cite{epr1935}, and later confirmed through Bell test experiments~\cite{bell1964}.

Importantly, these correlations do not allow for superluminal signaling. The no-signaling theorem ensures that while the outcomes of entangled measurements are correlated, no information can be transmitted faster than light. Thus, quantum mechanics preserves causality at the level of observable communication, even if the internal structure of the theory appears nonlocal.




\subsection{Causal Order and Measurement}
\label{subsec:measurementorder}

Unlike classical physics, quantum mechanics does not assign deterministic outcomes to all events in advance. Instead, outcomes are probabilistically determined, and their correlations may depend on measurement context. This leads to subtleties in defining causal order, especially when considering delayed-choice experiments, quantum erasers, and protocols involving indefinite causal structure.

Despite these complexities, quantum theory respects the constraints imposed by relativity. All observable effects — all measurable, usable outcomes — remain consistent with the light cone structure. Entanglement does not allow the construction of a causal loop or the violation of time-ordering in any frame that could be experimentally verified.

\subsection{The Role of \texorpdfstring{$c$}{c} in Quantum Theory}
\label{subsec:roleofcqm}

Unlike general relativity, quantum mechanics does not have a geometric spacetime background built into its formalism. Time is treated as a global parameter, not as a coordinate within a dynamic manifold. In this context, the speed of light \( c \) is not derived from geometric curvature but rather appears as a constraint inherited from the relativistic theories it must remain compatible with — particularly quantum field theory (QFT).



In quantum field theory:

\begin{itemize}
  \item Fields are defined over spacetime and must commute at spacelike separations to preserve causality.
  \item This ensures that operators corresponding to observables in spacelike regions do not influence one another.
  \item The structure of QFT depends on Lorentz invariance~\cite{streater2000}. — and therefore inherits the causal limits imposed by \( c \).
\end{itemize}


Thus, quantum mechanics — especially in its relativistic form, such as quantum field theory (QFT) — respects causality by construction \cite{streater2000}. Even when nonlocal effects appear, they are structured in such a way that they cannot transmit usable information faster than light.

\subsection{Summary}
\label{subsec:qmsummary}

Quantum mechanics appears to flirt with causality violations, but never crosses the line. While nonlocal correlations challenge classical intuitions, they are always bounded by the constraints of special relativity. The role of \( c \) in quantum mechanics is therefore more about compatibility than enforcement: it defines the limit that quantum field theory must not exceed, even as it permits strange behaviors within it.


\section{Reframing \texorpdfstring{$c$}{c}: From Protector of Causality to Consequence of Structure}
\label{sec:reframingc}

Throughout this paper, we have traced the role of the speed of light \( c \) across multiple physical frameworks: Newtonian mechanics, special and general relativity, and quantum theory. At each stage, the relationship between \( c \) and causality has shifted — not because the concept of causality itself changes, but because the underlying structure of time and space evolves.

In Newtonian mechanics, time is absolute and causality is guaranteed. There is no need for a limiting velocity. One could, in principle, send a signal instantaneously without creating a paradox, because all observers share a common global clock. In this world, \( c \) is irrelevant to causal order.

In special relativity, time becomes relative and simultaneity becomes frame-dependent. This opens the door to causal ambiguity, where different observers may disagree on the sequence of events. Here, \( c \) is not just the maximum speed of signal propagation — it is the slope of the light cone that defines what causal structure is even possible. It becomes necessary to prevent contradictions and closed causal loops.

In general relativity, spacetime itself is curved and dynamic, and causality is preserved locally by the shape of light cones as dictated by the spacetime metric. Once again, \( c \) appears — but only as a local limit, a structural feature embedded in the geometry, not as an external constraint.

In quantum mechanics and quantum field theory, \( c \) functions as a compatibility requirement. While quantum entanglement displays nonlocal correlations, these effects never violate relativistic causal boundaries. The field-theoretic requirement that operators commute at spacelike separations enforces causal consistency by ensuring that no influence can propagate faster than \( c \).

\subsection{Not a Guardian, But a Boundary Condition}
\label{subsec:notaguardian}

The common mistake is to treat \( c \) as a kind of metaphysical guardian of causality — a divine limit imposed upon the universe to keep cause and effect in line. This framing is backward.

Instead, we should say: the mathematical structures of relativity and quantum field theory \emph{create the conditions under which causality could be broken}. The introduction of frame-dependent simultaneity, or non-commutative operators at a distance, introduces risk. The speed of light then emerges as a necessary limit — not to defend causality in general, but to defend these specific models from self-contradiction.

\subsection{Conclusion}
\label{subsec:reframingconclusion}

The speed of light \( c \) is not the enforcer of causality across all physics. It is the consequence of adopting theories in which time and simultaneity are no longer absolute. Within such theories, \( c \) becomes indispensable — not to protect an external metaphysical principle, but to preserve internal coherence.

Thus, we reframe the claim:

\begin{quote}
\emph{“\( c \) does not protect causality. Causality is protected by the geometry and logic of the model. \( c \) is the slope that prevents those models from folding in on themselves.”}
\end{quote}

This distinction matters. It helps clarify what assumptions our theories are built on — and what principles are being preserved, versus imposed.

\vspace{2em}


\begin{tcolorbox}[
  colback=green!5!white,
  colframe=green!60!black,
  title=Summary Insight: What \( c \) Really Does,
  fonttitle=\bfseries,
  sharp corners=south
]
\textbf{Causality is preserved — not imposed — by the structure of each model.}

\begin{itemize}
  \item In \textbf{Newtonian mechanics}, time is universal and shared. Causality holds without needing any speed limit.
  \item In \textbf{Special Relativity}, time and simultaneity depend on the observer. To avoid contradictions, a maximum signal speed \( c \) is required.
  \item In \textbf{General Relativity}, spacetime bends and evolves. \( c \) defines the slope of local light cones — boundaries for what can cause what.
  \item In \textbf{Quantum Field Theory}, \( c \) ensures that no influence spreads between spacelike regions. It preserves causal consistency even amid entanglement.
\end{itemize}

\textbf{Conclusion:} The speed of light is not a universal enforcer of causality — it is the boundary that keeps certain models logically coherent when time and space are dynamic, observer-dependent, or curved.
\end{tcolorbox}


\vspace{2em}



\section{Conclusion}
\label{sec:conclusion}

The speed of light \( c \) has long held a privileged position in modern physics — not only as a constant of nature, but as a conceptual boundary on what is possible. It is often described as “the speed limit of the universe,” or as a guardian of causality, preventing paradoxes and backward-in-time effects. Yet a closer examination reveals that \( c \) does not serve this role universally. Its necessity arises specifically within theoretical frameworks that modify the classical structure of time.

In Newtonian mechanics, where time is absolute and shared by all observers, there is no logical requirement for a speed limit. Instantaneous action-at-a-distance presents no paradox, and causality is preserved by default. It is only when special relativity redefines time as frame-dependent that causality becomes vulnerable. In this new framework, simultaneity can be broken, and the order of events can vary between observers. To prevent contradiction, the theory imposes a limit — \( c \) — beyond which no influence may propagate.

General relativity carries this logic forward into curved spacetime, embedding causal structure into local geometries defined by light cones. Quantum mechanics, especially in its relativistic form, respects these boundaries even while introducing nonlocal correlations. Across all these systems, \( c \) is not a universal law that enforces causality — it is a consequence of adopting models in which causal order is no longer guaranteed.

This distinction has both pedagogical and philosophical importance. It clarifies that causality is an observed regularity, not an axiom of physics. It reminds us that theoretical features such as light cones, Lorentz invariance, and field commutation rules are designed to preserve that regularity within the specific logical systems we have built. And it reframes the role of \( c \): not as a metaphysical ceiling, but as a geometric constraint that makes those systems coherent.


\emph{“The speed of light is not what protects causality. It is what causality looks like once spacetime has been bent.”}



\footnote{I.e., the observed constraint on cause-effect relationships emerges as a geometric consequence of the curved spacetime manifold.}











\section{Motivation: From Causal Limits to Instructional Origins}
\label{sec:motivation}



This paper does not propose new physical laws — it clarifies the structural meaning of causality across established frameworks. But that clarification is not idle. It serves a specific goal: to prepare the foundation for a new physical model

\footnote{See McKinley (2025), \textit{Causal Instruction Arcs and the Timeless Light Model}, Zenodo. DOI: \href{https://doi.org/10.5281/zenodo.15813253}{10.5281/zenodo.15813253}.}in which causality itself is not an assumption, but an emergent outcome of a deeper mechanism.


\vspace{2em}

\begin{tcolorbox}[colback=blue!4!white, colframe=blue!80!black, title=Bridge to TLM: From Geometry to Instruction, fonttitle=\bfseries]

The preceding sections clarified that the speed of light \( c \) arises from the internal geometry of relativistic models. What follows builds on this by asking: \textit{what if geometry itself is the output of something deeper — a causal instruction set?} 

The \textit{Timeless Light Model} (TLM) emerges as a candidate framework that treats spacetime not as a primitive backdrop, but as a rendered projection of underlying, timeless instructions. In this view, \( c \) is no longer a fundamental enforcer of causality, but a derived constraint — a bound on how delay manifests in the conversion of instruction into appearance.
\end{tcolorbox}

\vspace{2em}



In the \textit{Timeless Light Model} (TLM), all observable events arise from a complete instruction set that exists outside of time. Rather than treating spacetime as the arena in which cause and effect unfold, TLM proposes that all events are instigated by a deeper, timeless substrate. In this view, the role of \( c \) is not to enforce causality, but to introduce the observable delay between the determination and realization of any action. Spacetime, then, is not fundamental — it is a projected manifestation of deeper sequential commands. The speed of light emerges not as a primitive constant, but as a derived constraint of the projection process itself.




These instructions are structured as \textbf{Causal Instruction Arcs (CI-ARCs)} — timeless, encoded directives that govern the observed sequence of cause and effect. From the perspective of the TLM, causality does not arise from propagation, but from deployment delay. What we experience as causal flow is the delayed resolution of prewritten instructions.

This reframing of causality — and of \( c \) itself — is a prerequisite for understanding that model.
Hence the purpose of this paper: not to challenge physics, but to prepare the ground for a theory
that treats causality as the result of simulation parameters, not geometry.


\subsection*{Falsifiability Example: A Concrete Prediction}
\label{subsec:falsifiability}

While full falsifiability criteria are detailed in McKinley (2025)\footnote{See McKinley (2025), \textit{Causal Instruction Arcs and the Timeless Light Model}, Zenodo. DOI: \href{https://doi.org/10.5281/zenodo.15813253}{10.5281/zenodo.15813253}.}, one example illustrates the testable predictions of the TLM framework:

\vspace{2em}

\begin{tcolorbox}[colback=white!95!gray, colframe=black!60!black, title=Testable Prediction, fonttitle=\bfseries]
If CI-ARCs impose an instruction delay \( T \), then high-energy photons traversing strong gravitational fields should exhibit a small, but measurable, residual phase-shift mismatch compared to general relativity predictions. This deviation is expected to manifest as a persistent offset in pulse timing or interference fringes, detectable by next-generation attosecond interferometry near black holes or neutron stars.
\end{tcolorbox}

\vspace{2em}

This prediction preserves GR at low energies and weak fields but diverges subtly at the highest precision scales. It offers a falsifiable signal — one that distinguishes instructional delay from purely geometric propagation models.


\subsection{Why CI-ARCs Are Acausal - (no prior cause within spacetime)}
\label{subsec:ciarcacausal}

CI-ARCs are acausal in the temporal sense because they are not located \textit{within} the spacetime they instruct. They originate from a timeless layer and are executed into spacetime with delay \( T \), but they themselves are not the result of prior physical events. Unlike field equations, which require boundary conditions and prior states, CI-ARCs encode complete outcomes from outside the causal chain.

This acausality is not a rejection of cause and effect — it is a relocation of their origin. Physics explains how outcomes unfold given initial conditions. It tells us \textit{what} happens, but not \textit{why} those conditions exist in the first place. Physics explains what happens, and how it happens — but not why the rules are what they are. That’s not a failure; it’s the nature of models. Between physics and religion lies an unclaimed territory: the \textit{design layer} — structures outside spacetime that make the model possible.

\vspace{2em}

\begin{tcolorbox}[colback=white!97!gray, colframe=black!50!black, title=Illustrative Example: CI-ARC and Muon Decay, fonttitle=\bfseries]

Imagine a muon decaying into an electron and neutrinos:
\[
\mu^- \rightarrow e^- + \bar{\nu}_e + \nu_\mu
\]
In the Timeless Light Model (TLM), this entire decay sequence is represented as a single Causal Instruction Arc (CI-ARC). The CI-ARC encodes both:
\begin{itemize}
  \item the \textbf{trigger state} — the existence and conditions of the muon, including its proper-time delay \( T \), and
  \item the \textbf{resolved outcome} — the rendered state of the resulting particles, including their trajectories and interaction paths.
\end{itemize}

No information is propagated across spacetime in the conventional sense. Instead, the final state unfolds as a rendered outcome of a pre-written instruction. What appears as stochastic decay in standard quantum mechanics is, under TLM, the resolution of a timeless instruction arc that always contained both the conditions and consequences of the event.
\end{tcolorbox}

\vspace{2em}

\subsection{Physics Says ``That'', Not ``Why''}
\label{subsec:physicswhy}


As Wheeler wrote~\cite{wheeler1990}, physics is about “the eternally given.”  It describes consistent rules, but cannot justify why those rules — and not others — apply. In this sense, all physical theories are declarations of structure, not explanations of origin. To ask \textit{why} there is causality at all — or why \( c \) defines its limit — is to step beyond physics.

The TLM embraces this division. It does not attempt to derive physical laws from within spacetime, but instead proposes that spacetime is a rendered consequence of timeless instruction. In doing so, it reframes causality itself: from a geometric or field-theoretic constraint, to an emergent delay in the deployment of external commands.




\vspace{2em}






\begin{tcolorbox}[
  colback=blue!4!white,
  colframe=blue!75!black,
  title=Briefing Part I: What Standard Relativity Tells Us,
  fonttitle=\bfseries,
  sharp corners=south
]

\textbf{ Standard Relativity (GR): What Everyone Agrees On}

\begin{enumerate}
  \item \textbf{The universal speed limit is \( c \)}. Nothing outruns light in vacuum — this caps all causal influence.
  \item \textbf{Massive objects can’t reach \( c \)}. Energy requirements diverge as speed increases — infinite energy is needed to match light.
  \item \textbf{Strange things happen at near-\( c \)} speeds:
  \begin{itemize}
    \item To outside observers: fast-moving clocks run slow.
    \item To the traveler: time feels normal, but vast time has passed for others.
  \end{itemize}
  \item \textbf{Photons are massless, so they always move at \( c \)} — never slower, never faster.
  \item \textbf{At \( c \), time disappears}\footnotemark. A photon experiences zero time between emission and absorption.


\end{enumerate}
\vspace{0.5em}
\textbf{These are not speculations — they follow directly from Einstein’s equations.}
\end{tcolorbox}

\vspace{2em}

\footnotetext{
    This is a standard result in relativity: the proper time along a lightlike (null) worldline is zero. 
    Richard Feynman famously stated that “a photon doesn’t age”~\cite{feynman1985}. 
    The same insight is echoed in the work of Penrose~\cite{penrose2004}, Brian Greene~\cite{greene1999}, and Sean Carroll~\cite{carroll2010}.
  }



\begin{tcolorbox}[
  colback=blue!4!white,
  colframe=blue!75!black,
  title=\title=Briefing Part II: Foundational Premises of the Timeless Light Model,
  fonttitle=\bfseries,
  sharp corners=south
]

\textbf{ From GR to TLM: The Path of Logic}

\begin{enumerate}
  \item \textbf{No time = no motion}. Motion requires time. Without time, light doesn’t “move.”
  \item \textbf{No motion = no space}. Motion defines position change. No motion, no space.
  \item \textbf{Therefore: light is not in spacetime}. We propose the following interpretive premise: Light appears to us as endpoints (emission and detection), but has no presence in between. And further, that a photon’s experience of zero proper time suggests it is not a participant in the sequential unfolding of spacetime. While general relativity models the photon path as a null geodesic within the manifold, the Timeless Light Model treats this as the observable endpoint of a deeper instruction rendered from outside the temporal frame. This is not a necessary consequence of relativity, but a foundational interpretive move. It serves as the launching point for the TLM hypothesis.

  \item \textbf{Light is not in the universe}. It affects the universe — but isn’t part of its evolving, time-based structure.
  \item \textbf{So: something outside spacetime can create observable effects within it}.
  \item \textbf{What we observe is a rendering — a projected instruction from outside time}.
\end{enumerate}

\end{tcolorbox}

\begin{tcolorbox}[
  colback=blue!4!white,
  colframe=blue!75!black,
  title=\title=Briefing Part II: Foundational Premises of the Timeless Light Model,
  fonttitle=\bfseries,
  sharp corners=south
]

\vspace{0.5em}
\textbf{Core Postulates of the Timeless Light Model (TLM)}


\begin{equation}
T \cdot m = \frac{\hbar}{c^2}
\end{equation}

\begin{equation}
T \cdot C_s = 1
\end{equation}

Where:
\begin{itemize}
  \item \( T \) is the instruction delay.
  \item \( m \) is rest mass.
  \item \( C_s \) is the causal deployment rate.
\end{itemize}

\textbf{Conclusion:} Light doesn’t travel — it instructs. Photons are not in spacetime; they render it.

These are not derived from prior theories, but are taken as foundational postulates of the Timeless Light Model. The first,
\[
T \cdot m = \frac{\hbar}{c^2},
\]
is equivalent in form to defining \( T \) as the Compton time of a particle — the characteristic timescale associated with mass \( m \). This connects TLM's instruction delay to established quantum quantities.

The second,
\[
T \cdot C_s = 1,
\]
defines \( C_s \) as the inverse of delay — a causal deployment rate. This postulate governs the appearance rate of events in spacetime, and replaces velocity-based causality with instruction-based delay.

These postulates do not arise from classical derivation, but their falsifiable consequences are explored in McKinley (2025)~\cite{mckinley2025}.


\end{tcolorbox}









\vspace{2em}



\paragraph{Postulates and Their Interpretive Basis.}


The relation 
\[
T \cdot C_s = 1
\]
is introduced in Section~3.4 of McKinley (2025)\footnote{J. C. W. McKinley, \textit{Causal Instruction Arcs and the Timeless Light Model}, Zenodo (2025). DOI: \href{https://doi.org/10.5281/zenodo.15813253}{10.5281/zenodo.15813253}} as the \textit{Instructional Rendering Law}. It formalizes the idea that causal deployment rate \( C_s \) and instruction delay \( T \) are inversely related, such that their product yields a normalized instruction flow across spacetime appearances.

Likewise, the mass-delay relation
\[
T \cdot m = \frac{\hbar}{c^2}
\]
appears in Section~3.2 as part of the Dual Delay Law. It links mass to instruction delay via Planck’s constant and the speed of light squared. This reflects the idea that mass-bound phenomena are delayed manifestations of pre-resolved massless instructions.

Additional dimensional justification and energy-rate discussion are provided in Section~3.5.






\vspace{2em}











\subsection{How This Paper Reframes Causality}
\label{subsec:howreframe}

This paper has shown that the speed of light \( c \) is not the source of causality, but a limit required by models in which simultaneity is broken. It demonstrated that Newtonian mechanics preserves causality without \( c \), and that relativity introduces the risk of causal reversal — which is then constrained by light cones.

By making this distinction clear, we isolate the assumptions that give rise to causal rules. This is crucial, because TLM replaces those assumptions: instead of embedding causality in space and time, it embeds time \textit{within} causal instructions. Causality is not enforced by \( c \); it is revealed by the order in which prewritten instructions are rendered.




\begin{table}[h!]
\centering
\caption{Causality Across Major Physical Frameworks}
\label{tab:causality-comparison}
\vspace{0.5em}
\begin{tabular}{@{}llp{7.5cm}@{}}
\toprule
\textbf{Framework} & \textbf{Role of \( c \)} & \textbf{Causality Enforcement} \\
\midrule
Newtonian Mechanics & Not relevant & Time is absolute; causality is structurally guaranteed without a speed limit. \\
Special Relativity  & Max signal speed & Prevents causal paradox by bounding influence within light cones. \\
General Relativity  & Local cone slope & Light cones curve with geometry; causal structure enforced locally by spacetime curvature. \\
Quantum Mechanics (QFT) & Compatibility constraint & Operators commute at spacelike separation; entanglement is non-signaling. \\
\bottomrule
\end{tabular}
\end{table}




\subsection{Further Reading}
\label{subsec:reading}

For readers interested in the full physical and "design layer" development of this framework, see:

\begin{quote}
\href{https://doi.org/10.5281/zenodo.15813253}{\textit{Causal Instruction Arcs and the 
Timeless Light Model:
A Unified Framework for Physics and Cosmology}}, 
John C. W. McKinley, Zenodo (2025). DOI: \texttt{10.5281/zenodo.15813253}
\end{quote}

This foundational paper presents the complete CI-ARC model, its mathematical infrastructure, simulation implications, and falsifiability criteria.



\section{Philosophical Implications and Metaphysical Context}
\label{sec:philosophy}

The \textit{Timeless Light Model} (TLM), while developed as a physical framework, carries implications that reach into the domains of metaphysics and philosophical inquiry. This section consolidates those broader reflections to maintain a clear distinction between the scientific core of the model and its interpretive extensions.

\vspace{1em}

TLM proposes that all observable events arise from a deeper, timeless instruction set—a view that naturally invites metaphysical interpretation. Concepts such as a \textit{design layer} or \textit{causal instruction lattice} echo long-standing philosophical questions about determinism, agency, and the origin of law-like structure. While such terms may border the metaphysical or theological, they are not essential to the operational or predictive content of the model.

\vspace{1em}

Readers are invited—but not required—to explore these implications. The central elements of the model, including:
\begin{itemize}
  \item the Causal Instruction Arcs (CI-ARCs),
  \item the dual delay laws \( T \cdot C_s = 1 \) and \( T \cdot m = \hbar / c^2 \),
  \item and the reinterpretation of spacetime as a rendered projection layer,
\end{itemize}
stand independently of any metaphysical assumptions. They are presented as formal and falsifiable physics proposals, suitable for critical analysis within the scientific tradition.

\vspace{1em}

By isolating metaphysical discussion in this section, the paper preserves clarity for readers focused strictly on physical theory, while offering a path for those interested in the broader implications of a timeless, instruction-driven universe.




\vspace{2em}


\begin{tcolorbox}[colback=white!97!gray, colframe=purple!60!black, title=Own the Vocabulary: Scientific Definitions of Key Terms, fonttitle=\bfseries]

The \textit{Timeless Light Model} (TLM) intentionally employs terminology that straddles physical and metaphysical domains. To avoid confusion—and to emphasize its scientific rigor—key terms are defined operationally:

\begin{itemize}
  \item \textbf{Authorship}: The point at which a Causal Instruction Arc (CI-ARC) is inserted into the instruction layer. This refers to the origin of causal resolution, not conscious intent or divine will.
  
  \item \textbf{Design Layer}: A pre-deployment instruction set encoding the full causal structure of observable reality. This “design” is algorithmic and structural—not theological or anthropomorphic.
  
  \item \textbf{Timeless Source}: A domain outside the parameterized flow of time (\( t \)), from which instruction sequences are resolved. It implies an ontological substrate, not a supernatural being.
\end{itemize}

These terms serve as bridges between physical causality and deeper interpretive layers. They should be read as scientific metaphors grounded in structural modeling—not religious doctrines or appeals to mysticism.
\end{tcolorbox}


\vspace{2em}






\section{Acknowledgments}

The author acknowledges Richard P. Feynman, who articulated with rare clarity that a photon experiences no passage of time. As he wrote:

\begin{quote}
“In the limit that the mass goes to zero, the proper time goes to zero. A photon ‘doesn’t age.’”
\end{quote}

\noindent
This insight, often overlooked or underestimated, helped shape the foundation for rethinking the relationship between time, causality, and light.

\vspace{1em}
\noindent
\textit{Source:} Richard P. Feynman, \textit{QED: The Strange Theory of Light and Matter}, Princeton University Press (1985), p. 89.




\TLMdivider



\section{Glossary}
\label{sec:glossary}

\begin{description}[style=nextline, leftmargin=1.8cm, labelwidth=1.6cm]

\item[\( T \)] 
Instruction delay. The time delay between when a causal instruction is resolved in the timeless layer and when it manifests as an observable event in spacetime. In the Timeless Light Model (TLM), \( T \) replaces proper time for massless particles.

\item[\( C_s \)] 
Causal deployment rate. Defined as the inverse of \( T \), i.e., \( C_s = \frac{1}{T} \). Represents the rate at which causal instructions are deployed into the observable frame. Not to be confused with \( c \), the speed of light; \( C_s \) is an abstract rate of manifestation rather than physical motion.

\item[CI-ARC]
Causal Instruction Arc. A timeless, non-propagating instruction that encodes both the trigger and outcome of an event. CI-ARCs exist outside spacetime and are deployed into it with a delay \( T \). Unlike propagating fields or signals, CI-ARCs do not transmit through space — they instantiate outcomes according to prewritten instructions.

\item[Photon]
In TLM, a photon is not a particle traveling through spacetime, but a rendered instruction that appears simultaneously at emission and absorption points. It has zero proper time and does not exist “in between” these endpoints.

\item[Light Cone]
In relativity, the boundary structure that defines what events can causally influence or be influenced by a given point in spacetime. In TLM, light cones are interpreted as emergent shadows of CI-ARC deployment boundaries.

\item[Spacetime]
A four-dimensional coordinate system combining space and time, used in relativity. In TLM, spacetime is treated not as a substrate but as a rendered output — the projection of timeless instructions.

\item[Causality]
In classical physics, the principle that effects follow causes. In TLM, causality arises from the order of instruction execution, not from physical propagation. Cause and effect are deployed in sequence, but are not generated from within the observable frame.

\item[Instruction Layer (PIL)]
The Photon Instruction Layer (PIL) is the hypothesized timeless substrate from which all observable events are derived. It contains CI-ARCs and governs the sequence of deployed events in spacetime.

\item[Simulation Delay]
The observable time \( T \) that emerges between instruction resolution and manifestation. Gives rise to the appearance of motion, sequence, and causality within rendered spacetime.

\item[Mass \( m \)]
Defined in TLM via the delay relation \( T \cdot m = \hbar / c^2 \). Mass reflects the degree of delay applied to an instruction — the more massive an object, the longer it takes for its instruction to fully render.

\end{description}


\TLMdivider


\begin{thebibliography}{9}

\bibitem{einstein1905}
A. Einstein, 
"Zur Elektrodynamik bewegter Körper" [On the Electrodynamics of Moving Bodies], 
\textit{Annalen der Physik} \textbf{17}, 891–921 (1905).

\bibitem{epr1935}
A. Einstein, B. Podolsky, and N. Rosen, 
"Can Quantum-Mechanical Description of Physical Reality Be Considered Complete?", 
\textit{Phys. Rev.} \textbf{47}, 777 (1935).

\bibitem{bell1964}
J. S. Bell, 
"On the Einstein-Podolsky-Rosen Paradox", 
\textit{Physics} \textbf{1}, 195–200 (1964). (This work initiated the era of experimental tests of local realism.)


\bibitem{streater2000}
R. F. Streater and A. S. Wightman, 
\textit{PCT, Spin and Statistics, and All That}, 
Princeton University Press (2000).

\bibitem{hawking1992}
S. W. Hawking, 
"Chronology protection conjecture", 
\textit{Phys. Rev. D} \textbf{46}, 603–611 (1992).

\bibitem{hensen2015}
B. Hensen \textit{et al.}, 
"Loophole-free Bell inequality violation using electron spins separated by 1.3 kilometres",
\textit{Nature} \textbf{526}, 682–686 (2015).

\bibitem{feynman1985}
R. P. Feynman, 
\textit{QED: The Strange Theory of Light and Matter}, 
Princeton University Press, Princeton, NJ (1985).


\bibitem{penrose2004}
R. Penrose, 
\textit{The Road to Reality: A Complete Guide to the Laws of the Universe}, 
Jonathan Cape (2004).

\bibitem{greene1999}
B. Greene, 
\textit{The Elegant Universe: Superstrings, Hidden Dimensions, and the Quest for the Ultimate Theory}, 
W. W. Norton \& Company (1999).

\bibitem{carroll2010}
S. Carroll, 
\textit{From Eternity to Here: The Quest for the Ultimate Theory of Time}, 
Dutton (2010).

\bibitem{wheeler1990}
J. A. Wheeler, “Information, Physics, Quantum: The Search for Links,” in *Complexity, Entropy and the Physics of Information*, ed. W. H. Zurek, Addison-Wesley (1990).

\bibitem{mckinley2025}
J. C. W. McKinley, 
\textit{Causal Instruction Arcs and the Timeless Light Model: A Unified Framework for Physics and Cosmology}, 
Zenodo (2025). DOI: \href{https://doi.org/10.5281/zenodo.15813253}{10.5281/zenodo.15813253}.









\end{thebibliography}





\end{document}
```

</details>

---
{% endraw %}
