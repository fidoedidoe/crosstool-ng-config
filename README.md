# crosstool-ng configuration file(s)
A collection of crosstool-ng configuration (".config") file(s) used to rebuild an android toolchain. 

See: The offcial crosstool-ng [documentation](https://crosstool-ng.github.io/docs/) for more information. For details on rebuilding a toolchain from a ".config" file see this specific [document](https://crosstool-ng.github.io/docs/configuration/). 

crosstool-ng compatability: version 1.24.0

tested on: GT-N5110 SMDK-4412 (3.0.101) Lineage 14.1 kernel build

Flags: 
* CT_ARCH="arm"
* CT_ARCH_ARM=y
* CT_ARCH_ARCH="armv7-a" 
* CT_ARCH_FLOAT="auto" 
* CT_ARCH_ARM_MODE="arm" 
* CT_ARCH_ARM_MODE_ARM=y
* CT_LINUX_VERSION="3.10.108" (crashed when compiling for earlier versions such as 3.0.101)
