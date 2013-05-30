Requirements
============

First you need to install rst2pdf

On Mac with macport: `sudo port install py-docutils`
On Mac with homebrew: https://groups.google.com/forum/?fromgroups#!topic/rst2pdf-discuss/vtLkQLc_r_0
On ubuntu: `apt-get install python-docutils`

Compiling your resume in PDF
============================
`rst2pdf -s resume.style --font-folder=~/Library/Fonts resume.rst -o resume.pdf`
