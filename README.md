# Setting up Tools and Software for HLS4ML and DPU for FPGA

This tutorial outlines the software and tools required for working with HLS4ML and DPU for FPGA. Please follow the instructions carefully to ensure a smooth setup process.

## Prerequisites

To get started, you will need to have the following software installed:

- Xilinx Vivado 2020.1
- Conda

## Installation Instructions

### Installing Xilinx Vivado 2020.1

Xilinx Vivado 2020.1 is required for using the `vivado_accelerator` backend for Alveo U250. Please follow the Xilinx user guide [UG973 2020-06-03](https://docs.xilinx.com/v/u/2020.1-English/ug973-vivado-release-notes-install-license) for installation instructions.

### Installing Conda

To install Conda, follow the instructions provided in the [Anaconda documentation](https://docs.anaconda.com/free/anaconda/install/linux/).

## XRT Versions for Different Approaches

Each approach (DPU and HLS4ML) has been tested with different versions of XRT. It is important to manage the correct XRT version depending on the approach you are following. Please refer to the following instructions for managing the appropriate XRT version: [Modifying XRT or Platform](https://xilinx.github.io/Alveo-Cards/master/debugging/build/html/docs/modifying-xrt-platform.html)

## Conclusion

That's it! You should now have Xilinx Vivado 2020.1 and Conda installed, which are the necessary tools for working with HLS4ML and DPU for FPGA. You can now proceed with the next steps in your tutorial.

For more detailed instructions on each approach, please refer to the following folders:

- [DPU Approach Instructions](https://github.com/dvorozhbit/alveo_purdue/tree/main/dpu-approach)
- [HLS4ML Approach Instructions](https://github.com/dvorozhbit/alveo_purdue/tree/main/hls4ml-approach)

Click on the links above to access the respective folders and follow the detailed instructions provided.

If you encounter any issues during the installation process or while following the approach instructions, please write a problem in the GitHub repository's Issues section for further assistance.
