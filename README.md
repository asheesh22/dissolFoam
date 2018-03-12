This is the OpenFoam solver for reactive transport with dissolution.

It solves for steady flow (Stokes or inertial) and reactant transport

Mesh motion is controlled by the normalMotionSlip (libsFoamAux) Parameters to the boundary condition include the name of the field that drives the dissolution and the magnitude of the motion. Examples can be found in dissolCases.

Reaction boundary conditions (linear/nonlinear/danckwerts) are coded boundary conditions that are located in the case directory in constant/bcInclude (template files in libsFoamAux/boundaryConditions) The moving interface in polyMesh/boundary should go first.

This version was developed with OpenFOAM-v1706. It should also work with v1712.

Additional documentation about the libraries, solver and cases can be found in the file doc.pdf in the dissol1706 snapshot.

