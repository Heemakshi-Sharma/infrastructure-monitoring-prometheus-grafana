## Issue 1

### Problem

Docker container name already exists.

### Cause

A container with the same name had already been created.

### Resolution

Removed the existing container or used a different container name.


## Issue 2

### Problem

Prometheus configuration file could not be mounted.

### Cause

Incorrect file path while creating the Docker container.

### Resolution

Verified the file location and corrected the volume mount path.


## Issue 3

### Problem

Ubuntu virtual machine ran out of disk space.

### Cause

Limited virtual disk allocation.

### Resolution

Removed unnecessary files and cleaned Docker resources.


## Issue 4

### Problem

Prometheus and Packet Tracer could not communicate.

### Cause

Packet Tracer runs as a simulator and was hosted separately from the Ubuntu VM.

### Resolution

Completed deployment of the monitoring platform and documented future integration using SNMP Exporter and Node Exporter.
