---
title: "Deep fusionnet for point cloud semantic segmentation"
collection: publications
permalink: /publication/2020-10-1-deep_fusion
excerpt: 'Many point cloud segmentation methods rely on transferring irregular points into a voxel-based regular representation. Although voxel-based convolutions are useful for feature aggregation, they produce ambiguous or wrong predictions if a voxel contains points from different classes. Other approaches (such as PointNets and point-wise convolutions) can take irregular points for feature learning. But their high memory and computational costs (such as for neighborhood search and ball-querying) limit their ability and accuracy for large-scale point cloud processing. To address these issues, we propose a deep fusion network architecture (FusionNet) with a unique voxel-based ??mini-PointNet?? point cloud representation and a new feature aggregation module (fusion module) for large-scale 3D semantic segmentation. Our FusionNet can learn more accurate point-wise predictions when compared to voxel d convolutional networks. It can realize more effective feature aggregations
with lower memory and computational complexity for large-scale point
cloud segmentation when compared to the popular point-wise convolutions. Our experimental results show that FusionNet can take more than
one million points on one GPU for training to achieve state-of-the-art
accuracy on large-scale Semantic KITTI benchmark. The code will be
available at https://github.com/feihuzhang/LiDARSeg.'
date: 2020-10-1
venue: 'ECCV 2020'
paperurl: 'https://ora.ox.ac.uk/objects/uuid:80c17ed9-01ef-486e-bea5-962cc4b56528/download_file?safe_filename=Deep%2520FusionNet.pdf&type_of_work=Conference+item'
citation: 'Zhang, Feihu, Jin Fang, Benjamin Wah, and Philip Torr. &quot;Deep fusionnet for point cloud semantic segmentation.&quot; In Computer Vision?CECCV 2020: 16th European Conference, Glasgow, UK, August 23?C28, 2020, Proceedings, Part XXIV 16, pp. 644-663. Springer International Publishing, 2020.'
---

<a href='https://ora.ox.ac.uk/objects/uuid:80c17ed9-01ef-486e-bea5-962cc4b56528/download_file?safe_filename=Deep%2520FusionNet.pdf&type_of_work=Conference+item'>Download paper here</a>

Many point cloud segmentation methods rely on transferring irregular points into a voxel-based regular representation. Although voxel-based convolutions are useful for feature aggregation, they produce ambiguous or wrong predictions if a voxel contains points from different classes. Other approaches (such as PointNets and point-wise convolutions) can take irregular points for feature learning. But their high memory and computational costs (such as for neighborhood search and ball-querying) limit their ability and accuracy for large-scale point cloud processing. To address these issues, we propose a deep fusion network architecture (FusionNet) with a unique voxel-based ??mini-PointNet?? point cloud representation and a new feature aggregation module (fusion module) for large-scale 3D semantic segmentation. Our FusionNet can learn more accurate point-wise predictions when compared to voxel d convolutional networks. It can realize more effective feature aggregations
with lower memory and computational complexity for large-scale point
cloud segmentation when compared to the popular point-wise convolutions. Our experimental results show that FusionNet can take more than
one million points on one GPU for training to achieve state-of-the-art
accuracy on large-scale Semantic KITTI benchmark. The code will be
available at https://github.com/feihuzhang/LiDARSeg.

Recommended citation: 
Zhang, Feihu, Jin Fang, Benjamin Wah, and Philip Torr. "Deep fusionnet for point cloud semantic segmentation." In Computer Vision?CECCV 2020: 16th European Conference, Glasgow, UK, August 23?C28, 2020, Proceedings, Part XXIV 16, pp. 644-663. Springer International Publishing, 2020.