# Next steps
## todo: literature search for state of the art in reliability and redundancy for unmanned aircraft

### Useful information

[PFreeman] says <mark>"certifiable techniques to address UAS LOC incidents must, whenever feasible, rely on analytical over hardware redundancy to maintain the
operational advantages of UAS"</mark>

### work in progress, quotes from reference documents [here](https://hackmd.io/IjcOlnhtSNO6bEC0fUDX-w#Reliability-and-redundancy-for-unmanned-aircraft) 
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


[PFreeman]: https://conservancy.umn.edu/bitstream/handle/11299/170136/Freeman_umn_0130E_15553.pdf "Reliability Assessment for Low-cost Unmanned Aerial Vehicles, Paul Michael Freeman, FACULTY OF THE GRADUATE SCHOOL OF THE Uo MINNESOTA, .pdf"
