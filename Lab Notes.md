# 28-08-2025
# Data for Lab 2
# 1 - 
# 2 - Diode Rectifiers
## 2.1 - Half-Wave Rectifier with Resistive Load
$$V_{dc(theoretical)} = V$$
$$V_{dc(measured)}= 9.6V,\:I_{dc}= 500\mu A$$
### 
###
## 2.2 - Full-Wave Rectifier with Resistive and Inductive Load
Resistive Load
$$V_{dc(measured)}= 8.3V,\:I_{dc}= 338 mA$$

Inductive Load
$$V_{dc(measured)}= 8.4V,\:I_{dc}= 332 mA$$
Measured $V_{D1}\:and\:V_{D2}$

###
###
###
###
###
###
## 2.3 - Full-Wave Rectifier with Capacitive Output Filter and Resistive Load
$$V_{pp}=\dfrac{I_{dc}}{2fC}$$
470 cap
$$V_{dc}=2.1V,\:I_{dc}=477mA$$
$$V_{pp}=7V$$
1000 cap
$$V_{dc}=1.2V,\:I_{dc}=520mA$$
$$V_{pp}=4.4V$$
2000 cap
$$V_{dc}=0.5V,\:I_{dc}=5322mA$$
$$V_{pp}=2.35V$$

###
###
###
###
# 3 - Thyristor Controlled Rectifiers
## 3.1 
## 3.2 - Semi-Converter with Resistive and Inductive Load

| Firing angle (α) | Digital multimeter Vₒ | Digital multimeter Iₒ | Calculated Vₒ |
|------------------|-----------------------|-----------------------|---------------|
| 0                | 0                     | 0                     |               |
| 20               | 0.8                   | 0.8                   |               |
| 45               | 3.4                   | 20                    |               |
| 60               | 5.6                   | 63                    |               |
| 90               | 9.7                   | 159                   |               |
| 100              | 10.2                  | 184                   |               |
| 120              | 10.9                  | 247                   |               |
| 140              | 10.6                  | 285                   |               |
| 160              | 9.5                   | 317                   |               |
| 180              | 8.8                   | 333                   |               |

/Detail the way you connected your oscilloscope probes and configured the oscilloscope to record simultaneously the source voltage, trigger signal, output voltage and current waveforms/
We made our commoon point where the + v_out is. Ch1 is the secondary transformer output. Ch2 is at the bottom of v_out. Ch3 is between 1\Omega and 47\Omega. Ch4 is + trigger input.

/Based on your observation, at what firing angle did you observe there to first be a boundary between continuous and discontinuous conduction (of current in the load). Compare to what you might expect from a theoretical view point?/
$100^o$

