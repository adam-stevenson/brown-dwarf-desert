# brown-dwarf-desert

This catalogue contains orbital parameters for brown dwarf (BD) companions on orbits with periods less than 10000 days. It was created to analyse the "brown dwarf desert", the paucity of brown dwarfs orbiting another star on orbits of less than a few astronomical units, and to search Gaia data release 3 (DR3) tables for updated information, allowing masses to be derived and brown dwarf classifications to be confirmed or refuted. It also contains information on the host stars.

Columns of the csv/spreadsheet are as follows:
Host_star = name / designation
method = Method of detection/mass determination: rv = detected with radial velocities; rv+H = radial velocity detection, Hipparcos astrometry used to determine mass; rv+HG = radial velocity detection, Hipparcos and Gaia astrometry used to determine mass; rv+HGCA = radial velocity detection, Hipparcos-Gaia catalogue of accelerations used to determine mass; rv+DR3 = radial velocity detection, Gaia data release 3 info updating orbital parameters and mass; Gaia binary_masses = objects detected and masses calculated solely by Gaia DR3 processing, accessed from the binary_masses table; rv+GASTON = radial velocity detection, mass estimated using astrometric fitting with the GASTON tool; transit = discovered/mass constrained by observing transit of the BD in front of parent star; imaging = orbital parameters from directly imaging the BD.
mass = constrained mass, if available. Units of Jupiter masses
msini = minimum mass from RV observations. Doppler spectroscopy allows calculation of the mass to within a sin(i) term, where i is the orbital inclination. Units of Jupiter masses
period = time taken for BD to complete an orbit around host. Units of days.
ecc= eccentricity, a measure of how elliptical the orbit is. Dimensionless parameter.
Mstar = mass of the host star. Units of Solar masses
Teff = effective temperature of the host star. Units of Kelvin.
logg = The base-10 logarithm of the surface gravity of the host star. Units of cm s-2
FeH = metallicity of the host star, ratio of metals to non-metals. 0.0 is solar metallicity.
source = DOI link to publication data comes from. In cases where objects are characterised in our work, object labelled with "this work", and also labelled in a suitable manner when from the Gaia binary_masses table.

For all columns of the file, p_"column" and m_"column" denote the uncertainties on the measurement, with "p" the upper uncertainty to be added to create the upper limit, and "m" the lower uncertainty to be removed from the value to find lower limit.



[Update 6 October 2023]
Catalogue updated, to file with date appended in name. Going forward, the most up-to-date version will be the most recent, but all previous versions will remain to see evolution. The original catalogue, BD_catalogue.csv, was used in creation of the journal publication.
