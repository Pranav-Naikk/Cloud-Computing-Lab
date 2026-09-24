---

# Experimental Results

## Type-1 Hypervisor — Proxmox VE

The following screenshots document the Type-1 hypervisor experiment performed using Proxmox VE.

### Proxmox VE Dashboard

![Proxmox Dashboard](Screenshots/type1-proxmox/01-proxmox-dashboard.png)

### Proxmox VM Configuration

![Proxmox VM Configuration](Screenshots/type1-proxmox/02-proxmox-vm-configuration.png)

### Proxmox VM Running

![Proxmox VM Running](Screenshots/type1-proxmox/03-proxmox-vm-running.png)

### Ubuntu Console

![Proxmox Ubuntu Console](Screenshots/type1-proxmox/04-proxmox-ubuntu-console.png)

### System Configuration

![Proxmox System Configuration](Screenshots/type1-proxmox/05-proxmox-system-configuration.png)

### Sysbench Result

![Proxmox Sysbench Result](Screenshots/type1-proxmox/06-proxmox-sysbench-result.png)

### Resource Monitoring

![Proxmox Resource Monitoring 1](Screenshots/type1-proxmox/07-proxmox-resource-monitoring_1.png)

![Proxmox Resource Monitoring 2](Screenshots/type1-proxmox/07-proxmox-resource-monitoring_2.png)

![Proxmox Resource Monitoring 3](Screenshots/type1-proxmox/07-proxmox-resource-monitoring_3.png)

![Proxmox Resource Monitoring 4](Screenshots/type1-proxmox/07-proxmox-resource-monitoring_4.png)

---

# Type-2 Hypervisor — VMware Workstation

The following screenshots document the Type-2 hypervisor experiment performed using VMware Workstation.

### VMware VM Configuration

![VMware VM Configuration](Screenshots/type2-vmware/01-vmware-vm-configuration.jpeg)

### VMware VM Running

![VMware VM Running](Screenshots/type2-vmware/02-vmware-vm-running.jpeg)

### VMware System Configuration

![VMware System Configuration](Screenshots/type2-vmware/03-vmware-system-configuration.jpeg)

### VMware Sysbench Result

![VMware Sysbench Result](Screenshots/type2-vmware/04-vmware-sysbench-result.jpeg)

---

# CPU Performance Comparison

## CPU Throughput Comparison

The CPU throughput comparison between Proxmox VE and VMware Workstation is shown below.

![CPU Throughput Comparison](../images/cpu-throughput-comparison.jpeg)

### Recorded Throughput

| Hypervisor | Events Per Second |
|---|---:|
| Proxmox VE | 1749.16 EPS |
| VMware Workstation | 707.43 EPS |

---

## CPU Latency Comparison

The average CPU latency comparison between Proxmox VE and VMware Workstation is shown below.

![CPU Latency Comparison](../images/cpu-latency-comparison.jpeg)

### Recorded Latency

| Hypervisor | Average Latency |
|---|---:|
| Proxmox VE | 0.57 ms |
| VMware Workstation | 1.41 ms |

---

# Performance Summary

| Metric | Proxmox VE | VMware Workstation |
|---|---:|---:|
| CPU Throughput | 1749.16 EPS | 707.43 EPS |
| Average Latency | 0.57 ms | 1.41 ms |

---

# Result

The benchmark results obtained from the experiment are documented through the Proxmox VE and VMware Workstation screenshots and the CPU performance comparison graphs.

The throughput and latency measurements provide the basis for comparing the CPU performance of the virtual machines under the two hypervisor environments.

---

# Conclusion

The experiment demonstrates the practical process of configuring virtual machines under Type-1 and Type-2 hypervisors and evaluating their CPU performance using Sysbench.

The complete configuration screenshots, benchmark outputs, throughput comparison, and latency comparison are included above for reference.
