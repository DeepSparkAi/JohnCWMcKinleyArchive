---
layout: default
title: '[2026] Physics Has Always Been Unified: General Timelessness, Null Proper Time, and the Clarified Architecture'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/physics-has-always-been-unified-general-timelessness-null-proper-time-and-the-clarified/
paper: true
---
{% raw %}
# [2026] Physics Has Always Been Unified: General Timelessness, Null Proper Time, and the Clarified Architecture
*   **DOI:** [10.5281/zenodo.20954931](https://doi.org/10.5281/zenodo.20954931)
*   **Date:** 12 September 2026

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

\documentclass[12pt,onecolumn]{article}

\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage[margin=1in]{geometry}
\usepackage{setspace}
\usepackage{amsmath,amssymb,amsthm}
\usepackage{tikz}
\usetikzlibrary{positioning,fit,backgrounds}

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
\usepackage{xcolor}
\usepackage{graphicx}
\usepackage{mdframed}
\usepackage{xurl}

% Clickable superscript link to definition
\newcommand{\defterm}[2]{#1\textsuperscript{\textcolor{gray}{\hyperref[#2]{\scriptsize$\dagger$}}}}

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
\lhead{Physics Has Always Been Unified}
\rhead{John C. W. McKinley}
\cfoot{\thepage}

\newcounter{nogo}[section]
\renewcommand{\thenogo}{\thesection.\arabic{nogo}}

\theoremstyle{plain}
\newtheorem{proposition}{Proposition}
\theoremstyle{definition}
\newtheorem{definition}{Definition}
\theoremstyle{remark}
\newtheorem{remark}{Remark}



\makeatletter
\let\c@proposition\c@nogo
\let\c@definition\c@nogo
\let\c@remark\c@nogo
\makeatother

\renewcommand{\theproposition}{\thenogo}
\renewcommand{\thedefinition}{\thenogo}
\renewcommand{\theremark}{\thenogo}




\title{\textbf{Physics Has Always Been Unified:\\
General Timelessness, Null Proper Time,\\
and the Clarified Architecture}\\[0.4em]
\large\textit{Why Quantum Mechanics and Relativity Were Never in Competition}}

\author{John C. W. McKinley\,\orcidlink{0009-0005-7097-5035}}

\date{September 12, 2026}

\begin{document}






\maketitle

\blfootnote{\scriptsize This version published at \href{https://doi.org/10.5281/zenodo.20954931}{10.5281/zenodo.20954931}.}

\begin{abstract}
Physics is already unified. The unification is not a mathematical framework yet to be discovered. It is an interpretive fact already present in the existing theories, which has gone unrecognized because the ontological consequences of null proper time were not consistently applied. The present paper states the unified physical description plainly and shows that quantum mechanics and relativity already perform distinct explanatory roles within it.

The unified description begins from a simple distinction: laws are not time. Physical reality is governed by \defterm{lawful structure}{def:lawfulstructure}, but time is not a constituent of lawful structure. A mathematical expression of a law may include a time parameter, but that symbolic reference does not make time a component of the law itself. Time belongs to spacetime relations. Some outcomes permitted by lawful structure \defterm{register}{def:registration} within spacetime and thereby possess temporal ordering, causal relation, geometric localization, and observability. When registration occurs, it is governed by the laws of special and general relativity. Quantum mechanics describes \defterm{lawful eligibility}{def:lawfuleligibility} --- the admissible outcomes and the mathematical relations governing their amplitudes and probabilities. Relativity describes the spacetime organization of registration.

These are not competing descriptions of one temporal process. They describe different explanatory aspects of one lawful order.

The apparent disunity of modern physics arose from treating quantum mechanics and relativity as competing descriptions of timebound physical processes. That misreading persisted because the full ontological consequences of \defterm{null proper time}{def:nullpropertime} were not propagated. A photon has no proper time. This is not a mathematical curiosity. It means that the ordinary persistence narrative --- the assumption that a physical thing travels through successive spacetime locations while accumulating a history --- does not apply to light. Once that consequence is honored consistently, timebound spacetime registration is recognized as the special case in which time applies rather than the general condition under which law holds. Quantum mechanics and relativity then assume their proper roles: quantum mechanics describes lawful eligibility, while relativity governs spacetime registration. No new equations are required. No existing predictions are altered. The unification is already here.
\end{abstract}













\noindent{\small\textcolor{gray}{Technical terms marked with a superscript dagger (\textsuperscript{\scriptsize$\dagger$}) link to their formal definition in Section~\ref{sec:definitions}.}}

\begin{center}
\textit{The universe is fundamentally lawful.}

\vspace{0.4em}

\textit{Lawful structure is timeless.}

\vspace{0.4em}

\textit{Spacetime registration is one class of lawful relation.}

\vspace{0.4em}

\textit{Physics has always been unified.}
\end{center}

\vspace{0.7em}


\clearpage
\tableofcontents
\clearpage

\section{Introduction}

The search for a unified theory of physics has proceeded for nearly a century under a shared assumption: that quantum mechanics and relativity are incomplete descriptions of the same physical reality, and that a deeper mathematical framework must therefore be found that reproduces both as limiting cases. This assumption has motivated extraordinary mathematical effort. It has not yet produced a successful unified theory. The present paper proposes that the assumption itself is mistaken, and that its correction requires no new mathematics at all.

The mistake is not mathematical but interpretive. Quantum mechanics and relativity were never in conflict because they answer different physical questions. Once \defterm{general timelessness}{def:generaltimelessness} is recognized, the apparent conflict dissolves. Quantum mechanics describes lawfully eligible outcomes and the mathematical relations governing their amplitudes and probabilities. Relativity governs relativistic registration. The demand for a third framework to reconcile them therefore rests on a false premise.

The argument begins from the simplest possible distinction: laws are not time. Physical laws govern which relations, outcomes, and structures are admissible, but time is not a constituent of the laws themselves. Laws do not age, wait, persist, or evolve. A mathematical expression of a law may include a time parameter, but that symbolic reference does not make time a component of the law itself. The mathematics describes a relation in which time may appear; time belongs to the spacetime relations being described.

Some outcomes permitted by lawful structure \defterm{register}{def:registration} within spacetime and thereby possess temporal ordering, causal relation, geometric localization, proper-time accumulation where applicable, and observability. Time applies to those registered spacetime relations. Timebound spacetime registration is therefore a special class of lawful physical appearance rather than the universal background condition under which law itself holds.

This is the principle of general timelessness, established in the published Timeless Light Model (TLM) corpus \cite{bedrock,generaltimelessness}. The present paper does not re-establish that result. It draws the consequence that follows from it: once time is no longer treated as the universal background of physical description, quantum mechanics and relativity cease to appear as competing accounts of one temporal process. They instead assume distinct explanatory roles within one lawful order.

Quantum mechanics describes the lawfully eligible outcomes and the mathematical relations governing their amplitudes and probabilities. Relativity governs relativistic registration: the coherent spacetime organization of registered outcomes, including temporal ordering, causal relation, geometric localization, proper-time accumulation, and observer receipt. These are not rival accounts of one timebound process. They describe different aspects of the same physical order: one concerns admissibility and its mathematical description, while the other concerns the spacetime organization of what registers.

The present paper therefore makes explicit what the prior corpus made available but did not state as its central conclusion: physics is already unified. Neither quantum mechanics nor relativity is incomplete in the explanatory sense addressed here. Neither requires replacement. Their apparent competition arose from treating both theories as if they were competing accounts of temporal physical evolution, rather than recognizing that temporal properties belong to spacetime registration and are not constituents of physical law.

General timelessness does not posit a timeless place outside spacetime. Lawful structure is not located anywhere, because it is not a physical object, region, or medium. It is the coordinated specification of the laws and relations governing what is admissible. Mathematical descriptions of those laws may refer to temporal, spatial, and other physical quantities without making those quantities constituents of law itself. Spacetime registration is the physical circumstance in which temporal ordering, causal relation, geometric localization, and proper-time accumulation apply.

The diagnostic clue is \defterm{null proper time}{def:nullpropertime}. A photon accumulates no proper time. Relativity establishes this as a mathematical fact. What was not consistently honored is what this means ontologically: the ordinary narrative of a persisting physical thing traveling through successive spacetime locations does not apply to light. Once that consequence is taken seriously, timebound spacetime registration is recognized as the special case rather than the universal background. The proper roles of quantum mechanics and relativity then become clear.

The sections that follow state this unified physical description plainly, review the published results upon which it rests, classify the roles of the existing theories, and show why the traditional unified-theory problem dissolves once those roles are correctly distinguished. No equations are altered. No predictions are changed. The contribution is interpretive: the unification lies in recognizing what the existing theories already describe.







\section{The Simplest Description of the Universe}

Before classifying physical theories, it is useful to state the underlying distinction as plainly as possible.

Laws are not time. Physical laws govern which relations, outcomes, and structures are admissible, but time is not a constituent of the laws themselves. Laws do not begin, age, evolve, or end. A mathematical expression of a law may include a time parameter, but that symbolic reference does not make time a component of the law itself. The mathematics may describe relations in which temporal ordering appears; time belongs to those spacetime relations.

Physical reality is therefore governed by lawful structure that does not itself require time in order to hold. Some outcomes permitted by that structure \defterm{register}{def:registration} within spacetime and thereby possess temporal ordering, causal relation, geometric localization, proper-time accumulation where applicable, and observability. Time applies to those registered spacetime relations. Timebound spacetime registration is therefore a special class of lawful physical appearance rather than the background condition upon which lawful structure depends.

This distinction is interpretive rather than mathematical. It concerns what the existing theories describe, not the accuracy of their predictions. Conservation principles, symmetries, admissibility conditions, selection rules, boundary conditions, and other physical laws govern what is possible. They are not themselves events occurring in time. Their mathematical expressions may refer to time, space, energy, momentum, or other physical quantities without making those quantities constituents of the laws themselves.

\begin{mdframed}[linewidth=0.8pt, innertopmargin=10pt, innerbottommargin=10pt, innerrightmargin=14pt, innerleftmargin=14pt, backgroundcolor=gray!15, leftmargin=0.33in, rightmargin=0.33in]
\normalsize\itshape
In the ancient fable, blind scholars each examine a different part of an elephant and reach different conclusions. Each describes what he touches. None is wrong. The disagreement arises only because no one has named the elephant.

\medskip

Quantum mechanics and relativity are not in conflict. They describe different aspects of one lawful order. Quantum mechanics describes lawful eligibility, while relativity governs relativistic \defterm{registration}{def:relativisticregistration}.
\end{mdframed}

Some admissible outcomes register within spacetime. They participate in temporal ordering, causal structure, geometric localization, and observation by other registered physical systems. Observers are themselves registered physical systems. Everything an observer can receive, measure, or detect is received through registration. What observers receive, where they receive it, and when they receive it are governed by the laws of special and general relativity.

This is the complete distinction needed for the present argument. Lawful structure governs what is admissible. Registration is the special circumstance in which an admissible outcome participates within spacetime. There are not two separate physical realms, nor is there a third physical mechanism standing between eligibility and registration. Lawful eligibility is not an earlier temporal stage that later becomes registration. One concerns what is admissible; the other concerns what is registered within spacetime.

Quantum mechanics and relativity therefore answer different questions. Quantum mechanics describes lawful eligibility: the admissible outcomes together with the mathematical relations governing their amplitudes and probabilities. Relativity describes the spacetime organization of registration: the causal structure, geometric relations, finite information propagation, proper-time accumulation, and observer consistency governing registered outcomes.

The resulting physical description is unified. Lawful structure governs admissibility without itself containing time as a constituent. Its mathematical description may refer to temporal quantities wherever the physical relation being described includes them. Registration is where timebound physical participation occurs. Quantum mechanics describes lawful eligibility; relativity governs the spacetime organization of registration. Together they describe one lawful order without requiring either theory to perform the explanatory task of the other.





\section{The Diagnostic Role of Null Proper Time}

The unified architecture described in the preceding section was not recognized because one known physical result was not consistently applied in all its ontological consequences. That result is null proper time for the photon.

Special relativity establishes that a photon has zero proper time along its worldline \cite{einstein1905}. The interval between any two events on the photon's path is null. This is not an approximation or a limiting case. It is an exact result of relativistic geometry.

\begin{mdframed}[linewidth=0.8pt, innertopmargin=10pt, innerbottommargin=10pt, innerrightmargin=14pt, innerleftmargin=14pt, backgroundcolor=gray!15, leftmargin=0.33in, rightmargin=0.33in]
\normalsize\itshape
Null proper time is the diagnostic clue. A photon has zero proper time along its worldline:
\[
\Delta s^2 = c^2\Delta t^2 - \Delta x^2 = 0.
\]
The spatial and temporal terms cancel exactly. For the photon, there is no accumulated proper-time history, no rest frame, and no internally lived sequence of intermediate locations. Emission and absorption are registered in spacetime; the lawful relation connecting them is not a persisting traveler between them.

Nor is the traveler restored by calling the wavefunction a physical wave in transit. The wavefunction assigns amplitudes and organizes the lawful structure of possible absorption events. It does not describe where a photon is between emission and absorption, and it does not add a second spacetime occupant crossing the gap \cite{wavefunctionnogo}. This is the physical case that exposes the clarified architecture.
\end{mdframed}

The ordinary persistence narrative assumes that a physical thing exists at successive spacetime locations and accumulates a history as it travels. This narrative applies to massive objects. It does not apply to the photon. A photon has no rest frame, no internal clock, no accumulated proper time, and therefore no sequence of locations constituting a history in the ordinary sense. Questions about what happens to the photon between emission and detection are not unanswered physical questions. They are questions directed at a category the theory does not supply \cite{bedrock,generaltimelessness}.

The failure to honor this consequence consistently had architectural effects. If the photon is treated as a persisting traveler despite the null proper-time result, then physical reality is implicitly interpreted as fundamentally temporal. Timelessness appears only as an edge case. The general condition of physics seems to be timebound existence within spacetime, and physical laws are consequently imagined as temporal rules operating upon things as those things evolve through time.

That last inference is the crucial mistake. Laws are not temporal constituents of the processes they govern. Time is not a component of lawful structure. A mathematical expression of a law may contain a symbol or parameter representing time, but the appearance of that symbol does not place time inside the law itself. The law governs the physical relation; the mathematics describes that relation. Temporal ordering belongs to registered spacetime relations where spacetime supplies it.

Under the mistaken temporal picture, quantum mechanics and relativity both appear to describe the evolution of things through time. They therefore appear to be competing descriptions of one timebound physical process. Incompatibilities between them then motivate the search for a deeper framework capable of reconciling two theories presumed to be performing the same explanatory task.

Honoring null proper time consistently reverses this picture. The photon shows that timebound persistence cannot be the universal condition of physical description. A physical relation can be governed lawfully without constituting the history of a persisting object accumulating proper time between its registered endpoints. Timeless lawful structure is therefore not defined by whether a mathematical expression happens to contain a time variable. It is timeless because time is not a constituent of law. Time enters physical reality where lawful outcomes register within spacetime and acquire temporal relations.

Null proper time is thus diagnostic rather than definitional. The photon does not establish timelessness merely because a particular equation lacks a time variable. It exposes the failure of the assumption that all physical reality must consist of things persisting through successive moments. Relativity itself supplies a physical case in which the ordinary timed-traveler narrative fails. Once that case is taken seriously, timebound spacetime registration is recognized as the special circumstance in which temporal ordering applies rather than the universal condition under which law holds \cite{generaltimelessness}.

Once this reversal is made, the explanatory roles of quantum mechanics and relativity become clear without any modification of their mathematics. Quantum mechanics already describes the lawfully eligible outcomes and the mathematical relations governing their probabilities and amplitudes. Relativity already governs the organization of timebound \defterm{registration}{def:relativisticregistration}. The unification was always present. It was obscured by treating time as though it were a constituent background of law and by reading null proper time as a mathematical curiosity rather than an ontological constraint.






\section{Prior Results}

The present paper rests upon a sequence of previously published results within the Timeless Light Model corpus. Those results are not re-established here. They are summarized in order to identify the published foundation upon which the architectural synthesis depends.

The Bedrock statement established the canonical form of the Timeless Light Model by expressing the framework in standard relativistic and quantum language, removing earlier developmental scaffolding \cite{bedrock}. The architectural distinction between timeless lawful structure and spacetime \defterm{registration}{def:relativisticregistration} that governs the present paper follows directly from that canonical statement.

The General Timelessness paper established that timelessness is the general condition of physical law, while timebound spacetime appearance is the special case \cite{generaltimelessness}. Three independent arguments support this conclusion: relativity rejects absolute universal time; the relativistic null case demonstrates that proper time is absent for light; and spacetime cannot consistently be treated as the condition of its own appearance. Taken together, these arguments reverse the conventional hierarchy. Timeless lawful relation is the general architectural condition. Timebound spacetime appearance is the special case.

The photon sequence argued that null proper time is not merely a mathematical result but an ontological constraint \cite{nullpropertime}. The absence of a photon rest frame removes the ordinary persistence narrative from light and motivates the conclusion that questions concerning intermediate photon history are category errors rather than unanswered physical questions \cite{norestframe,nullcurves}. The retrocausality no-go extended this result by showing that retrocausal objections to photon behavior presuppose a photon history that the null proper time result disallows \cite{retrocausality}.


The matter-side sequence extended the same architectural reading to bound matter. Stationary states, stable atoms, and radioactive atoms were interpreted as timeless lawful structures whose registrations occur within spacetime while their lawful content remains time-independent \cite{atom,generalatom}. Stable and radioactive systems differ by lawful content rather than by ontological category. Radioactive decay does not reflect an atom aging through time; it reflects a lawful channel realizing within spacetime.

The local-accrual paper distinguished timeless lawful structure from the accumulation of proper time along worldlines \cite{localaccrual}. Proper time belongs to the spacetime registration of massive systems. It does not belong to the timeless lawful structure itself.

The Newtonian Holodeck paper argued that the relativistic rules governing spacetime are not arbitrary constraints but the necessary conditions under which a coherent observable universe can sustain itself \cite{holodeck}. Finite information propagation, causal ordering, observer consistency, and relativistic geometry are architectural requirements of \defterm{relativistic registration}{def:relativisticregistration}, not optional features of a coherent spacetime.

The no-go cluster applied the same architectural distinction to specific physical phenomena. Fermion fields are not licensed as material things in space by the success of quantum field theory \cite{fermion}. Unruh radiation does not license vacuum substance ontology \cite{unruh}. Hawking radiation does not license transit ontology \cite{hawking}. In each case the no-go denies the inference from successful lawful description to material existence in spacetime.

Collectively these results establish one consistent architecture. Lawful structure is timeless. Registration is the special circumstance in which lawful outcomes participate within coherent spacetime. The present paper identifies the consequence of accepting these results together.

\section{Definitions}
\label{sec:definitions}

The following definitions establish the architectural terms used throughout the paper. They are consistent with the canonical vocabulary of the Timeless Light Model corpus.


\begin{definition}[General timelessness]
\label{def:generaltimelessness}
General timelessness is the principle that time is not a constituent of lawful structure. Physical laws do not themselves pass through time, age, persist, or evolve. A mathematical expression of a law may include a time parameter, but that symbolic reference does not make time a component of the law itself. Time belongs to spacetime relations. When an admissible physical outcome registers within spacetime, temporal ordering and, where applicable, proper-time accumulation apply to that registered outcome \cite{generaltimelessness}. Timebound spacetime registration is therefore the special circumstance in which temporal properties apply, not the general condition under which lawful structure holds.
\end{definition}



\begin{definition}[Null proper time]
\label{def:nullpropertime}
Null proper time is the relativistic condition in which the proper-time interval --- the time accumulated along a worldline --- is zero, $\Delta\tau=0$. For a photon, no proper time accumulates between emission and absorption. The term identifies this standard relativistic result; the present framework further examines its ontological consequences.
\end{definition}


\begin{definition}[Lawful structure]
\label{def:lawfulstructure}
Lawful structure is the complete specification of the physical relations, constraint conditions, conservation principles, symmetries, selection rules, boundary conditions, coupling structure, and mathematical laws governing a physical system. Lawful structure is independent of any particular spacetime \defterm{registration}{def:relativisticregistration}.
\end{definition}

\begin{definition}[Lawful eligibility]
\label{def:lawfuleligibility}
Lawful eligibility is the status of a possible physical outcome as admissible for registration under the governing lawful structure. It is not occurrence, observation, or registration. It is the condition of being among the outcomes permitted by the relevant conservation principles, symmetries, selection rules, boundary conditions, coupling structure, and other governing physical laws. The governing lawful structure specifies which outcomes are eligible. Quantum mechanics describes those lawfully eligible outcomes and the mathematical relations governing their amplitudes and probabilities. Lawful eligibility does not determine which admissible outcome becomes registered.
\end{definition}

\begin{definition}[Registration]
\label{def:registration}
Registration is the lawful participation of an admissible physical outcome within spacetime such that it possesses temporal ordering, causal relations, geometric localization, and the possibility of observation or measurement by registered physical systems.

Registration is not human observation or consciousness. It is the spacetime anchoring of a lawful outcome within the relativistic spacetime order.
\end{definition}

\begin{definition}[Relativistic registration]
\label{def:relativisticregistration}
Relativistic registration is the particular form of registration implemented by the physical laws of our universe. It is governed by the rules of special relativity and general relativity, including causal ordering, finite information propagation, proper-time accumulation, observer consistency, and spacetime geometry.
\end{definition}


\begin{definition}[Spacetime]
Spacetime is the coherent structure within which relativistic registration occurs. The present paper treats spacetime as the ordered form of registered physical outcomes rather than as the general condition of lawful physical existence.
\end{definition}

\begin{definition}[Architectural role]
\label{def:arcrole}
An architectural role is the function performed by one aspect of the overall physical description. A complete physical description may require multiple such roles when different aspects answer different physical questions within one lawful structure.
\end{definition}


\begin{definition}[Clarified architecture]
\label{def:clarifiedarchitecture}
The clarified architecture is the descriptive organization of physical theory in which lawful structure governs admissibility, quantum mechanics describes lawful eligibility, and relativity governs the spacetime registration of admissible outcomes. Time is not a constituent of lawful structure. Mathematical descriptions of physical laws may refer to temporal quantities without thereby making time part of the laws themselves. Temporal ordering, causal relation, geometric localization, proper-time accumulation where applicable, and observer receipt belong to registered spacetime outcomes. The term \emph{architecture} emphasizes that these explanatory assignments divide the work of physical description; it does not point to a physical structure, object, place, or realm.
\end{definition}


\section{Quantum Mechanics Describes Lawful Eligibility}

Within the unified description developed here, the role of quantum mechanics is specific. Quantum mechanics describes lawful eligibility. It identifies the admissible physical outcomes under the governing lawful structure and specifies the mathematical relations --- amplitudes, probabilities, conservation relations, and selection rules --- governing those admissible outcomes.

The distinction between physical law and mathematical description is important. Physical law governs reality. Mathematics describes the lawful relations by which reality is governed. Wave functions, state vectors, Hilbert spaces, operators, and interaction terms are mathematical descriptions of the lawful structure governing physical possibilities. They do not themselves create the possibilities they describe, nor do they require a picture of persisting objects moving through successive spacetime locations. Conservation principles constrain which outcomes are admissible. Selection rules identify which transitions the governing lawful structure permits. Quantum mechanics mathematically describes the resulting range and organization of eligible outcomes.

The appearance of a time parameter in a mathematical expression of quantum mechanics does not make time a constituent of lawful structure. In the time-dependent Schr\"{o}dinger equation, the parameter $t$ describes the temporal relation of quantum states within a timebound physical description. Its appearance in the equation does not place time inside the governing law. The equation refers mathematically to temporal relations just as other equations refer to spatial position, energy, momentum, or charge. Symbolic reference to a physical quantity is not constitutive presence of that quantity within the law itself.

This distinction follows directly from general timelessness. Lawful structure does not age, wait, persist, or evolve. Time belongs to registered spacetime relations. Where a physical system participates within spacetime, its registered states and events may possess temporal ordering and proper-time accumulation. Quantum mechanics may describe how the lawfully eligible states of such a system are related with respect to that temporal coordinate without thereby converting the governing lawful structure into a temporal object.

Stationary states make the distinction especially clear. Stationary bound states remain structurally unchanged across arbitrarily long registered intervals because their lawful content does not itself age \cite{atom,generalatom}. A hydrogen atom in its ground state does not acquire a different governing lawful structure merely because proper time accumulates along its spacetime history. The lawful structure continues to specify the same admissible interactions and outcomes.

Radioactive atoms illustrate the same distinction. The governing lawful structure already contains the admissible decay channel and the probability relations associated with it. The law does not wait for a period of time and then decide to permit decay. A registered decay is a spacetime event conforming to a lawful channel already present in the governing structure. Temporal ordering belongs to the registered atom and the registered decay event; it is not a temporal development of the law itself.

The wave function deserves particular attention. It is frequently interpreted as though it were a physical object propagating through spacetime and then collapsing when a measurement occurs. That interpretation generates the familiar question of how a superposed physical thing becomes a single observed result. The present description removes that presupposition. The wave function is the mathematical description of the lawfully eligible outcomes and of the amplitude and probability relations governing them. It is not, under this interpretation, an additional physical object traveling through spacetime.

A registered outcome is a spacetime fact. The wave function describes the lawful eligibility structure under which that outcome was admissible. Mathematics represents the range and relations of eligible outcomes; the governing lawful structure is what makes those outcomes physically admissible. Registration is not a transformation of mathematical possibility into physical substance. It is the spacetime participation of an admissible physical outcome.

The same distinction applies in quantum field theory. Operators, interaction terms, state spaces, and field-mode decompositions mathematically describe the lawful relations governing possible physical outcomes. Their predictive success establishes the accuracy of the description without by itself requiring that the corresponding mathematical structures be treated as material substances occupying space \cite{fermion}.

The distinction between amplitudes and probabilities is important. A quantum amplitude is not itself a probability. Amplitudes possess phase and therefore combine before probabilities are obtained; amplitudes associated with alternative outcomes may reinforce or cancel one another through constructive and destructive interference. The probability associated with a possible registered outcome is obtained from the squared magnitude of the resulting amplitude. Wave mathematics therefore describes more than the relative frequency with which outcomes register. It describes the lawful interference structure among eligible alternatives. Nothing in that mathematical wave structure requires the wave function to be interpreted as a material wave propagating through a physical medium. Under the clarified architecture, the interference belongs to the mathematical description of lawful eligibility, while the resulting detections are registered spacetime outcomes.

Quantum mechanics therefore performs one explanatory task within the clarified architecture: it describes lawful eligibility and the mathematical relations governing admissible outcomes. It does not create the laws, determine the relativistic organization of registered events, or supply a spacetime traveler ontology for its mathematical objects. The governing lawful structure determines admissibility. Quantum mechanics describes that admissibility mathematically. Relativity governs the geometric, causal, and temporal organization of outcomes when they register within spacetime. The apparent conflict arises only when quantum mechanics is expected to perform explanatory work belonging to registration as well as eligibility.






\section{Relativity Describes the Lawful Organization of Registration}

Within the \defterm{clarified architecture}{def:clarifiedarchitecture}, the role of relativity is equally specific and complete. Special relativity and general relativity describe the laws governing the organization of \defterm{relativistic registration}{def:relativisticregistration}. Those laws govern what registered observers receive, when they receive it, how registered events relate to one another causally and geometrically, and what the consistent spacetime structure of a universe containing multiple observers must be.

These are not arbitrary physical rules imposed from outside. The Newtonian Holodeck paper argued that the relativistic framework represents the necessary conditions under which a coherent observable universe can sustain itself \cite{holodeck}. Without finite information propagation, observers cannot maintain consistent causal histories. Without invariant light speed, simultaneity becomes incoherent across frames. Without proper-time accumulation along worldlines, the aging of massive systems has no consistent description. Without spacetime geometry relating registered events, observation becomes frame-dependent in ways that cannot be reconciled. Relativity describes the lawful organization of \defterm{registration}{def:relativisticregistration} itself.

Special relativity describes registration within flat spacetime. It establishes invariant relationships among inertial observers, finite propagation of information, Lorentz transformation of coordinates, and proper-time accumulation along timelike worldlines. General relativity extends these principles to curved spacetime, relating the distribution of stress-energy to spacetime geometry and determining the inertial paths of matter and radiation within that geometry.

Neither special relativity nor general relativity determines which physical outcomes are lawfully admissible. That is not their \defterm{architectural role}{def:arcrole}. What a distant observer receives when an atom emits a photon --- the direction, frequency, arrival time, and causal relationship to other events --- is governed by relativistic registration. Which outcomes the atom may produce in the first place is determined by the governing lawful structure. Quantum mechanics describes those lawfully eligible outcomes and the mathematical relations governing their probabilities and amplitudes. These questions do not compete. They belong to different architectural roles within one coordinated lawful structure.

The relativistic no-go results in the published corpus reinforce this reading. The interpretation of the invariant speed limit $c$ as a registration bound, developed previously in the Timeless Light Model, establishes that the speed of light is not a constraint on a traveler but a constraint on the coherent propagation of registration \cite{regbound}. The previously published retrocausality no-go establishes that retrocausal objections to photon behavior presuppose an intermediate photon history that null proper time disallows \cite{retrocausality}. The previously published Unruh and Hawking no-gos establish that observer-relative particle content and horizon-conditioned radiation do not license material substance in the vacuum or transit through the horizon \cite{unruh,hawking}. In each case the no-go denies a move from successful relativistic description to unwarranted ontological conclusion. The relativistic description governs registration. It does not license the inference that a persisting material thing was traveling.

Gravitational waves provide a further confirmation of this reading. In general relativity, gravitational waves propagate at the invariant speed and follow null structure. They are registered by detectors through local strain events, as in interferometric detection. Here the Einstein field equations describe the lawful structure of registration, including the admissible spacetime geometries and propagation forms, while relativistic registration governs how those solutions appear as registered strain within coherent spacetime. The clarified architecture therefore treats gravitational-wave observation in the same architectural pattern as photon observation: the registered detector events are spacetime facts, while the lawful relation connecting source and registration is governed by relativistic structure. No additional traveler ontology is required. The propagation law belongs to the lawful organization of registration; the registered strain belongs to the detector-side spacetime outcome.

Relativity is therefore complete in its architectural role. It describes the lawful organization of registered spacetime outcomes. Determining lawful eligibility lies outside its architectural responsibility.


\section{Entanglement Is Timeless Lawful Structure}

Quantum entanglement has long appeared mysterious because correlated outcomes are observed across spatial separation without any corresponding signal propagating between the detectors. Under the \defterm{clarified architecture}{def:clarifiedarchitecture}, the apparent mystery results from assigning a spacetime requirement to a lawful relation. The entanglement relation is not a signal, traveler, or physical transmission crossing the intervening distance. It is part of the lawful structure governing the joint system. Because nothing propagates between the detectors to establish the correlation, no propagation speed --- including the invariant speed $c$ --- applies to the correlation itself.

This distinction follows from the difference between physical law and its mathematical description. Mathematics describes the lawful relations governing physical reality; it does not create or control those relations. The governing law determines what physical outcomes are admissible and how the eligible outcomes are related. Quantum mechanics supplies the mathematical description of that lawful structure.

An entangled pair is described by a single joint wave function.\footnote{\scriptsize%
\textbf{Prior art and the present contribution.}

\textit{What standard physics already established.}
Quantum mechanics has long described entangled pairs using a single joint wave function $\Psi(x_1,x_2)$ defined over the configuration space of both particles. An entangled state cannot be factored into independent single-particle states. The joint state specifies correlated probability amplitudes for measurements performed on the two systems. Bell's theorem established that the experimentally observed correlations cannot be reproduced by local hidden-variable theories, and subsequent Bell-test experiments have confirmed the quantum predictions, including loophole-free tests reported in 2015 \cite{epr1935,schrodinger1935,bell1964,hensen2015}. The broader experimental program was recognized by the 2022 Nobel Prize in Physics \cite{nobel2022}.

The no-communication theorem further establishes that entanglement correlations cannot be used to transmit controllable information faster than light. Standard quantum mechanics therefore predicts the correlations without requiring an operational faster-than-light communication channel.

\textit{What standard physics left unresolved.}
The mathematical formalism accurately specifies the joint probabilities, but the formalism by itself does not determine an ontology for the correlation. It does not establish that a physical signal, influence, particle, or other spacetime object passes from one detector to the other. Interpretations differ precisely over what, if anything, should be added to the mathematical description.

\textit{The present contribution.}
The present paper supplies an architectural interpretation. The joint wave function is treated as the mathematical description of one governing lawful relation. The correlation itself belongs to lawful structure rather than to a spacetime transmission between the detectors. The registered detector outcomes occur locally within spacetime and are governed by relativistic registration. The correlation connecting those outcomes is not transmitted across the intervening space and therefore has no propagation speed to compare with $c$.

The resulting formulation is: ``one lawful relation, two local registrations.'' The mathematics describes the joint lawful eligibility structure; the governing law controls the physical admissibility and correlation of the outcomes; and relativity governs the local spacetime registration of each outcome.
}

The joint wave function describes the correlated lawfully eligible outcomes and mathematically represents their joint amplitude and probability structure. The mathematical description is not itself the physical cause of the correlation. It describes the governing lawful relation under which the possible registered outcomes are jointly constrained.

When a measurement outcome registers at one detector, that registration is local. When an outcome registers at the other detector, that registration is likewise local. Each detector event occupies its own place within relativistic spacetime and possesses the temporal ordering, causal relations, and geometric localization supplied by relativistic registration.

The correlation between those outcomes is different in kind. It is not another registered event lying between the detectors. It is not a signal departing one detector and arriving at the other. It is not a physical object moving through the intervening space. The correlation belongs to the joint lawful structure governing both registrations.

The invariant speed $c$ governs relativistic propagation within spacetime. A physical signal sent from one registered location to another is subject to that constraint. The entanglement relation is not such a signal. Since no correlation-bearing object or influence propagates from one detector to the other, there is no distance traversed per unit time and therefore no speed to assign to the correlation.

For this reason, describing entanglement as ``faster than light'' is already to import the wrong category. Faster and slower are properties of propagation through spacetime. The entanglement correlation does not propagate. It is the lawful relation under which the two local registrations are jointly governed.

This also explains why entanglement creates no conflict with relativity. Relativity governs each spacetime registration and any physical communication between registered systems. Nothing in the entanglement relation permits a controllable signal to be transmitted outside the relativistic causal structure. The joint correlation is not constrained by $c$ because it is not a spacetime transmission; the registered physical systems remain governed by relativity wherever spacetime propagation and causal interaction occur.

Bell's theorem reinforces this architectural distinction. The observed correlations cannot be explained by assigning each separated system a set of local predetermined values whose subsequent revelation reproduces the quantum statistics \cite{bell1964}. Under the clarified architecture, this is expected: the correlation is not carried independently by two local spacetime objects. It belongs to the single lawful structure governing their joint eligibility.

The absence of explicit time dependence in a stationary joint wave function is consistent with this interpretation, but it is not the basis of the argument. A mathematical expression may include or omit a time variable without thereby determining whether time is a constituent of the governing law. Mathematics describes the lawful relation. The ontological distinction instead follows from what the correlation physically is under the clarified architecture: a governing lawful relation rather than a spacetime event or transmission.

Entanglement therefore illustrates the division of explanatory roles at the center of this paper. Quantum mechanics describes the joint lawfully eligible outcomes and the mathematical relations governing their amplitudes and probabilities. Relativity governs the local spacetime registration of those outcomes. The entanglement correlation itself is part of the lawful structure governing the joint system. It does not cross the space between the detectors, does not propagate through time, and is not subject to $c$ as a propagation limit.

There is therefore no instantaneous mechanism to explain. ``Instantaneous'' still describes a temporal comparison between spacetime events. The correlation is not an event occurring rapidly between the detectors. There is one lawful relation and two local registrations. The apparent paradox arose from treating the lawful relation as though it were a physical process that had to travel from one registered location to another.





\section{The Photon Is Not a Thing}

The photon is not a side issue in the present architecture. It is the physical case that exposes the architecture. The reason the unified interpretation becomes visible at all is that null proper time removes the ordinary persistence narrative from light. Once that consequence is followed consistently, timeless lawful structure is no longer an abstraction placed behind physics. It is the general condition already disclosed by physics.

Under the \defterm{clarified architecture}{def:clarifiedarchitecture}, 
a photon is not a thing. It is a lawful relation between two state changes, 
consistent with the minimal TLM canon's description of the photon as a 
lawfully admissible charge-state relation whose spacetime appearance is a 
lawful change \cite{bedrock}.

Consider what is actually registered. An emitter drops to a lower energy state. At some later time, as organized within relativistic spacetime, an absorber rises to a higher energy state. These two events are real. They are registered in spacetime. They are temporally ordered by SR/GR for every registered observer. Between them, no photon in flight is ever registered. Every observation of light is a \defterm{registration}{def:relativisticregistration} at a detector --- an absorption event --- never an observation of a photon crossing the intervening space \cite{nogocrosssky}. This is not a technological limitation. It follows from the structure of photodetection itself: detecting a photon is already an absorption event, and therefore already a registration \cite{nogocrosssky}.

The ordinary traveler picture adds something not given in the registration record. It imagines that a photon leaves the emitter, occupies successive positions, crosses the intervening space, and finally arrives at the absorber. But the standard relativistic result does not support that narrative. A photon has zero proper time along its worldline. For light, the spacetime interval is null:
\[
\Delta s^2 = c^2 \Delta t^2 - \Delta x^2 = 0.
\]
The spatial and temporal terms cancel exactly. This is not an approximation. It is an exact result of relativistic geometry.

Zero proper time means no accumulated history. It means no internal clock, no rest frame, and no sequence of experienced locations. The photon does not possess the timed interior required by the traveler picture. From the standpoint of registered observers, emission and absorption are separated by distance and time. From the standpoint of the null interval, there is no proper-time middle in which a photon persists as an object crossing space.

This is the decisive clue. The photon is the case in which spacetime registration and timeless lawful relation visibly separate. SR/GR supplies the temporal and geometric ordering of the registered events. The governing lawful structure makes the emission and absorption relation admissible, and quantum mechanics describes that lawful eligibility. But the photon itself is not an additional persisting object inserted between the two. The word ``photon'' names the lawful relation connecting the state changes. It does not name a little traveler occupying the gap.

Nor does replacing the particle with a physical wave restore the traveler picture. 
That move merely relocates the same ontology from photon-bead to wave-stuff. 
The wavefunction belongs to lawful eligibility: it organizes the admissible structure of possible photon appearances in spacetime, but it does not supply an internal photon journey, a spacetime substance, or a second occupant crossing the gap \cite{bedrock,wavefunctionnogo}. The emitter's state change and the absorber's state change are the registered spacetime facts. The law connecting them belongs to timeless lawful structure.

The apparent journey of the photon is therefore the registration-side appearance of a timeless lawful relation. What observers receive is organized by SR/GR: direction, arrival time, frequency, causal order, and geometric relation to other registered events. What makes the relation physically admissible belongs to timeless lawful structure. Nothing crosses the intervening space because there is no persisting thing whose crossing needs to be described.

This also dissolves the retrocausality objection at its root. Retrocausal interpretations assume an intermediate photon history on which backward influence, endpoint coordination, or future boundary selection could be placed \cite{retrocausality}. But null proper time removes the intermediate history. The photon has no timed middle. There is no traveler to be influenced backward, no route to be selected in advance, and no physical object whose later absorption must reach back to govern its earlier path. The objection presupposes the very photon history that the null case disallows.

The photon is the decisive physical case for the clarified architecture. It shows why the general condition of physics cannot be ordinary spacetime persistence. Light appears, at first, to be the paradigmatic case of transmission across space. Yet when its null proper-time structure is taken seriously, the traveler picture fails precisely where it seemed strongest. What remains is not a persisting object moving between two events, but a timeless lawful relation and its registered state changes. The lawful structure makes the relation admissible. The state changes are registered. Relativity organizes those registrations. Quantum mechanics describes the lawfully eligible relation and the mathematical relations governing its amplitudes and probabilities. The photon is therefore not a thing traveling between the two events. It is the name given to the lawful relation by which the two registered state changes are connected.

This is why null proper time matters for unification. Once the photon is no longer treated as a persisting spacetime object, the larger architecture becomes visible. Quantum mechanics and relativity are not rival accounts of one traveling thing. They are complementary descriptions of lawful eligibility and registered spacetime ordering. The governing lawful structure determines the admissibility of the relation. Quantum mechanics describes that lawfully eligible relation and its amplitude and probability structure. Relativity organizes the registered state changes. The photon is the diagnostic case in which the clarified architecture becomes unavoidable.




\section{The Clarified Architecture}

The preceding sections establish the central hierarchy: lawful structure is the general condition, while relativistic registration is a special class of lawful relation within that structure. The present section states the resulting architecture formally.

\begin{proposition}[\defterm{Clarified architecture}{def:clarifiedarchitecture}]
Physical reality admits a unified description under one coordinated lawful structure. The governing lawful structure determines which physical outcomes are admissible. Quantum mechanics describes those lawfully eligible outcomes and the mathematical relations governing their amplitudes and probabilities. Special relativity and general relativity govern relativistic registration: the coherent spacetime organization of registered lawful outcomes. These are not rival descriptions of one temporal process. They are complementary architectural roles within one lawful structure.
\end{proposition}

\begin{proof}
The governing lawful structure determines which physical outcomes are admissible. Quantum mechanics describes those lawfully eligible outcomes. Its mathematical formalism represents the possible states of a physical system together with the amplitude, probability, conservation, and transition relations governing those possibilities. Quantum mechanics therefore describes lawful eligibility; it does not create, grant, or determine admissibility. Nor does it determine the relativistic organization of registered events.

Special relativity governs invariant relationships among inertial observers, finite information propagation, proper-time accumulation, and causal ordering. General relativity governs the geometric organization of spacetime through the relationship between stress-energy and curvature. Neither relativistic theory determines which physical outcomes are lawfully admissible.

The explanatory questions answered by these architectural roles are therefore different and complementary.

Lawful structure answers: what are the governing laws under which outcomes are admissible?

Lawful eligibility answers: which possible outcomes fall inside the admissible set and which fall outside it?

Quantum mechanics answers: what is the range of eligible outcomes to be expected, and what mathematical relations govern their amplitudes and probabilities?

Relativistic registration answers: how are registered outcomes coherently organized within spacetime, and what do observers receive?

Because these questions are distinct and jointly sufficient for the architectural description developed here, the existing theories together constitute a complete unified explanatory architecture.
\end{proof}

The architecture is represented in Figure~\ref{fig:architecture}.

\begin{figure}[h]
\centering
\begin{tikzpicture}[
box/.style={draw, rounded corners=4pt, text centered,
minimum width=7.4cm, minimum height=1.35cm,
font=\sffamily},
outer/.style={draw, rounded corners=6pt, inner sep=0.35cm,
fill=gray!10},
arrow/.style={->, thick, >=stealth}
]
\node[box, fill=gray!20] (eligibility) {%
\begin{tabular}{c}
\textbf{LAWFULLY ELIGIBLE OUTCOMES}\\[3pt]
{\small Described by Quantum Mechanics}
\end{tabular}};
\node[box, fill=gray!15, below=0.55cm of eligibility] (registration) {%
\begin{tabular}{c}
\textbf{RELATIVISTIC REGISTRATION}\\[3pt]
{\small Governed by Special and General Relativity}
\end{tabular}};
\node[box, fill=gray!5, below=0.55cm of registration] (spacetime)
{\textbf{COHERENT SPACETIME ORGANIZATION}};

\begin{pgfonlayer}{background}
\node[outer, fit=(eligibility)(registration)(spacetime),
label={[font=\sffamily\bfseries]above:TIMELESS LAWFUL STRUCTURE}]
(lawfulstructure) {};
\end{pgfonlayer}

\draw[arrow] (eligibility.south) -- (registration.north);
\draw[arrow] (registration.south) -- (spacetime.north);
\end{tikzpicture}
\caption{Clarified architecture. Lawful structure is the general condition and determines which physical outcomes are admissible. Quantum mechanics describes those lawfully eligible outcomes and the mathematical relations governing their amplitudes and probabilities. Relativistic registration is the special class of lawful relation in which admissible outcomes participate within coherent spacetime, governed by special and general relativity.}
\label{fig:architecture}
\end{figure}

Two features of this architecture deserve emphasis.

The arrows in Figure~\ref{fig:architecture} do not indicate temporal sequence. They indicate architectural dependence. Timeless lawful structure is the general condition. Relativistic registration is one class of lawful relation within that structure: the class in which lawful outcomes participate in spacetime with temporal ordering, causal relation, geometric localization, proper-time accumulation, and observer receipt.

Lawful eligibility and registration are therefore not sequential stages. There is no temporal order in which lawful eligibility first exists and registration later follows. Lawful structure is timeless. Registration is timebound. The distinction is architectural, not chronological. Importing a temporal order between them would reproduce the very error the clarified architecture is designed to correct.

Nor are lawful eligibility and registration two equal ontological domains standing side by side. Lawful structure is the general condition. Registration is a special case within it. The governing lawful structure determines the admissibility of physical outcomes. Quantum mechanics describes those lawfully eligible outcomes and the mathematical relations governing their amplitudes and probabilities. Relativity governs their spacetime organization when they register. These descriptions are complementary, but not symmetrical: relativity does not stand outside lawful structure; it describes the rule-governed form that lawful structure takes when outcomes participate in coherent spacetime.



\section{Why Physics Appeared Disunified}

If the unified architecture was always present in the existing theories, why was it not recognized?

The answer lies in the failure to propagate the ontological consequences of null proper time consistently throughout physics.

The standard physical picture begins with time. Physical reality is assumed to consist of things that exist within spacetime and evolve as time progresses. Laws are rules that govern how those things change. Under this picture, timelessness is an edge case --- a mathematical abstraction that occasionally appears but does not reflect the general condition of reality.

Under this assumption, both quantum mechanics and relativity appear to be theories about how things evolve through time. Quantum mechanics appears to govern the time evolution of state vectors --- the mathematical objects used to represent a system's possible physical states. Relativity appears to govern the time evolution of spacetime geometry --- the mathematical structure used to represent distances, durations, causal relations, and gravitational curvature --- together with the histories of massive objects. Both theories therefore appear to describe the same kind of process: temporal evolution within a universe of persisting physical things. Their mathematical incompatibilities then naturally motivate the search for a deeper framework.


The error originates in not following null proper time to its ontological conclusion. Relativity establishes that the photon has zero proper time. A photon has no rest frame, no accumulated proper-time history, and no internally ordered sequence of locations through which it travels as a massive object does. If this result is honored ontologically and not merely noted mathematically, then the ordinary persistence narrative does not apply to light.

That consequence is decisive. Light is the physical case most often mistaken for a carrier moving through spacetime. It appears to be the paradigm of transmission: something leaves here, crosses the gap, and arrives there. But null proper time removes the timed middle required by that picture. Emission and absorption are registered in spacetime; the lawful relation connecting them is not a persisting traveler between them.

Once the carrier picture fails for light, timelessness can no longer be treated as an edge case. The physical case that seemed most to require spacetime transit instead discloses the reversal established in the General Timelessness paper \cite{generaltimelessness}: timebound registration is the special case, and timeless lawful structure is the general architectural condition.

Under this reversal, quantum mechanics and relativity no longer appear to compete. Quantum mechanics describes the lawfully eligible outcomes and the mathematical relations governing their amplitudes and probabilities, exactly as its formalism has always done. Relativity governs timebound \defterm{registration}{def:relativisticregistration}, exactly as its formalism has always done. The apparent competition was produced by reading both theories through a temporal lens that null proper time already disallows.


The unified theory problem therefore did not arise from a genuine incompleteness of the existing theories. It arose from an architectural misreading that was itself produced by an incomplete application of a known physical result.

\begin{remark}[The measurement problem]
The measurement problem, as traditionally framed, asks why one lawfully admissible outcome rather than another is registered as the result of a given observation, and what physical process produces the transition from superposed possibilities to a single registered outcome. The \defterm{clarified architecture}{def:clarifiedarchitecture} dissolves rather than answers that question. The problem arises only if the wave function is treated as a physical thing occupying spacetime that must somehow collapse into a single result.

The clarified architecture denies that presupposition. The governing lawful structure determines which outcomes are admissible. The wave function describes those lawfully eligible outcomes and the mathematical relations governing their amplitudes and probabilities; it is not a physical object in spacetime. The lawful-eligibility structure is definite. The single registered spacetime outcome belongs to registration, not to the description of lawful eligibility itself.

The apparent problem results from assigning to lawful eligibility an explanatory task that belongs to registration. Quantum mechanics describes the lawfully eligible outcomes and their amplitude and probability relations. Relativistic registration governs the spacetime ordering, localization, causal relation, and observer receipt of the outcome that registers. These are complementary descriptions of one lawful order, but they answer different questions.

\end{remark}


\begin{remark}[Outcome selection and collapse]
In this architecture, outcome selection is a misleading phrase if it suggests an additional physical operation behind registration. Relativistic registration organizes the registered outcome; it does not select it. Quantum mechanics describes the lawful eligibility structure, including the amplitudes and probabilities of admissible outcomes. The registered outcome is the spacetime fact.

Asking for an additional physical mechanism that turns eligibility into registration repeats the category error the architecture is designed to remove. It treats lawful eligibility as though it were a spacetime process requiring a further transition. Under the clarified architecture, there is no such process. There is lawful eligibility, and there are registered outcomes. Each registered outcome is lawful because it is an admissible outcome under the eligibility structure; the probability relations are expressed across ensembles of registrations.

The double-slit experiment illustrates the point. A single detection on the screen is a local registered event. Across many such registrations, the distribution expresses the lawful wave structure. The pattern does not require a photon-object to have traveled through both slits as a physical thing, nor does it require a physical collapse of that thing at detection. The apparent need for selection arises only when the probability structure is mistaken for a physical object in spacetime \cite{wavefunctionnogo}.

\end{remark}

\section{Physics Is Already Unified}

The preceding sections establish the following.

Physical reality is governed by timeless lawful structure. Some relations permitted by that structure register within spacetime and thereby acquire temporal ordering, causal relation, geometric localization, and observability. When registration occurs, it is governed by the laws of special and general relativity. The governing structure determines which physical outcomes are admissible. Quantum mechanics describes those eligible outcomes and the mathematical relations governing their amplitudes and probabilities. Relativity describes the spacetime organization of registered outcomes.


\begin{proposition}[Physics is already unified]
The existing physical theories of quantum mechanics, special relativity, and general relativity constitute a unified physical description under the \defterm{clarified architecture}{def:clarifiedarchitecture} established by general timelessness.
\end{proposition}

\begin{proof}
A unified architectural description requires an account of which physical outcomes are lawfully admissible, how the amplitudes and probabilities of those outcomes are mathematically related, and how registered outcomes participate within coherent spacetime.

The governing lawful structure determines which physical outcomes are admissible. Quantum mechanics provides the mathematical description of those lawfully eligible outcomes. Its formalism represents the admissible states and outcomes of physical systems together with the amplitude, probability, conservation, and transition relations governing them. Quantum mechanics therefore describes lawful eligibility; it does not create, grant, or determine admissibility.

Special relativity and general relativity provide the account of the spacetime organization of relativistic registration. Their formalisms govern the causal ordering, geometric organization, finite information propagation, proper-time accumulation, and observer consistency of registered outcomes within spacetime.

Together these theories perform the complementary roles required by the clarified architecture. Quantum mechanics describes the lawfully eligible outcomes and their mathematical relations. Special relativity and general relativity describe the coherent spacetime organization of registered outcomes. No third theory is required to bridge them for this architectural purpose, because the apparent conflict arose from assigning both theories the same explanatory task. Once their roles are correctly distinguished, there is no architectural conflict requiring resolution.

The existing theories therefore constitute a unified physical description. The unification does not require new mathematics. It requires recognizing their functions as complementary descriptions.
\end{proof}

This result does not close physics. Future theories may extend quantum mechanics, extend relativity, or describe phenomena not yet accessible to observation. Nothing in the present argument forecloses such developments. The claim is more specific: the traditional demand for a unified theory, understood as a demand to reconcile quantum mechanics and relativity as competing descriptions of one timebound physical process, is answered by the clarified architecture.

Quantum mechanics and relativity were never rival accounts of one temporal process. The governing lawful structure determines which outcomes are admissible. Quantum mechanics describes those lawfully eligible outcomes and the mathematical relations governing their amplitudes and probabilities. Relativity describes the coherent spacetime organization of registered outcomes. General timelessness identifies the lawful structure within which both roles are possible: time-free admissibility and timebound registration. The demand for reconciliation therefore does not require new mathematics. It requires recognizing the complementary roles played by the existing theories.


\section{Relationship to Existing Physics}

The \defterm{clarified architecture}{def:clarifiedarchitecture} leaves the predictive content of existing physics entirely unchanged.

Quantum mechanics continues to provide the mathematical formalism describing lawfully eligible outcomes and the relations governing their amplitudes and probabilities. State vectors, operators, amplitudes, spectra, conservation principles, and selection rules retain their ordinary predictive roles. The Schr\"{o}dinger equation is unchanged. Quantum field theory is unchanged. The Standard Model is unchanged.

Special relativity continues to govern invariant relations among observers, Lorentz transformations, proper-time relations, and finite information propagation. General relativity continues to govern the relation between stress-energy and spacetime geometry. No established prediction of either theory is altered.

The present paper changes none of these mathematical structures. Its claim is architectural and interpretive. It concerns the explanatory role each theory performs within the overall physical description. The governing lawful structure determines which physical outcomes are admissible. Quantum mechanics describes those lawfully eligible outcomes and the mathematical relations governing their amplitudes and probabilities. Relativity describes the coherent spacetime organization of registered outcomes. The predictive content of each theory remains unchanged.

Several phenomena that have appeared mysterious or unresolved under conventional interpretations are straightforwardly handled by the clarified architecture. Quantum entanglement is resolved by recognizing that the joint correlation belongs to the lawful structure governing the entangled system rather than to a signal or physical influence propagating through spacetime. The two detector outcomes register locally and remain relativistically consistent, while the correlation itself does not traverse the intervening distance and therefore has no propagation speed to compare with $c$. The joint wave function mathematically describes that lawful relation; whether its mathematical expression includes an explicit time variable is not what makes the relation timeless. The ontological puzzles surrounding Hawking radiation and Unruh radiation are resolved by the published no-go results: neither effect licenses transit ontology or vacuum substance ontology, and both are correctly read as observer-relative registration phenomena governed by the lawful structure of the field \cite{hawking,unruh}. The Hawking derivation is an exterior result; it does not license interior ontology \cite{hawkinginterior}. The inference from successful quantum field description to material field substance in space is likewise denied by the fermion fields no-go \cite{fermion}. In each case, the architecture does not introduce new physics. It supplies the architectural reading that the existing physics already implies.



\section{What This Paper Does Not Claim}

The architectural argument is intentionally limited in scope.

\begin{remark}
The present paper does not replace quantum mechanics. The standard mathematical formalism of quantum mechanics remains unchanged. The interpretation advanced here concerns the architectural role performed by that formalism rather than its predictive content.
\end{remark}

\begin{remark}
The present paper does not replace special relativity or general relativity. Lorentz invariance, invariant light speed, proper time, the standard relativistic transformation laws, and the Einstein field equations all remain unchanged.
\end{remark}

\begin{remark}
The present paper does not derive one existing theory from another. It does not derive quantum mechanics from relativity or relativity from quantum mechanics. It argues that each theory performs a distinct explanatory function within a common architectural framework.
\end{remark}

\begin{remark}
The present paper introduces no new physical constants, particles, fields, conservation laws, or experimentally measurable quantities. Its contribution is architectural and interpretive.
\end{remark}


\section{What This Paper Does Not Cover}

The distinction developed in the preceding section --- between what this paper claims and what it does not claim --- concerns the architecture itself. A further distinction is needed concerning the content of physical law within that architecture.

The present paper does not claim that the content of physical law is fully known. The Standard Model's free parameters, the hierarchy problem, and the cosmological constant problem remain open research questions about what the lawful structure specifically contains. These are gaps in physics's current knowledge of the laws, not gaps in the architecture itself. If quantum field theory is missing a law it needs in order to predict some result, that is a problem for physics to solve, not a problem with the existence of lawful structure. The universe is not confused about its own laws; physicists are still working out what those laws say.

The universe is not coming apart at the seams between quantum and relativistic description. It continues to function coherently across every observed regime. This coherence is itself evidence that some lawful structure already governs whatever physics has not yet written down. The architecture established in this paper does not depend on physics having completed that work. It depends only on recognizing that lawful eligibility and relativistic registration perform complementary explanatory roles, regardless of how much of their detailed content remains to be discovered.

This is consistent with the published corpus. The Bedrock statement establishes the distinction between timeless lawful structure and timebound spacetime registration \cite{bedrock}. The General Timelessness paper establishes that time is not the universal background condition of physical law and that timebound spacetime appearance is the special case \cite{generaltimelessness}. Neither result depends upon whether a mathematical expression of a law includes a time variable. A mathematical description may refer to temporal quantities without making time a constituent of the law itself. Temporal properties belong to registered spacetime relations.

Neither result therefore requires a complete specification of every law's content. Both hold regardless of how many parameters the Standard Model eventually requires, regardless of whether the hierarchy problem is ever solved, and regardless of what quantum gravity research eventually produces for extreme regimes such as black hole interiors or the early universe.

The present paper therefore claims only that lawful eligibility and relativistic registration are complementary explanatory roles within one coordinated lawful structure. It does not claim that the content of that lawful structure has been completely specified by current theory, and it does not claim to supply that missing content itself.



\section{Discussion}

The claim that physics is already unified is a strong claim. It is appropriate to say precisely what it means and what it does not mean.

It means that the existing mathematical formalisms of quantum mechanics and relativity, interpreted under the \defterm{clarified architecture}{def:clarifiedarchitecture} established by general \defterm{timelessness}{def:generaltimelessness}, provide a complete and non-competing physical description for this architectural purpose. The governing lawful structure determines which physical outcomes are admissible. Quantum mechanics describes those lawfully eligible outcomes and the mathematical relations governing their amplitudes and probabilities. Relativity governs how registered outcomes participate within coherent spacetime. No third framework is needed to reconcile the theories for this purpose, because they do not conflict when their explanatory roles are correctly distinguished.

It does not mean that all physical questions are answered. The nature of dark matter, the cosmological constant, the origin of the universe, and the behavior of physics in extreme regimes such as black hole interiors remain open. These are genuine open questions. They are not symptoms of a conflict between quantum mechanics and relativity as architectural frameworks. They are open questions about the detailed content of lawful structure and its registered spacetime expression. Dark matter, whatever it proves to be, presents a problem concerning the lawful content of physics and its \defterm{relativistic registration}{def:relativisticregistration}: it gravitates, affects spacetime geometry, and influences the motion of observable matter. The clarified architecture does not require a complete inventory of everything that registers in spacetime. It requires only that every physical outcome be admissible under the governing lawful structure and that every spacetime outcome register according to the laws governing coherent spacetime.

\begin{mdframed}[linewidth=0.8pt, innertopmargin=10pt, innerbottommargin=10pt, innerrightmargin=14pt, innerleftmargin=14pt, backgroundcolor=gray!15, leftmargin=0.33in, rightmargin=0.33in]
\noindent\textit{The unified-theory problem, as traditionally framed, rests on a false premise. Quantum mechanics and relativity do not need to be reconciled as rival descriptions of one temporal process. They were never rivals. The governing lawful structure determines which physical outcomes are admissible. Quantum mechanics describes those lawfully eligible outcomes and the mathematical relations governing their amplitudes and probabilities. Relativity governs the coherent spacetime organization of registered outcomes. The apparent conflict arose because both theories were forced into the same explanatory role. Once that misassignment is corrected, the demand for a third reconciling framework dissolves.}
\end{mdframed}

It does not mean that future mathematical work is unnecessary. Physics may still require additional formal development in regimes where current theory is incomplete, including black hole interiors, the earliest universe, quantum gravity, dark matter, and the detailed content of lawful structure. The present paper does not address those problems. It addresses the specific conceptual claim that quantum mechanics and relativity stand in conflict because they must be reduced to one deeper framework. That claim is mistaken. The apparent conflict arose from treating both theories as competing descriptions of timebound physical processes rather than recognizing that they provide complementary descriptions of one lawful order.

The distinction between physical law and its mathematical description is central to this conclusion. Physical law governs reality. Mathematics describes the lawful relations by which reality is governed. A mathematical expression may refer to time, space, energy, momentum, or other physical quantities without making those quantities constituents of the law itself. In particular, the appearance of a time parameter in an equation does not make time a component of lawful structure. Time belongs to spacetime relations and applies where admissible physical outcomes register within spacetime.

The same distinction clarifies why the absence of an explicit time variable in a mathematical expression is not, by itself, proof of timelessness. Timelessness is not inferred from notation. Lawful structure is timeless because time is not one of its constituents. Mathematical forms may express that lawful structure with or without explicit temporal parameters depending upon the physical relations being described.

Entanglement illustrates the point directly. The joint wave function mathematically describes one lawful relation governing the correlated eligible outcomes. The correlation itself is not a signal, traveler, or influence propagating between the detectors. It therefore has no propagation speed to compare with $c$. The detector outcomes register locally within spacetime and remain governed by relativity. There is one lawful relation and two local registrations. The apparent conflict with relativity arises only if the correlation is first mistaken for a spacetime transmission.

The deepest consequence of the clarified architecture may be that it changes what unification means. The traditional program sought unification through reduction --- one framework that replaces two. The clarified architecture achieves unification through recognition --- two formalisms that were always complementary, now correctly assigned to their explanatory roles. Quantum mechanics and relativity were never competing descriptions of one temporal process. They were always describing different features of one lawful order.

General timelessness names the condition underlying that order. Time is not a constituent of lawful structure. Within that lawful structure, physical outcomes possess lawful eligibility, quantum mechanics describes those eligible outcomes and their amplitude and probability relations, and relativity governs their coherent spacetime organization when they register. The resulting physical description is unified not because one theory absorbs the other, but because both theories perform complementary functions within one coordinated lawful structure.

That architecture was always present. It required only that the ontological consequences of null proper time be followed consistently and that time cease to be treated as a constituent background of law.

\subsection{Lawful Structure Is Not a Place}

The \defterm{clarified architecture}{def:clarifiedarchitecture} does not divide reality into two locations. It does not place timeless lawful structure in one realm and relativistic registration in another. The distinction is not spatial. Reality is governed by lawful structure, while spacetime registration is the circumstance in which admissible physical outcomes possess temporal ordering, causal relation, geometric localization, proper-time accumulation where applicable, and observer receipt.

Lawful structure therefore has no geometry, extension, location, or temporal duration. It is not somewhere outside spacetime, nor is it a background stage on which spacetime events occur. It is the coordinated structure of the laws governing physical reality. Time is not a constituent of those laws. Mathematical expressions of lawful relations may refer to temporal and spatial quantities without thereby making time or space constituents of law itself. Spacetime is not the container of lawful structure; relativistic registration is the lawful organization of physical outcomes that possess spacetime relations.

This distinction has a direct consequence for how physical information is understood. The standard picture treats light as a carrier --- a particle that departs one location, crosses the intervening space, and arrives at another, delivering information along the way. That picture imports the traveler narrative into a case where the physical structure does not license it. Under the clarified architecture, the lawful relation is not sent from source to destination. The emitter and absorber register as spacetime events, and their relation conforms to the governing lawful structure. No persisting carrier is required between those registered endpoints.

The same principle applies more generally. A lawful relation does not have to occupy the spacetime interval separating the events it governs. The mathematics may describe the spatial separation, temporal ordering, amplitudes, probabilities, or other measurable relations associated with those events, but the governing law is not thereby converted into an object extended through that space or duration. The law governs the relation; registered outcomes possess the spacetime properties.

This is why null proper time is not merely a mathematical curiosity but an architectural key. The absence of a photon history between emission and detection is not explained merely by saying that the photon has no clock. Null proper time exposes the deeper error in the transmission picture itself \cite{retrocausality}. Emission and absorption are registered spacetime facts. The lawful relation connecting them does not constitute a persisting object traversing the interval.

The apparent journey of the photon is therefore the registration-side appearance of a timeless lawful relation. Relativity governs the spatial and temporal organization of the registered endpoints. Quantum mechanics describes the lawful eligibility of the relation and its amplitude and probability structure. The governing law itself does not travel, wait, age, or cross the intervening space. There is lawful structure, and there are spacetime registrations governed by it.

\begin{remark}[Architectural consequence]
The clarified architecture is not an independent postulate. It follows directly from the previously established hierarchy that timeless lawful structure is the general condition of physics while timebound spacetime appearance is the special case. Once that hierarchy is accepted, the roles of quantum mechanics and relativity within the unified architecture follow naturally.
\end{remark}




\section{Conclusion}

Physics has always been unified. The unification is interpretive rather than mathematical. It does not require new equations, new particles, or new interactions. It requires recognizing the distinct explanatory roles already performed by the existing theories.

The central distinction is simple: laws are not time. Physical reality is governed by lawful structure, but time is not a constituent of that structure. Mathematical expressions of physical laws may include temporal parameters, but symbolic reference to time does not place time inside the laws themselves. Mathematics describes the lawful relations governing physical reality; the laws govern reality itself. Time belongs to spacetime relations.

Some admissible physical outcomes \defterm{register}{def:registration} within spacetime and thereby possess temporal ordering, causal relation, geometric localization, proper-time accumulation where applicable, and observability. Quantum mechanics describes lawful eligibility: the admissible outcomes and the mathematical relations governing their amplitudes and probabilities. Relativity governs the spacetime organization of registration. These theories therefore describe different aspects of one lawful order.

The appearance of disunity arose because the ontological consequences of \defterm{null proper time}{def:nullpropertime} were not propagated consistently. A photon accumulates no proper time. This means that the ordinary persistence narrative --- the assumption that a physical thing travels through successive spacetime locations while accumulating a history --- does not apply to light. Emission and absorption register within spacetime, but the lawful relation connecting them is not a persisting traveler occupying the interval between those registrations.

Once that consequence is honored, timebound spacetime registration is recognized as the special circumstance in which temporal properties apply rather than the universal background condition of physical law. Quantum mechanics and relativity then assume their proper explanatory roles, and the apparent competition between them dissolves.

The same distinction explains why phenomena such as entanglement need not be interpreted as violations of relativity. An entanglement correlation is part of the lawful structure governing the joint system, not a signal propagating between two registered locations. The local detector outcomes register within spacetime and remain governed by relativity. The correlation itself does not traverse the intervening distance and therefore has no propagation speed to compare with $c$. Quantum mechanics describes the joint lawful eligibility structure; relativity governs the spacetime registration of the outcomes.

No existing prediction of quantum mechanics, special relativity, or general relativity is altered by this recognition. No new mathematical framework is proposed. The contribution is the recognition itself: quantum mechanics and relativity were never rival descriptions of one temporal process. Quantum mechanics describes lawful eligibility. Relativity governs the spacetime organization of registered outcomes. Their apparent conflict arose from assigning both theories the same explanatory task.

General timelessness expresses the principle underlying this distinction. Lawful structure does not age, evolve, wait, or pass through time because time is not one of its constituents. A mathematical expression of a law may refer to time without making time part of the law itself. Temporal properties arise where admissible physical outcomes participate within spacetime. Once this distinction is maintained consistently, the unified description is already present in the existing physics.

\vspace{1em}

\begin{center}
\textit{Physical reality is governed by law.}

\vspace{0.5em}

\textit{Laws are not time.}

\vspace{0.5em}

\textit{Time is not a constituent of law.}

\vspace{0.5em}

\textit{Time is a feature of spacetime.}

\vspace{0.5em}

\textit{Spacetime registration is the special case in which time applies.}

\vspace{0.5em}

\textit{Quantum mechanics describes lawful eligibility.}

\vspace{0.5em}

\textit{Relativity describes the spacetime organization of registration.}

\vspace{0.5em}

\textit{Physics has always been unified.}
\end{center}










\section*{Related Reading}

Readers interested in the broader development of the Timeless Light Model architecture may also consult the following related publications. These works provide supporting discussions of photon ontology, null proper time, spacetime \defterm{registration}{def:relativisticregistration}, and the interpretation of relativistic propagation. They are complementary to the present synthesis but are not required premises for the arguments developed here.

\begin{itemize}

\item J.~C.~W.~McKinley,
\textit{Timebound Does Not Mean Traveler:
A No-Go on Deriving Bead-Path Ontology from Quantum Admissibility}.
Zenodo, 2026.\\
\href{https://doi.org/10.5281/zenodo.20114077}{doi:10.5281/zenodo.20114077}.

\item J.~C.~W.~McKinley,
\textit{Photon Out of Time: Why Light Experiences No Time---and What That Means for Physics}.
Zenodo, 2025.\\
\href{https://doi.org/10.5281/zenodo.16470583}{doi:10.5281/zenodo.16470583}.
(Note: this paper uses pre-Bedrock scaffolding terminology.)

\item J.~C.~W.~McKinley,
\textit{Light as Absent: Reclassifying the Photon as a Timeless Instruction}.
Zenodo, 2025.\\
\href{https://doi.org/10.5281/zenodo.16627549}{doi:10.5281/zenodo.16627549}.
(Note: this paper uses pre-Bedrock scaffolding terminology.)

\item J.~C.~W.~McKinley,
\textit{Resolving Wave--Particle Duality Through the Proposed Timeless Light Model:
Photons as Timeless Instructions and Waves as Deployed Delay}.
Zenodo, 2025.\\
\href{https://doi.org/10.5281/zenodo.16510861}{doi:10.5281/zenodo.16510861}.
(Note: this paper uses pre-Bedrock scaffolding terminology.)

\end{itemize}

\begin{thebibliography}{99}

\bibitem{bedrock}
J.~C.~W.~McKinley,
\textit{A Minimal Structural Statement of the Timeless Light Model}.
Zenodo, 2026.
\href{https://doi.org/10.5281/zenodo.18521383}{doi:10.5281/zenodo.18521383}.

\bibitem{generaltimelessness}
J.~C.~W.~McKinley,
\textit{Timelessness Is the General Condition: Spacetime Is the Special Case}.
Zenodo, 2026.
\href{https://doi.org/10.5281/zenodo.19771924}{doi:10.5281/zenodo.19771924}.



\bibitem{nullpropertime}
J.~C.~W.~McKinley,
\textit{Taking Null Proper Time Seriously:
An Interpretive Clarification of Null Proper Time}.
Zenodo, 2025.
\href{https://doi.org/10.5281/zenodo.18004632}{doi:10.5281/zenodo.18004632}.

\bibitem{norestframe}
J.~C.~W.~McKinley,
\textit{No Rest Frame, No Persistence:
A Kinematic Constraint on Photon Interpretation}.
Zenodo, 2025.
\href{https://doi.org/10.5281/zenodo.18005884}{doi:10.5281/zenodo.18005884}.

\bibitem{nullcurves}
J.~C.~W.~McKinley,
\textit{Null Curves Without Carriers:
Resolving an Ontological Tension in Relativistic Geometry}.
Zenodo, 2025.
\href{https://doi.org/10.5281/zenodo.18028886}{doi:10.5281/zenodo.18028886}.




\bibitem{atom}
J.~C.~W.~McKinley,
\textit{The Atom Is Available When Called On}.
Zenodo, 2026.
\href{https://doi.org/10.5281/zenodo.20114822}{doi:10.5281/zenodo.20114822}.

\bibitem{generalatom}
J.~C.~W.~McKinley,
\textit{General Timelessness and the Atom}.
Zenodo, 2026.
\href{https://doi.org/10.5281/zenodo.20279574}{doi:10.5281/zenodo.20279574}.

\bibitem{localaccrual}
J.~C.~W.~McKinley,
\textit{Local Accrual as the Only Intrinsic Time-Quantity}.
Zenodo, 2026.
\href{https://doi.org/10.5281/zenodo.20225644}{doi:10.5281/zenodo.20225644}.

\bibitem{holodeck}
J.~C.~W.~McKinley,
\textit{The Failure of the Newtonian Holodeck:
Why a Universe Without Relativity Cannot Sustain Itself}.
Zenodo, 2025.
\href{https://doi.org/10.5281/zenodo.16750632}{doi:10.5281/zenodo.16750632}.

\bibitem{retrocausality}
J.~C.~W.~McKinley,
\textit{Retrocausal Objections Are Disallowed for the Photon}.
Zenodo, 2026.
\href{https://doi.org/10.5281/zenodo.19648208}{doi:10.5281/zenodo.19648208}.

\bibitem{nogocrosssky}
J.~C.~W.~McKinley,
\textit{No-Go on Seeing a Photon Cross the Sky}.
Zenodo, 2026.
\href{https://doi.org/10.5281/zenodo.20225003}{doi:10.5281/zenodo.20225003}.

\bibitem{wavefunctionnogo}
J.~C.~W.~McKinley,
\textit{Wavefunction Prediction Does Not License a Photon Path:
A Short Interpretive No-Go}.
Zenodo, 2026.
\href{https://doi.org/10.5281/zenodo.19504771}{doi:10.5281/zenodo.19504771}.

\bibitem{regbound}
J.~C.~W.~McKinley,
\textit{$c$ Is a Registration Bound, Not a Traveler's Speed:
A Registration-Based Interpretation of the Information Speed Limit}.
Zenodo, 2026.
\href{https://doi.org/10.5281/zenodo.20114176}{doi:10.5281/zenodo.20114176}.

\bibitem{fermion}
J.~C.~W.~McKinley,
\textit{Fermion Fields Are Not Licensed as Things in Space:
A Structural No-Go on Substrate Ontology in Quantum Field Theory}.
Zenodo, 2026.
\href{https://doi.org/10.5281/zenodo.20092058}{doi:10.5281/zenodo.20092058}.

\bibitem{unruh}
J.~C.~W.~McKinley,
\textit{Unruh Radiation Does Not License Vacuum Substance Ontology:
A Short Interpretive No-Go on Observer-Relative Particle Content}.
Zenodo, 2026.
\href{https://doi.org/10.5281/zenodo.20100443}{doi:10.5281/zenodo.20100443}.

\bibitem{hawking}
J.~C.~W.~McKinley,
\textit{Hawking Radiation Does Not License Transit Ontology:
A Short Interpretive No-Go on Horizon-Conditioned Particle Appearance}.
Zenodo, 2026.
\href{https://doi.org/10.5281/zenodo.20099663}{doi:10.5281/zenodo.20099663}.

\bibitem{hawkinginterior}
J.~C.~W.~McKinley,
\textit{Hawking Radiation Is an Exterior Result:
A Short Interpretive No-Go on Interior Ontology}.
Zenodo, 2026.
\href{https://doi.org/10.5281/zenodo.20100228}{doi:10.5281/zenodo.20100228}.

\bibitem{einstein1905}
A.~Einstein,
\textit{Zur Elektrodynamik bewegter K{\"o}rper}.
Annalen der Physik 17, 891--921, 1905.

\bibitem{epr1935}
A.~Einstein, B.~Podolsky, and N.~Rosen,
\textit{Can Quantum-Mechanical Description of Physical Reality Be Considered Complete?}
Physical Review 47, 777--780, 1935.

\bibitem{schrodinger1935}
E.~Schr{\"o}dinger,
\textit{Discussion of Probability Relations between Separated Systems}.
Proceedings of the Cambridge Philosophical Society 31, 555--563, 1935.

\bibitem{bell1964}
J.~S.~Bell,
\textit{On the Einstein Podolsky Rosen Paradox}.
Physics 1, 195--200, 1964.

\bibitem{hensen2015}
B.~Hensen et al.,
\textit{Loophole-free Bell inequality violation using electron spins separated by 1.3 kilometres}.
Nature 526, 682--686, 2015.

\bibitem{nobel2022}
The Nobel Prize in Physics 2022,
\textit{Awarded to Alain Aspect, John F. Clauser and Anton Zeilinger for experiments with entangled photons, establishing the violation of Bell inequalities and pioneering quantum information science}.
NobelPrize.org, 2022.

\end{thebibliography}

\end{document}


```

</details>

---
{% endraw %}
