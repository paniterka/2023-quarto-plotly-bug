# 2023-quarto-plotly-bug 

`quarto_demo_clear.ipynb`: a clear notebook with no output stored  
`quarto_demo_plotly5-1X.ipynb`: a notebook with code output stored. A respective plotly version has been used to generate the code output.  
`quarto_demo_plotly5-1X.html`: rendered respective notebook using quarto 1.3.361  
`requirements_plotly5-1X.txt`: requirements used to create a venv 

Notebook expects a venv named `quarto39`. 

To switch between plotly versions without re-installing the whole venv: `pip install plotly==5.11 force reinstall` 

