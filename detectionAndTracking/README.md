本项目使用 Azure Kinect 深度相机作为输入设备， 对目标物体实现实时检测和跟踪。
对于目标物体的检测，使用了Gorunding DINO模型， 对于目标物体的跟踪，则使用了foundation pose 模型。 目前两个模型都是基于pytorch实现的, 后续将用mindspore进行改写，并迁移权重。

## 相关链接
- [Azure Kinect DK](https://learn.microsoft.com/zh/azure/kinect-dk/)
- [Grounding DINO](https://github.com/IDEA-Research/GroundingDINO)
- [Foundation Pose](https://github.com/NVlabs/FoundationPose)