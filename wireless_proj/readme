# Energy Efficient Wireless Communication Using IoT Devices

**Overview**

Energy Efficient Wireless Communication is a MATLAB-based simulation that analyzes and compares four power-saving techniques for IoT networks in agricultural monitoring applications. The system models realistic wireless channel conditions, battery consumption, and network performance to determine the most effective strategy for prolonging device lifetime in remote deployments. The simulation demonstrates how different communication protocols balance energy efficiency with data transmission reliability.

**Features**

* **Multi-Technique Analysis**: Compares Duty Cycling, Adaptive Modulation & Coding (AMC), Wake-Up Receiver, and CSS (LoRa-like) techniques
* **Realistic Channel Modeling**: Incorporates path loss, fading, shadowing, and interference effects  
* **Energy Consumption Tracking**: Detailed battery drain analysis with component-specific power models
* **Performance Metrics**: Evaluates throughput, BER, connectivity, and energy efficiency simultaneously
* **Agricultural Context**: Optimized for soil moisture, temperature, humidity, and light sensor networks
* **Visual Analytics**: Generates comprehensive plots for network topology, battery life, and performance comparison
* **Multi-Criteria Decision**: Weighted scoring system to recommend optimal technique based on application requirements

**Installation**

* **Ensure MATLAB is installed**
```
MATLAB R2018b or later required
```

* **Download the source code**
```
# Download Wireless_Energy_Efficient.m to your local directory
```

* **Open MATLAB and navigate to project directory**
```
cd /path/to/project/directory
```

* **Run the simulation**
```
Wireless_Energy_Efficient()
```

**Usage**

* **Default Simulation**: Run with predefined parameters for 20 IoT nodes over 1 hour
* **Parameter Modification**: Edit simulation parameters in the code for custom scenarios
* **Results Analysis**: View generated plots and console output for performance comparison
* **Technique Selection**: Use the recommendation system output to choose optimal strategy

**Example Session**

```
>> Wireless_Energy_Efficient()

Simulating Energy Efficient Wireless Communication...
Network initialized with 20 nodes
Channel conditions updated...
Simulating communication techniques...

=== Final Results ===
Technique           Data(kb)    Battery(mAh)    Eff(kb/mAh)
Duty Cycle          145.2       847.3           0.95
AMC                 167.8       823.1           0.97
Wake-Up             134.6       889.4           1.22
CSS (LoRa-like)     198.4       794.5           0.96

Recommended Technique: Wake-Up Receiver (Score: 0.87)

Figures generated:
- Network Topology
- Battery Consumption Comparison  
- Network Throughput Comparison
- Error Performance Comparison
- Network Connectivity Over Time
```

**Simulation Parameters**

* **Network**: 20 IoT nodes, 1000 mAh battery capacity, 100m coverage area
* **Channel**: 2.4 GHz frequency, path loss exponent 3.5, Rayleigh fading
* **Techniques**: 4 power-saving strategies with realistic power consumption models
* **Duration**: 3600 seconds with 0.1s time steps for detailed analysis

**Results Summary**

| Technique | Best For | Energy Efficiency | Latency | Complexity |
|-----------|----------|------------------|---------|------------|
| Duty Cycling | Balanced performance | High | Moderate | Low |
| Enhanced AMC | Variable conditions | High | Low | High |
| Wake-Up Receiver | Ultra-low power | **Highest** | Moderate | Medium |
| CSS (LoRa-like) | Long range | High | High | Medium |

**Team 7**

* **Nalesh Kumar** 
* **Athithya**
* **Tilak** 
* **Tanush Krishna**

**Application Context**

Designed for IoT-based agriculture monitoring systems featuring soil moisture sensors, temperature/humidity sensors, light sensors, wireless communication modules, and gateway devices. The simulation addresses key challenges including limited power availability, communication range requirements, environmental interference, and network scalability in agricultural deployments.

**References**

Based on extensive research in wireless sensor networks, LoRa technology, and energy-efficient communication protocols for IoT applications in precision agriculture.
