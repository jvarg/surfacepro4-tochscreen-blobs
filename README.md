# surfacepro4-touchscreen-blobs-linux
blobs for the surface pro touchscreen

Intel Blobs for usage with the linux kernel

i use it with the surface pro 4 kernel from AUR.

for more instructions and help see:
https://github.com/jimdigriz/debian-mssp4
as a guide.

sudo cp /usr/src/linux/firmware/intel/ipts/ipts_fw_config.bin /lib/firmware/intel/ipts
sudo ln -s iaPreciseTouchDescriptor.bin /lib/firmware/intel/ipts/intel_desc.bin
sudo ln -s SurfaceTouchServicingDescriptorMSHW0078.bin /lib/firmware/intel/ipts/vendor_desc.bin
sudo ln -s SurfaceTouchServicingKernelSKLMSHW0078.bin /lib/firmware/intel/ipts/vendor_kernel.bin
sudo ln -s SurfaceTouchServicingSFTConfigMSHW0078.bin /lib/firmware/intel/ipts/config.bin
