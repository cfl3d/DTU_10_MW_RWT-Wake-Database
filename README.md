# DTU_10_MW_RWT-Wake-Database
  This project presents a high-resolution flow field database for the wake of the DTU 10 MW reference wind turbine under extremely high Reynolds numbers.

  The data file is provided in Tecplot format and includes four columns: hub-height sectional positions X/D and Y/D, time-averaged velocity, and turbulence intensity. The files can be directly opened using Tecplot. Additionally, the Tecplot script files TI.lay and Ux.lay allow for direct visualization of turbulence intensity and mean velocity.

\begin{table}[!htb]
	\centering
	\caption{All numerical simulation conditions: Velocity and Yaw.}
	\label{tblallcase}
	\begin{tabular}{ r c c c c c c c}
		\hline
	          & $4$ \SI{}{m/s} & $8$ $\SI{}{m/s}$& $11$ $\SI{}{m/s}$& $12$ $\SI{}{m/s}$& $16$ $\SI{}{m/s}$& $20$ $\SI{}{m/s}$ & $24$ $\SI{}{m/s}$ \\
		\hline
            $-15^{\circ}$  & V4Y-15 &        & V11Y-15 &        & V16Y-15 &         & V24Y-15 \\
            $-10^{\circ}$  & V4Y-10 &        & V11Y-10 &        & V16Y-10 &         & V24Y-10 \\
            $-5^{\circ}$   & V4Y-5  &        & V11Y-5  &        & V16Y-5  &         & V24Y-5 \\
            $ 0^{\circ}$   & V4Y0   & V8Y0   & V11Y0   & V12Y0  & V16Y0   &  V20Y0  & V24Y0 \\
            $5^{\circ}$    & V4Y5   &        & V11Y5   &        & V16Y5   &         & V24Y5 \\
            $10^{\circ}$   & V4Y10  &        & V11Y10  &        & V16Y10  &         & V24Y10 \\
            $15^{\circ}$   & V4Y15  &        & V11Y15  &        & V16Y15  &         & V24Y-15 \\
		\hline
	\end{tabular}%
\end{table}

  To use this database, please cite "Wenhao Xu, Gaohua Li, Feng Guo, Zhen Gao. A high-fidelity database for data-driven wake model considering wind farm active yaw control(Under Review), Wind Energy, 2025." 
