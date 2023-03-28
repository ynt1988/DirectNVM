# DirectNVM
An open-source RTL NVMe controller IP for Xilinx FPGA.

## Profile
The repository contains a RTL project based on **[fpga-drive-aximm-pcie](https://github.com/fpgadeveloper/fpga-drive-aximm-pcie)**.  
And it also contains a loadable module and application API. With them, user can read/write Nvme SSD directly in application.  
The perfermance is better than kernel-single. The result details is stored in [result.csv](https://github.com/ynt1988/DirectNVM/blob/master/result/result.csv).    
The perfermance overview:  
![image](https://user-images.githubusercontent.com/11566120/228145932-29020ae2-fb32-4103-a601-7a869e6ca2bf.png)
