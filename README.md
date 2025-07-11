# BHSD: A 3D Multi-class Brain Hemorrhage Segmentation Dataset

Authors: [Biao Wu](https://scholar.google.com/citations?user=Y3SBBWMAAAAJ&hl=en), [Yutong Xie](https://v3alab.github.io/author/yutong-xie/), [Zeyu Zhang](https://steve-zeyu-zhang.github.io), [Jinchao Ge](https://github.com/jinchaogjc), [Kaspar Yaxley](https://radiopaedia.org/users/kaspar-lewis-yaxley?lang=us), [Suzan Bahadir](https://au.linkedin.com/in/suzan-bahadir-57870416b), [Qi Wu](http://www.qi-wu.me/), [Yifan Liu](https://scholar.google.com/citations?user=ksQ4JnQAAAAJ&hl=zh-CN), [Minh-Son To](https://www.flinders.edu.au/people/minhson.to)*

*Corresponding author

<em><b>MLMI 2023</b></em>
 
[[Paper](https://doi.org/10.1007/978-3-031-45673-2_15)] [arXiv [v1](https://arxiv.org/abs/2308.11298v1) [v2](https://arxiv.org/abs/2308.11298.pdf)] [[Dataset](https://huggingface.co/datasets/WuBiao/BHSD)] [[BibTeX](https://github.com/White65534/BHSD/tree/main#citation)]

Intracranial hemorrhage (ICH) is a pathological condition characterized by bleeding inside the skull or brain, which can be attributed to various factors. 
Identifying, localizing and quantifying ICH has important clinical implications, in a bleed-dependent manner. 
While deep learning techniques are widely used in medical image segmentation and have been applied to the ICH segmentation task, existing public ICH datasets do not support the multi-class segmentation problem. 
To address this, we develop the Brain Hemorrhage Segmentation Dataset (BHSD), which provides a 3D multi-class ICH dataset containing 192 volumes with pixel-level annotations and 2200 volumes with slice-level annotations across five categories of ICH. 
To demonstrate the utility of the dataset, we formulate a series of supervised and semi-supervised ICH segmentation tasks. 
We provide experimental results with state-of-the-art models as reference benchmarks for further model developments and evaluations on this dataset. 



![BHSD](brains.png)


# News

\[02/27/2024\] 👉 Please see our latest work: <a href="https://steve-zeyu-zhang.github.io/Awesome-3D-Medical-Imaging-Segmentation/"><b>3D Medical Imaging Segmentation: A Comprehensive Survey</b></a> for latest updates on 3D medical imaging segmentation.

\[09/29/2023\] Our paper has been accepted by [MLMI 2023](https://sites.google.com/view/mlmi2023)!

\[08/23/2023\] Our paper has been indexed by [CVer](https://wx.zsxq.com/mweb/views/topicdetail/topicdetail.html?topic_id=588155111148854&group_id=142181451122&inviter_id=585252854845544)!

# 📚 Datasets 
- Access the datasets used in the paper! [Dataset is publicly available on Huggingface](https://huggingface.co/datasets/WuBiao/BHSD)
- For the official train-test split and label of each semantic used in the paper, see [dataset.json](https://github.com/White65534/BHSD/blob/main/dataset.json).
- The format is ```.nii.gz```.


# Citation

For academic use, please cite:
```
@inproceedings{wu2023bhsd,
  title={BHSD: A 3D Multi-class Brain Hemorrhage Segmentation Dataset},
  author={Wu, Biao and Xie, Yutong and Zhang, Zeyu and Ge, Jinchao and Yaxley, Kaspar and Bahadir, Suzan and Wu, Qi and Liu, Yifan and To, Minh-Son},
  booktitle={International Workshop on Machine Learning in Medical Imaging},
  pages={147--156},
  year={2023},
  organization={Springer}
}
```

# Contact us

Please do not hesitate to open an issue. You don't want to send us an email since you probably not getting prompt feedback.


# Contributing to BHSD 🤖🌟

First off, big high fives 🙌 and thank you for considering a contribution to BHSD! Your help and enthusiasm can truly elevate this project. Whether you're fixing bugs 🐛, adding features 🎁, or just providing feedback, every bit matters! 

Please open a new issue when contributing to BHSD.



# License

BHSD is under NCND license. no commerical use. Do not modify BHSD for another dataset.

![license](https://github.com/White65534/BHSD/blob/main/license.png)
