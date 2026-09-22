---
layout: default
title: '[2025] Timeless Light Model (TLM v2.0): Frameless Quanta, Framed Observers, and Bridge Laws'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/timeless-light-model-tlm-v2-0-frameless-quanta-framed-observers-and-bridge-laws/
paper: true
---
{% raw %}
# [2025] Timeless Light Model (TLM v2.0): Frameless Quanta, Framed Observers, and Bridge Laws
*   **DOI:** [10.5281/zenodo.16934697](https://doi.org/10.5281/zenodo.16934697)
*   **Date:** 23 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt,letterpaper]{article}

% --- Packages ---
\usepackage[margin=1in]{geometry}
\usepackage[T1]{fontenc}
\usepackage[utf8]{inputenc}
\usepackage{lmodern}
\usepackage{microtype}
\usepackage{amsmath,amssymb}
\usepackage{enumitem}
\usepackage{booktabs}
\usepackage[numbers,sort&compress]{natbib}
\usepackage{tikz}
\usetikzlibrary{arrows.meta,calc}
\usepackage{graphicx} % handy if figures expand later
\usepackage{hyperref}
\hypersetup{colorlinks=true,linkcolor=blue,urlcolor=blue,citecolor=blue}

% --- Metadata ---
\title{Timeless Light Model (TLM v2.0): \\ Frameless Quanta, Framed Observers, and Bridge Laws}
\author{John C. W. McKinley\\
\href{https://orcid.org/0009-0005-7097-5035}{ORCID: 0009-0005-7097-5035}\\
}
\date{August 23, 2025}
\begin{document}
\maketitle
\begingroup\renewcommand\thefootnote{}\footnotetext{This version published at
\href{https://doi.org/10.5281/zenodo.16934697}{https://doi.org/10.5281/zenodo.16934697}.}\endgroup




\begin{abstract}
We present TLM v2.0, a reformulation of the Timeless Light Model in which quanta are frameless state-change ticks and all spacetime structure belongs to observer frames. The model distinguishes a frameless (timeless) layer from GR/SR frames that render time, distance, and causal order. Two bridge laws (Mass--Delay Duality, \(T \cdot m=\hbar/c^{2}\), and Causal Resolution Constancy, \(T \cdot C_{s}=1\)) govern frame behavior and deployment speed, respectively. Wave phenomena are recast as frame-geometry effects rather than photon properties. We state axioms, derive corollaries matching standard GR/SR and QM effects, map axioms to experimental tests, and list falsifiability conditions. This consolidates earlier strands (pairing, conservation, binary detection, delay laws) into a coherent, empirically anchored framework \citep{cornerstone,wfat,quanta_global,binary_law,transfer,pairing}.
\end{abstract}

\noindent\textbf{Keywords:} Timeless Light Model, frameless quanta, frames, GR/SR, mass--delay duality, causal resolution, wavefunction geometry, binary detection, axiomatic foundations, falsifiable ontology, quantum foundations

\section{Introduction}
TLM v2.0 evolves earlier papers \citep{cornerstone,wfat,quanta_global,binary_law,transfer,pairing} by making explicit that quanta are frameless state-change ticks while observers own frames that supply time, space, and causal order. We elevate two bridge laws---Mass--Delay Duality \(T\cdot m=\hbar/c^{2}\) and Causal Resolution Constancy \(T\cdot C_{s}=1\)---as the compact generators of familiar GR/SR and QM appearances. We also formalize detection, rendering (display vs.\ non-display), and a frame-geometry origin for the wavefunction, then tie each axiom to concrete experimental domains and falsifiability criteria.






\section{Foundations}

\subsection{Quanta are frameless}
\begin{itemize}[leftmargin=1.2cm]
  \item No proper time, no rest frame, no path.
  \item Exist only as \textbf{state-change ticks}:
    \begin{itemize}
      \item Emission (E): charge/energy down-tick.
      \item Absorption (A): charge/energy up-tick.
    \end{itemize}
  \item No sphere of influence and no ability to bend space or propagate waves.
\end{itemize}

\subsection{Frames belong to observers}
\begin{itemize}[leftmargin=1.2cm]
  \item A \textbf{frame} is a point with a local clock and ruler.
  \item Frames obey GR/SR rules:
    \begin{itemize}
      \item \textbf{Time law:} proper time, dilation, simultaneity shifts.
      \item \textbf{Space law:} local geometry curved by mass/energy.
      \item \textbf{Interaction law:} exchange ticks under conservation laws.
    \end{itemize}
  \item Frames supply time, space, and causal order that quanta lack.
\end{itemize}

\subsection{Spacetime Deployment Frame (SDF)}
\begin{itemize}[leftmargin=1.2cm]
  \item The SDF is the observer's rendered world:
    \begin{itemize}
      \item Time flows; events propagate at \(c\).
      \item Neighbors follow GR/SR rules.
    \end{itemize}
  \item Quanta are mapped into the SDF \emph{as if} they had trajectories; in truth they are frameless ticks.
\end{itemize}

\begin{figure}[t]
\centering
\begin{tikzpicture}[>=Latex,scale=1.0]
  % Frameless layer box
  \draw[rounded corners=2pt] (-4.6,0.2) rectangle (-0.2,2.3);
  \node[anchor=west] at (-4.6,2.5) {\small Frameless layer (timeless)};
  % E and A ticks
  \fill (-4,1.2) circle (1.8pt) node[left=4pt] {\small E};
  \fill (-1,1.2) circle (1.8pt) node[right=4pt] {\small A};
  \draw[dashed] (-4,1.2) -- (-1,1.2);
  % Arrow to SDF
  \draw[->,thick] (-0.2,1.25) -- (0.9,1.25);
  % SDF box
  \draw[rounded corners=2pt] (1.0,-0.3) rectangle (6.2,2.8);
  \node[anchor=west] at (1.0,3.0) {\small Spacetime Deployment Frame (observer)};
  % Worldlines and c-limited display
  \draw[thick] (1.8,0.0) -- (1.8,2.4) node[above]{\tiny emitter};
  \draw[thick] (5.3,0.0) -- (5.3,2.4) node[above]{\tiny absorber};
  \draw[->,thick] (1.8,0.4) -- (5.3,1.7) node[midway,above=8pt]{\tiny displayed path at \(c\)};
\end{tikzpicture}
\caption{Frameless tick \(\{E,A\}\) mapped into a frame as a displayed \(c\)-limited trajectory. In truth, the tick itself has no path.}
\label{fig:mapping}
\end{figure}

\section{Detection in TLM}

\subsection{Detection mechanism}
\begin{itemize}[leftmargin=1.2cm]
  \item A photon tick is recorded in the frameless layer as \(\{E,A\}\).
  \item When the absorber lies in a frame's sphere of influence, the frame registers a local state change (energy, charge, or momentum increment).
  \item To the observer: the photon arrived at this place and time.
  \item Reality: the frameless tick is mapped into the frame's coordinates and rendered as a spacetime-local event.
\end{itemize}

\subsection{Display vs.\ non-display events}
\begin{itemize}[leftmargin=1.2cm]
  \item \textbf{Display events} (photons, propagating quanta): frames render them as \(c\)-limited trajectories between \(E\) and \(A\).
  \item \textbf{Non-display events} (entanglement, tunneling): frames register the tick directly as a correlation or outcome, with no trajectory displayed.
\end{itemize}

\section{Wavefunction in TLM}

\subsection{Not a photon property}
\begin{itemize}[leftmargin=1.2cm]
  \item A frameless photon cannot bend, spread, or interfere.
  \item Wave-like behavior is generated entirely by the frame's geometry.
\end{itemize}

\subsection{Frame geometry deformation law}
\begin{itemize}[leftmargin=1.2cm]
  \item Boundary conditions (slits, lenses, gravitational curvature) bend rays into interference terrains.
  \item Repeated exclusive ticks populate those terrains, producing the familiar statistical trace \(|\psi|^2\).
\end{itemize}

\subsection{Interpretation}
\begin{itemize}[leftmargin=1.2cm]
  \item \textbf{Wavefunction} \(=\) frame geometry deformation law.
  \item Not a ``photon wave,'' but the observer's probability terrain created by frame bending.
\end{itemize}

\section{Bridge Laws: Mass--Delay and Causal Resolution}

\subsection{Mass--Delay Duality}
\begin{itemize}[leftmargin=1.2cm]
  \item \(T \cdot m = \hbar/c^{2}\).
  \item In GR/SR: massive bodies experience time; photons do not.
  \item Zero mass implies \emph{zero proper time} (no frame attached to the photon). Large mass implies slow proper time (dilation).
  \item Encodes why GR/SR behaves as observed: why clocks slow near mass and why photons have zero proper time.
\end{itemize}

\subsection{Causal Resolution Constancy}
\begin{itemize}[leftmargin=1.2cm]
  \item \(T \cdot C_{s} = 1\).
  \item \(T\) is the delay budget (proper time interval), \(C_{s}\) is the causal resolution rate (deployment speed of instructions).\footnote{Here \(C_{s}\) denotes the causal speed parameter that keeps rendered phenomena consistent with invariant \(c\) across frames. It is a deployment rate, not a spacetime velocity.}
  \item Expresses that all frames play the movie of experience at the same pace; accounts for invariant \(c\).
\end{itemize}

\section{Axioms of TLM}
\begin{enumerate}[leftmargin=1.2cm,label=\textbf{Axiom \arabic*.}]
  \item \textbf{Frames are for observers, not quanta.} A frame is a point with a local clock and ruler, obeying GR/SR rules. Quanta have no frame.
  \item \textbf{Frameless quanta have no time or space.} Photons are frameless ticks: exclusive emission--absorption state changes.
  \item \textbf{Mass--Delay Duality (law of frame behavior).} \(T \cdot m = \hbar / c^{2}\). Frames obey this relation, explaining why clocks slow near mass and why photons have zero proper time.
  \item \textbf{Causal Resolution Constancy (law of deployment).} \(T \cdot C_{s} = 1\). Frames deploy instructions at a universal causal rate, enforcing the experiential speed of light.
  \item \textbf{Free will and timeless insertion.} Choices inscribe new instructions into the frameless layer. Once written, they always were.
  \item \textbf{Frame geometry generates the wavefunction.} The wave pattern belongs to the frame's bending of space, not the photon.
  \item \textbf{Conservation governs state changes.} Every tick obeys conservation laws. No orphan quanta exist. Repeated ticks yield \(|\psi|^2\).
  \item \textbf{Binary law of quanta (local 0/1 toggle).} For any photon instruction, each candidate absorber registers a local state change that is binary: either one full tick (1) or none (0). Global exclusivity ensures that, per instruction, at most one absorber registers 1. Ensemble statistics (\(|\psi|^2\)) arise from many such binary events.
  \item \textbf{Display vs.\ non-display events.} Frames render photons as \(c\)-limited trajectories. Other phenomena (entanglement, tunneling) are rendered directly, without paths.
  \item \textbf{Ontological seniority.} The frameless layer (timeless, \(T\)-null) is ontologically senior to GR/SR. Frames only project ordered, causal illusions for observers.
\end{enumerate}

\section{Sketch derivations from the bridge laws}

\subsection{Time dilation and redshift}
Let a simple clock have rest mass \(m_{0}\) and total energy \(E = \gamma m_{0} c^{2}\). If the effective mass governing delay scales with total energy, \(m_{\text{eff}}=\gamma m_{0}\), then with \(T \cdot m_{\text{eff}}=\hbar/c^{2}\) we have
\[
T(\gamma) \;=\; \frac{\hbar}{c^{2} m_{\text{eff}}} \;=\; \frac{\hbar}{c^{2}\gamma m_{0}} \;=\; \frac{T_{0}}{\gamma},
\]
so moving clocks accumulate less proper time per displayed interval, consistent with SR dilation.

For weak gravity, redshift between potentials \(\phi_{1}\) and \(\phi_{2}\) can be sketched by writing \(m_{\text{eff}}(\phi)\approx m_{0}\!\left(1+\frac{\phi}{c^{2}}\right)\). Then
\[
\frac{\Delta T}{T} \approx -\,\frac{\Delta m_{\text{eff}}}{m_{\text{eff}}} \approx -\,\frac{\Delta \phi}{c^{2}}
\quad\Rightarrow\quad
\frac{\Delta \nu}{\nu} \approx \frac{\Delta \phi}{c^{2}},
\]
matching the gravitational redshift sign and scale tested by Pound\textendash Rebka and GPS \citep{poundrebka,ashby_gps}.

\subsection{QM sketch: binary + geometry to SE (outline)}
Following \citep{cornerstone}, treat repeated exclusive ticks on a frame-bent terrain as sampling a complex amplitude field \(\psi(\mathbf{x},t)\) whose intensity gives the binary detection statistics, \(P=|\psi|^{2}\). Let the frame geometry enter via an effective phase action \(S[\mathbf{x}(t)]\) so that path contributions scale as \(\exp(iS/\hbar)\). In the paraxial/nonrelativistic limit, with \(S=\!\int ( \tfrac{1}{2}m v^{2}-V )\,dt\) and geometry encoded in \(V(\mathbf{x},t)\), stationary variation of the phase functional yields the familiar evolution:
\[
i\hbar\,\partial_{t}\psi(\mathbf{x},t)\;=\; \bigg[-\,\frac{\hbar^{2}}{2m}\nabla^{2} + V(\mathbf{x},t)\bigg]\psi(\mathbf{x},t),
\]
interpreted here not as a photon wave but as the frame's geometry-driven law that shapes detection statistics.

\section{Corollaries of the axioms}

\subsection{From Mass--Delay Duality}
\begin{itemize}[leftmargin=1.2cm]
  \item Gravitational time dilation: clocks slow near massive bodies.
  \item Photons are timeless: \(m=0\) implies \emph{zero proper time} (no photon frame).
  \item Null geodesics: photon paths are rendered as \(c\)-limited trajectories only in frames.
\end{itemize}

\subsection{From Causal Resolution Constancy}
\begin{itemize}[leftmargin=1.2cm]
  \item Invariance of the speed of light across all frames.
  \item Consistent causal pacing: all observers see the movie unfold at the same experiential rate.
\end{itemize}

\subsection{From Binary law + conservation}
\begin{itemize}[leftmargin=1.2cm]
  \item No fractional detections: detectors register full quanta (1) or none (0).
  \item \(|\psi|^2\) statistical law arises from repeated binary exclusive events.
  \item No orphan quanta: all ticks are emission--absorption paired \citep{pairing}.
\end{itemize}

\subsection{From display vs.\ non-display}
\begin{itemize}[leftmargin=1.2cm]
  \item Double-slit interference: photons follow the binary law but land on frame-generated wave terrains (e.g., \citep{taylor}).
  \item Entanglement correlations: direct frameless registration, no propagation path \citep{bell,aspect,hensen}.
  \item Tunneling: absorber registration without a displayed intermediate trajectory.
\end{itemize}

\section{Axiom--corollary--test mapping}

\begin{table}[h!]
\centering
\renewcommand{\arraystretch}{1.25}
\begin{tabular}{|p{3.7cm}|p{6.8cm}|p{5.2cm}|}
\hline
\textbf{Axiom} & \textbf{Corollaries} & \textbf{Experimental tests} \\
\hline
Mass--Delay Duality (\(T \cdot m = \hbar / c^2\)) 
& Gravitational time dilation; photons have zero proper time; null geodesics. 
& Pound\textendash Rebka redshift; GPS satellite clock corrections; null photon proper time in SR. \\
\hline
Causal Resolution Constancy (\(T \cdot C_s = 1\)) 
& Speed of light invariant across frames; consistent causal pacing. 
& Michelson\textendash Morley; modern cavity tests; time-of-flight invariance of \(c\). \\
\hline
Binary law of quanta (0/1 toggle) 
& Detectors record full ticks or none; \(|\psi|^2\) emerges statistically. 
& Single-photon double slit; photon-counting detectors; quantum random number generator statistics. \\
\hline
Conservation of state changes 
& No orphan photons; conservation holds in all frames. 
& Energy/charge conservation in photon processes; absence of free charge in QED. \\
\hline
Display vs.\ non-display events 
& Photons rendered as trajectories; entanglement/tunneling as direct correlations. 
& Bell tests; tunneling time measurements; quantum eraser experiments \citep{yoon}. \\
\hline
Wavefunction as frame geometry 
& \(|\psi|^2\) terrains arise from bent geometry, not photon properties. 
& Double-slit with massive particles; gravitational-lensing interference. \\
\hline
Free will and timeless insertion 
& Choices inscribe new instructions; appear causal in SDF but timeless in QP. 
& Delayed-choice quantum eraser; freedom-of-choice loophole tests \citep{hensen}. \\
\hline
Ontological seniority (frameless \(>\) framed) 
& Frameless layer is senior; GR/SR render illusions. 
& Consistency across relativistic quantum experiments; searches for causality violations. \\
\hline
\end{tabular}
\caption{Mapping of TLM v2.0 axioms to corollaries and experimental test domains.}
\end{table}

\subsection{Falsifiability conditions}

Each axiom of TLM v2.0 is open to experimental disproof. The following conditions would directly refute the framework:

\begin{itemize}[leftmargin=1.2cm]
  \item \textbf{Mass--Delay Duality:} Observation of a photon with nonzero rest mass or evidence of photons experiencing proper time would refute \(T \cdot m = \hbar/c^2\).
  \item \textbf{Causal Resolution Constancy:} Any verified measurement of light speed varying by frame (beyond experimental error) would falsify \(T \cdot C_s = 1\).
  \item \textbf{Binary law of quanta:} Demonstration of fractional photon detection (for example, one photon partially absorbed by two detectors simultaneously) would falsify the 0/1 toggle principle.
  \item \textbf{Conservation of state changes:} Discovery of orphan photons (emission without absorption), or violations of energy/charge conservation in photon processes, would falsify this axiom.
  \item \textbf{Display vs.\ non-display events:} If entanglement correlations or tunneling events were shown to require hidden propagating signals rather than direct frameless registration, this axiom would fail.
  \item \textbf{Wavefunction as frame geometry:} If \(|\psi|^2\) distributions were observed without any frame-defining geometry (no curvature, boundaries, or constraints), this axiom would be challenged.
  \item \textbf{Free will and timeless insertion:} Evidence that measurement settings are predetermined (eliminating choice as an insertion) or that retrocausal signaling is required for correlations would undermine this axiom, including robust failures of freedom-of-choice loophole tests \citep{hensen}.
  \item \textbf{Ontological seniority:} Robust detection of acausal influences or systematic breakdowns of GR/SR not attributable to frame rendering would weaken the seniority claim.
  \item \textbf{Quantitative probe (CMB tails):} A targeted search for weak, systematic non-Gaussian tails in the CMB at very high multipoles (\(\ell \sim 10^{6}\)) consistent with a frame-geometry origin, with null results at stated sensitivity, would constrain or falsify specific TLM terrain predictions \citep{cmb_tails}.
\end{itemize}

\section{Internal consistency and evolution from prior works}

The refinements in TLM v2.0 integrate consistently with foundations established in earlier works, including Cornerstone equations \citep{cornerstone}, WFAT disambiguation \citep{wfat}, Quanta global--frames local \citep{quanta_global}, Binary law \citep{binary_law}, Quanta transfer \citep{transfer}, and the generalized pairing program \citep{pairing}. The new axioms formalize and clarify mechanisms that were previously implied.

\subsection{Axiom of detection}
Formalizes registration: frameless ticks \(\{E,A\}\) are mapped into frame geometry as local increments. Consistent with bridge laws (\(T \cdot m\), \(T \cdot C_{s}\)), the binary law, and conservation. Evolves quanta transfer and pre-resolved instruction language \citep{transfer}.

\subsection{Axiom of display vs.\ non-display events}
Classifies rendering modes. Display events use SDF GR/SR illusions (paths at \(c\)); non-display events map ticks directly as correlations. Aligns with pairing rules; adds granularity \citep{pairing}.

\subsection{Axiom of free will and timeless insertion}
Resolves agency without retrocausality: choices are insertions in the frameless layer, appearing causal only in frames. Philosophically new; consistent with timeless authorship implied previously.

\subsection{Axiom of wavefunction as frame geometry}
Attributes \(|\psi|^2\) to frame geometry, not photon properties. Emerges from repeated 0/1 toggles on terrains bent by GR/SR geometry.

\section{Clean slogan recap}

\begin{itemize}[leftmargin=1.2cm]
  \item Frames = points with clocks and rulers.
  \item Quanta = frameless ticks, no time, no path.
  \item Mass--Delay Duality = law of frame behavior.
  \item Causal Resolution Constancy = law of deployment.
  \item Wavefunction = frame's geometry, not a photon property.
  \item Conservation = no orphan ticks.
  \item Binary law = local 0/1 toggle per absorber.
  \item Detection = frame registers state change.
  \item Display vs.\ non-display = photons get movies, entanglement/tunneling do not.
  \item Seniority = frameless \(>\) framed.
\end{itemize}

\section{Conclusion}
TLM v2.0 offers a unified ontology in which GR/SR/QM are frame-rendered appearances of frameless ticks governed by two compact bridge laws. By separating frameless instructions from framed displays, the model clarifies detection, wavefunction origins, and correlation phenomena, while remaining empirically vulnerable via the outlined falsifiability conditions. The program is thus precise enough to test and simple enough to extend.

\bibliographystyle{plainnat}
\section*{References}
\begin{thebibliography}{99}

\bibitem{cornerstone}
McKinley, J. C. W. (2025).
\newblock Deriving Cornerstone Equations from TLM Axioms.
\newblock Zenodo. \href{https://doi.org/10.5281/zenodo.16596589}{10.5281/zenodo.16596589}.

\bibitem{wfat}
McKinley, J. C. W. (2025).
\newblock Timeless Light Model vs Wheeler--Feynman Absorber Theory: A Disambiguation (v5.0).
\newblock Zenodo. \href{https://doi.org/10.5281/zenodo.16924316}{10.5281/zenodo.16924316}.

\bibitem{quanta_global}
McKinley, J. C. W. (2025).
\newblock Quanta are Global, Frames are Local: A Rosetta Statement of the Timeless Light Model (v1.0).
\newblock Zenodo. \href{https://doi.org/10.5281/zenodo.16917106}{10.5281/zenodo.16917106}.

\bibitem{binary_law}
McKinley, J. C. W. (2025).
\newblock The Binary Law of Quanta: Location as a Timeless Choice.
\newblock Zenodo. \href{https://doi.org/10.5281/zenodo.16913425}{10.5281/zenodo.16913425}.

\bibitem{transfer}
McKinley, J. C. W. (2025).
\newblock The Quanta Transfer Law (v1.0).
\newblock Zenodo. \href{https://doi.org/10.5281/zenodo.16897573}{10.5281/zenodo.16897573}.

\bibitem{pairing}
McKinley, J. C. W. (2025).
\newblock Generalized Pairing Law: No Quantum Emission Without an Absorber.
\newblock Zenodo. \href{https://doi.org/10.5281/zenodo.16892099}{10.5281/zenodo.16892099}.

\bibitem{cmb_tails}
McKinley, J. C. W. (2025).
\newblock A Falsifiable Prediction of Non-Gaussian Tails in the CMB from Timeless Quantum Physics.
\newblock Zenodo. \href{https://doi.org/10.5281/zenodo.16730256}{10.5281/zenodo.16730256}.

\bibitem{einstein1905}
Einstein, A. (1905).
\newblock Zur Elektrodynamik bewegter K{\"o}rper.
\newblock \emph{Annalen der Physik} 17, 891--921.

\bibitem{michelson}
Michelson, A. A., \& Morley, E. W. (1887).
\newblock On the Relative Motion of the Earth and the Luminiferous Ether.
\newblock \emph{American Journal of Science} 34, 333--345.

\bibitem{poundrebka}
Pound, R. V., \& Rebka, G. A. (1960).
\newblock Apparent Weight of Photons.
\newblock \emph{Physical Review Letters} 4, 337--341.

\bibitem{ashby_gps}
Ashby, N. (2003).
\newblock Relativity in the Global Positioning System.
\newblock \emph{Living Reviews in Relativity} 6, 1.

\bibitem{bell}
Bell, J. S. (1964).
\newblock On the Einstein Podolsky Rosen Paradox.
\newblock \emph{Physics} 1, 195--200.

\bibitem{aspect}
Aspect, A., Grangier, P., \& Roger, G. (1982).
\newblock Experimental Realization of Einstein-Podolsky-Rosen-Bohm Gedankenexperiment.
\newblock \emph{Physical Review Letters} 49, 91--94.

\bibitem{hensen}
Hensen, B., \emph{et al.} (2015).
\newblock Loophole-free Bell inequality violation using electron spins separated by 1.3~km.
\newblock \emph{Nature} 526, 682--686.

\bibitem{taylor}
Taylor, G. I. (1909).
\newblock Interference Fringes with Feeble Light.
\newblock \emph{Proceedings of the Cambridge Philosophical Society} 15, 114--115.

\bibitem{yoon}
Kim, Y.-H., Yu, R., Kulik, S. P., Shih, Y., \& Scully, M. O. (2000).
\newblock ``Delayed `Choice' Quantum Eraser''.
\newblock \emph{Physical Review Letters} 84, 1--5.

\end{thebibliography}

\end{document}
```

</details>

---
{% endraw %}
