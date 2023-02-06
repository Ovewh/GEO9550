# A clearer view of cloudy skies: Understanding cloud and radiation errors in a global model

***Date:*** *Oslo joint seminar Dec 2nd 2022* 

***Speaker:*** *Richard Forbes, ECMWF*

###### tags: `GEO9550`

Achieving correct TOA radiation fluxes is crucial for climate modelling and NWP 
The global mean TOA radiative balances is typically correct because the models 
are tuned to be so. However, there are often large regional biases, due to 
biases in the cloud representation.
There have only been small progress since CMIP3 and CMIP5. The systemic errors 
persist with Large part of the ocean are too reflective.
For example the; ECWMF "climate model" 80km vs ECMWF day-1 model 9km annual 
mean; Have much of the same systematic errors over the Southern ocean. These 
errors are not corrected by the assimilation. 

**Why does it matter?**
* Southern Ocean SW bias produces SST bias in the Ocean. 
* Hemispheric albedo, Southern hemisphere albedo is close to northern hemisphere. 
* Climate sensitivity. 


## Examples on how we diagnose and reduce the systematic errors in cloud and radiation.  

### Example 1: Cold air outbreaks:
- **Problem:** Not reflective enough in the cold air outbreak regions. Too little water according to microwave sounder remote sensing. 
- **Culprit:** Too little super cooled liquid water. 
- **Solution:** Errors in the convection scheme. Error reduced through improved storm tracks. 

### Example 2: Stratocumuls and trade-cumulus
- **Problem:** The ECWMF Model does pretty good in trade cumulus, but not so well in the stratocumulus.
- **Culprit:** Correcting LWP from MODIS using offline radiation model. Most of the error is the LWP.
- **Solution:** Effective radius further improve stratocumulus regions and
Heterogeneity correction further improves the model cloud cover in the stratocumulus region. 

IFS 47r3 significantly improved the errors in the trade cumulus regions. 
However, there are still problems with closed cell convection in the IFS model, but open-cell from the observations.
Does it help with high resolution? Gets smaller scale structures but the problems is still there. 

## Conclusions
* Future Potential for assimilation of visible reflectances. Is the IFS reflectance good enough?
* Error common across the NWP and Climate models. Improvement in NWP which are 
  close to observations can be used to diagnose the models errors, which then feeds upto improved representation in the climate models. 
