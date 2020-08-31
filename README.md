# Nek5000 Resolvent Tools

**Nek5000 ResolventTools** is intended as a collection of resolvent-based tools developed on top of [Nek5000](https://nek5000.mcs.anl.gov/) code, which can be used for resolvent analysis [1] and estimation [2] of incompressible flows. 

The tools used here share a set of routines, e.g. for reading/saving snapshots, computing Fourier transforms,  etc. These are stores in the "Libs" folder. Links for the routines used are created on each tool folder.

## Get the code 
Time marching and other intensive tasks are implemented on top of *Nek5000* open-source code, with most pos/pre processing operations are performed in the [Octave](https://www.gnu.org/software/octave/) environment, please make sure to have these setup and working. The tools were developed and tested using v17, but should also work with v19.

To download  the code **Nek5000 Resolvent tools** use this [link](https://github.com/eduardomartini/Nek5000_ResolventTools/archive/master.zip), for a clean version of the code, this [link](https://github.com/eduardomartini/Nek5000_ResolventTools/archive/examples.zip) to also obtain files needed to run the exaples, or by the terminal by typing: 
> `git clone https://github.com/eduardomartini/Nek5000_ResolventTools.git`.


For flexibility, all the tools are developed as to use *Nek5000* for intensive tasks, e.g. time integration, application of time filters, some Fourier transforms, etc. Less intensive tasks are performed using  and can be used with Matlab with minor changes.

Specific instructions for each tools are included in their respective folders. 

## References

1. Martini, Eduardo, Daniel Rodríguez, Aaron Towne, and André V. G. Cavalieri. “Efficient Computation of Global Resolvent Modes,” 2020. [https://arxiv.org/abs/2008.10904](https://arxiv.org/abs/2008.10904) 
2. Martini, Eduardo, André V. G. Cavalieri, Peter Jordan, Aaron Towne, and Lutz Lesshafft. “Resolvent-Based Optimal Estimation of Transitional and Turbulent Flows.” Journal of Fluid Mechanics 900 (2020): A2. [https://doi.org/10.1017/jfm.2020.435](https://doi.org/10.1017/jfm.2020.435)





