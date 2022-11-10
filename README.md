# MSI-H97_PC_MATE-i7_4790-OpenCore_0.8.5
古老平台，无UEFI启动MacOS，最高支持Monterey。



第一步：写入U盘/硬盘0磁道，模拟UEFI启动（这个需要手头有现有的MacOS系统了。。。。）
      具体可参考：https://www.douyin.com/video/7080091876795108621

第二步：windows系统下面定制USB，生成USBPorts.kext。
      具体可参考：https://github.com/USBToolBox/tool

第三步：将下载的EFI拖入启动盘根目录，写入三码，并用第二步生成的的USBPorts.kext进行替换。


我用的是免驱显卡，没有注入核显，没空折腾了，没独显的自己琢磨着来吧；）
