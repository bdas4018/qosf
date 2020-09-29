# qosf

Contains the solution of Task 2.

1. Please download the .ipynb file and do "Restart and Run All".
2. Also, can have a look at the pdf file (NOTE: Everything is ditto same here as in the .ipynb file).
3. Can use: https://nbviewer.jupyter.org to view too.
4. In NBviewer/Github/PDF, when one tries to view,latex code of few matrices don't get converted in section "Results and Explanations(*)". So, please refer to the .png image.

**PLEASE NOTE**: Made a small change in cell no. 231 (of the .ipynb file) in the **## Alternate for the BONUS Part section**, added a "modulo pi" to avoid  the state 01-10 and get the state 01+10 always. Please see 
*results_new.png* (the result at the last in ## Alternate for the BONUS Part section) AND *small_correction.png* (changed second line, circuit.ry(**theta**,0) to circuit.ry(**theta%np.pi**,0)). 
