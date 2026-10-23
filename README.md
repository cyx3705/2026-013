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

### logo与作者

- 作者：pinavia
- ![logo](./Logo.png)

### 学习许可与权利保留

- 本项目允许个人、学校和研究者进行非商业性的学习、研究和引用。
- 未经著作权人书面许可，不得将项目内容用于商业开发、产品制造、商业服务、商业宣传、投标交付、毕业设计成品交付或再授权。
- 不得删除作者、来源、版本历史和第三方许可证声明，不得将本项目或其衍生成果宣称为与作者无关的原创项目。
- 软件源码适用 [PolyForm Noncommercial 1.0.0](https://polyformproject.org/licenses/noncommercial/1.0.0/)；机械模型、PCB、原理图、图片、文档、Unity 工程和其他非软件资料适用 [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/)。
- SE、SW、STEP/STP 及其他三维模型仅允许个人或学校进行非商业学习、评审和研究；未经著作权人书面许可，不得用于加工、打样、制造、销售、量产、投标、产品交付、商业宣传、改作或再授权。
- 第三方组件、模板、元件库、外购件模型和工具仍受其原始许可证约束；本声明不扩大作者对第三方内容的权利。

商业使用、产品化、公司内部长期使用、转让或排他性授权需另行取得著作权人的书面许可。
