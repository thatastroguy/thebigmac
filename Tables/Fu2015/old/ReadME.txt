J/ApJ/799/72        Binary AGNs from the VLA Stripe 82 survey        (Fu+, 2015)
================================================================================
Radio-selected binary active galactic nuclei from the Very Large Array
Stripe 82 survey.
    Fu H., Myers A.D., Djorgovski S.G., Yan L., Wrobel J.M., Stockton A.
   <Astrophys. J., 799, 72 (2015)>
   =2015ApJ...799...72F
================================================================================
ADC_Keywords: Active gal. nuclei ; Radio continuum ; Photometry, SDSS; Redshifts
Keywords: galaxies: active; galaxies: interactions; galaxies: nuclei;
          radio continuum: galaxies

Abstract:
    Galaxy mergers play an important role in the growth of galaxies and
    their supermassive black holes. Simulations suggest that tidal
    interactions could enhance black hole accretion, which can be tested
    by the fraction of binary active galactic nuclei (AGNs) among galaxy
    mergers. However, determining the fraction requires a statistical
    sample of binaries. We have identified kiloparsec-scale binary AGNs
    directly from high-resolution radio imaging. Inside the 92deg^2^
    covered by the high-resolution Very Large Array survey of the Sloan
    Digital Sky Survey (SDSS) Stripe 82 field, we identified 22 grade A
    and 30 grade B candidates of binary radio AGNs with angular
    separations less than 5" (10kpc at z=0.1). Eight of the candidates
    have optical spectra for both components from the SDSS spectroscopic
    surveys and our Keck program. Two grade B candidates are projected
    pairs, but the remaining six candidates are all compelling cases of
    binary AGNs based on either emission line ratios or the excess in
    radio power compared to the H{alpha}-traced star formation rate. Only
    two of the six binaries were previously discovered by an optical
    spectroscopic search. Based on these results, we estimate that ~60% of
    our binary candidates would be confirmed once we obtain complete
    spectroscopic information. We conclude that wide-area high-resolution
    radio surveys offer an efficient method to identify large samples of
    binary AGNs. These radio-selected binary AGNs complement binaries
    identified at other wavelengths and are useful for understanding the
    triggering mechanisms of black hole accretion.

Description:
    About a third of the Stripe 82 area has been mapped by the VLA at
    1.4GHz in its most extended configurations between 2007 and 2009
    (Hodge et al. 2011AJ....142....3H). The VLA-Stripe82 survey covers a
    total area of ~92deg^2^. The VLA survey has an angular resolution of
    1.8" and a median rms noise of 52uJy/beam.

    We obtained longslit spectroscopy during part of 2011 October 23 (UT)
    with the Low Resolution Imaging Spectrometer (LRIS) on the Keck I
    telescope.

File Summary:
--------------------------------------------------------------------------------
 FileName    Lrecl  Records   Explanations
--------------------------------------------------------------------------------
ReadMe          80        .   This file
table1.dat      95       44  *Grade A candidate binary radio AGNs
table2.dat      95       60  *Grade B candidate binary radio AGNs
table3.dat      96       12  *Properties of spectroscopically confirmed pairs
--------------------------------------------------------------------------------
Note on table1.dat, table2.dat and table3.dat: every two lines is a pair.
  See Note (1) of table3 for the grade definition.
--------------------------------------------------------------------------------

See also:
 VII/260 : The SDSS-DR7 quasar catalog (Schneider+, 2010)
 VIII/65 : 1.4GHz NRAO VLA Sky Survey (NVSS) (Condon+ 1998)
 J/MNRAS/441/1802 : Low-redshift QSOs in SDSS Stripe 82 (Karhunen+, 2014)
 J/MNRAS/436/3581 : X-ray observations of Stripe 82 (LaMassa+, 2013)
 J/ApJ/753/42  : Double-peaked AGN. I. Dual AGN candidates (Comerford+, 2012)
 J/ApJ/746/L22 : Dual AGNs in the nearby Universe (Koss+, 2012)
 J/A+A/525/A37 : Variability index of QSOs in SDSS Stripe 82 (Meusinger+, 2011)
 J/ApJ/737/101 : AGN pairs from SDSS-DR7. I. (Liu+, 2011)
 J/ApJ/716/866 : SDSS search for binary AGN (Smith+, 2010)
 J/ApJ/708/427 : Type 2 AGNs with double-peaked [OIII] lines (Liu+, 2010)
 J/ApJ/705/L76 : AGNs with double-peaked [OIII] lines (Wang+, 2009)
 J/ApJ/690/20  : Models of the AGN and black hole populations (Shankar+, 2009)
 J/A+A/487/993 : MAMBO Mapping of c2d Clouds and Cores (Kauffmann+, 2008)
 J/MNRAS/362/9 : Radio-loud AGN in SDSS (Best+, 2005)
 J/ApJ/554/803 : New VLA Sky Survey (NVSS) Cat of IRAS 2 Jy Galaxies (Yun+ 2001)
 http://www.sdss3.org/ : SDSS-III home page

Byte-by-byte Description of file: table[12].dat
--------------------------------------------------------------------------------
   Bytes Format Units   Label    Explanations
