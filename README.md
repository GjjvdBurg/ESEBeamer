ESEBeamer
=========

Unofficial Beamer style for the Erasmus School of Economics

Author: Gertjan van den Burg

This is an unofficial beamer style based on the official 
Powerpoint style for ESE.

This code is released under the GPL License (v2) (see LICENSE).

Usage
-----
See the file `example.tex`. Include the following command
in the preamble of the tex file:

    \usetheme{Rotterdam}

Options are:

  - emphasizegreen: highlight using the EUR green colour
    instead of black
  - structgreen: use EUR green as the structure colour 
    (this changes the colour of bullets etc.)
  - titleyellow: apply a yellow bar around the frame title
  - logogreen: use the EUR green logo instead of the black
    one.

Which can be used as usual as (for example):

    \usetheme[titleyellow]{Rotterdam}


Installation
------------

- Linux: See http://tex.stackexchange.com/a/1138. Create a
         local directory ~/texmf/tex/latex/beamer/rotterdam 
         and place the beamerthemeRotterdam.sty file in 
         this folder, together with the required pdf 
         images. Finally, update the package database with 
         texhash or mktexlsr.

- Windows: See http://tex.stackexchange.com/a/2066.
