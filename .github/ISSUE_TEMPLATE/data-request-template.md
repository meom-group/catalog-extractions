---
name: Data request template
about: Specification of the dataset you want MEOM to provide
title: "[data]"
labels: data request
assignees: auraoupa

---

You need some simulation outputs, in order for MEOM to proceed to the extraction you need to specify :
  - the configuration (ex: eNATL60, eORCA36, CALEDO60)
  - the simulation (ex: BLBT002, the one with tides, the climatological forcing one)
  - the variables (ex: SSH, temperature at 60m, density, EKE)
  - the region (ex: whole domain, SICIL, OSMOSIS, global)
  - the vertical levels (ex: surface, 60m depth, bottom)
  -  the period (ex: 01/07/2009-30/06/2010, the whole period)
  - the temporal frequency (ex: 1h, 1d)
  -  some extra computation (ex: spatial degradation, daily mean, MLD, density, EKE)
