# eNATL60-BLB002 daily vertical mean of velocities between 0 and 10m

 - Configuration : [eNATL60](../simulations/eNATL60.md)
 - Simulation : [eNATL60-BLB002](../simulations/eNATL60-BLB002.md)
 - Region : [extended North Atlantic](../regions/eNATL.md)
 - Period : 01/07/2009-30/06/2010
 - Frequency : 1d
 - Variables : vozocrtx_vert_mean, vomecrty_vert_mean
 - Vertical levels : mean between surface and 10m
 - Size : 350 Go
 - Grid files : [details here](eNATL60-grid-files.md)
 - Path : 
   - on [MEOM opendap](../platforms/opendap.md) : [https://ige-meom-opendap.univ-grenoble-alpes.fr/thredds/catalog/meomopendap/extract/Eurosea/MEDWEST/catalog.html](https://ige-meom-opendap.univ-grenoble-alpes.fr/thredds/catalog/meomopendap/extract/eNATL60/eNATL60-BLB002/eNATL60/UVvertmean1d/catalog.html)
   - on [cal1 server](../platforms/cal1.md) : /mnt/meom/MODEL_SET/eNATL60/eNATL60-BLB002-S/1d/eNATL60
 - Scripts : 
   - [make_compute_vertmean_BLB002_UV0-10m.ksh](https://github.com/auraoupa/extract-occigen/blob/main/make_compute_vertmean_BLB002_UV0-10m.ksh)
   - [job_eNATL60-BLB002_1dmean_UVvertmean.ksh](https://github.com/auraoupa/extract-cal1/blob/master/job_eNATL60-BLB002_1dmean_UVvertmean.ksh)
