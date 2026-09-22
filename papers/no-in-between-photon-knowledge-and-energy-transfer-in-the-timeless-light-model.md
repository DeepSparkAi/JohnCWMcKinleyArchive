---
layout: default
title: '[2025] No In-Between: Photon Knowledge and Energy Transfer in the Timeless Light Model'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/no-in-between-photon-knowledge-and-energy-transfer-in-the-timeless-light-model/
paper: true
---
{% raw %}
# [2025] No In-Between: Photon Knowledge and Energy Transfer in the Timeless Light Model
*   **DOI:** [10.5281/zenodo.17274555](https://doi.org/10.5281/zenodo.17274555)
*   **Date:** 5 October 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt,onecolumn]{article}

% ---------- Encoding & Fonts ----------
\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage{lmodern}
\usepackage{setspace}
\setstretch{1.12}
\usepackage{microtype}
\usepackage{tcolorbox}
% --- TLM law macros (preamble) ---
\newcommand{\MassDelayLaw}{T\,m=\hbar/c^{2}}
\newcommand{\CausalSpeedLaw}{T\,C_s=1}




% ---------- Page & Layout ----------
\usepackage[margin=1in]{geometry}

% ---------- Math ----------
\usepackage{amsmath,amssymb,amsthm,bm}
% --- Definition environment (place in preamble, after amsthm) ---
\theoremstyle{definition}
\newtheorem{definition}{Definition}




% ---------- Figures ----------
\usepackage{booktabs}
\usepackage{tikz}
\usetikzlibrary{arrows.meta, positioning, calc, shapes.geometric}
\usepackage{graphicx} % for \rotatebox in the predictions table


% ---------- Links & References ----------
\usepackage{hyperref}
\hypersetup{
  colorlinks=true,
  linkcolor=blue,
  urlcolor=blue,
  citecolor=blue
}
\usepackage{cleveref}

% ---------- Headers ----------
\usepackage{fancyhdr}
\pagestyle{fancy}
\fancyhf{}
\lhead{No In-Between: Photon Knowledge and Energy Transfer in TLM}
\rhead{\thepage}

% --- Preamble addition ---
\usepackage{enumitem}
\newlist{gloss}{description}{1}
\setlist[gloss]{style=nextline, font=\bfseries, labelsep=0.6em, leftmargin=1.6em, itemsep=0.6em, topsep=0.6em}




% ---------- Title ----------
\title{\vspace{-1.2cm}\textbf{No In-Between: Photon Knowledge and Energy Transfer in the Timeless Light Model}\\[6pt]
\large The Energy Is Here, Then There---No Traveler Required}
\usepackage{orcidlink}
\author{John C. W. McKinley\orcidlink{0009-0005-7097-5035}\\Independent Researcher}
\date{October 05, 2025}

\begin{document}
\maketitle

