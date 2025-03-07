</head> <body> <h1>Fine-Tuning SAM (Segment anything) for River Water Segmentation</h1> <h2>Overview</h2> <p> This repository presents the Python code for fine-tuning the Segment Anything Model (SAM) to perform river water segmentation from close-range remote sensing imagery. This work is based on our paper published in IEEE Access: </p> <p> <strong>A. Moghimi, M. Welzel, T. Celik, and T. Schlurmann</strong>, "A Comparative Performance Analysis of Popular Deep Learning Models and Segment Anything Model (SAM) for River Water Segmentation in Close-Range Remote Sensing Imagery," IEEE Access, 2024. <a href="https://ieeexplore.ieee.org/document/10493013">IEEE Access</a> </p> 


## The easy-to-use and adaptable code for river water and other segmentation tasks and use for other remote sensing datasets: 
## Try it in Colab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/169TpQs74YkzF1Dffb_SHddCdOJX6fDdE?usp=drive_link)
## The LuFI-RiverSNAP.v1 (river water segmentation) Dataset in Google Drive: [![Open In Google Drive](https://upload.wikimedia.org/wikipedia/commons/archive/1/12/20201006132532%21Google_Drive_icon_%282020%29.svg)](https://drive.google.com/drive/folders/1fA78HOktI98PTKfhxxzPCijTodlBaf_r?usp=sharing)
 ![Test Image 1](https://github.com/ArminMoghimi/Fine-tune-the-Segment-Anything-Model-SAM-/blob/main/Fig16.jpg)

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <p>Some examples of river water segmentation results on the LuFI-RiverSnap.<i>v1</i>. 
    (a) Images and segmentation results generated by (b) U-Net<sub>(ResNet50)</sub>, 
    (c) PSPNet<sub>(ResNet50)</sub>, (d) DeeplabV3+<sub>(ResNet50)</sub>, 
    (e) PAN<sub>(ResNet50)</sub>, (f) LinkNet<sub>(ResNet50)</sub>, and (g) SAM were used as DL models 
    for river water segmentation. Green: False Positives (<span style="color: green;">FP</span>) detection, 
    Pink: False Negatives (<span style="color: pink;">FN</span>) detection, 
    Blue: correct detection of river water.</p>
</body>
</html>

## Try it in Colab:</br></br>
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/169TpQs74YkzF1Dffb_SHddCdOJX6fDdE?usp=drive_link)

Please also follow and read the reference codes we created for our fine-tuning SAM based on.
<li>Original SAM Code: <a href="https://github.com/facebookresearch/segment-anything">GitHub - Segment Anything</a></li> <li>Fine-Tuning Tutorial: <a href="https://encord.com/blog/learn-how-to-fine-tune-the-segment-anything-model-sam/">Encord Blog - Fine-Tune SAM</a></li> </ul> 

![Test Image 2](https://github.com/ArminMoghimi/Fine-tune-the-Segment-Anything-Model-SAM-/blob/main/Fig18.jpg)
 {Some examples of river water segmentation results on the LuFI-RiverSnap.\textit{v}1. (a) Images and segmentation results generated by (b) MobileSAM (TinyViT), (c) SAM (ViT-B), (d) and SAM (ViT-L)}   
    
<h3>Dataset</h3>
<p>The LuFI-RiverSNAP.v1 dataset for river water segmentation is available on multiple platforms:</p>
<ul>
    <li><a href="https://www.kaggle.com/datasets/arminmoghimi/lufi-riversnap">Kaggle: LuFI-RiverSNAP</a></li>
    <li><a href="https://www2.isprs.org/commissions/comm3/icwg-3-4a/datasets/">ISPRS ICWG III/IVa "Disaster Management" Datasets</a></li>
    <li><a href="https://ieee-dataport.org/documents/lufi-riversnap-river-water-segmentation">IEEE DataPort: LuFI-RiverSNAP</a></li>
</ul>
  
  ## Try it in Colab:</br></br>
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/169TpQs74YkzF1Dffb_SHddCdOJX6fDdE?usp=drive_link)  

  ## Cite
Please cite the following papers if they help your research. You can use the following BibTeX entry:
```
@article{moghimi2024comparative,
  title={A Comparative Performance Analysis of Popular Deep Learning Models and Segment Anything Model (SAM) for River Water Segmentation in Close-Range Remote Sensing Imagery},
  author={Moghimi, Armin and Welzel, Mario and Celik, Turgay and Schlurmann, Torsten},
  journal={IEEE Access},
  year={2024},
  doi={https://doi.org/10.48550/arXiv.2304.02643},
  publisher={IEEE}
}
```
A. Moghimi, M. Welzel, T. Celik, and T. Schlurmann, "A Comparative Performance Analysis of Popular Deep Learning Models and Segment Anything Model (SAM) for River Water Segmentation in Close-Range Remote Sensing Imagery," in IEEE Access, doi: 10.1109/ACCESS.2024.3385425. https://ieeexplore.ieee.org/document/10493013

The original paper of SAM.
```
@inproceedings{kirillov2023segment,
  title={Segment anything},
  author={Kirillov, Alexander and Mintun, Eric and Ravi, Nikhila and Mao, Hanzi and Rolland, Chloe and Gustafson, Laura and Xiao, Tete and Whitehead, Spencer and Berg, Alexander C and Lo, Wan-Yen and others},
  booktitle={Proceedings of the IEEE/CVF International Conference on Computer Vision},
  pages={4015--4026},
  doi={https://doi.org/10.48550/arXiv.2304.02643},
  year={2023}
}
```

Please cite the original SAM paper if you use our code and paper anyway,  as our idea came from the original paper of SAM which changed the segmentation process and we appreciate it as helping us a lot. 
 </code> </pre> <h2>Contact</h2> <p> For any queries or contributions, feel free to contact us. </p> </body> 
