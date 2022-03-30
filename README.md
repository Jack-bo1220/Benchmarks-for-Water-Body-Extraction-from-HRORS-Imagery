# Benchmarks-for-Water-Body-Extraction-from-High-Resolution-Optical-RS-Imagery
----
## Paper
- Title: Water body classification from high-resolution optical remote sensing imagery: Achievements and perspectives.
- DOI: https://doi.org/10.1016/j.isprsjprs.2022.03.013

<div align=center><img src="https://ars.els-cdn.com/content/image/1-s2.0-S0924271622000867-gr2.jpg" width="850" height="500" /></div>

----

## Benchmarks
To facilitate the qualitative and quantitative comparison in the research avenue, the two benchmarks employed in our paper and links to other relevant datasets and open-source codes will be summarized and released in this reponsitory. 

**No.1 Gaofen Image Dataset (GID)**

- Introduction: The GID was proposed in 2018 by a group from Wuhan University and contains 5 or 15 classes originally. In total, this dataset includes 10 fine land cover images and annotations, and 150 large-scale images and annotations. They are all captured from the GF-2 satellite and the pixel resolution is 4 m. we select representative samples and crop them to small samples with the size of 256 × 256, of which the total images number is 19500. 60% are used for training, 20% and 20% are used for validation and testing, respectively.
- The benchmark can be download from Baidudrive:
  - Link: [Baidudrive][gid] (extraction code: ae4y)
- Copyright Announcement：Please consider citing as follows:

```
@article{tong2020land,
  title={Land-cover classification with high-resolution remote sensing images using transferable deep models},
  author={Tong, Xin-Yi and Xia, Gui-Song and Lu, Qikai and Shen, Huanfeng and Li, Shengyang and You, Shucheng and Zhang, Liangpei},
  journal={Remote Sensing of Environment},
  volume={237},
  pages={111322},
  year={2020},
  publisher={Elsevier}
}
```

**No.2 2020 Gaofen challenge water body segmentation dataset**

- Introduction: The 2020 Gaofen challenge water body segmentation dataset was released by the 2020 Gaofen Challenge committee, which is the current only specific high-resolution optical dataset for water body classification. The dataset contains 1000 RGB images from the GF-2 satellite, of which the pixel resolution is ranging from 1 to 4 m.
- The benchmark can be download from Baidudrive:
  - Link: [Baidudrive][gf] (extraction code: jo56)
- Copyright Announcement：Please consider citing as follows:

```
@article{sun2021automated,
  title={Automated High-Resolution Earth Observation Image Interpretation: Outcome of the 2020 Gaofen Challenge},
  author={Sun, Xian and Wang, Peijin and Yan, Zhiyuan and Diao, Wenhui and Lu, Xiaonan and Yang, Zhujun and Zhang, Yidan and Xiang, Deliang and Yan, Chen and Guo, Jie and others},
  journal={IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing},
  volume={14},
  pages={8922--8940},
  year={2021},
  publisher={IEEE}
}
``` 
## Relevant information
**:one: Other relevant datasets（:white_check_mark: Last updated on March 30, 2022)**
 
Datasets  | Total image number  | Image bands number | Image size (pixels)  | Spatial resolution | Data sources  | Year | Link
:----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: 
Zurich Summer | 20 | 4 | 600∼1600 × 600∼1600 | 0.62m | QuickBird | 2015 | [Zurich Summer][Zurich Summer]
WHDLD | 4940 | 3 | 256 × 256 | 2m | GF-1 & ZY-3 | 2018 | [WHDLD][WHDLD]
DLRSD | 2100 | 3 | 256 × 256 | 0.3m | UC Merced archive | 2018 | [DLRSD][DLRSD]
DeepGlobe | 803 | 3 | 2448 × 2448 | 0.5m | DigitalGlobe | 2018 | [DeepGlobe][DeepGlobe]
GID | 10/150 | 3/4 | 7200 × 6800 | 4m | GF-2 | 2018 | [GID][GID]
DroneDeploy | 55 | 3 | 6000 × 6000 | 0.1m | Aerial images | 2019 | [DroneDeploy][DroneDeploy]
EORSSD | 2000 | 3 | 500 × 500 | - | Google Earth | 2020 | [EORSSD][EORSSD]
Landcover_ai | 41 | 3 | 9000 × 9500/4200 × 4700 | 0.25m/0.5m | Public Geodetic Resource | 2020 | [Landcover_ai][Landcover_ai]
2020 Gaofen Challenge dataset | 1000/2500 | 3 | 492∼2000 × 492∼2000 | 1 to 4m | GF-2 | 2020 | [GF-water][GF-water]
LoveDA | 5987 | 3 | 1024 × 1024 | 0.3m | Google Earth | 2021 | [LoveDA][LoveDA]

