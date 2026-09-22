---
layout: default
title: '[2025] Spacelessness as a Consequence of Timelessness in the Quantum Platform of the Timeless Light Model'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/spacelessness-as-a-consequence-of-timelessness-in-the-quantum-platform-of-the-timeless-light/
paper: true
---
{% raw %}
# [2025] Spacelessness as a Consequence of Timelessness in the Quantum Platform of the Timeless Light Model
*   **DOI:** [10.5281/zenodo.16350754](https://doi.org/10.5281/zenodo.16350754)
*   **Date:** 23 July 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[11pt]{article}
\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage[a4paper,margin=1in]{geometry}
\usepackage{lmodern}
\usepackage{amsmath, amssymb, amsthm}
\usepackage{graphicx}
\usepackage{caption}
\usepackage{subcaption}
\usepackage{tikz}
\usepackage{pgfplots}
\pgfplotsset{compat=1.18}
\usepackage{hyperref}
\usepackage{cleveref}
\usepackage{titlesec}
\usepackage{fancyhdr}
\usepackage{enumitem}
\usepackage{upgreek}
\usepackage{xcolor}
\usepackage{booktabs}
\usepackage{longtable}
\usepackage{array}
\usepackage[most]{tcolorbox}
\tcbuselibrary{breakable, skins}

\usetikzlibrary{arrows.meta, positioning, calc, shapes.geometric, decorations.pathmorphing, patterns, math}

\hypersetup{
    colorlinks=true,
    linkcolor=blue,
    citecolor=blue,
    urlcolor=blue,
    pdftitle={Spacelessness as a Consequence of Timelessness},
    pdfauthor={J. C. W. McKinley}
}

\titleformat{\section}{\large\bfseries}{\thesection}{1em}{}
\titleformat{\subsection}{\normalsize\bfseries}{\thesubsection}{1em}{}

\title{Spacelessness as a Consequence of Timelessness in the Quantum Platform of the Timeless Light Model}
\author{John C. W. McKinley \\ Independent Researcher \\ \href{https://orcid.org/0009-0005-7097-5035}{0009-0005-7097-5035}}
\date{July 2025}

\begin{document}

\maketitle

\renewcommand{\thefootnote}{}
% New DOI
\footnotetext{This version published at \href{https://doi.org/10.5281/zenodo.16350754}{https://doi.org/10.5281/zenodo.16350754}.}

\begin{abstract}
In the Timeless Light Model (TLM), the Quantum Platform (QP) is defined as a timeless domain from which all physical phenomena are deployed into the spacetime frame. This paper defends the logical extension of that premise: that a truly timeless domain must also be \textit{spaceless}. We argue that space has no definable or operational meaning in the absence of time, since all spatial metrics require change—motion, separation, or progression—to be observed or defined. As a result, the QP is not merely timeless but also devoid of geometric or locational structure. This insight reframes discussions around causality, entanglement, and the nature of physical law by establishing that space itself is a rendered artifact, not a foundational substrate.
\end{abstract}


\section{Introduction}

The Timeless Light Model (TLM) proposes that all observable phenomena are deployed from a foundational layer—the Quantum Platform (QP)—which is fundamentally outside of time. While this premise is widely accepted within the model, a deeper implication often goes unstated: \textit{timelessness necessitates spacelessness}. This paper formalizes that claim.

In physics and philosophy alike, time and space are usually treated as linked but independent entities. We challenge this assumption. Without temporal change, we argue, space has no operational meaning. There is no traversal, no measurement, and no distinction of location without time. Therefore, if the QP is timeless, it cannot contain or refer to space.

We develop this thesis in four steps: (1) analyzing the logical dependence of space on time, (2) applying this dependency to the QP under TLM, (3) resolving quantum paradoxes like entanglement and wavefunction collapse using this insight, and (4) critiquing other models that posit timeless geometries.

Finally, we propose a set of falsifiable predictions based on this framework—highlighting where experiments might detect the absence of spacetime structure prior to rendering. In doing so, we reinforce the idea that the QP is not just pre-spacetime but \textit{outside} all geometry altogether.

The foundational axioms and mathematical structure referenced throughout this paper are drawn from McKinley’s synthesis \cite{mckinley2025}.


\begin{figure}[h!]
\centering
\begin{tikzpicture}[every node/.style={font=\large}]

% QP Box
\node[draw, rounded corners, minimum width=5cm, minimum height=3.5cm, align=center, fill=blue!5] (QP) at (-4,0) {
    \textbf{Quantum Platform (QP)}\\
    \textit{Timeless \& Spaceless}\\[1ex]
    \textbullet\ No geometry\\
    \textbullet\ No motion\\
    \textbullet\ Causal resolutions only
};

% SDF Box
\node[draw, rounded corners, minimum width=5cm, minimum height=3.5cm, align=center, fill=green!5] (SDF) at (4,0) {
    \textbf{Spacetime Deployment Frame (SDF)}\\
    \textit{Space \& Time Rendered}\\[1ex]
    \textbullet\ Observable geometry\\
    \textbullet\ Motion and change\\
    \textbullet\ Entropic unfolding
};

% Arrow connecting them
\draw[->, thick, >=Stealth] (QP.east) -- node[below=1in, font=\bfseries\footnotesize] {Causal Deployment (Instructions Rendered)} (SDF.west);

% Optional annotations
\node[above=1cm of QP, align=center, font=\scriptsize\large] {No \underline{space} because no \underline{change}\\No clocks, no distances};
\node[above=1cm of SDF, align=center, font=\scriptsize\large] {Rendered change\\defines space and time};

\end{tikzpicture}
\caption{Causal flow from the Quantum Platform (QP) into the Spacetime Deployment Frame (SDF). The QP is timeless and spaceless; space and time emerge only during rendering into SDF.}
\label{fig:qp_sdf_diagram}
\end{figure}

\vspace{1cm}
















\section{The Dependence of Space on Time}

The idea that space can exist independently of time is common in both casual speculation and in some formulations of theoretical physics. Yet upon closer inspection, this notion collapses under both philosophical scrutiny and physical logic. In this section, we show that space is not just correlated with time—it is \emph{dependent} on it for its definition, observability, and causal function.

\subsection{Philosophical Foundations}

From the pre-Socratic Heraclitus to modern thinkers like Julian Barbour, the inseparability of space and change has been a recurring insight. Heraclitus famously asserted that "everything flows," emphasizing that all existence is marked by flux. For him, being and becoming are inseparable—there is no static ontology. Leibniz similarly rejected Newton’s notion of absolute space, arguing instead for a relational view: space has no independent reality but is simply the order of coexistences, defined by relations between entities, which are themselves in flux.

Heraclitus famously asserted that “everything flows,” emphasizing that all is change \cite{heraclitus}. Leibniz rejected Newton’s absolute space in favor of a relational ontology \cite{leibniz1704}. Julian Barbour developed a modern timeless framework in which time emerges from relative configurations \cite{barbour1999}.


Julian Barbour's work in timeless physics echoes this sentiment in modern form. In his framework, time does not flow as an independent background, but instead emerges from configurations and relationships of a system. Without transformation, there is no time; and without that transformation, there is no meaningful definition of space either.

\subsection{Physical Insight: Space Requires Time to Be Measurable}

Even in operational physics, the concept of \textit{space} without \textit{time} becomes incoherent. Consider the act of measuring length: whether using a ruler, radar pulses, or light-based interferometry, one must incorporate time into the process. To say something is one meter long ultimately implies that something—light, an object, or a particle—\emph{traverses} that length, which presupposes temporal evolution.

Length has no physical meaning without temporal change; even in special relativity, spacetime intervals require time to define distance \cite{barbour1999}.


Formally, even spatial separation in relativity is tied to the spacetime interval, which inherently blends distance and time:
\[
s^2 = c^2 \Delta t^2 - \Delta x^2 - \Delta y^2 - \Delta z^2
\]
Remove \( \Delta t \), and the metric collapses: you are left with inert, meaningless geometry that cannot evolve or be observed.

\subsection{Illustrative Example: Crossing a Meter Without Time?}

Let us suppose, for argument’s sake, that we define a meter in a timeless realm. What would that mean? Could anything traverse it? Could any observer compare one end to another? Without time, there is no before and after. An object at point A cannot get to point B, because there is no motion, no causal update, and no ability to register a difference.

Thus, we conclude: no object can move across a meter without time passing. And if an object cannot traverse a length—nor can an observer record a change across it—then that “length” has no physical meaning.

\subsection{Conclusion: Space Is an Emergent Construct of Change}

From this analysis, we are compelled to acknowledge a deep principle:

\begin{quote}
\textbf{No time, no change. No change, no space.}
\end{quote}

Space is not an eternal container but an emergent structure defined through the process of change. This makes temporal structure ontologically prior to spatial structure. It follows directly that in any domain where time is absent—such as the Quantum Platform (QP) in the Timeless Light Model—space must also be absent. Geometry, distance, location, and extension all require temporal substrates to be meaningful or measurable. Without time, there is no operational space.















\section{Timelessness in the TLM Framework}

The Timeless Light Model (TLM) proposes a radical restructuring of physics by asserting that all observable phenomena are the delayed deployment of resolved instructions from a timeless domain—the Quantum Platform (QP). Within this model, causality is preserved not through continuous evolution, but through the rendering of discrete, pre-resolved events into the spacetime frame. The QP exists outside of time, outside of dynamics, and—crucially—as we now show, \emph{outside of space}.

\subsection{The Quantum Platform (QP): Not a Place, but a Resolution Source}

One of the most common misconceptions about the QP is to imagine it as a kind of static "realm" or "container"—perhaps an abstract grid or frozen higher-dimensional geometry. This imagery is deeply misleading. The QP is not a location, and it contains no structure. It does not evolve, and it does not occupy. It is not embedded in a larger dimensional background. It is, rather, the domain of finalized causality: a logic-complete but unrendered layer from which all spacetime events are derived.

In TLM, we refer to the frame in which instructions become extended and experienced as the \textbf{Spacetime Deployment Frame (SDF)}. The SDF is where time and space \textit{appear}, because delay (T) occurs during rendering. It is the only frame in which space is operational.

\subsection{Why the QP Cannot Contain Geometry or Fields}

Because geometry implies distances, orientations, and transformation properties, any claim that the QP "contains" geometry is logically contradictory. Without change, there can be no displacement. Without displacement, no coordinate system has meaning. Therefore:

\begin{itemize}[leftmargin=2em]
    \item The QP contains no metric.
    \item There is no curvature, because curvature presupposes a manifold with dimensional relationships.
    \item There are no vectors or fields, because these require coordinates and evolution over space and time.
\end{itemize}

In short, the QP contains no \textit{structure} of any kind that depends on space or time.

\subsection{Instructional Reality, Not Geometric Reality}

The entities that “exist” in the QP are not things in a location, but causal resolutions awaiting deployment. You can think of them as completed instructions—fully resolved in logic, but not yet rendered into any frame that includes extension, duration, or interaction.

This view supports a dramatic simplification of the quantum-classical interface. Where standard models must wrangle with wavefunctions in infinite-dimensional Hilbert space or speculate about hidden geometries, TLM simply states: no geometry exists until deployment. The QP is not quantum spacetime—it is \textit{pre-space, pre-time}, where the only ontology is resolved instruction.

\subsection{TLM's Clean Separation: Resolution vs. Deployment}

The architectural clarity of TLM lies in its commitment to a full separation between:

\begin{enumerate}
    \item \textbf{Resolution} (in the QP): timeless, spaceless, purely causal
    \item \textbf{Deployment} (in the SDF): experienced space, time, mass, and delay
\end{enumerate}

Nothing in the QP is measured, curved, or extended. Those are functions of the deployment frame. Gravity, velocity, radiation, and motion occur \emph{only} in the SDF, as a result of how instructions are delayed or rendered.

\subsection{Summary: Spaceless QP, Spacetime SDF}

The lesson is simple but profound. Once we accept that the QP is timeless, we must also accept that it is spaceless. This aligns precisely with the central rendering mechanism of TLM: what we experience as space and time is not inherited from a substrate, but produced through delay in rendering. The QP, being free of delay, contains no space at all.







\section{Consequences of a Spaceless QP}

Recognizing that the Quantum Platform (QP) is not only timeless but also spaceless has far-reaching implications. In this section, we examine how a spaceless QP changes our interpretation of quantum phenomena, challenges conventional metaphysical assumptions, and resolves longstanding paradoxes such as nonlocality and wavefunction collapse.

\subsection{Entanglement Without Distance}

In standard quantum mechanics, entanglement seems to defy spatial separation. Two particles become entangled, and then—even if separated by light-years—measurement of one appears to instantaneously influence the other. This has been described as "spooky action at a distance," and has fueled speculation about superluminal signaling or hidden connections.

Quantum entanglement, often described as “spooky action at a distance,” was formalized in Bell's theorem \cite{bell1964} and experimentally verified by Aspect et al. \cite{aspect1982}. In TLM, these correlations arise without spatial transmission because the QP is spaceless.


But if the QP is spaceless, the mystery dissolves. Entangled outcomes are not traveling between spatially separated particles—they are simply resolved from a shared, nonlocal instruction in the QP. Since there is no space in that domain, the idea of "distance" between entangled particles is meaningless. The apparent simultaneity is not a transmission of information, but the joint rendering of a pre-resolved instruction into spacetime at two distinct locations.




\vspace{1cm}



\begin{figure}[h!]
\centering
\begin{tikzpicture}[every node/.style={font=\small}, scale=1]

% QP node (top center)
\node[draw, rounded corners, fill=blue!5, minimum width=6cm, minimum height=1.5cm, align=center] (QP) at (0,5) {
    \textbf{Quantum Platform (QP)} \\
    \textit{Spaceless, Timeless Instruction Layer}
};

% Two detectors (left and right, SDF)
\node[draw, rounded corners, fill=green!5, minimum width=3.5cm, align=center] (Alice) at (-5,0) {
    \textbf{Detector A (Alice)} \\
    \textit{Spacetime Deployment}
};

\node[draw, rounded corners, fill=green!5, minimum width=3.5cm, align=center] (Bob) at (5,0) {
    \textbf{Detector B (Bob)} \\
    \textit{Spacetime Deployment}
};

% Dashed lines from QP to Alice/Bob (TLM)
\draw[->, thick, dashed, >=Stealth, blue!70!black] (QP.south west) -- node[sloped, above, font=\footnotesize\itshape] {Instruction Deployment} (Alice.north);
\draw[->, thick, dashed, >=Stealth, blue!70!black] (QP.south east) -- node[sloped, above, font=\footnotesize\itshape] {Instruction Deployment} (Bob.north);

% Classical signal between detectors (Standard View)
\draw[<->, thick, red!60, bend left=10] (Alice.east) to node[above, font=\footnotesize\itshape, red!80!black] {Spacetime Signal?} (Bob.west);

% Annotations
\node[above=0.5cm of QP, font=\scriptsize\itshape] {No space, no distance, no delay};

\node[below=1.2cm of Alice, align=center, font=\scriptsize] {Standard view: requires signal between A and B};
\node[below=1.2cm of Bob, align=center, font=\scriptsize] {TLM view: shared instruction rendered separately};

\end{tikzpicture}
\vspace{.1cm}
\caption{Entanglement under standard interpretation (red, signal across space) vs.\ TLM (dashed blue, spaceless instructional deployment). In TLM, no spatial link is needed because the QP issues matched instructions without reference to location.}
\label{fig:entanglement_tlm_vs_local}
\end{figure}

\vspace{.5cm}








\subsection{No Geometry, No Locality—And No Violation of Relativity}

A spaceless QP offers a clean explanation for why entanglement does not violate special relativity. In relativity, no signal can travel faster than light through spacetime. TLM agrees: in the SDF, causal rendering is limited by delay and instructional deployment.

However, the QP does not operate within the SDF. Since it is spaceless, there is no velocity, no direction, and no locality to violate. Relativity remains intact in the SDF, while the QP serves as a non-spatial instruction source. What appears as instantaneous "correlation at a distance" is simply the simultaneous rendering of a single timeless resolution into two deployment points.

\subsection{Superposition and Instruction Latency}

Superposition in quantum mechanics is another phenomenon clarified by the spaceless nature of the QP. In TLM, superposition does not imply the physical co-location of multiple outcomes in some bizarre probabilistic medium. Rather, it means that the instruction has not yet been rendered. It exists in the QP as a resolved possibility, but not yet expressed in the SDF.

There is no need to interpret the QP as containing a “probability cloud” in space. Probability arises only upon deployment. Until then, the system has not taken on a spatial configuration at all.

\subsection{No Fields, No Waves, No Collapse—Just Resolution}

Because the QP contains no space, it cannot contain wavefunctions spread out over space. There are no fields in space waiting to collapse. Instead, all outcomes are logical instructions awaiting rendering. Collapse is not a physical process that happens over a spatial field—it is simply the moment at which an instruction is deployed from the QP into the SDF.

This view bypasses the measurement problem entirely: there is no “collapse” in the QP. There is only deployment. The moment of observation is the moment of rendering. What was spaceless becomes spatial only when rendered.

\subsection{Summary: From Paradox to Clarity}

By treating the QP as truly spaceless, the Timeless Light Model eliminates the need for exotic spatial metaphors to explain quantum behavior. Entanglement is no longer spooky, wavefunction collapse is no longer mysterious, and nonlocality is no longer problematic. These phenomena are not spatial oddities—they are consequences of a deeper non-spatial causal framework.

The explanatory power of this move is substantial. It resolves paradoxes not by adding metaphysical baggage, but by removing unjustified assumptions. If we let go of the idea that the instruction layer must itself contain space, we gain a unified, delay-based rendering model that aligns perfectly with both quantum outcomes and relativistic constraints.








\subsection{Predictions Arising from Spaceless QP}
\addcontentsline{toc}{subsection}{Predictions Arising from Spaceless QP}

The assertion that the QP is spaceless is not merely philosophical—it yields concrete predictions:

\begin{enumerate}[label=\textbf{P\arabic*}, leftmargin=2.5em]
    \item \textbf{Nonlocal Entanglement Correlations Without Signal Exchange:}  
    Since the QP is outside of space, entangled outcomes do not involve communication across distance. TLM predicts that Bell inequality violations and delayed-choice quantum erasure experiments will continue to show instantaneous correlations even under spacetime-separated configurations—without requiring faster-than-light transfer.

    \item \textbf{Geometry-Free Instruction Collapse:}  
    Collapse events (e.g., detection of a photon or electron) will display no dependence on spatial geometry between emitter and detector. The outcome only reflects instruction resolution, not any continuous path in space. TLM therefore predicts that certain quantum tunneling or absorption phenomena will violate classical locality constraints, especially under ultra-short path separations.

    \item \textbf{Absence of Pre-Rendered Field Structures:}  
    If geometry is rendered only at deployment, then measurements attempting to probe substructure “prior” to rendering (e.g., in vacuum field configurations or spacetime foam) should yield stochastic rather than deterministic structure. TLM predicts that vacuum fluctuations and zero-point energy signatures will lack spatial coherence beyond what is required for rendering delay.

    \item \textbf{Instructional Coincidence Tests:}  
    In engineered quantum systems (e.g., Bose-Einstein condensates with shared past light cones), the spaceless QP predicts that collapsed states may show high cross-system correlation even if the systems are not in causal contact—so long as their instructions originate from the same resolution arc.
\end{enumerate}

These predictions provide a testable framework for falsifying or supporting the claim that all rendered spacetime emerges from a non-geometric instruction layer. Unlike many interpretations of quantum mechanics, the TLM explicitly invites laboratory tests of its core assumptions.














\section{Objections and Counterarguments}

The assertion that timelessness necessarily implies spacelessness may initially seem extreme, especially to those accustomed to thinking of timeless realms—like Platonic forms, Hilbert space, or the block universe—as richly structured, often with geometric or higher-dimensional traits. In this section, we examine the most common objections and show why, under closer inspection, they either misunderstand the premises or rely on unacknowledged temporal assumptions.

\subsection{Objection 1: ``Can’t the QP Just Be a Higher-Dimensional Space?''}

A popular idea in string theory and multiverse proposals is that our universe is embedded within a larger “timeless” geometry—typically with 10 or 11 dimensions, or some manifold beyond spacetime. Some may attempt to view the QP this way: as a timeless container of extra-dimensional geometry.

\textbf{Response:} Even higher-dimensional geometries rely on the concept of change to be meaningful. Coordinates, angles, and metrics imply a system in which comparative structure exists—yet comparison requires motion or difference. If there is no time, then nothing can traverse these extra dimensions, and no observer can distinguish one point from another. Geometry without change is indistinguishable from no geometry at all.

Therefore, any attempt to make the QP “timeless space” secretly smuggles in temporal logic under a geometric mask.

\subsection{Objection 2: ``What About Hilbert Space?''}

In quantum mechanics, the wavefunction is often described as a vector in Hilbert space—a complete, abstract space with infinite dimensions. Doesn’t this provide a kind of geometry, even in timeless formulations?

\textbf{Response:} Hilbert space is a mathematical structure, not a physical one. Its “space” is metaphorical: it represents logical relationships, not distances or positions in a physical manifold. In the TLM, the QP is not a region of Hilbert space, nor does it require one. Logical resolution occurs without reference to spatial representation. There is no need to embed instructions in an abstract geometry when their only function is deployment into the rendered world.

\subsection{Objection 3: ``What About the Block Universe? Isn’t That Timeless Space?''}

In relativity, the block universe treats time as a static dimension—so all of spacetime already “exists” as a 4D block. Doesn’t that contradict the idea that timelessness excludes space?

\textbf{Response:} The block universe is not truly timeless in the same sense TLM means. It still presumes a spacetime manifold—albeit static—that has already been deployed. The block model is a rendered object. It describes an unfolded history, not an unrendered instruction set. In TLM terms, the block universe is the \emph{SDF}, frozen in view. The QP is prior to this—outside even the block itself, containing the resolved instructions that \emph{generate} the block.

Thus, the block universe still presupposes a spacetime context, and cannot be used to argue for spaceless timelessness.

\subsection{Objection 4: ``If the QP Is Spaceless, How Can It Target a Location?''}

A pragmatic concern arises: if the QP contains no space, how can it issue instructions to specific locations in the SDF? Doesn’t targeting require coordinates?

\textbf{Response:} No. Instructional targeting is part of the rendering process, not the resolution process. The QP does not “aim” instructions at coordinates; rather, instructions include outcome conditions that, when rendered, map into SDF positions. It is the act of rendering that produces coordinates—not the instruction’s internal content. In software terms, a compiled function doesn’t contain screen pixels—it becomes pixels only when rendered by the graphics engine.

The QP thus encodes resolution logic, not deployment geometry. Position arises downstream of causality, not upstream.

\subsection{Summary: The Burden of Geometry Is Always Temporal}

Each objection, when unpacked, turns out to rely on unstated assumptions about temporal process. Whether it's a higher-dimensional shape, a block of frozen history, or an abstract state vector, the concept of space always relies on the possibility of change—on something \emph{happening} within or across that space.

Once that requirement is made explicit, the case becomes clear: true timelessness is incompatible with space. The Quantum Platform, if it is truly outside time, must be spaceless as well. Any theory that proposes “timeless geometry” must either abandon that term or admit hidden time.



\section{Implications for Other Theories}

The assertion that timelessness implies spacelessness is not only a refinement of the Timeless Light Model (TLM); it also places significant pressure on other theoretical frameworks. Many modern models of fundamental physics rely—explicitly or implicitly—on timeless structures that nonetheless presume geometric or spatial content. This section examines how the spacelessness of a truly timeless domain challenges these approaches and suggests paths for reinterpretation or revision.

\subsection{Critique of Extra-Dimensional Physics (e.g., String Theory)}

String theory and M-theory posit that the universe is fundamentally composed of vibrating one-dimensional strings embedded in higher-dimensional manifolds, often with 10 or 11 spatial dimensions. These extra dimensions are often said to be “compactified” or “hidden,” yet present from the beginning, even before time as we experience it emerges.

\textbf{Problem:} If these dimensions are part of a timeless substrate, they still encode spatial structure—length, curvature, shape—even in the absence of time.

\textbf{TLM Rebuttal:} Without temporal change, these higher-dimensional spaces cannot be probed, traversed, or functionally distinguished. They become inert scaffolds with no operational significance. Unless one allows time to exist in those dimensions (which contradicts the notion of a timeless origin), then the claim that the universe “comes from” a higher-dimensional geometry lacks operational meaning. TLM instead suggests that dimensionality itself is a rendered feature, not a pre-existing one.

\subsection{Simulation Hypotheses and Pre-Spacetime Computation}

Simulation theory posits that our universe is the output of some form of underlying computation. Often, this is imagined as taking place outside our spacetime—perhaps in a computational substrate that is not bound by our notions of space or time.

Simulation hypotheses often assume a non-spatiotemporal substrate capable of generating experiential reality \cite{bostrom2003}. TLM aligns with this view if that substrate is interpreted as a timeless, spaceless instruction layer. Wheeler’s “it from bit” proposal similarly suggests that information is more fundamental than space or matter \cite{wheeler1990}.

\textbf{Opportunity:} The TLM provides a rigorous architecture for this view. A simulation substrate that is truly outside of spacetime must not merely “contain” space in a different form. It must operate without any spatial assumptions at all. The QP provides exactly such a layer: it is a resolution engine, not a geometric container. It supports the simulation hypothesis—but only if that simulation engine is spaceless and timeless, and produces space and time as effects, not as causes.

\textbf{Interpretive Shift:} TLM thus reframes simulation theory. The “program” does not live in a hyperspatial computer; it exists as a timeless resolution layer whose outputs unfold as space and time in the deployment frame.

Simulation theory posits that our universe is the output of some form of underlying computation~\cite{bostrom2003simulation}.


\subsection{Information-Theoretic Physics and the Bit-Layer View}

Recent trends in physics—including Wheeler’s “it from bit” proposal—suggest that the universe is fundamentally informational~\cite{wheeler1989itfrombit}. But many of these models still smuggle in space: bits are stored “on a surface,” entropy is “distributed in a volume,” or black holes “encode area.”

\textbf{TLM Refinement:} Information does not exist \textit{in} space. Space exists \textit{as} information—specifically, rendered instructional delay. The QP contains neither surface area nor volume; it contains pure causal instruction. All apparent geometry is downstream of resolution delay in the SDF.

\textbf{Conclusion:} TLM converts information-based physics into a two-layer model: the bit-layer is spaceless and timeless (QP), and the experiential world is the rendering of that bit-layer into spacetime (SDF). This restores clarity to the information ontology without invoking self-contradictory geometric metaphors.

\subsection{Theological and Metaphysical Implications}

Many spiritual or metaphysical traditions posit a timeless “source” of the universe—God, the Tao, Brahman, or the Absolute. Often, these are visualized as existing “beyond” the universe or “outside” of creation, yet still imagined spatially—as a realm, a kingdom, or a dimension.

\textbf{TLM Clarification:} If that source is truly timeless, then it is also spaceless. This aligns with apophatic traditions which describe God as beyond all attributes, all location, all form. The TLM therefore supports a rigorous metaphysical framing in which the Creator is not a being in space, but the timeless, spaceless origin of rendered reality.

\subsection{Summary: Many Models Must Be Recast}

Any theory that invokes a timeless layer while retaining geometry must be reexamined. String theory, block universe models, Hilbert space metaphysics, and simulation narratives all carry hidden assumptions about space within their timeless foundations. TLM makes these assumptions explicit—and replaces them with a clean, axiomatic division:

\begin{quote}
    \textbf{No space without time. No geometry without change. No structure without rendering.}
\end{quote}

Any theory that violates this will either require a hidden time—or it must give up the illusion of timeless geometry entirely.




\section{Conclusion}

This paper has argued for a deceptively simple but foundational principle: \textbf{true timelessness entails absolute spacelessness}. In the context of the Timeless Light Model (TLM), this means that the Quantum Platform (QP)—defined as the origin of all causal instructions—is not a spatial realm, geometric lattice, or higher-dimensional manifold. It is a \textit{resolution layer}, not a rendered substrate. It contains no coordinates, no distance, no curvature, and no field values—only resolved instructions awaiting rendering.

We began by showing how the very definition of space depends on change: without time, there is no motion; without motion, there is no measurement; without measurement, space has no operational meaning. We then applied this insight to TLM’s architecture, demonstrating that space arises only in the Spacetime Deployment Frame (SDF) through delay. All observable geometry, causality, and motion are effects of this rendering—not inputs to it.

By exploring quantum phenomena like entanglement and superposition through this lens, we eliminated several interpretive paradoxes. No spooky action, no collapse mechanics, and no nonlocal transmissions are needed—only the timely rendering of a timeless instruction. We then extended this framework to critique and reinterpret other theoretical models, from string theory and block universe models to simulation theory and metaphysics.

The result is an ontological realignment: space is no longer assumed to be fundamental. Instead, it is a rendered effect, dependent entirely on instructional delay. The QP, as the timeless source, cannot contain space. Any theory that claims otherwise must either sneak in hidden time—or surrender its coherence.



\appendix
\section*{Appendix A: Core Axiom and Glossary Snapshot}
\addcontentsline{toc}{section}{Appendix A: Core Axiom and Glossary Snapshot}

\begin{tcolorbox}[colback=gray!5!white, colframe=black, title={\textbf{Axiom IX: Timelessness Entails Spacelessness}}, fonttitle=\bfseries, breakable]
A domain that is truly timeless cannot contain or define spatial structure.

In the absence of temporal progression, no metric space can exist, as space requires change to define location, distance, or dimensionality.

Therefore, the Quantum Platform (QP) is both \textbf{timeless and spaceless}, issuing resolved instructions that only acquire temporal and spatial meaning upon deployment into the Spacetime Deployment Frame (SDF).
\end{tcolorbox}

\bigskip







\appendix
\section*{Appendix B: Glossary and Core Equations}
\addcontentsline{toc}{section}{Appendix B: Glossary and Core Equations}

\subsection*{Glossary of Key Terms}

\begin{itemize}[leftmargin=2em, label=--]
  \item \textbf{Quantum Platform (QP):} A timeless and spaceless resolution layer that issues fully-resolved causal instructions. It contains no geometry, duration, or localizable fields. In TLM, all observable events are projections from QP into spacetime.

  \item \textbf{Spacetime Deployment Frame (SDF):} The rendered arena of experience where instructions from QP are deployed with delay \( T \). Time, space, mass, and curvature arise in this layer.

  \item \textbf{Timeless Light Model (TLM):} A unifying framework asserting that General Relativity (GR) emerges as a rendered projection from a deeper timeless instruction set. Causality is preserved, but space and time are effects of deployment, not substrates.

  \item \textbf{Instructional Delay \( T \):} The time taken for a resolved instruction in QP to be rendered into the SDF. For photons, \( T = 0 \). For massive particles, \( T = 1/m \) in Planck units.

  \item \textbf{Causal Deployment Rate \( C_s \):} The inverse of delay. TLM postulates a fundamental law: 
  \[
  T \cdot C_s = 1
  \]
  asserting that the product of delay and deployment speed is constant.

  \item \textbf{Null Geodesic:} A spacetime path along which the interval \( ds^2 = 0 \). In GR, this defines the photon’s path and mathematically implies zero proper time \( \tau \).

  \item \textbf{Rest Frame:} A reference frame in which an object is at rest. Defined only for massive particles with \( \tau > 0 \). Not definable for photons.

  \item \textbf{Embedment:} An entity is said to be embedded in spacetime if it follows a timelike worldline and possesses a proper time and rest frame.

    \item \textbf{Rendering Delay (T):} The delay between resolution (in QP) and deployment (in SDF); defines temporal experience and mass.
  \item \textbf{Instruction Deployment:} The act of projecting timeless resolutions into the SDF, producing spacetime structure.

\end{itemize}

\subsection*{Supporting Equations and Derivations}

\paragraph{Proper Time for Massless Particles}

For any worldline in spacetime, the line element is:

\[
ds^2 = -c^2 d\tau^2 + dx^2 + dy^2 + dz^2
\]

For massless particles (e.g., photons), GR sets:

\[
ds^2 = 0 \quad \Rightarrow \quad d\tau = 0
\]

Hence, photons experience no proper time: \( \tau = 0 \).

\paragraph{Lorentz Boost Singularity at Light Speed}

The Lorentz factor is:

\[
\gamma = \frac{1}{\sqrt{1 - \frac{v^2}{c^2}}}
\]

As \( v \to c \), \( \gamma \to \infty \), implying that no finite transformation can define a rest frame for a photon. This supports the claim that photons cannot be embedded in any inertial frame.

\paragraph{Instructional Delay Law}

TLM postulates a universal rendering law:

\[
T \cdot C_s = 1
\]

This law expresses the inverse relationship between rendering delay and deployment speed in the SDF. It replaces the traditional interpretation of \( c \) as fundamental, interpreting \( c \) instead as an emergent limit derived from spaceless deployment dynamics.

\paragraph{Mass–Delay Relation (Planck-normalized)}

\[
T = \frac{1}{m}
\]

Mass is interpreted as the inverse of rendering delay. Greater mass implies shorter instruction delay (i.e., more anchoring in the SDF), while massless entities like photons are rendered instantly (\( T = 0 \)).

\paragraph{Rendering and Apparent Propagation}

Although a photon appears to traverse a path in space over time \( t \), from the TLM perspective this is the unfolding of a rendered instruction with no time experienced by the photon:

\[
\text{Apparent travel} \sim \text{delayed deployment in SDF, not intrinsic journey in QP}
\]

This explains why photons mediate causal links without being “in” space or time.


























\begin{thebibliography}{99}

\bibitem{mckinley2025}
John C. W. McKinley. \textit{Foundational Equations and Axiomatic Structure of the Timeless Light Model: A Synthesis Across Sixty Papers and Working Notes}. Zenodo. July 2025.\\
\href{https://doi.org/10.5281/zenodo.16187719}{https://doi.org/10.5281/zenodo.16187719}

\bibitem{barbour1999}
Julian Barbour. \textit{The End of Time: The Next Revolution in Physics}. Oxford University Press, 1999.

\bibitem{leibniz1704}
Gottfried Wilhelm Leibniz. \textit{Monadology}, 1714. English translation in: G. H. R. Parkinson (ed.), \textit{Leibniz: Philosophical Writings}. Everyman, 1934.

\bibitem{heraclitus}
Heraclitus (fragments). In: G. S. Kirk and J. E. Raven, \textit{The Presocratic Philosophers}. Cambridge University Press, 1957.

\bibitem{bell1964}
John S. Bell. “On the Einstein Podolsky Rosen Paradox.” \textit{Physics}, 1(3):195–200, 1964.

\bibitem{aspect1982}
Alain Aspect, Philippe Grangier, and Gérard Roger. “Experimental Realization of Einstein–Podolsky–Rosen–Bohm Gedankenexperiment: A New Violation of Bell’s Inequalities.” \textit{Physical Review Letters}, 49(2):91–94, 1982.

\bibitem{wheeler1990}
John Archibald Wheeler. “Information, physics, quantum: The search for links.” In W. Zurek (ed.), \textit{Complexity, Entropy, and the Physics of Information}. Addison-Wesley, 1990.

\bibitem{bostrom2003}
Nick Bostrom. “Are You Living in a Computer Simulation?” \textit{Philosophical Quarterly}, 53(211):243–255, 2003.

\end{thebibliography}


\end{document}

















```

</details>

---
{% endraw %}
