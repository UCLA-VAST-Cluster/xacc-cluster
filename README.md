# UCLA VAST XACC Cluster

### Public Servers

| Server | CPU        | Memory | Additional Resource                            |
| :-:    | :-:        | :-:    | :-:                                            |
| `n0`   | `2680v4`×2 | `64G`  | `7V3` `240G SSD`×2 `800G SSD` `4T HDD`×2       |
| `n1`   | `2680v4`×2 | `64G`  | `7V3` `KU3` `240G SSD`×2 `4T HDD`×2            |
| `n2`   | `2680v4`×2 | `256G` | `7V3` `240G SSD`×2 `4T HDD`×2                  |
| `n5`   | `2680v4`×2 | `512G` | `7V3` `K1200` `240G SSD`×2 `4T HDD`×2          |
| `n6`   | `2680v4`×2 | `256G` | `7V3` `K1200` `240G SSD`×2 `4T HDD`×2          |
| `n7`   | `2680v4`×2 | `512G` | <del>`7V3`</del> `K1200` `240G SSD` `4T HDD`×2 |
| `n10`  | `2680v4`×2 | `128G` | `4T HDD`×4                                     |
| `n11`  | `2699v3`×2 | `128G` | `240G SSD`×2 `800G SSD` `4T HDD`×4             |
| `n12`  | `2699v3`×2 | `128G` | `240G SSD`×2 `4T HDD`×5                        |
| `n13`  | `2699v3`×2 | `128G` | `800G SSD` `4T HDD`×2                          |
| `n14`  | `2699v3`×2 | `112G` | `240G SSD`×2 `4T HDD`                          |
| `n15`  | `2699v3`×2 | `128G` | `240G SSD`×2 `4T HDD`                          |
| `n16`  | `2699v3`×2 | `128G` | `240G SSD`×2 `4T HDD`                          |
| `n17`  | `2680v4`×2 | `256G` | `240G SSD`×2 `800G SSD` `4T HDD`×2             |
| `n18`  | `2680v4`×2 | `256G` | `240G SSD`×2 `800G SSD` `4T HDD`×2             |
| `n19`  | `2680v4`×2 | `64G`  | `7v3` `240G SSD`×2 `4T HDD`×2                  |
| `n20`  | `2680v4`×2 | `256G` | `240G SSD`×2 `4T HDD`×2                        |
| `n21`  | `6244`×2   | `96G`  | `U50` `U200` `U250` `U280`                     |
| `n22`  | `6244`×2   | `192G` | `U50` `U250`×2 `U280`                          |
| `n23`  | `6244`×2   | `384G` | `U250`×2 `U280`                                |
| `jc1`  | `4807`×4   | `128G` | `320G HDD` `4T HDD`                            |
| `jc2`  | `4807`×4   | `128G` | `DE5a-net` `320G HDD` `4T HDD`                 |
| `jc3`  | `2680v4`×2 | `68G`  | `DE5a-net`×2 `K40`                             |
| `jc5`  | `2680v4`×2 | `72G`  | `VCU1525` `Stratix10`                          |
| `jc8`  | `2680v4`×2 | `80G`  | `U280` `A100`                                  |

### Controller Servers

Those servers are not for computation uses but only administrative.  They may act as Ceph monitors, etc.

| Server | CPU        | Memory | Additional Resource           |
| :-:    | :-:        | :-:    | :-:                           |
| `n100` | `2620`×2   | `252G` | `6T HDD x 12` `4T HDD x 2`    |
| `n101` | `2420`×2   | `96G`  | `7v3` `4T HDD`×4              |
| `n102` | `2420`×2   | `96G`  | <del>`7v3`</del> `4T HDD`×4   |
| `n103` | `2680v4`×2 | `256G` | `7V3` `240G SSD`×2 `4T HDD`×2 |
| `n104` | `2680v4`×2 | `64G`  | `7V3` `240G SSD`×2 `4T HDD`×2 |

### Legend

+ `2680v4`: [Intel Xeon E5-2680 v4 CPU](https://ark.intel.com/products/91754/Intel-Xeon-Processor-E5-2680-v4-35M-Cache-2_40-GHz)
+ `2699v3`: [Intel Xeon E5-2699 v3 CPU](https://ark.intel.com/products/81061/Intel-Xeon-Processor-E5-2699-v3-45M-Cache-2_30-GHz)
+ `2420`: [Intel Xeon E5-2420 CPU](https://ark.intel.com/products/64617/Intel-Xeon-Processor-E5-2420-15M-Cache-1_90-GHz-7_20-GTs-Intel-QPI)
+ `4807`: [Intel Xeon E7-4807 CPU](https://ark.intel.com/products/53569/Intel-Xeon-Processor-E7-4807-18M-Cache-1_86-GHz-4_80-GTs-Intel-QPI)
+ `6244`: [Intel Xeon Gold 6244 CPU](https://ark.intel.com/content/www/us/en/ark/products/192442/intel-xeon-gold-6244-processor-24-75m-cache-3-60-ghz.html)
+ `7V3`: [Alpha Data ADM-PCIE-7V3 board](https://www.alpha-data.com/dcp/products.php?product=adm-pcie-7v3)
+ `KU3`: [Alpha Data ADM-PCIE-KU3 board](https://www.alpha-data.com/dcp/products.php?product=adm-pcie-ku3)
+ `VCU1525`: [Xilinx VCU1525 board](https://www.xilinx.com/products/boards-and-kits/vcu1525.html)
+ `U50`: [Xilinx Alveo U50 board](https://www.xilinx.com/products/boards-and-kits/u50.html)
+ `U200`: [Xilinx Alveo U200 board](https://www.xilinx.com/products/boards-and-kits/u200.html)
+ `U250`: [Xilinx Alveo U250 board](https://www.xilinx.com/products/boards-and-kits/u250.html)
+ `U280`: [Xilinx Alveo U280 board](https://www.xilinx.com/products/boards-and-kits/u280.html)
+ `DE5a-net`: [Teraisc DE5a-net board](https://www.terasic.com.tw/_sub/de5a-net)
+ `Stratix10`: [Altera Stratix 10 board](https://www.altera.com/products/boards_and_kits/dev-kits/altera/kit-s10-fpga.html)
+ `K1200`: [Nvidia Quadro K1200 card](https://images.nvidia.com/content/quadro/product-literature/data-sheets/11306_DS_NV_Quadro_K1200_FEB15_NV_US_HR.pdf)
+ `K40`: [Nvidia Telsa K40 card](https://www.nvidia.com/content/PDF/kepler/nvidia-tesla-k40.pdf)
+ `A100`: [Nvidia A100 PCIe 40G card](https://www.nvidia.com/content/dam/en-zz/Solutions/Data-Center/a100/pdf/A100-PCIE-Prduct-Brief.pdf)

## Board Allocation

+ `7V3`: 9 in `n0` `n1` `n2` `n3` `n4` `n5` `n6` `n9` `n19`
+ `KU3`: 1 in `n1`
+ `VCU1525`: 1 in `jc5`
+ `U50`: 1 in `n21`, 1 in `n22`
+ `U200`: 1 in `n21`
+ `U250`: 1 in `n21`, 2 in `n22`, 2 in `n23`
+ `U280`: 1 in `n21`, 1 in `n22`, 1 in `n23`, 1 in `jc8`
+ `DE5a-net`: 1 in `jc2`, 2 in `jc3`
+ `K1200`: 3 in `n5` `n6` `n7`
+ `K40`: 1 in `jc3`
+ `A100`: 1 in `jc8`
