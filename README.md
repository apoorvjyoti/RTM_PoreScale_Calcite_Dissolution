# RTM_PoreScale_Calcite_Dissolution
The Java code couples Comsol and PhreeqC and is an implementation of the calcite dissolution at the pore scale using unstructured finite element meshes.

The code is run in Interface COMSOL -PhreeqC (iCP) and requires a COMSOL file (.mph) which contains the information of the unstructured
grids with boundary conditions defined on the pore geometry. It also contains the mathematical equations to be solved on the finite 
element mesh. The sequences of solvers which are used in the model are also contained in the COMSOL file.

The second part is contained in PhreeqC which defined the aqueous speciation of the multiple components in the aqueous phase. It contains two files, one containing the initial pore fluid composition and the other containing the injection fluid composition.
