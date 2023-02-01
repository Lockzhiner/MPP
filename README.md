# 安装MPP
## 版本

|文档版本|修改人|修改内容简介|
|-|-|-|
|0_0_0|郑必城|初步完成文档编写|


## 简介

Toybrick中的MPP库版本为1.4.0但是最新的MPP库版本应该为1.5.0+，由于MPP库是开源的，因此最好自己编译一个MPP

## 安装过程

```Bash
git clone https://github.com/Lockzhiner/MPP.git
cd MPP/build/linux/aarch64
./make-Makefiles.bash
make -j3
sudo make install
```