# Kernel-HYM-WXX
适用于HONOR Magicbook 16 pro（HYM-WXX）的6.1.7内核配置，其中，AMD Ryzen 7 5800H CPU支持x86-64-v3指令集，可以使用`CFLAGS_=" -march=x86-64-v3 -mtune=native "`优化

## 可用设备：
- 无线网络：Qualcomm QCNFA765/ Atheros WCN685x -> ath11k
- 显卡：AMD Radeon Vega 8 -> amdgpu
- IOMMU： AMD IOMMU Version 2 -> iommu_v2
