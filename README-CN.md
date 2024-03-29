# FluidS
[![license](https://img.shields.io/github/license/MuGeminorum/FluidS.svg)](https://www.gnu.org/licenses/gpl-3.0.en.html)
[![AppVeyor](https://img.shields.io/appveyor/ci/MuGeminorum/FluidS.svg?logo=appveyor)](https://ci.appveyor.com/project/MuGeminorum/FluidS)
[![Github All Releases](https://img.shields.io/github/downloads/MuGeminorum/FluidS/total.svg)](https://github.com/MuGeminorum/FluidS/releases)
[![GitHub release](https://img.shields.io/github/release/MuGeminorum/FluidS.svg)](https://github.com/MuGeminorum/FluidS/releases/latest)

其仿真过程的核心算法参考了 Robert Bridson 的 <i>Fluid Simulation for Computer Graphics</i>。它使用 Navier-Stokes 方程的数值解来预测 Qt 的 OpenGL 小部件中显示的每一帧中粒子的密度和速度分布。有两种分辨率可供用户选择：64 × 64 和 128 × 128。用户还可以在 7 种颜色的密度和速度之间切换显示模式。

| ![fsd](https://user-images.githubusercontent.com/20459298/233125917-4eb82aec-a305-4e92-8bb7-88fb5f52d775.PNG) | ![fsv](https://user-images.githubusercontent.com/20459298/233125957-1e9ed77d-85f5-40a5-873d-86efc9adba2f.PNG) |
| :-----------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------: |
|                                                  **密度场**                                                   |                                                  **速度场**                                                   |

## 代码下载
```bash
git clone https://github.com/MuGeminorum/FluidS.git
```

## 环境安装配置及代码调试发布
此部分内容请统一参考此[博文](https://www.cnblogs.com/MuGeminorum/p/17017055.html)


## 许可证
<a href="https://opensource.org/licenses/GPL-3.0" target="_blank">
    <img src="https://www.gnu.org/graphics/gplv3-127x51.png" />
</a>

