# The impact of secondary ice production on clouds and climate

###### tags: `GEO9550`
**Date:** *Oslo joint seminar June 1 2023*

**Speaker:** *Georgia Sotiropoulou, EFPL*

In the CMIP6 models, there is a high correlation between total cloud feedback and Equilibrium 
Climate Sensitivity. Furthermore, the uncertainty in cloud feedback is dominated by the 
high-latitude and mixed-phase clouds.

Mixed-phase clouds contain both ice and supercooled liquid and exist between 0 and -38°C. Studies have shown that the mixed-phase and ice clouds are responsible for most of the precipitation formation. 
Thus,understanding ice formation inside of mixed-phased clouds can lead to improved forecasting 
of extreme precipitation events, which has huge impacts on society.

At temperatures below -38°C ice can free homogeneously without the aid of ice nucleating particles (INP)s, At warmer temperatures an INP is required. Besides these two pathways for formation of primary ice, there are also secondary ice processes (SIP) that have been confirmed by observations to play in important role in enhancing the ice crystal number concentration (ICNC) inside of clouds. 

Therefore, to properly model cold clouds, we have to account for SIP. Models typically include the Rime splintering (Hallet-Mossop) process in their cloud microphysics schemes, which is active in temperature ranges between -3°C to -8°C. The work presented here explores the effect of including more mechanisms for SIP in different kinds of models, from small-scale LES to global climate models.

## WHat happens if we include the missing parameterized in the models.    
Additional SIP parameterizations was put into a LES model, the WRF meso-scale model and the 
global climate models, NorESM2, ECHAM-HAM amd EC-Earth. 

* The implementation of SIP in the LES resulted in a better representation of arctic clouds 
compared to observations. Simultaneously activating both the Hallet-Mossop and droplet shattering 
processes yielded the best agreement with observations and resulted in a higher Ice Crystal 
Number Concentration (ICNC) than what adding their single contributions would suggest. Thus there are non-linear behavior in how these SIP processes interact with each other.

* The implementation of droplet shattering in the WRF showed that SIP plays an important role in 
producing precipitation from higher cloud layers into the ones below, particularly in orographic clouds in the Alps. This mechanism enhanced the precipitation from lower clouds.

* To include more SIP processes in a global climate models, a random forest regression machine 
learning approach was used. The random forrest was trained on WRF simulations that include many 
SIP processes to provide a simplified parameterization that can efficiently run on a global 
scale. While the ECHAM-HAM model was not sensitive to the inclusion of SIPs, the other two models 
showed a substantial impact on ICNC, due to including more SIP processes. This has broad implications for how the models simulate cloud feedbacks and precipitation changes in response to global warming.

Overall, SIP has a considerable influence on ice formation at temperatures above -15°C, where it 
could potentially be more important than primary ice mechanisms. SIP processes have an impact at 
all scales, from the smallest to the largest. Although the SIP processes still carry high 
uncertainty they have important implications for how we understand the radiation budget and
precipitation formation and how these will potentially change in the future.
