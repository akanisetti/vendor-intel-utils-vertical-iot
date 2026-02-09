# Intel Vendor Utils Vertical IoT

This repository contains vendor-specific utilities and patches for Intel vertical IoT Android builds.

## Repository Structure

This repository is organized into the following main directories:

### aosp_diff/
Contains AOSP (Android Open Source Project) patches and modifications organized by target:

- **base_aaos/**: Patches for AAOS (Android Automotive OS) packages
  - Car applications (DialerPrebuilt, Settings)
  
- **caas/**: Patches for CAAS (Container as a Service) builds
  - Android framework components (art, build, frameworks)
  - Hardware interfaces
  - Package applications (Camera2, Contacts, Settings, etc.)
  - System modules (Bluetooth, WiFi, Permission, etc.)
  - Security and system patches

### bsp_diff/
Contains BSP (Board Support Package) patches organized by platform:

- **common/**: Common patches applicable across platforms
  - Device-specific patches for Intel mixins
  - SELinux policy updates
  - Build system modifications
  - Media and graphics HAL updates
  - Firmware files and licenses
  - Hardware interface updates

- **caas/**: CAAS-specific BSP patches
  - Platform-specific mixins
  - Kernel configuration updates
  - Performance tuning
  - Hardware-specific modifications

### Configuration Files

- **autopatch.sh**: Script for automatically applying patches
- **vendorsetup.sh**: Vendor setup script for build environment
- **x86_64_defconfig**: Default kernel configuration for x86_64 architecture

### Documentation

- **LICENSE**: Repository license file
- **TREE.md**: Complete repository tree structure (see below)

## Complete Repository Tree

For a complete visualization of all files and directories in this repository, see [TREE.md](TREE.md).

The tree includes:
- 180 directories
- 385 files

## Usage

This repository is designed to be integrated into an AOSP/Android build environment. The patches should be applied during the build process using the provided scripts.

### Applying Patches

Use the `autopatch.sh` script to apply patches:

```bash
./autopatch.sh
```

### Build Environment Setup

Source the vendor setup script to configure the build environment:

```bash
source vendorsetup.sh
```

## Patches Organization

Patches are organized by:
1. **Target**: AOSP vs BSP
2. **Platform**: Common, CAAS, AAOS
3. **Component**: Framework, hardware, packages, etc.

Each patch file follows the naming convention:
- `NNNN-<description>.patch` where NNNN is a sequence number

## License

See [LICENSE](LICENSE) file for licensing information.
