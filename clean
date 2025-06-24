#!/bin/bash
#make -C buildroot distclean
#!/bin/bash

# Clean script for Buildroot project
# Runs make distclean inside the buildroot directory

set -e

# Path to the buildroot directory (relative path)
BUILDROOT_DIR=buildroot

echo "Running make distclean in ${BUILDROOT_DIR}..."

# Run make distclean inside buildroot
make -C ${BUILDROOT_DIR} distclean

echo "Buildroot cleaned successfully."
