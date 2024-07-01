ArminMoghimi
/
Fine-tune-the-Segment-Anything-Model-SAM-

Type / to search

Code
Issues
Pull requests
Actions
Projects
Wiki
Security
Insights
Settings
Creating a new file in Fine-tune-the-Segment-Anything-Model-SAM-
BreadcrumbsFine-tune-the-Segment-Anything-Model-SAM-/<!DOCTYPE html> <html lang="en"> <head> <meta charset="UTF-8"> <meta name="viewport" content="width=device-width, initial-scale=1.0"> <title>Fine-Tuning SAM for River Water Segmentation</title> </head> <body> <h1>Fine-Tuning SAM for River Water Segmentation</h1> <h2>Overview</h2> <p> This repository presents the Python code for fine-tuning the Segment Anything Model (SAM) to perform river water segmentation from close-range remote sensing imagery. This work is based on our paper published in IEEE Access: </p> <p> <strong>A. Moghimi, M. Welzel, T. Celik, and T. Schlurmann</strong>, "A Comparative Performance Analysis of Popular Deep Learning Models and Segment Anything Model (SAM) for River Water Segmentation in Close-Range Remote Sensing Imagery," IEEE Access, 2024. <a href="https://ieeexplore.ieee.org/document/10493013">IEEE Access</a> </p> <h3>Try it in Colab</h3> <p> You can try our fine-tuning code directly in Google Colab by clicking the link below: </p> <p> <a href="https://colab.research.google.com/drive/169TpQs74YkzF1Dffb_SHddCdOJX6fDdE?usp=drive_link"><strong>Open In Colab</strong></a> </p> <h2>Code and Dataset</h2> <h3>Code</h3> <p> The fine-tuning code is developed based on the original SAM code by Facebook Research and a tutorial by Alexandre Bonnet. </p> <ul> <li>Original SAM Code: <a href="https://github.com/facebookresearch/segment-anything">GitHub - Segment Anything</a></li> <li>Fine-Tuning Tutorial: <a href="https://encord.com/blog/learn-how-to-fine-tune-the-segment-anything-model-sam/">Encord Blog - Fine-Tune SAM</a></li> </ul> <h3>Dataset</h3> <p> The LuFI-RiverSNAP.v1 dataset for river water segmentation is available on multiple platforms: </p> <ul> <li><a href="https://www.kaggle.com/datasets/arminmoghimi/lufi-riversnap">Kaggle: LuFI-RiverSNAP</a></li> <li><a href="https://www2.isprs.org/commissions/comm3/icwg-3-4a/datasets/">ISPRS ICWG III/IVa "Disaster Management" Datasets</a></li> </ul> <h2>Citing Our Work</h2> <p> If you find our work helpful, please cite our paper using the following BibTeX entry: ## Cite
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
Kirillov, A., Mintun, E., Ravi, N., Mao, H., Rolland, C., Gustafson, L., ... & Girshick, R. (2023). Segment anything. In Proceedings of the IEEE/CVF International Conference on Computer Vision (pp. 4015-4026).
https://doi.org/10.48550/arXiv.2304.02643 <code> @inproceedings{kirillov2023segment, title={Segment anything}, author={Kirillov, Alexander and Mintun, Eric and Ravi, Nikhila and Mao, Hanzi and Rolland, Chloe and Gustafson, Laura and Xiao, Tete and Whitehead, Spencer and Berg, Alexander C and Lo, Wan-Yen and others}, booktitle={Proceedings of the IEEE/CVF International Conference on Computer Vision}, pages={4015--4026}, doi={https://doi.org/10.48550/arXiv.2304.02643}, year={2023} } </code> </pre> <h2>Contact</h2> <p> For any queries or contributions, feel free to contact us. </p> </body> <
