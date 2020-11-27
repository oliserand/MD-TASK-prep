# MD-TASK-prep
Reduces the size of an protein MD trajectory by removing water and selecting only CB and CA atoms.
By default it will attempt to use any of MDTraj, MDAnalysis, PYTRAJ, CPPTRAJ, GROMACS and VMD.
All the other parameters are optional.

## Most common usage pattern:
1. Copy the repository to a directory on your computer
`git clone https://github.com/oliserand/MD-TASK-prep`
2. Move to the directory
`cd MD-TASK-prep`
3. Run the tool
`./mdtaskprep.py topology trajectory`
4. Upload the trajectory to the web server

## Positional arguments:
 - topology: Topology file required for the trajectory
 - trajectory: The trajectory

### Optional arguments:
 - -h, --help    show this help message and exit
 - --mdtraj      Force use of MDTraj
 - --mdanalysis  Force use of MDAnalysis
 - --pytraj      Force use of pytraj
 - --cpptraj     Force use of CPPTRAJ
 - --gmx         Force use of GROMACS
 - --vmd         Force use of VMD
