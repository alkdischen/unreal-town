# unreal-town
42期prp

基于UE4与unrealcv的城镇环境

## 基础配置

**UE4版本**：4.22.3
**Python版本**：3.8

## 环境内容

- **环境位于：**`\content\AssetsvilleTown\Maps\Demostration`, 双击即可打开。

>特别的，由于Github不方便上传大内存文件，因此将demostration.uasset进行了压缩，需要提前解压

- **车流蓝图类位于：**`\content\Spline_Car\Spline_carFlow`

- **人物蓝图类位于：**`\content\Spline_Car\SplineTools\Spline_ManFlow`

- **人物随机蓝图类位于：** `\content\ai-random\renwuB\renwuB_random`

## 使用

- 车流/人物蓝图拖入环境，在右下设置即可。
- 人物蓝图需要同时导入人物模型和骨骼，同时在左边搜索 `Nav Mesh Bounds Volume` 导入环境，人物即可在限制范围内进行移动。