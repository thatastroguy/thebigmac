17 June 2020
Nathan Secrest
--------
Summary:
--------
The purpose of this catalog is to have an exhaustive list of all known multiple
AGNs from the literature. A multiple AGN is defined as the manifestation of two
or more AGNs at some wavelength that are associated with each other due to some
astrophysical process. This astrophysical process can be:

- Multiple AGNs in a galaxy interaction, merger, or post-merger
- Multiple AGNs that are gravitationally bound, e.g. binary AGNs
- The appearance of multiple AGNs due to gravitational lensing (e.g. an Einstein cross)

This catalog should be *exhaustive*, so include not only confirmed systems but
also candidate systems. These systems should be everything that indicates or
potentially indicates the presence or apparent presence of more than one AGN
associated with a system (e.g. multiple X-ray/radio component, doubling of
spectroscopic lines, astrometric jitter, etc.)

----------------------
WMAGN catalog columns:
----------------------

System type (Dual/triple AGN, binary AGN, or gravitational lens)

Discovery method (e.g., multiple X-ray/radio components, spectroscopic, astrometric, etc.)

Literature name (e.g. SDSS J084905.51+111447.2)

Component (e.g. Gal1/Gal2/Gal3, a/b/c, 1/2/3, etc)
- One row for each component; components share same unique system name

Unique, standardized system name
- NED, Simbad, or IAU name preferred 

Coordinates
- Must be in ICRS system. If listed in FK5/FK6, convert to ICRS (e.g. with AstroPy)
- Equinox J2000.0
- Native epoch (i.e. not corrected for "proper motion")
- Degrees, full precision (i.e. 0.00001 deg = 0.036 arcsec)
- If coordinates not available for each component individually, just repeat the
  listed system coordinates for each source.

Coordinate epoch (e.g. 2015.5 for Gaia DR2)
- Leave blank if not determinable

Coordinate wavelength/frequency
- Leave blank if not determinable

Coordinate source (e.g. SDSS, 2MASS, VLBA, Chandra, etc)

Redshift
- Leave blank if not determinable

Redshift type (spec/photo)
- Leave blank if not determinable

Brightness band
- E.g., Johnson V, SDSS r, Gaia G, WISE W1, radio X-band, etc.

Brightness numerical value
- Magnitude or flux density

Brightness type
- E.g., VEGAMAG, ABMAG/STMAG, Jy

Bibcode(s), e.g. 2019ApJ...883..167P,2019ApJ...887...90L
- Ordered by date

NED hyperlink

Simbad hyperlink

Confidence level
- Up to you how you want to qualify this. E.g., "potential", "likely", "confirmed"
- Preferably numeric so catalog can be sorted. E.g. 1=potential, 2=likely, 3=confirmed.

Essential object notes
