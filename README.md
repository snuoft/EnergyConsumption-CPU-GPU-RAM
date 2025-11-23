# EnergyConsumption‑CPU‑GPU‑RAM

Measure, analyze, and understand the energy footprint of your code across CPU, GPU, and memory. This lightweight Python tool captures power consumption over time to help you optimize energy efficiency.

## Why Use This

- Identify which components (CPU, GPU, RAM) consume the most power.
- Profile the energy usage of machine learning workloads or high‑performance code.
- Track energy trends over time to inform optimizations or infrastructure decisions.

## Key Features

- Real‑time power monitoring for CPU, GPU, and RAM  
- Lightweight and non‑intrusive — minimal overhead  
- Logging to CSV for post‑analysis  
- Configurable sampling rate  
- Cross‑platform support (where underlying tools allow)  

## Requirements

- Python 3.7+  
- `psutil` for CPU/RAM metrics  
- NVIDIA GPU? Requires `pynvml` or NVML support  
- (Optional) Administrative or privileged access may be needed depending on hardware and OS

##Extensions & Ideas

This project is built to be extended. Some potential additions:

- Headless mode / daemon: Run the monitor in the background on a server.
- Dashboard integration: Stream the data into a web UI or Grafana.
- Notifications: Trigger alerts when power consumption exceeds a threshold.
- Batch profiling: Run energy measurements across multiple runs or workloads.
