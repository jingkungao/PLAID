# PLAID
This repository contains the code to parse [PLAID dataset](http://www.plaidplug.com) and run analysis for load identification research. More open source code using PLAID for analysis can be found [here](https://github.com/LeenDB/PLAID).

## Dataset Description
PLAID currently includes current and voltage measurements sampled at 30 kHz from 11 different appliance types present in more than 60 households in Pittsburgh, Pennsylvania, USA. Data collection took place during the summer of 2013, and winter of 2014. Each appliance type is represented by dozens of different instances of varying make/models. For each appliance, three to six measurements were collected for each state transition. These measurements were then post-processed to extract a few-second-long window containing both the steady-state operation and the startup transient (when available). Measurements with significant noise in the voltage due to measurement errors were removed, after which we were left with 1074 instances in PLAID 1 and 719 instances in PLAID 2.

### PLAID 1 Statistics
|           Appliance Type|	# Appliances	|# Instances|
|:----:|:----:|:----:|
|          Air Conditioner|	        14	|        66|
| Compact Fluorescent Lamp|	        31	|       175|
|                      Fan|	        23	|       115|
|                   Fridge|	        21	|        38|
|                Hairdryer|	        32	|       156|
|                   Heater|	         7	|        35|
|  Incandescent Light Bulb|	        23	|       114|
|                   Laptop|	        34	|       172|
|                Microwave|	        28	|       139|
|                   Vacuum|	         8	|        38|
|          Washing Machine|	         9	|        26|
|   |   |   |
|                    Total|	       230	|      1074|

### PLAID 2 Statistics
|           Appliance Type|	# Appliances	|# Instances|
|:----:|:----:|:----:|
|          Air Conditioner|	         7	|       142|
| Compact Fluorescent Lamp|	         9	|        45|
|                      Fan|	         7	|        95|
|                   Fridge|	         9	|        52|
|                Hairdryer|	         5	|        92|
|                   Heater|	         6	|        50|
|  Incandescent Light Bulb|	         7	|        34|
|                   Laptop|	         7	|        35|
|                Microwave|	         9	|        90|
|                   Vacuum|	         7	|        35|
|          Washing Machine|	         9	|        49|
|   |   |   |
|                    Total|	        82	|       719|


### Data Download

The dataset can be downloaded [here](http://plaidplug.com/static/dataset/Plaid.tar.gz).

## References

- Gao, Jingkun, Suman Giri, Emre Can Kara, and Mario Bergés. "PLAID: a public dataset of high-resolution electrical appliance measurements for load identification research: demo abstract." In proceedings of the 1st ACM Conference on Embedded Systems for Energy-Efficient Buildings, pp. 198-199. ACM, 2014.
- Gao, Jingkun, Emre Can Kara, Suman Giri, and Mario Bergés. "A feasibility study of automated plug-load identification from high-frequency measurements." In Signal and Information Processing (GlobalSIP), 2015 IEEE Global Conference on, pp. 220-224. IEEE, 2015.
- De Baets, Leen, G. Jingkun, Chris Develder, Tom Dhaene, M. Berges, and Dirk Deschrijver. "Handling imbalance in an extended PLAID." In SustainIT 2017, the 5th IFIP Conference on Sustainable Internet and ICT for Sustainability, pp. 1-5. 2017.
- Medico, Roberto, Leen De Baets, Jingkun Gao, Suman Giri, Emre Kara, Tom Dhaene, Chris Develder, Mario Bergés, and Dirk Deschrijver. "A voltage and current measurement dataset for plug load appliance identification in households." Scientific Data 7, no. 1 (2020): 1-10.
