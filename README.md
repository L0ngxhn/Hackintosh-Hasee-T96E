# 作者已经更换了m1芯片的mbp。所以该仓库不再维护！ 保留EFI供用兴趣的人参考使用


# Hackintosh-Hasee-T96E（clove p95xer/ep）
  这是神舟精盾系列T96E型号的黑苹果EFI仓库-clove p95xer/ep  
    **理论上神舟精盾系列8代标压CPU笔记本均可使用**  
    
    
### 套用该EFI前请先更新bios版本  
  测试不同的bios版本可能导致不可预料的问题，所以请先更新bios[下载地址](http://kfgl.hasee.com/bios/bios_nb/P95xEP%20ER6_B10RHA2精盾/P95xEP%20ER6_B10RHA2精盾.zip)
  
#### CFG解锁  
   CFG Lock: 0x5C2  
   解锁代码：setup_var_3 0x5C2 0x0
  
  ### 配置信息如下：
   CPU: Intel i7-8750H  
   内存：16GB  
   核心显卡：UHD630  
   独立显卡：GTX1060（无法驱动  
   声卡：ALC1220  
   硬盘：KINGSTON RBUSNS8154P3256GJ（SSD）   
   无线网卡：博通 BCM94352Z  
   
  ### 系统版本：Big Sur 11.2  
  
---
## 贡献者&鸣谢：
  1.感谢黑果小兵提供的镜像文件  
  2.感谢kirainmoe提供的同类EFI作为参考[仓库](https://github.com/kirainmoe/hasee-tongfang-macos)  
