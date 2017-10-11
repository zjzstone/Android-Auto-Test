# 欢迎进入Android自动化测试
@(我的第一个笔记本)[android|测试用例]
> Android自动化测试的实现可以从[Google Developers](https://developer.android.google.cn/training/testing/index.html)上找到测试用例

---
[TOC]

## 测试金字塔

### Small tests
**Small tests**叫**小测试**，也叫**单元测试**。通常模拟每个主要组件的单独测试，是脱离**模拟器**或**实际设备**。
- [Robolectric](http://robolectric.org/)
- [Mockito](http://site.mockito.org/)

### Medium tests
**Medium tests**叫**介质测试**，介于Small tests和Large tests之间，是需要依靠**模拟器**或**实际设备**，测试多个组件在不同硬件屏幕尺寸下的效果。
- **服务测试**
- **集成测试**
- **UI测试**

### Large tests
**Large tests**叫**UI工作流测试**，根据预期设定的效果来仿真或实际设备上完成一系列的UI测试，各个测试用例是分开的，互不影响。
- [JUnit](http://junit.org/junit4/)
- [Espresso](https://developer.android.google.cn/training/testing/espresso/index.html)
- [UI Automator](https://developer.android.google.cn/training/testing/ui-automator.html)
