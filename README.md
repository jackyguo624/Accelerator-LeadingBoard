
| XPU  | Manu   | Arch   | FP32 (TF) | FP16 (TF)    | FP8(TF) | Memory(GB) | Memroy BW(TB/s) | Inter-Card BW(GB/s)                | PCIe |
| ---- | ------ | ------ | --------- | ------------ | ------- | ---------- | --------------- | ---------------------------------- | ---- |
| H200 | Nvidia | Hopper | 989       | 1979         | 3958    | 141        | 4.8             | 64(PCIe)/400Gb(ib-cx7)/900(NVLink) | Gen5 |
| A800 | A800   | Ampere | 312       | 624          |         | 40/80      | 1.88            | 64(PCIe)/400Gb(ib-cx7)/400(NVLink) | Gen4 |
| H20  | Nvidia | Hopper | 74        | 148          | 296     | 96         | 4.0             | 64(PCIe)/400Gb(ib-cx7)/900(NVLink) | Gen5 |
| 4090 | Nvidia | Ada    | 83        | 330          | 660     | 24         | 1 (DDR6)        | 32(PCIe)/400Gb(ib-cx7)/            | Gen4 |
| 3090 | Nvidia | Ampere | 35        | 142          | /       | 24         | 0.87(900GB)     | 32(PCIe)/400Gb(ib-cx7)/            | Gen4 |
| V100 | Nvidia | Volta  | 14        | ?            | /       | 32/16      | 0.87(900GB)     | 32(PCIe)/400Gb(ib-cx7)/            | Gen4 |
| 910B | Ascend | Da V   | 94        | 376/320/200? | 640     | 64         | 0.78(800GB)     | 392(HCCL)?/400Gb(ib-cx7)/          | Gen5 |


ref: 
![V100/A100/H100](https://www.cnblogs.com/upyun/p/17817417.html)
![H20](https://blog.csdn.net/Jamence/article/details/145801570)
![910A/B/C/D](https://zhuanlan.zhihu.com/p/1901246123114464301)
![4090 vs 3090](https://blog.csdn.net/qq_35082030/article/details/138716559)
![3090bw](https://www.itcreations.com/nvidia-gpu/nvidia-geforce-rtx-3090-gpu)
![910B/H20/A100/H100/H200](https://blog.csdn.net/qq_42068614/article/details/146016873)
![H200](https://nvdam.widen.net/s/nb5zzzsjdf/hpc-datasheet-sc23-h200-datasheet-3002446)
![IB](https://zhuanlan.zhihu.com/p/673903240)
![A800](https://www.nvidia.com/zh-tw/products/workstations/a800/)
![A800](https://blog.csdn.net/sinat_39620217/article/details/135916437?spm=1001.2101.3001.6650.2&utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromBaidu%7EPaidSort-2-135916437-blog-146016873.235%5Ev43%5Econtrol&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromBaidu%7EPaidSort-2-135916437-blog-146016873.235%5Ev43%5Econtrol&utm_relevant_index=4)
![A800](https://resources.nvidia.com/en-us-briefcase-for-datasheets/proviz-a800-40gb-dat?ncid=no-ncid)
# Accelerator-LeadingBoard
