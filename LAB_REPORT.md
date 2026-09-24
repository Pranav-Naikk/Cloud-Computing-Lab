\# Cloud Computing Laboratory Report



\## Student Information



| Field | Details |

|---|---|

| Name | Pranav Naik |

| Course | Cloud Computing |

| Laboratory | Cloud Computing Laboratory |

| University | KLE Technological University |



\---



\# Experiment 01 — Performance Analysis of Type-1 and Type-2 Hypervisors



\## Aim



To create identically configured virtual machines on a Type-1 hypervisor and a Type-2 hypervisor and compare their CPU performance using the Sysbench CPU benchmark.



\## Hypervisors Used



| Type | Hypervisor |

|---|---|

| Type-1 | Proxmox VE |

| Type-2 | VMware Workstation |



\## Guest Operating System



Ubuntu Linux



\## Benchmark



Sysbench CPU benchmark was used to measure CPU performance in the virtualized environments.



\## Performance Metrics



The experiment considers:



\- Execution time

\- Total events

\- Events per second

\- Average latency



\## Results



\### CPU Throughput



The recorded benchmark results show:



| Environment | Events per Second |

|---|---:|

| Proxmox VE | 1749.16 EPS |

| VMware Workstation | 707.43 EPS |



!\[CPU Throughput Comparison](images/cpu-throughput-comparison.jpeg)



\### Average Latency



| Environment | Average Latency |

|---|---:|

| Proxmox VE | 0.57 ms |

| VMware Workstation | 1.41 ms |



!\[CPU Latency Comparison](images/cpu-latency-comparison.jpeg)



\## Experiment Documentation



The complete experiment procedure, configuration details, screenshots, and supporting results are available in:



\[Experiment 01 – Hypervisor Analysis](Experiment-01-Hypervisor-Analysis/README.md)



\## Conclusion



The experiment provides a practical comparison of CPU performance for virtual machines running under Type-1 and Type-2 hypervisor environments.



The benchmark results and observations are documented in the Experiment 01 directory.



\---



\# Future Experiments



Additional Cloud Computing laboratory experiments will be added to this repository as they are completed.

