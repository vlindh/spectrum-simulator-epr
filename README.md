Degree project in molecular science and engineering
Electron Paramagnetic Resonance (EPR) Spectrum simulator for learning purposes
Made in Python using Jupyter Notebook
Requires ipympl (https://matplotlib.org/ipympl/) to run

How to use:
Run the code and a number of buttons, fields, and other controls should appear in cell no.2 with a spectrum figure below
Adjust values as necessary, press "Commit splits" and change values of either Resolution, X min or X max to update the spectrum figure
Change "Number of splits" to add/remove rows for equivalent splits
Each split row is for one set of a number of (SplitX no. nuclei) equivalent nuclei

The spectrum figure Y-axis can be interpreted as relative intensity, although the values are not normalized

Because the figure does not auto zoom there are some restrictions on possible hyperfine constant values. These can be altered in the code however by changing the values of X min and X max and increasing the resolution of the stats.norm function.
