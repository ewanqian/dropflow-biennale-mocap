# Drop Flow · 杭州双年展版 / Motion Capture & Stage Previs

钱誉文 Ewan Qian / VIRTURA 的《滴流 Drop Flow》双年展版工作坊资料。公开下载，用于查看数字舞台、方块人物与舞蹈动作的组织方式。

## 下载

文件放在 **GitHub Releases**，不需要 Git LFS。下载后用 Blender 打开。

- [DropFlow_Biennale_Block_Dancer_24fps_v1.blend](https://github.com/ewanqian/dropflow-biennale-mocap/releases/download/v1.0.0/DropFlow_Biennale_Block_Dancer_24fps_v1.blend) — 推荐：方块舞者独立工程，包含 Cube、Sphere、Sphere.001 与 Reference 骨架；33 骨骼、24 fps，动作位于 NLA。适合改人物与制作分镜。
- [DropFlow_Biennale_Raw_Mocap.zip](https://github.com/ewanqian/dropflow-biennale-mocap/releases/download/v1.0.0/DropFlow_Biennale_Raw_Mocap.zip) — 原始 BVH 动作数据（ZIP 无损压缩，解压后使用）。与舞台的 33 骨骼重定时版本不同，导入时请检查帧率与骨架映射，不要直接覆盖。
- [DropFlow_Biennale_Stage_Public_v1.blend](https://github.com/ewanqian/dropflow-biennale-mocap/releases/download/v1.0.0/DropFlow_Biennale_Stage_Public_v1.blend) — 完整舞台公开副本：保留舞台、人物、相机和 NLA 动作；24 fps，时间线 0–10484。部分外部视频、图片与声音未包含，不能直接还原完整演出。

## 使用说明

Blender 5.2.2 LTS 已重新打开验证：两个工程均有 33 骨骼、有效 NLA 动作、Cube 骨骼绑定；不同帧姿态发生变化。独立人物版只有 4 个对象，不包含舞台、灯光和相机，请自行添加。

舞台副本来自原有预演工程，未重新创作舞蹈。公开副本将外链改为相对占位路径，并移除内嵌文本；本机原文件未修改。外部素材列表见 dependencies.json，未打包素材不在本次发布范围内。

本次只发布数据与工程，不包含演出音轨、完整影像或舞者身份信息。暂未授予开放许可证；公开下载不等于允许商业使用、再分发或其他再授权。作品、表演与动作数据相关权利仍归各自权利人。需要再利用请联系发布者确认。

原始 BVH 的时间采样请以文件内 Frame Time 为准；舞台工程为重新定时版本。修改前请另存新文件。