\begingroup
  \footnotetext[0]{This version published at
  \href{https://doi.org/10.5281/zenodo.17274555}{https://doi.org/10.5281/zenodo.17274555}.}
\endgroup

\begin{abstract}
\noindent
In this paper we analyze what it means to say that a photon ``knows'' it is traveling.
All empirical evidence of light in the universe comes from emission and absorption events; direct observation of a photon “in flight” as a localized, persisting carrier has not been achieved.\footnote{Field-theoretic descriptions (e.g., QFT correlators/propagators) successfully model correlations between endpoints; our claim concerns \emph{direct mid-flight detection of a persisting carrier}, not the existence of field-theoretic amplitudes.}



Within the Timeless Light Model (TLM), this gap is not a mystery but a signature of causal deployment: energy transfers occur as timeless instructions, not as traveling entities.
We formalize the ``No-In-Between Lemma,'' showing that knowledge or awareness cannot apply to massless quanta since proper time $\tau=0$ forbids internal evolution.
The constant $c$ thus represents a rendering delay rather than a voyage speed.
Light does not traverse the universe---it resolves it.
\end{abstract}

% =====================================================
\section{Introduction}
\label{sec:intro}
A viewer once asked whether a photon ``knows'' it is traveling.
That simple question exposed a profound ontological fault line in physics.
Our detectors record only emission and absorption events; between those endpoints, no \emph{direct} mid-flight detection of a localized, persisting photon has been achieved.\footnote{QFT accounts for endpoint correlations via propagators and correlation functions. Here we distinguish that formal success from \emph{direct} observation of a mid-flight carrier in spacetime.}
Between those endpoints lies not an unseen object but (on the TLM reading) an unobservable state of the would-be carrier.


As recorded in the public YouTube exchange archived in
\textit{Comment Archive: “Does a Photon Know It Travels?” — Transcript of YouTube Short (hBDI0LFVxF0)}~\cite{photoncomment},
the author replied:
\begin{quote}
“The energy is here, then the energy is there. No in-between.
It just takes the delay of $c$ for the destination to get the news.”
\end{quote}

This dialogue serves as the conceptual origin of the present paper.
It suggests that the absence of a photon in flight is not a gap in our understanding
but an inevitable consequence of massless causality.
Within the Timeless Light Model (TLM), the constant $c$ is reinterpreted
as a delay rate governing rendering pace in the Spacetime Deployment Frame (SDF),
rather than the velocity of motion through space.




% =====================================================
\section{Timeless Light Model Summary}
\label{sec:tlm-summary}
The Timeless Light Model (TLM) posits a dual-layer ontology:

\begin{itemize}
  \item \textbf{Quantum Platform (QP):} a timeless, extra-spatiotemporal layer issuing complete emission–absorption instructions.
  \item \textbf{Spacetime Deployment Frame (SDF):} a rendered projection where those instructions appear as events filtered through gravitational delay and quantum structure.
\end{itemize}

All events are authored as completed causal instruction arcs (CI-ARCs) on the QP, satisfying the invariant \textbf{Mass–Delay Law}
\begin{equation}
  T \cdot m = \frac{\hbar}{c^{2}}.
  \label{eq:mass-delay}
\end{equation}
For massless quanta ($m=0$), the delay $T=0$ and proper time $\tau=0$, implying instantaneous resolution on the QP and no persistent existence in the SDF.

% =====================================================
\section{The No-In-Between Lemma}
\label{sec:no-in-between}

\begin{tcolorbox}[title=\textbf{No-In-Between Lemma}]
Let $(\mathcal{M},g)$ be a Lorentzian spacetime with signature $(-,+,+,+)$.
If a massless excitation connects emission $E$ and absorption $A$ along a future-directed null curve $\gamma$ with $g(\dot\gamma,\dot\gamma)=0$, then the accumulated proper time between $E$ and $A$ is identically zero:
\[
d\tau=\frac{1}{c}\sqrt{-\,g(\dot\gamma,\dot\gamma)}\,d\lambda = 0.
\]
Consequently there is no proper-time parametrization along $\gamma$, no rest frame, and no internal evolution between $E$ and $A$.
\end{tcolorbox}

\noindent\textbf{Proof (sketch).}
For any causal curve $\gamma$, proper time satisfies
\[
\tau[\gamma] = \frac{1}{c}\int_{\lambda_E}^{\lambda_A}\sqrt{-\,g(\dot\gamma,\dot\gamma)}\,d\lambda.
\]
For a null curve, $g(\dot\gamma,\dot\gamma)=0$ everywhere, so $d\tau\equiv 0$ and $\tau[\gamma]=0$.
Since invariant internal change requires $\Delta\tau>0$, no internal state evolution can occur along $\gamma$.
Thus any apparent ``in-between'' history is not a photon's physical state but an observer-side rendering in the SDF constrained by $c$.


\noindent\textit{Terminology note.}
“Observer-side rendering” is TLM terminology for the Spacetime Deployment Frame (SDF) mechanism introduced in \cref{sec:tlm-summary};
it is \emph{not} standard GR/QFT jargon and is used here solely to denote the proposed TLM mapping from timeless instructions to rendered events.


\noindent\textit{Affine freedom of the parameter.}
Any null curve admits an affine reparametrization $\lambda' = a\lambda + b$ with $a>0$.
This freedom leaves $g(\dot\gamma,\dot\gamma)=0$ and therefore $d\tau=\frac{1}{c}\sqrt{-\,g(\dot\gamma,\dot\gamma)}\,d\lambda\equiv 0$ invariant.
Thus the bounds $[\lambda_E,\lambda_A]$ merely label the endpoints; $\tau[\gamma]=0$ for any affine choice.


See the endpoint-only updates formalized in the Minimal Interface, \cref{sec:min-interface}.

\begin{tcolorbox}[title=\textbf{Corollary: No Mid-Flight State}]
There is no physically meaningful ``photon in flight'' carrying memory or knowledge between $E$ and $A$; only endpoint transfers are observable.
\end{tcolorbox}

\noindent\textit{Remark (affine parameter).}
Null geodesics admit an affine parameter $\lambda$, but $\lambda$ is not proper time and has no clock interpretation; it cannot host internal evolution.





\begin{tcolorbox}[title=\textbf{Interface Corollary (No Intermediate Updates)}]
Under the No-In-Between Lemma, a photon’s null link from emission \(E\) to absorption \(A\) admits no intermediate proper-time slices.
Therefore the instruction tuple
\[
I=\langle x_e^\mu,x_a^\mu;\,\Delta p^\mu,\Delta J^{\mu\nu},\Delta Q\rangle
\]
cannot be updated along the path: transfers apply \emph{only} at endpoints,
\[
p^\mu_e \to p^\mu_e-\Delta p^\mu,\qquad
p^\mu_a \to p^\mu_a+\Delta p^\mu,
\]
with analogous updates for \(J^{\mu\nu}\) and charges.
There is no well-defined map \(\lambda\mapsto \Delta p^\mu(\lambda)\) on the null segment (no rest frame, \(\tau\equiv 0\)).
This is consistent with the Generalized Pairing Law (one realized instruction, one absorber) and with the endpoint-only observables in the SDF.
\end{tcolorbox}




% =====================================================
\section{Minimal QP$\to$SDF Instruction Interface}
\label{sec:min-interface}

\begin{definition}[Instruction tuple]
A realized instruction is the endpoint record
\[
I=\big\langle x_e^\mu,\,x_a^\mu;\; \Delta p^\mu,\, \Delta J^{\mu\nu},\, \Delta Q \big\rangle,
\]
where $x_e^\mu$ and $x_a^\mu$ are emitter/absorber spacetime coordinates in the chosen SDF chart, and
$(\Delta p^\mu,\Delta J^{\mu\nu},\Delta Q)$ are the conserved transfers applied at the endpoints.
For photons (massless), $\Delta p^\mu \Delta p_\mu = 0$ and $d\tau=0$ along the link.
\end{definition}

\paragraph{Endpoint-only updates (no mid-flight state).}
By the No-In-Between Lemma (\S\ref{sec:no-in-between}), a null link admits no proper-time slices and thus no intermediate state:
\[
p^\mu_e \;\longrightarrow\; p^\mu_e - \Delta p^\mu, \qquad
p^\mu_a \;\longrightarrow\; p^\mu_a + \Delta p^\mu,
\]
with analogous updates for $J^{\mu\nu}$ and charges.
There is no well-defined map $\lambda \mapsto \Delta p^\mu(\lambda)$ along the null segment (no rest frame, $\tau\equiv 0$).

\paragraph{Bridge laws (deployment delay).}
For realized instructions, deployment timing in the SDF is constrained by
\[
\MassDelayLaw, \qquad \CausalSpeedLaw,
\]
so that mass acts as delay (drag) and the causal rendering rate is fixed. For $m=0$ (photons), $T=0$, consistent with the absence of internal evolution.

\paragraph{Generalized Pairing Law (GPL).}
A QP instruction exists iff a compatible absorber condition exists; there are no pending or partial records. The tuple $I$ therefore encodes a \emph{single} emission–absorption realization, with observable changes only at the endpoints.











% =====================================================
\section{Rendering Delay of \texorpdfstring{$c$}{c}}
\label{sec:rendering-delay}
In the TLM, $c$ represents the rate at which the SDF renders timeless causal resolutions.
The appearance of a light-speed limit arises from the finite rendering delay necessary for ordered experience.
This reinterprets $c$ as a structural constant of information deployment rather than the velocity of a moving object.
Spacetime thus measures the observer’s delay in resolving timeless causal updates.

% =====================================================
\section{Epistemic Consequences}
\label{sec:epistemic}
Knowledge, awareness, and memory exist only in systems with finite delay ($T>0$, $m>0$).
Photons, having no delay, cannot host such states.
Consequently, the question ``does light know?'' collapses: only massive observers can experience, record, or perceive causality.
Mass slows time; time enables knowledge.

% =====================================================
\section{Predictions and Tests}
\label{sec:predictions}


\noindent\textit{Derivation note (citations).}
The scaling \(\Delta t \sim GM_{\text{det}}/c^{3}\) arises in the TLM from the bridge-law view that mass imposes deployment delay in the SDF, so a detector’s gravitational potential contributes a fixed latency offset to coincident outcomes.
A derivation and experimental framing are provided in \cite{emissiondelay,tlmwhy,tlmreview,tlmtestmenu}.


\begin{table}[h!]

\centering
\caption{Selected predictions derived from the No-In-Between principle.}
\vspace{1cm}
\renewcommand{\arraystretch}{1.2}
\rotatebox{90}{%
\begin{tabular}{@{}lll@{}}
\toprule
\textbf{Prediction} & \textbf{Observable} & \textbf{Null (GR/QM) expectation} \\
\midrule
Entanglement latency & $\Delta t \sim GM_{\text{det}}/c^{3}$ & $0$ \\
Emission delay law & Excited-state lifetime $\propto$ absorber availability & Energy-only decay \\
No mid-flight detection & Photon never observed between endpoints & Continuous field expectation \\
\bottomrule
\end{tabular}
}
\end{table}

These predictions align with previous TLM tests~\cite{emissiondelay,noenergy,photonnot,tlmwhy}.

% =====================================================
\section{Conclusion}
\label{sec:conclusion}
The photon’s ignorance is perfect because it is non-existent as a traveler.
Between emission and absorption there is no thing, no duration, and no observer.
What we call ``light'' is the delayed rendering of a completed causal instruction.
In this view, the constant $c$ is not the speed of the photon, but the pace of the universe learning what has already happened.

% =====================================================
\section{Acknowledgment}
This paper was directly prompted by the public exchange archived as
\textit{Comment Archive: “Does a Photon Know It Travels?” — Transcript of YouTube Short (hBDI0LFVxF0)}~\cite{photoncomment},
Zenodo DOI: 10.5281/zenodo.17274572.



% =====================================================
% =====================================================
\section*{Glossary (TLM \& Standard Physics)}

\subsection*{Timeless Light Model (TLM) terms}
\begin{gloss}
  \item[Quantum Platform (QP)] Timeless, extra-spatiotemporal layer that issues completed emission–absorption instructions (no duration, no internal evolution).
  \item[Spacetime Deployment Frame (SDF)] Rendered arena (our observed spacetime) where QP instructions appear as events subject to gravitational/structural filtering.
  \item[Causal Instruction Arc (CI-ARC)] Completed emission–absorption pair authored on QP; not a propagating object in spacetime.
  \item[Rendering delay \(T\)] Deployment lag in the SDF between QP resolution and observable record; governs experienced time/ordering.
  \item[Mass–Delay Law] \(\MassDelayLaw\). For \(m=0\), \(T=0\) (no delay; no internal evolution).
\item[Causal speed \(C_s\)] Deployment rate dual to \(T\); obeys \(\CausalSpeedLaw\).
  \item[Generalized Pairing Law (GPL)] A QP instruction exists iff a compatible absorber condition exists; no partial/pending records.
  \item[Emission Delay Law (EDL)] Excited states persist until an absorber condition exists; emission timing depends on absorber availability.
  \item[No Mid-Flight Energy Principle] No usable energy exists “between” endpoints; only endpoint transfers are physical.
  \item[Instruction tuple] \(I=\langle x_e^\mu,x_a^\mu;\,\Delta p^\mu,\Delta J^{\mu\nu},\Delta Q\rangle\) encodes the realized transfer and conserved updates at endpoints.







  
\end{gloss}

\subsection*{Standard physics terms}
\begin{gloss}
  \item[Proper time \(\tau\)] Clock time along a worldline. For massless carriers on null paths, \(\tau=0\).
  \item[Spacetime interval \(ds^{2}\)] In flat spacetime, \(ds^{2}=-c^{2}dt^{2}+dx^{2}+dy^{2}+dz^{2}\) (up to sign convention).
  \item[Null geodesic / null worldline] Curve with \(ds^{2}=0\); photons follow null geodesics and accrue no proper time (\(\tau=0\)).
  \item[Timelike worldline] \(ds^{2}<0\) (with the above sign); massive objects have \(\tau>0\).
  \item[Spacelike separation] \(ds^{2}>0\); no causal influence between the events.
  \item[Light cone] Boundary separating timelike from spacelike regions; null directions lie on the cone (45° in a \(ct\)–\(x\) Minkowski plot).
  \item[Minkowski diagram] Spacetime plot (typically \(ct\) vertical, \(x\) horizontal) depicting worldlines, light cones, and causal structure.
  \item[Affine parameter \(\lambda\)] Parameter along a null geodesic used when \(\tau=0\).
  \item[Four-momentum \(p^\mu\)] Energy-momentum 4-vector; conserved at emission/absorption endpoints with transfers \(\Delta p^\mu\).
  \item[Hilbert space \(\mathcal{H}\)] Vector space for quantum states; observables are self-adjoint operators acting on \(\mathcal{H}\).
\end{gloss}


% =====================================================

\begin{thebibliography}{9}


\bibitem{tlmreview}
McKinley, J.~C.~W. (2025).
\textit{A Review of the Timeless Light Model: Foundations, Derivations, and Empirical Predictions}.
Zenodo. \href{https://doi.org/10.5281/zenodo.16958221}{doi:10.5281/zenodo.16958221}.

\bibitem{tlmtestmenu}
McKinley, J.~C.~W. (2025).
\textit{Test Menu for the Timeless Light Model (TLM)}.
Zenodo. \href{https://doi.org/10.5281/zenodo.16957884}{doi:10.5281/zenodo.16957884}.




\bibitem{photoncomment}
McKinley, J.~C.~W. (2025).
\textit{Comment Archive: “Does a Photon Know It Travels?” — Transcript of YouTube Short (hBDI0LFVxF0)} (v1.0).
Zenodo.
\href{https://doi.org/10.5281/zenodo.17274572}{doi:10.5281/zenodo.17274572}.


\bibitem{photonnot}
McKinley, J.~C.~W. (2025). \textit{Photons Not in the Universe: An Axiomatic Derivation from Masslessness and Non-Travel.}
Zenodo. \href{https://doi.org/10.5281/zenodo.17010029}{doi:10.5281/zenodo.17010029}.

\bibitem{noenergy}
McKinley, J.~C.~W. (2025). \textit{The “No Mid-Flight Energy” Principle: Operational Consistency and Ontological Implications for the Timeless Light Model.}
Zenodo. \href{https://doi.org/10.5281/zenodo.17018871}{doi:10.5281/zenodo.17018871}.

\bibitem{emissiondelay}
McKinley, J.~C.~W. (2025). \textit{The Emission Delay Law: A General Principle for the Realization of Quanta in the Timeless Light Model.}
Zenodo. \href{https://doi.org/10.5281/zenodo.17032235}{doi:10.5281/zenodo.17032235}.

\bibitem{photonthought}
McKinley, J.~C.~W. (2025). \textit{Photon Thought Experiments and the Timeless Ontology: Why Photons and Quanta Are “Not Here.”}
Zenodo. \href{https://doi.org/10.5281/zenodo.17216652}{doi:10.5281/zenodo.17216652}.

\bibitem{tlmwhy}
McKinley, J.~C.~W. (2025). \textit{Why the Timeless Light Model Deserves Scientific Consideration: A Foundational Framework with Derivations, Critiques, and Experimental Proposals.}
Zenodo. \href{https://doi.org/10.5281/zenodo.16724187}{doi:10.5281/zenodo.16724187}.

\end{thebibliography}

% =====================================================
\section*{Appendix: TikZ Diagram (GR vs TLM)}
\begin{figure}[h!]
\centering
\begin{tikzpicture}[scale=1.0,>=Latex]

% -------- Panel titles --------
\node[font=\bfseries\small] at (2.7,5.6) {GR: Null worldline in spacetime};
\node[font=\bfseries\small] at (9.9,5.6) {TLM: Timeless inst. linking endpoints};

% -------- Left panel: GR --------
% axes
\draw[->] (0.3,0.5) -- (0.3,4.9) node[above] {$t$};
\draw[->] (0.3,0.5) -- (5.1,0.5) node[right] {$x$};

% emitter/absorber worldlines
\draw[thick] (1.2,1.0) -- (1.2,4.6) node[above] {\scriptsize Emitter};
\draw[thick] (4.2,1.0) -- (4.2,4.6) node[above] {\scriptsize Absorber};

% lightlike (null) path
\fill (1.2,1.2) circle (1.2pt);
\fill (4.2,4.2) circle (1.2pt);
\draw[blue,very thick,dashed,->] (1.2,1.2) -- (4.2,4.2)
  node[midway,above,sloped] {\scriptsize $ds^2=0$ (null)};

% legend/notes
\node[align=left, font=\scriptsize] at (2.7,0.1) {No proper time along null path: $\tau=0$};

% -------- Right panel: TLM --------
\begin{scope}[xshift=6.8cm]
% axes
\draw[->] (0.3,0.5) -- (0.3,4.9) node[above] {$t$};
\draw[->] (0.3,0.5) -- (5.1,0.5) node[right] {$x$};

% emitter/absorber worldlines
\draw[thick] (1.2,1.0) -- (1.2,4.6) node[above] {\scriptsize Emitter};
\draw[thick] (4.2,1.0) -- (4.2,4.6) node[above] {\scriptsize Absorber};

% endpoints only (no mid-flight state)
\fill (1.2,1.2) circle (1.2pt) node[below left=-2pt] {\scriptsize $E$};
\fill (4.2,4.2) circle (1.2pt) node[above right=-2pt] {\scriptsize $A$};

% timeless instruction (no propagation)
\draw[red,thick,dotted,<->] (1.2,1.2) -- (4.2,4.2)
  node[midway,above,sloped] {\scriptsize timeless instruction};

% rendered sequencing cue
\draw[->,gray!70,thick] (1.2,1.2) .. controls (2.0,2.0) and (3.4,2.9) .. (4.2,4.2)
  node[pos=0.55,below,sloped,fill=white,inner sep=1pt]
  {\scriptsize rendered order limited by $c$ in SDF};

% legend/notes
\node[align=left, font=\scriptsize] at (2.7,0.1) {No mid-flight entity; $\tau=0$ forbids internal evolution};
\end{scope}

\end{tikzpicture}
\caption{Two readings of an emission–absorption link. \textbf{Left (GR):} a null worldline connects emitter and absorber. \textbf{Right (TLM):} a timeless instruction links the same endpoints; the apparent “travel” is rendered sequencing in the SDF at rate $c$, with no physical in-between state.}
\label{fig:gr-vs-tlm-clean}
\end{figure}

\end{document}

```

</details>

---
{% endraw %}