--------------------------------------------------------------------------------
   1- 18  A18   ---     RName    Radio designation (HHMMSS.ss+DDMMSS.s; J2000)
  20- 24  F5.2  mJy     S1.4pk   [0.3/23.2] 1.4GHz peak flux density
                                   (in mJy/beam)
  26- 29  F4.2  mJy   e_S1.4pk   [0.05/0.8] S1.4pk uncertainty
  31- 35  F5.2  mJy     S1.4int  [0.3/43.5] 1.4GHz integrated flux density
  37- 54  A18   ---     OName    Optical designation of the counterpart
                                   (HHMMSS.ss+DDMMSS.s; J2000)
  56- 58  F3.1  arcsec  Sep      [1.6/6] Angular separation between the optical
                                  counterparts in the pair
  60- 63  F4.1  mag     umag     [17.5/28.1]? SDSS u-band Petrosian AB magnitude
  65- 68  F4.1  mag     gmag     [15.7/25.7]? SDSS g-band Petrosian AB magnitude
  70- 73  F4.1  mag     rmag     [14.8/25.5]? SDSS r-band Petrosian AB magnitude
  75- 78  F4.1  mag     imag     [14.2/25.5]? SDSS i-band Petrosian AB magnitude
  80- 83  F4.1  mag     zmag     [14/23.6]? SDSS z-band Petrosian AB magnitude
  85- 90  F6.4  ---     z        [0.04/1]? Spectroscopic redshift
  92- 95  A4    ---     Inst     Instrument used to obtained the spectroscopic
                                   redshift (SDSS, BOSS or LRIS)
--------------------------------------------------------------------------------

Byte-by-byte Description of file: table3.dat
--------------------------------------------------------------------------------
   Bytes Format Units   Label     Explanations
--------------------------------------------------------------------------------
   1- 18  A18   ---     RName     Radio designation (HHMMSS.ss+DDMMSS.s; J2000)
      20  A1    ---     Q         [AB] Grade of the candidate binary (1)
  22- 27  F6.4  ---     z         [0.04/0.4] Spectroscopic redshift
  29- 32  A4    ---     Inst      Instrument used to obtained z: LRIS or SDSS
  34- 36  F3.1  arcsec  aSep      [2.5/4.6] Angular separation between the
                                   optical counterparts in the pair
  38- 41  F4.1  kpc     pSep      [4.1/12] Projected separation in kiloparsecs
  43- 47  F5.1  km/s    DelV      [20.9/137] Radial velocity separation {Delta}V
  49- 52  F4.1 [W/Hz]   logP1.4   [22/25] Logarithmic radio power computed from
                                   the integrated source flux density at 1.4GHz
      54  A1    ---   l_logLHa    Limit flag on logLHa
  56- 59  F4.1 [10-7W]  logLHa    [39.4/42.4] Log H{alpha} luminosity in erg/s;
                                   corrected for reddening and aperture-loss
  61- 64  F4.1  0.1nm   EWHa      [-3/51] H{alpha} equivalent width in the
                                   observed frame in {AA}
  66- 68  F3.1  0.1nm e_EWHa      [0.1/1.2] EWHa uncertainty
  70- 72  F3.1  ---     [NII]/Ha  [0.5/1.7]? [NII]{lambda}6584/H{alpha} line
                                   flux ratio
  74- 76  F3.1  ---   e_[NII]/Ha  [0.1/0.4]? The 1{sigma} error on [NII]/Ha
  78- 80  F3.1  ---     [OIII]/Hb [0.3/1.3]? [OIII]{lambda}5007/H{beta} line
                                   flux ratio
  82- 84  F3.1  ---   e_[OIII]/Hb [0.1/0.7]? The 1{sigma} error on [OIII]/Hb
  86- 91  A6    ---     Rcl       "Excess" or "Normal" Radio classification (2)
  93- 96  A4    ---     BPTcl     "Comp" or "AGN2" classification based on the
                                   BPT line-ratio diagram in Figure 6 (3)
--------------------------------------------------------------------------------
Note (1): Grade is (see section 7):
   A = Both optical sources are well enclosed by the radio structure and are
       clearly associated with a discrete radio source (i.e.,
       "secure optical IDs"). In such cases, the PA between the optical IDs is
       well aligned with that of the radio structure (i.e., "aligned PAs").
   B = Secure optical ID and aligned PAs, but the radio morphologies suggest
       that one of the optical components could be either a projected source
       within the radio lobe generated by the primary component or emission-line
       gas ejected by the radio outflow. Projected pairs are a significant
       concern because of the high source density of the deep co-added SDSS
       images. On average, ~36% of optical sources in the SDSS co-adds would
       have a nearby optical source within 5". However, we note that there is
       no clear boundary between grades A and B and the separation is quite
       subjective.
Note (2): Radio classification based on the Kauffmann et al.
     (2003MNRAS.346.1055K) classification in Figure 7.
Note (3): Classification from Baldwin et al. 1981PASP...93....5B:
  Comp = AGN-star forming composite galaxy
  AGN2 = type 2 Seyfert or LINER
--------------------------------------------------------------------------------

History:
    From electronic version of the journal

================================================================================
(End)                                     Emmanuelle Perret [CDS]    12-Jun-2015