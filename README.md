# vertex-k-center
Implementation of the main approximation algorithms and heuristics for the vertex k-center selection problem.

The kcp python file must be runned from its path, and with the Lib folder at this same path.

The kcp python file is runned with the command:

  - python kcp.py algorithm library seed repetitions outputfile
  
  being:
    - algorithm = CDS_h, CDS_app, CDS+_h, CDS+_app, CDS_n4, Gon, Gon+, Gr, Gr+, HS, Scr
    - library = ORLib, smallTSPLib, u1060, u1817, pcb3038
          (the pcb3038 instance is not present in the Lib folder because GitHub can support so heavy files)
    - seed = any number
    - repetitions = every instance can be repeated more than 1 time
    - outputfile = path and name for the outputfile with the experimental approximation factor obtained by the tunned algorithm over the selected instances
