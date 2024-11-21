# The Big Multi-AGN Catalog (Big MAC)

Author: Ryan W. Pfeifle<sup>1</sup> <br />
Contributor(s): Kimberly Weaver<sup>1</sup>, Nathan Secrest<sup>2</sup>, Barry Rothberg<sup>2</sup>, David Patton<sup>3</sup>
<br />
<sup>1</sup> X-ray Astrophysics Laboratory, NASA Goddard Space Flight Center (GSFC)<br />
<sup>2</sup> United States Naval Observatory (USNO)<br />
<sup>3</sup> Trent University<br />
<br />
Current Version: 0.9 <br />
Git Repo Creation Date: 23 July 2022 <br />
First 'official' update to README.md (here): 28 March 2023 <br />
Original DR0.1 catalog creation dates (not tracked by Git): June 2020 - October 2020 <br />
Additional changes and additions occurred during the period (not tracked by Git): November 2020 - March 2023 <br />
Last Revision Date: 29 December 2023

GitHub Website: https://thatastroguy.github.io/thebigmac/index.html

# WARNING: This repository is public but we are currently rolling out the DR1 and making final adjustments to the release. For the time being, the currently available version of the catalog is the "DR0.9"; consider this version of the catalog a beta release and proceed with caution!

## Do you have feedback or suggestions for the catalog and/or website? Please reach out to us!

## Matched ICRF3 tables coming soon. Updates for full tables coming soon.

## Interested in using Big MAC for your science? Looking to collaborate on Big MAC? Drop us an email!

## Catalog Content of the DR0.1 and DR0.5. (Larger update to the readme coming after DR0.5.)
The purpose of this catalog is to have an exhaustive list of all known multiple AGNs from the literature. A multiple AGN (multi-AGN) is defined as the manifestation of two or more physically-associated AGNs in an interacting system of galaxies. This includes: <br />
- Multiple AGNs on kpc- and sub-kpc-scales in a galaxy interaction, merger, or post-merger <br />
- Multiple AGNs that are gravitationally bound, e.g. binary AGNs (separations <30 pc) <br />

This catalog is designed to be exhaustive, including both all candidate and confirmed dual, binary, recoiling, and N-tuple AGN systems. These systems should be everything that indicates or potentially indicates the presence or apparent presence of more than one AGN associated with a system (e.g. multiple X-ray/radio component, doubling of spectroscopic lines, astrometric jitter, etc.) Note: gravitational lenses **_are not purposefully included in this catalog_**; this catalog is meant to encapsulate only multiple, but physically distinct, AGN systems, not systems comprising images of a single AGN.

**_DR0.1 consists of work done during the period June 2020 - October 2020 and was only an internal release at USNO._**

## Big MAC catalog columns: <br />
- System type (Ex: Dual/triple AGN, binary AGN, or gravitational lens)
- Discovery method (e.g., multiple X-ray/radio components, spectroscopic, astrometric, etc.)
- Confirmation method (if available)
- Literature name (e.g. SDSS J084905.51+111447.2)
- Component (e.g. Gal1/Gal2/Gal3, a/b/c, 1/2/3, etc)
- Unique, standardized system name (NED, Simbad, or IAU name preferred)
- Coordinates 
    - (Must be in ICRS system. If listed in FK5/FK6, convert to ICRS (e.g. with AstroPy))
    - Equinox J2000.0
    - Native epoch (i.e. not corrected for "proper motion")
    - If coordinates not available for each component individually,  system coordinates listed for each source.
    - Coordinate epoch (e.g. 2015.5 for Gaia DR2)
    - Coordinate wavelength/frequency
    - Coordinate source (e.g. SDSS, 2MASS, VLBA, Chandra, etc)
- Redshift (left blank if unavailable)
- Redshift type (spec/photo; Left blank if not determinable)
- Brightness band (E.g., Johnson V, SDSS r, Gaia G, WISE W1, radio X-band, etc.)
- Brightness numerical value (Magnitude or flux density)
- Brightness type (E.g., VEGAMAG, ABMAG/STMAG, Jy)
- Author+Year (orderd by date)
- Bibcode(s) (e.g. 2019ApJ...883..167P,2019ApJ...887...90L; Ordered by date)
- DOI tag
- Confidence level (Subjective flag)
- Essential object notes



# Release Notes


## DR0.1, DR0.15, and initial commits to this GitHub Repo
DR 0.1 consists of work spanning June 2020 - October 2020. Notes on DR0.1 coming soon. 
DR0.15 will consist of all of the DR0.1 files as well as additional files created since then, or modifications to the DR0.1 since it's original creation in 2020. The official first release on GitHub will be DR0.1, in  order to preserve (to the best of my ability) the original files and notebooks used to create that version. This will be followed immediately by a revision to DR0.1.1 to account for any changes to the documents since then, as well as additional notebooks I am working on. Changes include additions or revisions to the Jupyter Notebook, figures recreated using the Notebook but after October 2020, etc. As of right now, I have only committed files from 2020-2021, and the files from 2021 appear to only be the result of rerunning cells in the original Jupyter Notebook (like figures being recreated.)

DR0.1 source lists are preserved with naming conventions that denote the version number. These deliverables were provided to USNO as part of an internal release in October 2020.