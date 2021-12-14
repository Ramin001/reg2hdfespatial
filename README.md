# reg2hdfespatial
Spatial and serial correlation adjustment for regressions with high dimensional fixed effects. This version also includes the possibility of instrumental variable regression and working with weighted data

The main building block is the code created by Solomon Hsiang used in the following paper:
Hsiang, Solomon M. "Temperatures and cyclones strongly associated with economic production in the Caribbean and Central America." Proceedings of the National Academy of sciences 107, no. 35 (2010): 15367-15372.

You can access Solomon's main code here:
http://www.fight-entropy.com/2010/06/standard-error-adjustment-ols-for.html

This code has previously been augmented to be used in regressions with high dimensional fixed effects by Thiemo Fetzer:
http://www.trfetzer.com/conley-spatial-hac-errors-with-fixed-effects/

The reg2hdfespatial.ado in this repository adds the possibility of using weighted data and IV estimation to Thiemo's code. This version is used in the following paper:
Baum-Snow, Nathaniel, and Lu Han. "The microgeography of housing supply." Work in progress, University of Toronto (2019).

To use this code, copy reg2hdfespatial.ado and ols_spatial_HAC.ado in your personal ado folder and install them using the stata command : >install *.ado
