# Next steps
## todo: literature search for state of the art in reliability and redundancy for unmanned aircraft

work in progress, quotes from reference documents [here](https://hackmd.io/IjcOlnhtSNO6bEC0fUDX-w#Reliability-and-redundancy-for-unmanned-aircraft)  

## Useful information

[PFreeman] says <mark>"certifiable techniques to address UAS LOC incidents must, whenever feasible, rely on analytical over hardware redundancy to maintain the
operational advantages of UAS"</mark>

### [PFreeman], 2018
- Existing low-cost unmanned aerospace systems are unreliable {citation?}
- engineers must blend reliability analysis with fault-tolerant control in novel ways
- introduces the University of Minnesota unmanned aerial vehicle flight research platform, a comprehensive simulation and flight test facility for reliability and fault-tolerance research. 
- An FMEA is performed for an unmanned aircraft
    - control surface
    - servo-actuation subsystem
    - extended by using a high-fidelity nonlinear aircraft simulation
    - Maintaining effector health is essential for safe flight; failures may lead to loss of control incidents. 
    - Failure likelihood, severity, and risk are qualitatively assessed for several effector failure modes. 
- Design changes are recommended to improve aircraft reliability based on this analysis. 
- Most notably, the control surfaces are split, providing independent actuation and dual-redundancy. 
- The simulation models for control surface aerodynamic effects are updated to reflect the split surfaces using a first-principles geometric analysis.
- A trim state discovery is performed to identify the achievable steady, wings-level flight envelope of the healthy and damaged vehicle. 
- Tolerance of elevator actuator failures is studied using familiar tools from linear systems analysis. This analysis reveals significant inherent performance limitations for candidate adaptive/reconfigurable control algorithms used for the vehicle.
- demonstrates how these tools can be applied in a design feedback loop to make safety-critical unmanned systems more reliable.
- using model-based and model-free approaches and applies those algorithms to experimental faulted and unfaulted flight test data. 
- Flight tests are conducted with actuator faults that affect the plant input and sensor faults that affect the vehicle state measurements. 
    - A model-based detection strategy is designed and uses robust linear filtering methods to reject exogenous disturbances, e.g. wind, while providing robustness to model variation. 
    - A data-driven algorithm is developed to operate exclusively on raw flight test data without physical model knowledge. 
- The fault detection and identification performance of these complementary but different methods is compared. 

### [EPetritoliFLecceseLCiani], 2014

interval for the maintenance activities for Unmanned Aerial Vehicles (UAV)

commercial aviation failure rate is about 1/10^5 flight hours, while for drones, it has been verified at about 1/10^3 flight hours, so a higher magnitude of two orders. From a different point of view, sophisticated UAV systems have an overall failure rate of 25%. 

new ideas to increase the reliability of a drone optimizing maintenance activities. For this, we start from the philosophy of apportioning the percentages of reliability assigned (on average) to each system (and subsystem), trying to optimize them according to safety requirements. On the other hand, it is necessary to optimize the time intervals (and consequently the costs) of maintenance, taking into account that all critical systems must absolutely support preventive maintenance criteria: in these cases, we are helped by the concepts of soft and hard failure [2,3].

reliability of commercial electronic components is now extremely high, even those with plastic casing. This is also a consequence of the continuous research in the automotive field, where the operating temperature range is quite high. All of these aspects, combined with low construction complexity, lead to a high reliability level


### Less relevant information

#### [RCowen-Hirsch], 2017
US Air Force is also exploring commercially provided Ka-band ... [for] ... seamless, globally available high-capacity wideband connectivity on land, at sea, and in the air.

[PFreeman]: https://conservancy.umn.edu/bitstream/handle/11299/170136/Freeman_umn_0130E_15553.pdf "Reliability Assessment for Low-cost Unmanned Aerial Vehicles, Paul Michael Freeman, FACULTY OF THE GRADUATE SCHOOL OF THE Uo MINNESOTA, .pdf"
[RCowen-Hirsch]: http://www.milsatmagazine.com/story.php?number=1996685133 "Why Ka-Band Has Emerged As Critical For UAS Missions An Inmarsat Focus, Rebecca Cowen-Hirsch, Government Strategy and Policy, Inmarsat US Government Business, .html"
[EPetritoliFLecceseLCiani]: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6165073/ "Reliability and Maintenance Analysis of Unmanned Aerial Vehicles, Enrico Petritoli; Fabio Leccese; Lorenzo Ciani, Copyright © 2018 by the authors; (CC BY) license"

## Bibliography

- [Improving UAV reliability](https://duckduckgo.com/?q=improving-uav-reliability)
- [Why Ka-band is critical for unmanned aircraft missions](https://duckduckgo.com/?q=Why+Ka-band+is+critical+for+unmanned+aircraft+missions)
- [Reliability and Maintenance Analysis of Unmanned Aerial Vehicles](https://duckduckgo.com/?q=Reliability+and+Maintenance+Analysis+of+Unmanned+Aerial+Vehicles)

<mark>progress so far</mark>

- [DSIAC Reliability of UAVs and Drones](https://duckduckgo.com/?q=DSIAC+Reliability+of+UAVs+and+Drones)
- [A Fast Reliability Analysis for an Unmanned Aerial Vehicle Performing a Phased Mission](https://duckduckgo.com/?q=A+Fast+Reliability+Analysis+for+an+Unmanned+Aerial+Vehicle+Performing+a+Phased+Mission)
- [Dual Redundant Flight Control System Design for Microminiature. UAV](https://duckduckgo.com/?q=Dual+Redundant+Flight+Control+System+Design+for+Microminiature.+UAV)
- [Design of Intelligent Fault-Tolerant Flight Control System for Unmanned Aerial Vehicles](https://duckduckgo.com/?q=Design+of+Intelligent+Fault-Tolerant+Flight+Control+System+for+Unmanned+Aerial+Vehicles)
- [Practical Methods for Small Unmanned Aerial Vehicles](https://duckduckgo.com/?q=Practical+Methods+for+Small+Unmanned+Aerial+Vehicles)
- [Active Fault Tolerant Flight Control System Design—A UAV Case Study](https://duckduckgo.com/?q=Active+Fault+Tolerant+Flight+Control+System+Design%E2%80%94A+UAV+Case+Study)
- [Development of a Fault Tolerant Flight Control System](https://duckduckgo.com/?q=Development+of+a+Fault+Tolerant+Flight+Control+System)
- [Implementing Fault-Tolerance via Modular Redundancy](https://duckduckgo.com/?q=Implementing+Fault-Tolerance+via+Modular+Redundancy)
- [Reliability assessment of UAV systems](https://duckduckgo.com/?q=Reliability+assessment+of+UAV+systems)
- [Unmanned Aerial Vehicle Reliability Study](https://duckduckgo.com/?q=Unmanned+Aerial+Vehicle+Reliability+Study)
- [Manual versus Speech Input for the Unmanned Aerial Vehicle Control Station Operations](https://duckduckgo.com/?q=Manual+versus+Speech+Input+for+the+Unmanned+Aerial+Vehicle+Control+Station+Operations)
- [Failure Analysis Methods in Unmanned Aerial Vehicle (UAV) Applications](https://duckduckgo.com/?q=Failure+Analysis+Methods+in+Unmanned+Aerial+Vehicle+(UAV)+Applications)
- [An Evidence Theoretical Approach to Design of Reliable Low-Cost UAV’s](https://duckduckgo.com/?q=An+Evidence+Theoretical+Approach+to+Design+of+Reliable+Low-Cost+UAV%E2%80%99s)
- [Engineering Safety and Reliability into UAV Systems: Mitigating the Ground Impact Hazard.](https://duckduckgo.com/?q=Engineering+Safety+and+Reliability+into+UAV+Systems%3A+Mitigating+the+Ground+Impact+Hazard.)
- [Overview of Military Drones Used By the UK Armed Forces](https://duckduckgo.com/?q=Overview+of+Military+Drones+Used+By+the+UK+Armed+Forces)
- [Reliability Degradation, Preventive and Corrective Maintenance of UAV Systems](https://duckduckgo.com/?q=Reliability+Degradation%2C+Preventive+and+Corrective+Maintenance+of+UAV+Systems)