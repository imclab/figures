img:file://networks/torus_construction/torus_3d.png

Assorted Figures
================

This repository contains an informal library of figures created in various ways
and for various purposes which may be of use to others. These figures are
typically described in [TikZ](http://en.wikipedia.org/wiki/PGF/TikZ),
[Inkscape](http://inkscape.org/) or generated by Python (usually by outputting
machine generated SVG or TikZ source).

Though the figures are intended to be aesthetically pleasing, their descriptions
are often not. Please be aware of this if you are considering adapting a figure!

Note: A more plesant browsing experience for this repository can be found [on my
website](http://jhnet.co.uk/projects/figures).

LaTeX Preamble
--------------

LaTeX/TikZ figures assume that the following is in the preamble:

	::latex
	\usepackage{amsmath}
	\usepackage{amssymb}
	
	\usepackage{graphicx}
	
	\usepackage{ifthen}
	
	\usepackage[outline]{contour}
	\contourlength{1.5pt}
	
	\usepackage{tikz}
	\usepackage{tikz3d}
	\usetikzlibrary{ hexagon
	               , calc
	               , backgrounds
	               , positioning
	               , decorations.pathreplacing
	               , decorations.markings
	               , arrows
	               , positioning
	               , automata
	               , shadows
	               , fit
	               , shapes
	               , arrows
	               }

Which notably relies on the non-standard [hexagon
library](https://github.com/mossblaser/tikz-hexagon) and TikZ3D (part of
[Tex-SX](http://bazaar.launchpad.net/~tex-sx/tex-sx/development/files))
libraries.
