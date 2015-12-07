Lightmap 烘培
=============

场景准备
--------
1. 检查单体的Asset
		a. 导入场景前需要确保有且只有一套UV，并命名为“UVChannel_1”。

2. 将资产导入Maya进行拼装
		a. 保持材质命名不变，diffuse、emission、transparency等参数等值转换（工具实现）
		b. 根据需要对场景进行Lightmap分组，自动生成 UVChannel_3

3. 设置灯光，VRay参数
		a. Linear Workflow
		b. AA参数