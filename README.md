# Gamma Radiation Attenuation Simulation

This Python script models the attenuation of gamma radiation through common shielding materials using the Beer–Lambert law:

    I = I0 * exp(-μx)

where:
- I0 = initial intensity  
- μ  = linear attenuation coefficient  
- x  = material thickness  

## Materials modelled
- Air  
- Water  
- Concrete  
- Lead  

The script uses approximate μ values for ~0.5–1 MeV gamma energies.

## Output
The plot compares the relative intensity (I/I0) as a function of thickness, showing how high-Z materials like lead attenuate much more effectively than lower-density materials.

## Requirements
- numpy
- matplotlib

