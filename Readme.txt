To Install:

  Copy files to /etc/vmware-vpx/vcsim/model:

    - initInventory-perf.cfg-LARGE
    - initInventory-perf.cfg-MEDIUM
    - initInventory-perf.cfg-SMALL
    - initInventory-perf.cfg-XLARGE
    - metricMetadata-perf.cfg
    - vcsim-perf.cfg

  "Select" inventory size by renaming one of the (-LARGE, -MEDIUM, -SMALL, -XLARGE) to initInventory-perf.cfg

====

To Start:

  vmware-vcsim-start /etc/vmware-vpx/vcsim/model/vcsim-perf.cfg

