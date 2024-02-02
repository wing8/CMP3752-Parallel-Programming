# OpenCL Tutorials

## Requirements

The presented tutorials were developed and tested on Windows 11, Visual Studio 2022 and the Intel SDK so that it could be run on Windows PCs in the computing labs here at the University of Lincoln. If you would like to develop OpenCL programs on your own computer you could try to replicate the [Windows setup](#windows-setup) (shown below) from the labs. In the event that this is not plausible, working physically in the labs (and remotely via [Splashtop](https://digitaltechnologies.lincoln.ac.uk/2020/12/15/how-to-splashtop/)) are good options.
 
## Windows Setup
 - OS + IDE: Windows 11, Visual Studio 2022
 - OpenCL SDK: the SDK enables you to develop and compile the OpenCL code. In our case, we use [Intel SDK for OpenCL Applications](https://software.intel.com/en-us/intel-opencl). You are not tied to that choice, however, and can use SDKs by NVIDIA or AMD - just remember to make modifications in the project include paths. Each SDK comes with a range of additional tools which make development of OpenCL programs easier.
 - OpenCL runtime: the runtime drivers are necessary to run the OpenCL code on your hardware. Both NVIDIA and AMD GPUs have an OpenCL runtime included with their drivers. For CPUs, you will need to install a dedicated driver by [Intel](https://software.intel.com/en-us/articles/opencl-drivers) or APP SDK for older AMD processors. It seems that AMD’s OpenCL support for newer CPU models was dropped unfortunately, but many of them work by simply using the Intel drivers instead. You can check the existing OpenCL support on your PC using [GPU Caps Viewer](http://www.ozone3d.net/gpu_caps_viewer/).
