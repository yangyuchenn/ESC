Pytorch code for [Robust Noisy Correspondence Learning with Equivariant Similarity Consistency](https://openaccess.thecvf.com/content/CVPR2024/papers/Yang_Robust_Noisy_Correspondence_Learning_with_Equivariant_Similarity_Consistency_CVPR_2024_paper.pdf) (CVPR2024)

If you have any questions about our work, please contact email yuchenyanggm@gmail.com.

Environments
---
Code is implemented based on original code provided by [BiCro](https://github.com/xu5zhao/BiCro) and [NCR](https://github.com/XLearning-SCU/2021-NeurIPS-NCR).

And you can refer to [NCR](https://github.com/XLearning-SCU/2021-NeurIPS-NCR) to create your virtual environment.

Datasets
---
#### MS-COCO and Flickr30K

We follow [SCAN](https://github.com/kuanghuei/SCAN) to obtain image features and vocabularies.

#### CC152K

We use CC152k dataset like [NCR](https://github.com/XLearning-SCU/2021-NeurIPS-NCR), and here is the [download link](https://ncr-paper.cdn.bcebos.com/data/NCR-data.tar).

Citation
---

If our work is helpful to you, please follow this paper:

```
@inproceedings{yang2024robust,
  title={Robust noisy correspondence learning with equivariant similarity consistency},
  author={Yang, Yuchen and Wang, Likai and Yang, Erkun and Deng, Cheng},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={17700--17709},
  year={2024}
}
