# latex_figures
Different personal latex figures 
### Windows (PowerShell)
```powershell
pdflatex example.tex; pdftocairo -png -r 300 -singlefile example.pdf
```

### Linux
```bash
pdflatex example.tex && pdftocairo -png -r 300 -singlefile example.pdf
```
