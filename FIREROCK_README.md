# NetApp Firerock Development Branch

This is the main NetApp DPDK development branch for Firerock.

  - All modifications made to DPDK by NetApp should be made in a sub-branch off of the firerock-dev branch
  - All modifcations made to the DPDK code will be BSD licensed, open source software
  - Modifications made to this branch may be donated back to the SPDK/DPDK project.
  - Modifications made to this branch are subject to the NetApp OSRB code review process.

Contact: johnm@netapp.com for more information.

# KV-Store Repository Setup

The new Bitbucket KV-STORE project is located at: https://bitbucket.eng.netapp.com/projects/KV-STORE-BB

Use the new setup-kv-store.sh setup script to set up a local working repository: `/x/eng/site/smokejumper/spdk/autotest/setup-kv-store.sh

To create a working copy of this repository use command:

```
    setup-kv-store.sh spdk
```

# dpdk submodule

The firerock-dev branch in the dpdk submodule is used for spdk development

The unvme-dev branch in the dpdk submodule is used for unvme/spdk development

