# Refractive Index

Usage: [N [,w]] = refractiveIndex(wavelength, substance, waveunit)

For ice, the code uses the data from Warren & Brandt (2008) complementing from 320 to 600 nm with data from Picard et al. (2016). Available options include retrieving the Warren-Brandt data without the Picard supplement, or using the Warren (1984) data instead.
For water, the code uses data from Hale and Query (1973).
For dust and carbon, the code now has the values available from the SNICAR code base. Choices for dust are 'Sahara', 'Greenland', or 'SanJuan'. Choices for carbon are 'soot' for Black Carbon, 'coatsoot' for Sulfur-Coated Black Carbon, 'brc' for Brown Carbon, and 'coatbrc' for Sulfur-Coated Brown Carbon.

Other dust properties will be added as information becomes available.

The various data sources are:

SNICAR

He, C., Flanner, M.G., Chen, F., Barlage, M., Liou, K N., Kang, S., et al. (2018). Black carbon-induced snow albedo reduction over the Tibetan Plateau: uncertainties from snow grain shape and aerosol–snow mixing state based on an updated SNICAR model. Atmospheric Chemistry and Physics, 18, 11507-11527. https://doi.org/10.5194/acp-18-11507-2018

The code base is at https://github.com/mflanner/SNICARv3.

ICE

Picard, G., Libois, Q., & Arnaud, L. (2016). Refinement of the ice absorption spectrum in the visible using radiance profile measurements in Antarctic snow. The Cryosphere, 10, 2655-2672. https://doi.org/10.5194/tc-10-2655-2016

Warren, S.G. (1984). Optical constants of ice from the ultraviolet to the microwave. Applied Optics, 23, 1206-1225. https://doi.org/10.1364/AO.23.001206

Warren, S. G., & Brandt, R. E. (2008). Optical constants of ice from the ultraviolet to the microwave: A revised compilation. Journal of Geophysical Research: Atmospheres, 113, D14220. https://doi.org/10.1029/2007JD009744

Bond, T.C., & Bergstrom, R.W. (2006). Light absorption by carbonaceous particles: An investigative review. Aerosol Science and Technology, 40, 27-67. https://doi.org/10.1080/02786820500421521

WATER

Hale, G.M., & Querry, M.R. (1973). Optical constants of water in the 200-nm to 200-µm wavelength region. Applied Optics, 12, 555-563. https://doi.org/10.1364/AO.12.000555

DUST

Balkanski, Y., Schulz, M., Claquin, T., & Guibert, S. (2007). Reevaluation of mineral aerosol radiative forcings suggests a better agreement with satellite and AERONET data. Atmospheric Chemistry and Physics, 7, 81-95. https://doi.org/10.5194/acp-7-81-2007

Polashenski, C. M., Dibb, J. E., Flanner, M. G., Chen, J. Y., Courville, Z. R., Lai, A. M., et al. (2015). Neither dust nor black carbon causing apparent albedo decline in Greenland's dry snow zone: Implications for MODIS C5 surface reflectance. Geophysical Research Letters, 42, 9319-9327. https://doi.org/10.1002/2015GL065912

Skiles, S.M., Painter, T., & Okin, G.S. (2017). A method to retrieve the spectral complex refractive index and single scattering optical properties of dust deposited in mountain snow. Journal of Glaciology, 63, 133-147. https://doi.org/10.1017/jog.2016.126

CARBON

Bond, T. C., & Bergstrom, R. W. (2006). Light absorption by carbonaceous particles: An investigative review. Aerosol Science and Technology, 40, 27-67. https://doi.org/10.1080/02786820500421521

Kirchstetter, T.W., Novakov, T., & Hobbs, P.V. (2004). Evidence that the spectral dependence of light absorption by aerosols is affected by organic carbon. Journal of Geophysical Research: Atmospheres, 109, D21208. https://doi.org/10.1029/2004JD004999