**:two: Summary of existing reviews of water body classification（:white_check_mark: Last updated on March 30, 2022)**
No. | Review title | Year | Publication | DOI/URL
:----: | :----: | :----: | :----: | :----: 
1 | A review of hyperspectral remote sensing and its applicationin vegetation and water resource studies | 2007 | Water Sa | https://journals.co.za/doi/abs/10.10520/EJC116430
2 | Water-body area extraction from high resolution satellite images-an introduction, review, and comparison | 2010 | IJIP | http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.301.8033&rep=rep1&type=pdf
3 | Water body extraction methods study based on RS and GIS | 2011 | PROENV | https://doi.org/10.1016/j.proenv.2011.09.407
4 | A review on extraction of lakes from remotely sensed optical satellite data with a special focus on cryospheric lakes | 2015 | ARS | https://doi.org/10.4236/ars.2015.43016
5 | A review of applications of satellite SAR, optical, altimetry and DEM data for surface water modelling, mapping and parameter estimation | 2015 | HESS | https://hess.copernicus.org/articles/19/3755/2015/hess-19-3755-2015.pdf
6 | Detecting, extracting, and monitoring surface water from space using optical sensors: A review | 2018 | REV GEOPHYS | https://doi.org/10.1029/2018RG000598
7 | A review on applications of remote sensing and geographic information systems (GIS) in water resources and flood risk management | 2018 | Water | https://doi.org/10.3390/w10050608
8 | Evaluation of water indices for surface water extraction in a Landsat 8 scene of Nepal | 2018 | Sensors | https://doi.org/10.3390/s18082580
9 | Inundation extent mapping by synthetic aperture radar: A review | 2019 | Remote Sensing | https://doi.org/10.3390/rs11070879
10 | Surface water detection and delineation using remote sensing images: A review of methods and algorithms | 2020 | SWAM | https://link.springer.com/content/pdf/10.1007/s40899-020-00425-4.pdf
11 | A comprehensive review of deep learning applications in hydrology and water resources | 2020 | Water Sci Technol | https://doi.org/10.2166/wst.2020.369
12 | Towards Synoptic Water Monitoring Systems: A Review of AI Methods for Automating Water Body Detection and Water Quality Monitoring Using Remote Sensing | 2022 | Sensors | https://doi.org/10.3390/s22062416
13 | Water body classification from high-resolution optical remote sensing imagery: Achievements and perspectives | 2022 | ISPRS JPRS | https://doi.org/10.1016/j.isprsjprs.2022.03.013

**:three: Relevant open-source codes（:white_check_mark: Last updated on March 30, 2022)**

- [Deepwatermap][Deepwatermap]
- [NDWI][NDWI]
- [WaterNet][WaterNet]
- [MECNet][MECNet]
- [MSResNet-via-SSL][MSResNet-via-SSL]
- [WatNet][WatNet]
- [WatNetv2][WatNetv2]

**:four: Some latest papers/approaches not included in our paper（:white_check_mark: Last updated on March 30, 2022)**
No. | Title | Category | Year | Publication | DOI/URL
:----: | :----: | :----: | :----: | :----: | :----:
1 | NFANet: A Novel Method for Weakly Supervised Water Extraction From High-Resolution Remote-Sensing Imagery | Weakly Supervised | 2022 | IEEE TGRS | https://doi.org/10.1109/TGRS.2022.3140323
2 | Multi-Scale Feature Aggregation Network for Water Area Segmentation | Feature fusion-based | 2022 | Remote Sensing | https://doi.org/10.3390/rs14010206
3 | SADA-Net: A Shape Feature Optimization and Multiscale Context Information-Based Water Body Extraction Method for High-Resolution Remote Sensing Images | - | 2022 | IEEE J-STARS | https://doi.org/10.1109/JSTARS.2022.3146275

## Citation

If our work has any help to you, please cite as follows:

```
@article{li2022water,
  title={Water body classification from high-resolution optical remote sensing imagery: Achievements and perspectives},
  author={Li, Yansheng and Dang, Bo and Zhang, Yongjun and Du, Zhenhong},
  journal={ISPRS Journal of Photogrammetry and Remote Sensing},
  volume={187},
  pages={306--327},
  year={2022},
  publisher={Elsevier}
}
```

## Contact

If you have any questions about it, please feel free to let me know. (:email: email:bodang@whu.edu.cn)

 
*******************
[gid]:https://pan.baidu.com/s/1f7yd8B_Y8nl3Za8zl7KI0Q 
[gf]:https://pan.baidu.com/s/1HMvZC933f3xgNr6vrDHSzg
[Zurich Summer]:https://sites.google.com/site/michelevolpiresearch/data/zurich-dataset
[WHDLD]:https://sites.google.com/view/zhouwx/dataset#h.p_hQS2jYeaFpV0
[DLRSD]:https://sites.google.com/view/zhouwx/dataset#h.p_hQS2jYeaFpV0
[DeepGlobe]:http://deepglobe.org/challenge.html
[GID]:https://captain-whu.github.io/GID15/
[DroneDeploy]:https://github.com/dronedeploy/dd-ml-segmentation-benchmark
[EORSSD]:https://hub.fastgit.org/rmcong/EORSSD-dataset
[Landcover_ai]:https://landcover.ai/
[GF-water]:https://github.com/AICyberTeam/2020Gaofen
[LoveDA]:https://github.com/Junjue-Wang/LoveDA
[Deepwatermap]:https://github.com/isikdogan/deepwatermap
[MSResNet-via-SSL]: https://github.com/Jack-bo1220/MSResNet-via-SSL
[MECNet]: https://github.com/ZhangZhily/MECNet
[WaterNet]:https://github.com/treigerm/WaterNet
[WatNet]:https://github.com/xinluo2018/WatNet
[WatNetv2]:https://github.com/xinluo2018/WatNetv2
[NDWI]:https://github.com/Whu-yla/NDWI-Project
