---
layout: default
title: '[2025] Why Rockets Can''t Go Faster Than Light'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/why-rockets-can-t-go-faster-than-light/
paper: true
---
{% raw %}
# [2025] Why Rockets Can't Go Faster Than Light
*   **DOI:** [10.5281/zenodo.17083607](https://doi.org/10.5281/zenodo.17083607)
*   **Date:** 9 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

\documentclass[12pt, a4paper]{article}

% === ENCODING & FONT ===
\usepackage[utf8]{inputenc} % Input encoding
\usepackage[T1]{fontenc}    % Output encoding for better character support
\usepackage{lmodern}        % Use the Latin Modern font (good default)

% === PAGE LAYOUT ===
\usepackage[margin=1in]{geometry} % Set 1-inch margins

% === MATH & SYMBOLS ===
\usepackage{amsmath, amssymb, amsthm} % Essential math packages

% === TABLES & GRAPHICS ===
\usepackage{tabularx, longtable, booktabs} % For professional tables
\usepackage{graphicx}                      % For including images
\usepackage{array}                         % For custom table column types
\newcolumntype{L}[1]{>{\raggedright\arraybackslash}p{#1}}

% === DIAGRAMS (TikZ) ===
\usepackage{tikz}
\usepackage{pgfplots}
\pgfplotsset{compat=1.18}
\usetikzlibrary{arrows.meta, positioning, shapes.geometric}

% === DOCUMENT STRUCTURE & FORMATTING ===
\usepackage{titlesec}      % For customizing section titles (optional)
\usepackage{fancyhdr}      % For custom headers and footers
\usepackage{enumitem}      % For customizing lists
\usepackage{float}         % For improved figure placement with [H]
\usepackage{tcolorbox}     % For creating colored boxes (great for theorems/definitions)

% === BIBLIOGRAPHY & REFERENCES ===
\usepackage{natbib}        % For flexible citation commands

% === HYPERLINKS & CROSS-REFERENCES ===
% It is best practice to load hyperref and cleveref last
\usepackage{hyperref}
\hypersetup{
    colorlinks=true,
    linkcolor=blue,
    urlcolor=blue,
    citecolor=blue
}
\usepackage{cleveref}      % For smart cross-referencing (e.g., "Figure 1" instead of just "1")

% --- DOCUMENT START ---

\title{{Why Rockets Can’t Go Faster Than Light}}
\author{John C. W. McKinley \\ Independent Researcher \\ \href{https://orcid.org/0009-0005-7097-5035}{0009-0005-7097-5035}}
\date{September 09, 2025}

\begin{document}
\maketitle

\renewcommand{\thefootnote}{\fnsymbol{footnote}} % Use symbols for the first few footnotes
\footnotetext[1]{This version published at \href{https://doi.org/10.5281/zenodo.17083607}{doi.org/10.5281/zenodo.17083607.}}
\renewcommand{\thefootnote}{\arabic{footnote}} % Switch back to numbers for the rest

\section{Introduction: The Universe's Edict}

We don’t know who made the law — but it’s the law\footnote{\textbf{For the careful reader (and the referee):} The brass-tacks tone above is rhetorical; the physics underneath is standard. To de-foam a few likely objections: (i) When I say the speed limit is “not a theory,” I mean \emph{not merely conjectural}: it is an \emph{operational rule} encoded in Lorentz symmetry and used daily in navigation and metrology. In ordinary scientific parlance it is of course a theory—special relativity (with GR where gravity matters)—that has survived severe tests \citep{einstein1905,ashby2003}. By “proof” I mean a converging body of empirical evidence, not a theorem. (ii) The anthropomorphic phrasing (“the universe enforces the law,” “reality contorts”) is shorthand for geometry and dynamics: in SR, the invariant interval and Lorentz transformations dictate time dilation, length contraction (along the line of motion, with Einstein simultaneity), and the velocity-addition law; in GR, local physics respects light cones defined by the metric and clocks follow proper time along worldlines. Nothing mystical is intended. (iii) “Broken speedometer” parses as: there is no \emph{frame-free, local} device that reads an absolute $v$; what you can measure locally are invariants (proper time, proper acceleration) and relative kinematics to a chosen reference via radar ranging/Doppler. Picking the CMB rest frame is a convenient convention, not a violation of relativity. (iv) “Distance shrinks” is the usual length contraction: $L=L_0/\gamma$ \emph{in your frame} along the direction of motion; the rod keeps its rest length in its own frame. (v) “Unbearably heavy” means momentum and energy scale with $\gamma$: $p=\gamma m v$, $E=\gamma m c^2$. A fixed proper thrust yields diminishing \emph{coordinate} acceleration as $v\to c$; the rocket never outruns a light front in any local inertial frame \citep{taylor1992,rindler2006}. (vi) “Nearly infinite energy” is “diverges as $v\to c$” (unbounded in the idealized point-particle model). Under constant proper acceleration $a$, $v(\tau)=c\tanh(a\tau/c)$ approaches $c$ only asymptotically. (vii) About “nothing faster than light”: the claim is \emph{local}. In curved spacetime some coordinate speeds can exceed $c$; that’s a coordinate choice, not a signal. Phase/group velocities in media can exceed $c$ without superluminal information. Hypothetical tachyons, warp metrics, and wormholes require exotic stress–energy or break other assumptions; they are not part of the evidence base summarized here. (viii) The “symmetrical slowing” remarks belong to simultaneity conventions during separation; the permanent age difference at reunion is the proper-time integral along different worldlines (bookkeeping). For that bookkeeping—and a Doppler/tick-count version that avoids distant simultaneity—see the companion note \emph{Illusion and Invariant: Making Sense of Time Dilation—Reciprocity, Simultaneity, and Proper Time} \citep[][and refs.\ therein]{mckinleySymmetry2025}. (ix) Finally, “law” here is not metaphysics but a compact way to say: Lorentz symmetry, tested in labs and in the sky \citep{will2014,ashby2003}, plus the energy–momentum relation and velocity-addition law \citep{taylor1992,rindler2006}, jointly imply that composing any two subluminal speeds yields another subluminal speed and that no timelike worldline crosses a local light cone. The folksy metaphors are doing outreach; the equations do the work.}: nothing can go faster than the speed of light. This isn’t logic; it’s enforcement. The universe doesn’t stop you with a wall — it alters space and  time to restrain you. Like falling into Alice in Wonderland, the sharp corners of your Victorian house dissolve. Time slows. Distance shrinks. Passing trolleys become unbearably heavy. Reality contorts itself just to keep you below the limit.

The prohibition against exceeding the speed of light is not a theory; it is a fundamental, observable rule of the universe. The math is not the \textit{reason} for the limit; it is the \textit{description} of a limit proven by empirical evidence. The universe operates on foundational laws. The absolute nature of the speed of light is one such law~\citep{einstein1905}.  And the question isn't ``Why can’t we?'' but rather: \textit{``What happens when we try?''} \cite{einstein1905, feynmanlectures}.



\section{The Proof: How We Know The Law is Real}

The entire framework of special relativity is built on two simple but powerful postulates, which are the foundational rules of the game. Everything else, including the universal speed limit, flows directly from accepting them~\citep{einstein1905}.

Here is the definitive proof from observable reality:

\begin{itemize}
    \item \textbf{GPS \& Atomic Clocks:} GPS satellites require constant time adjustments based on their speed and gravitational position. This daily, operational necessity is direct proof that time is relative, with relativistic corrections from both special and general relativity (orbital speed and gravitational potential)~\citep{ashby2003}.
    \item \textbf{Particle Accelerators:} We can spend nearly infinite energy accelerating particles, but they only approach, never reach, \(c\). This is the energy barrier observed in action: energy rises without bound while \(v\) approaches but never reaches \(c\); the extra energy goes into \(\gamma\) (time dilation, momentum), not further \(v\)~\citep{french1968}.
    \item \textbf{Atmospheric Muons:} Muons created in the upper atmosphere reach the ground due to time dilation, living longer in our frame than their proper lifetime would allow~\citep{rossi1941}.
\end{itemize}


\begin{tcolorbox}[colback=gray!10, colframe=blue!50!black, title=Postulates of Special Relativity]
\begin{enumerate}
    \item Physics is the same in all inertial frames.
    \item The speed of light \( c \) is invariant.
\end{enumerate}
From these two, everything in special relativity flows, including the speed limit~\citep{einstein1905}.
\end{tcolorbox}



\section{The View from the Rocket: A Symmetrical Reality}

\subsection{The Broken Speedometer}

A speedometer cannot exist without measuring the spin of your wheels on the road, or how much time elapses between mile markers.\footnote{Speed is not an intrinsic property; it is a relative measurement between two frames of reference. Speed is relational, whereas acceleration is a local phenomenon that can be measured with an on-board accelerometer.}

To measure your speed, you need an external object—an asteroid, a planet. The moment you do look at that passing asteroid to see how fast you are going, you are measuring across frames. Your speedometer is not measuring your own speed, but your \textit{relationship} to another frame.\footnote{Because absolute velocity is not a frame-invariant concept, any speed reading is inherently relative. Common measurements like the Doppler shift or velocity relative to the Cosmic Microwave Background (CMB) are still just comparisons between frames.}

As you approach the speed of light, your observation of the other frame's spacetime warps. You perceive its clock as slowing down (time dilation) and its length as contracting. It becomes immovably heavy. This isn't an illusion; it's the universe reconfiguring the measurements to preserve the ultimate law~\citep{taylor1992}.

This is not "sensible", it is what we have to accept.

\subsection{The Traveler's Paradox}

From your rocket, you feel constant acceleration. "My engines are firing, I should be going faster." You \textit{are} accelerating locally. However, the universe will not allow you to see the asteroid passing by your window at a speed greater than \(c\).

The reason you never \textit{observe} yourself breaking the speed limit is that the objects you are passing are outlawed from passing you at faster than light.

\subsection{The Symmetrical Law}

All speed is measured as if you are standing still and the world is going past you, because that is how God, Gods or Unicorn Dreams made the universe. Deal with it. The limitation isn't a force acting on you. From your internal view, you observe that \textbf{no other frame can pass you at a speed faster than \(c\)}—which is simply that other frame morphing to force compliance with the universal speed limit.\footnote{This is a direct consequence of Lorentz symmetry and the relativistic velocity-addition formula. Composing any two speeds less than \(c\) will always result in a speed that is also less than \(c\). From any perspective, no object ever observes another exceeding the light-speed barrier.} So, just as we cannot observe a particle in an accelerator exceed \(c\), you cannot observe an asteroid pass us at faster than \(c\). It is the law, and it applies to everything, everywhere, from every perspective. Gas Station Gary would say: Ain't Nobody passing Nobody at greater than \(c\).

\section{Conclusion: The Cosmic Governor}

The question "Why can't we exceed the speed of light?" is answered simply: The universe is constructed with a governor, a speed limiter just like on a 1985 moped that can’t exceed 35 mph. That governor says: \textit{I will bend time and space and objects in such a way that your speed will be limited.}

You cannot break the law because you, the rocket, and also the asteroids are all subject to the law. The limit is not an obstacle placed in your way; the structure of the universe will gradually change in time, depth and inertia to prevent breakage of the speed limit.

\appendix


\section{Afterword: Beyond Speed—Toward Origin}

Einstein showed that the universe bends space and warps time to protect the cosmic speed limit. But this protective mechanism may not be the full story. According to the hypothetical \textit{Timeless Light Model} (TLM)\cite{mckinley_tlm_2025}, that universal speed limit is not a forceful cap, but a minimum rendering delay: a symptom of how experience is deployed from a timeless instruction source.

In this framework, the universe is not built from particles bouncing around in spacetime. Rather, it is constructed from \textit{instructions} issued from a timeless, causally senior layer—the \textbf{Quantum Platform} (QP). These instructions resolve into observable events within the \textbf{Spacetime Deployment Frame} (SDF), where time, mass, and velocity are rendered with delay.

From this perspective, the speed of light \( c \) is not a thing to be reached; it’s the maximum rate at which rendered instructions can be deployed from outside time. Reality brings an instant instruction down to an appreciable experience. All velocity, all inertia, all apparent resistance is the byproduct of \textbf{delay}.

\vspace{1em}
\begin{center}
\Large
Reality = Instruction + Delay
\end{center}
\vspace{1em}





\section{Technical Appendix: Math Box}

Here are the key equations for reference:

Velocity Addition:
\[
u' = \frac{u + v}{1 + \frac{uv}{c^2}}
\]
This guarantees that composing any two subluminal speeds always yields \(u' < c\)~\citep{taylor1992}.

Lorentz Factor:
\[
\gamma(v) = \frac{1}{\sqrt{1 - \frac{v^2}{c^2}}}
\]

Time dilation \& length contraction:
\[
\Delta t = \gamma \, \Delta \tau, \quad L = \frac{L_0}{\gamma}
\]~\citep{taylor1992}

Energy–Momentum Relation:
\[
E^2 = (p c)^2 + (m c^2)^2 \implies E = \gamma m c^2 \quad (\text{so } E \to \infty \text{ as } v \to c)
\]~\citep{griffiths2013}

Constant Proper Acceleration:
Under constant proper acceleration \(a\),
\[
v(\tau) = \frac{a \tau}{\sqrt{1 + \left( \frac{a \tau}{c} \right)^2}}
\]
so \(v \to c\) only asymptotically (relative to any inertial frame)~\citep{rindler2006}.

Why can’t you add speeds past \(c\)? The hyperbolic geometry (rapidity) of Minkowski space composes like angles, not ordinary sums: \(v/c = \tanh \phi\) with rapidity \(\phi\). Adding velocities = adding rapidities; \(\tanh\) keeps \(|v| < c\)~\citep{rindler2006}.

In a Minkowski diagram, light cones define timelike paths; the rocket's worldline under constant proper acceleration approaches the light cone asymptotically (Rindler horizon). A plot of \(\gamma(v)\) would show a vertical asymptote as \(v \to c\).



\begin{figure}[H]
\centering
\begin{tikzpicture}
\draw[->] (-3,0) -- (3,0) node[right] {$x$};
\draw[->] (0,-3) -- (0,3) node[above] {$ct$};
\draw[dashed] (-2,2) -- (2,-2) node[right] {Light cone};
\draw[dashed] (-2,-2) -- (2,2);
\draw[thick, blue] plot[domain=0:2] (\x, {sqrt(\x*\x + 1)}) node[right] {Rocket worldline};
\end{tikzpicture}
\caption{Minkowski diagram showing the rocket's worldline approaching the light cone.}
\label{fig:minkowski}
\end{figure}



\section{Glossary}

This glossary defines key terms used in the document ``Why Rockets Can’t Go Faster Than Light,'' drawing from foundational concepts in special relativity. Definitions are based on standard interpretations in the field.

\begin{description}
    \item[Inertial Frame] A reference frame in which an object with no net force acting on it moves with constant velocity (including zero). Physics laws, particularly Newton's first law, hold identically in all such frames. This is one of the core postulates of special relativity.
    
    \item[Speed of Light ($c$)] The invariant speed at which electromagnetic waves, including light, propagate in vacuum, approximately $3 \times 10^8$ m/s. It is constant regardless of the motion of the source or observer, forming the second postulate of special relativity.
    
    \item[Time Dilation] The effect where the time interval between two events, as measured by a clock moving relative to an observer, is longer than the proper time measured by a clock at rest with respect to the events. Mathematically, $\Delta t = \gamma \Delta \tau$, where $\gamma$ is the Lorentz factor.
    
    \item[Length Contraction] The phenomenon where the length of an object, measured in a frame where it is moving, appears shorter along the direction of motion compared to its proper length (measured in its rest frame). Expressed as $L = L_0 / \gamma$.
    
    \item[Lorentz Factor ($\gamma$)] A dimensionless quantity that quantifies relativistic effects, defined as $\gamma(v) = \frac{1}{\sqrt{1 - \frac{v^2}{c^2}}}$. It approaches infinity as $v$ approaches $c$.
    
    \item[Proper Time ($\tau$)] The time interval between two events as measured by a clock following the worldline connecting them (i.e., in the rest frame of the object or events). It is the shortest time interval between the events.
    
    \item[Proper Acceleration] The acceleration experienced by an object as measured in its instantaneous rest frame. Unlike coordinate acceleration, it is frame-invariant and can be felt locally (e.g., via an accelerometer).
    
    \item[Rapidity ($\phi$)] A hyperbolic angle parameterizing velocity in Minkowski space, defined as $\phi = \tanh^{-1}(v/c)$. Velocities add via rapidities: $\phi_3 = \phi_1 + \phi_2$, ensuring the result remains below $c$.
    
    \item[Minkowski Space] The four-dimensional spacetime manifold of special relativity, with metric signature typically $(+,-,-,-)$ or $(-,+,+,+)$, where intervals are invariant under Lorentz transformations.
    
    \item[Light Cone] In Minkowski space, the surface defining the boundary of causal influence. Points inside are timelike (reachable at subluminal speeds), on the cone are null (lightlike), and outside are spacelike (acausal).
    
    \item[Invariant] A quantity that remains the same in all inertial frames, such as the speed of light or the spacetime interval $ds^2 = c^2 dt^2 - dx^2 - dy^2 - dz^2$.
    
    \item[Relativistic Momentum] The momentum of an object in relativity, given by $p = \gamma m v$, where $m$ is rest mass. It diverges as $v \to c$.
    
    \item[Relativistic Energy] The total energy $E = \gamma m c^2$, including rest energy $m c^2$. Kinetic energy is $E - m c^2$.
\end{description}

\section{Rigorous Mathematical Derivations}

Below are detailed derivations of the key equations mentioned in the document's Technical Appendix. These are derived from the two postulates of special relativity: (1) The laws of physics are the same in all inertial frames, and (2) The speed of light $c$ is constant in all inertial frames. We assume familiarity with basic algebra and coordinate systems.

\subsection{Derivation of the Lorentz Transformation}
The Lorentz transformation maps coordinates $(t, x, y, z)$ in frame $S$ to $(t', x', y', z')$ in frame $S'$, where $S'$ moves at velocity $v$ along the $x$-axis relative to $S$.

Assume linear transformations of the form:
\[
x' = \gamma (x - v t), \quad t' = \gamma \left( t - \frac{v x}{c^2} \right), \quad y' = y, \quad z' = z,
\]
where $\gamma$ is to be determined.

\begin{itemize}
    \item \textbf{Step 1}: Invariance of light speed. A light pulse emitted at $t=0, x=0$ in $S$ satisfies $x = c t$. In $S'$, it must satisfy $x' = c t'$.
    Substitute: $c t' = \gamma \left( c t - \frac{v (c t)}{c^2} \right) = \gamma c t (1 - v/c)$,
    and $x' = \gamma (c t - v t) = \gamma t (c - v)$.
    Set $x' = c t'$: $\gamma t (c - v) = \gamma t (c - v)$, which holds identically.
    
    \item \textbf{Step 2}: Solve for $\gamma$. Consider the inverse: a light pulse in $S'$ at $t'=0, x'=0$ gives $x' = c t'$, so in $S$: $x = -c t$ (for negative direction, but symmetry applies).
    Full consistency requires the transformation to preserve the interval $c^2 t^2 - x^2 = c^2 t'^2 - x'^2$.
    Plugging in yields $\gamma = \frac{1}{\sqrt{1 - v^2/c^2}}$.
\end{itemize}

This derivation follows Einstein's original approach~\cite{einstein1905}. The full set is:
\[
x' = \gamma (x - v t), \quad t' = \gamma \left( t - \frac{v x}{c^2} \right).
\]

\subsection{Derivation of the Velocity Addition Formula}
Let an object move at velocity $u$ in $S$, so $u = dx/dt$. In $S'$ (moving at $v$ relative to $S$), the velocity is $u' = dx'/dt'$.

\begin{itemize}
    \item \textbf{Step 1}: Use differentials from Lorentz transformation:
    \[
    dx' = \gamma (dx - v dt), \quad dt' = \gamma \left( dt - \frac{v dx}{c^2} \right).
    \]
    
    \item \textbf{Step 2}: Divide:
    \[
    u' = \frac{dx'}{dt'} = \frac{\gamma (dx - v dt)}{\gamma \left( dt - \frac{v dx}{c^2} \right)} = \frac{dx/dt - v}{1 - \frac{v (dx/dt)}{c^2}} = \frac{u - v}{1 - \frac{u v}{c^2}}.
    \]
    (Note: The document has $u' = \frac{u + v}{1 + \frac{u v}{c^2}}$, which is for parallel velocities in the same direction; the sign depends on convention.)
\end{itemize}

This ensures that if $u < c$ and $v < c$, then $u' < c$~\cite{taylor1992}.

\subsection{Derivation of the Lorentz Factor and Time Dilation/Length Contraction}
From the Lorentz transformation above, $\gamma$ emerges directly.

\begin{itemize}
    \item \textbf{Time Dilation}: For events at fixed $x'$ in $S'$ ($\Delta x' = 0$), proper time $\Delta \tau = \Delta t'$. From inverse transformation: $\Delta t = \gamma \Delta t'$, so $\Delta t = \gamma \Delta \tau$.
    
    \item \textbf{Length Contraction}: A rod at rest in $S'$ has proper length $L_0 = \Delta x'$ (measured simultaneously in $S'$, $\Delta t' = 0$). In $S$: for simultaneous in $S$ ($\Delta t = 0$):
    Standard result: $L = L_0 / \gamma$.
\end{itemize}

\subsection{Derivation of the Energy-Momentum Relation}
Assume relativistic momentum $p = \gamma m v$ (consistent with conservation laws).

\begin{itemize}
    \item \textbf{Step 1}: Work done: $dE = F dx = dp/dt \cdot dx = v dp$ (since $F = dp/dt$).
    Integrate: $E = \int v dp = \int v d(\gamma m v)$.
    
    \item \textbf{Step 2}: Compute: $\gamma = (1 - v^2/c^2)^{-1/2}$, $d\gamma = \gamma^3 (v dv / c^2)$.
    $dp = m (\gamma dv + v d\gamma) = m \gamma^3 dv$.
    More precisely: $E = \gamma m c^2$ (up to constant; rest energy when $v=0$).
    
    \item \textbf{Step 3}: Square: $E^2 = (\gamma m c^2)^2 = p^2 c^2 + m^2 c^4$.
\end{itemize}

As $v \to c$, $\gamma \to \infty$, so $E \to \infty$~\cite{griffiths2013}.

\subsection{Derivation of Velocity Under Constant Proper Acceleration}
Proper acceleration $a$ is constant in the instantaneous rest frame.

\begin{itemize}
    \item \textbf{Step 1}: In the rocket's frame, $dv/d\tau = a$ (but $v$ is coordinate velocity).
    Rapidity: $d\phi / d\tau = a / c$, since $v = c \tanh \phi$.
    
    \item \textbf{Step 2}: Integrate: $\phi = (a \tau)/c$, so $v = c \tanh(a \tau / c) = \frac{a \tau}{\sqrt{1 + (a \tau / c)^2}}$.
\end{itemize}

As $\tau \to \infty$, $v \to c$~\cite{rindler2006}.

This hyperbolic motion approaches the light cone asymptotically.

\section{Bibliography}

These sources substantiate the empirical proofs (e.g., GPS, muons, accelerators) and mathematical framework discussed in the document~\cite{ashby2003,rossi1941,french1968}.
\begin{thebibliography}{99}

\bibitem{ashby2003}
Ashby, N. (2003). Relativity in the Global Positioning System. \textit{Living Reviews in Relativity}, 6(1).  
Also published in abridged form: ``Relativity and the Global Positioning System,'' \textit{Physics Today}, vol. 55, no. 5, pp. 41–47.

\bibitem{cernlhc}
CERN. ``How does a particle accelerator work?''  
Online: \url{https://home.cern/science/accelerators}.

\bibitem{einstein1905}
Einstein, A. (1905). \textit{On the Electrodynamics of Moving Bodies}. Annalen der Physik, 17(891), 891–921.

\bibitem{feynmanlectures}
Feynman, R., Leighton, R., \& Sands, M. (1964). \textit{The Feynman Lectures on Physics, Vol. 1, Ch. 15: The Special Theory of Relativity}. Addison-Wesley.
\bibitem{french1968}
French, A. P. (1968). \textit{Special Relativity}. W. W. Norton \& Company.

\bibitem{griffiths2013}
Griffiths, D. J. (2013). \textit{Introduction to Electrodynamics} (4th ed.). Pearson.

\bibitem{mckinley_tlm_2025}
J. C. W. McKinley, \textit{Causal Instruction Arcs and the Timeless Light Model: A Unified Framework for Physics and Cosmology}, Zenodo (2025), \href{https://doi.org/10.5281/zenodo.15813253}{doi:10.5281/zenodo.15813253}.





\bibitem{muons}
Griffiths, D. J. (2008). \textit{Introduction to Elementary Particles} (2nd ed.). Wiley-VCH.

\bibitem{rindler2006}
Rindler, W. (2006). \textit{Relativity: Special, General, and Cosmological} (2nd ed.). Oxford University Press.

\bibitem{rossi1941}
Rossi, B., \& Hall, D. B. (1941). Variation of the Rate of Decay of Mesotrons with Momentum. \textit{Physical Review}, 59(3), 223–228.

\bibitem{taylor1992}
Taylor, E. F., \& Wheeler, J. A. (1992). \textit{Spacetime Physics: Introduction to Special Relativity} (2nd ed.). W. H. Freeman.

\bibitem{will2014}
Will, C. M. (2014).
The Confrontation between General Relativity and Experiment.
\textit{Living Reviews in Relativity}, 17, 4.
\href{https://doi.org/10.12942/lrr-2014-4}{doi:10.12942/lrr-2014-4}.

\bibitem{mckinleySymmetry2025}
McKinley, J. C. W. (2025).
\textit{Illusion and Invariant: Making Sense of Time Dilation - 
Reciprocity, Simultaneity, and Proper Time}.
Zenodo. % Replace with your actual DOI once assigned:
\href{https://doi.org/10.5281/zenodo.17083276}{doi:10.5281/zenodo.17083276}.


\end{thebibliography}



















\end{document}

```

</details>

---
{% endraw %}
