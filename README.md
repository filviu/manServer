manServer
=========

manServer is a server/converter for man2html. It's download page is broken so I'm keeping a copy here.

Originally found at: http://www.squarebox.co.uk/users/rolf/download/manServer.shtml


SYNOPSIS
========
    manServer [ -s [ port ] ] [ filename ] 

DESCRIPTION
===========

manServer is a troff (or nroff) to HTML interpreter written in Perl. It is designed specifically to convert manual pages written using the man(7) troff macros into HTML for display and navigation with a web browser. To this end it includes direct support for man macros (also limited support for tbl, eqn and the doc macros) as well as the most common troff directives.

It differs from programs like man2html which merely take rather ugly nroff output and put a thin HTML wrapper around it.

The following macros and directives are supported by manServer, with varying degrees of correspondence to their troff counterparts. Where there are significant differences these are usually due to the fact that troff tends to be layout-oriented while HTML is more content-oriented and does not provide the same kind of detailed layout control. 

MORE
====

see html or txt for more details
