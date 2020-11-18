## PTP software timestamp support for Raspberry pi 4 B

**Rasbian Linux Kernel version:** 4.19

**Ethernet driver:**  bcmgenet

**Patch:** bcmgenet-ptp-support.patch

Overview of Application steps: 

1- Pull the kernel source and apply the patch.
2- Edit config and set the parameters given below:

- CONFIG_PTP_1588_CLOCK=y

- CONFIG_NETWORK_PHY_TIMESTAMPING=y

3- Rebuild kernel and install new modules.

4- Configure ptp4l for both master and slaves. 

### TODO
 
- More detailed instructions
