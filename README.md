# BritishNationalGrid.jl-artifacts

This repository contains binary artifacts for use by
[BritishNationalGrid.jl](https://github.com/anowacki/BritishNationalGrid.jl),
a Julia package for converting between WGS84 longitude and latitude
coordinates and the Ordnance Survey of Great Britain's National Grid.

## Files packaged in this repo

### `uk_os_ISTN15_NTv2_OSGBtoETRS.tar.gz`
This contains the grid files necessary for converting between the
OSGB and ETRF systems.  Proj uses the file in this tarball automatically
when converting, but the file is not distributed with Proj.

The tarball contains the following files:
- `uk_os_ISTN15_NTv2_OSGBtoETRS.tif`
    - Original source: OS, via [PROJ](https://github.com/OSGeo/PROJ-data/blob/master/uk_os/uk_os_OSTN15_NTv2_OSGBtoETRS.tif), from the [OS](https://www.ordnancesurvey.co.uk/business-government/tools-support/os-net/for-developers)
    - [Direct link](https://github.com/OSGeo/PROJ-data/raw/master/uk_os/uk_os_OSTN15_NTv2_OSGBtoETRS.tif)
    - Licence: [two-clause BSD](https://opensource.org/license/bsd-2-clause/)