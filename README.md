# Swift-PCN

This repository provides the official PyTorch implementation for the following paper:

**SwiftPCN: Fast, Implementation-Efficient, and Accurate Point Cloud Completion Network with Flexible Output Resolution**<br>
[Kevin Tirta Wijaya](https://www.ktirta.xyz), [Dong-Hee Paek](http://ave.kaist.ac.kr/bbs/board.php?bo_table=sub1_2&wr_id=5&sca=Ph.+D.+Candidate), and [Seung-Hyun Kong](http://ave.kaist.ac.kr/)<br>

> **Abstract:** *Existing point cloud completion networks (PCCNs) have achieved remarkable completion accuracy, but often at the cost of inference speed and memory consumption. Furthermore, the networks' output resolution is often fixed, which could lead to a mismatched point density when the input scans are of different resolutions. In this work, we propose SwiftPCN, a pair of novel PCCNs that can recover the missing points accurately and efficiently. SwiftPCN consists of two novel networks: (1) SwiftPCN-fixed that achieves the most optimal trade-off between completion accuracy, inference latency, and number of parameters when compared with existing networks, and (2) SwiftPCN-flex that can generate point clouds of various resolution. In SwiftPCN-fixed, we utilize the prototypical encoder, a novel encoder that enables efficient modelling of binary interactions between input points. Meanwhile, in SwiftPCNflex, we propose an implementation-efficient occupancy network that extracts the implicit representation of point cloud using a simplified prototypical encoder and 2D convolutions.  We evaluate SwiftPCN networks on synthetic and real-world datasets, in which they successfully maintain competitive completion accuracy while reducing inference latency and number of parameters by 10-20 times compared with previous
state-of-the-art networks, demonstrating its suitability for real-world applications where resources are limited and real-time inference is necessary.*

**The codes will be made available after review.**
