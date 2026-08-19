# 2026-013-NXUG学习

> NX/UG 学习资料，包含将 YD-ESP32-S3 开发板 STEP 导入 Siemens NX 得到的零件文件，以及对应的 IGES/STEP 交换模型

## 项目内容

1. **b-Module-GE**
通用交换格式三维模型：`_model2.igs`（IGES）、`_model2.stp`（STEP）。
2. **b-Module-NX**

- Siemens NX 零件（`.prt`）共 110 个，由 `YD-ESP32-S3 v34.step` 经 NX STEP AP203 转入，转换记录见 `YD-ESP32-S3 v34.log`；
- 模组与板级：ESP32-S3-WROOM（本体、外壳、过孔及镜像）、PCB、USB Type-C 6pin 母座、WS2812B、22 位排针；
- 阻容与封装：R0402、C0402、C1206、0805 LED（红 / 绿 / 琥珀）、QFN-16、SOT-23、SOT-223、DO220AA；
- 另有 `_model1.prt`、`_model2.prt`，以及阳极、阴极、灯体等拆分零件。

## 保留内容
- 本模板项目介绍：此为最初的准备的项目模板
    每个分支项目都会由他去继承
- 作者：Pinavia - 2025
