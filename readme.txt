To use this template:

1. Rename report.tex into something else. Proposed form
      PROJECTNAME-PHASE-WORKPACKAGE-LASTNAME-yourworkname.tex
    EXAMPLE:
	CubETH-C-ADCS-Ivanov-KalmanFilterEstimates.tex

2. To compile fully file run:
   latex $name.tex
   bibtex $name
   makeglossaries $name
   latex $name

   You only need to run bibtex and makeglossaries once, after you have
   introduced new reference items or acronyms.

