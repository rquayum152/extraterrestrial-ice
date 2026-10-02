Files are already loaded into the Ansys Model. The 100% GSR simulation has 6 loading files:

- "glr_heating_flux_100.csv"- This file is entered into the simulation as the GLR heat flux entering the surface of the dome and the regolith foundation.

- "gsr_heat_flux_regolith_100.csv"- This file is entered into the simulation as GSR heat flux entering the surface of the regolith foundation.

- "outer_radiation_temp_100.csv"- This file is entered into the simulation as the outer ambient temperature that the system is radiating to. 

- "gsr_transmitted_ice_internal_heat_gen_100.csv" - This file is entered into the simulation as the flux absorbed by the ice dome. 

- "gsr_surface_internal_heat_gen_100.csv"- This file is entered into the simulation as the flux transmitted by the ice dome and absorbed by the regolith surface of the dome.

- "convection_100.csv" - This file is entered into the simulation as convective heat transfer occurring in the air between the ice dome and the regolith dome surface.

The 40% powered ground simulation, similarly, has 6 loading files with the same contents and the same applications, but with attenuation of incoming GSR to 40%:

- "glr_heating_flux_40.csv"
- "gsr_heat_flux_regolith_40.csv"
- "outer_radiation_temp_40.csv"
- "gsr_surface_internal_heat_gen_40.csv"
- "gsr_transmitted_ice_internal_heat_gen_40.csv"
- "convection_40.csv"

