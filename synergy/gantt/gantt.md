img:file://gantt_chart.png
tags: Synergy
      TikZ

TikZ Gantt Chart
================

A [Gantt chart](http://en.wikipedia.org/wiki/Gantt_chart) in TikZ, sort-of
written as a library (see bottom of file for the definition of the shown Gantt
chart). Has the following features:

* Non-linear timescales
* Dependencies
* Slack
* Super-High Box-Ticking Synergizing Powers

[Download `gantt.tex`](file://src/gantt.tex)

Usage
-----

	::latex
	\input{gantt}

\begin{latex}[--pdf Gantt Chart]
	\input{src/gantt}
\end{latex}
