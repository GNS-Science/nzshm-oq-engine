## NOTE

This "cscaling.py" is not required anymore as it has been now included in the GEM/OpenQuake officially.

https://github.com/gem/oq-engine/pull/7736



## Magnitude Area C-Scaling

The simplified "c" magnitude-area scaling relations are used in the NZ-NSHM 2022. 
In the hazard calculations, these relations are required for the distributed seismicity models.


#### What to do?

Until "cscaling" becomes a part of the official "GEM/openquake/hazardlib/scalerel", 
we can work by copying the file: <b>cscaling.py</b> in the folder:  
openquake/hazardlib/scalerel/ of your active OpenQuake installation.

Now, that's a hack. But, I believe that there is nothing illegal about it.

Some examples of source (xml) files for the distributed seismicity models 
can be found at: https://github.com/GNS-Science/nz-oq-distrseis/tree/main/haz-testdrive/sources

