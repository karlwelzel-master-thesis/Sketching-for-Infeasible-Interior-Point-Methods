# Sketching for Infeasible Interior-Point Methods
My master thesis for the MSc in Mathematical Sciences at the University of Oxford

## Final Submission
You can find the final version of the PDF [here](20210426_Dissertation.pdf). Some PDF features are only usable after downloading the document.

## Editor Setup
I've used Visual Studio Code with the "LaTeX Workshop" and "LTex" extensions.
To compile the document, clone the repository, open `dissertation.tex` with VS Code and hit "Build LaTeX project" or alternatively compile it on the command line using 

```bash
latexmk -synctex=1 -interaction=nonstopmode -file-line-error -shell-escape dissertation.tex
```

Note that the automatic word count feature requires the `-shell-escape` flag to execute the `texcount` script from within the LaTeX document.

## License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
