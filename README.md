# furg-fire-dataset

A dataset to compare the performance of different non-stationary video based fire detectors. Each video file has an associated XML annotation file (in the weird OpenCv 2.4.9 XML format). We are no longer updating this repository.

![Example](https://github.com/steffensbola/furg-fire-dataset/raw/master/annotation_tool.png "Example Annotation")
 

Each video file has a corresponding XML file with regular rectangles around each flame. They are OpenCv rectangle definitions. This XML was generated using OpenCv 2.4.9 and hasn't (probably won't) been updated since.

Rect(int x, int y, int width, int height) x and y are the top left corner.
For more info, have a look at the documentation: [OpenCv Rect](https://docs.opencv.org/3.1.0/d2/d44/classcv_1_1Rect__.html)


References:

[First response fire combat: Deep leaning based visible fire detection](https://ieeexplore.ieee.org/document/8215312)
```
@inproceedings{huttner2017first,
  title={First response fire combat: Deep leaning based visible fire detection},
  author={H{\"u}ttner, Valqu{\'\i}ria and Steffens, Cristiano Rafael and da Costa Botelho, Silvia Silva},
  booktitle={2017 Latin American Robotics Symposium (LARS) and 2017 Brazilian Symposium on Robotics (SBR)},
  pages={1--6},
  year={2017},
  organization={IEEE}
}
```

[A Texture Driven Approach for Visible Spectrum Fire Detection on Mobile Robots](https://ieeexplore.ieee.org/document/7783536)
```
@inproceedings{steffens2016texture,
  title={A Texture Driven Approach for Visible Spectrum Fire Detection on Mobile Robots},
  author={Steffens, Cristiano Rafael and Botelho, Silvia Silva Da Costa and Rodrigues, Ricardo Nagel},
  booktitle={Robotics Symposium and IV Brazilian Robotics Symposium (LARS/SBR), 2016 XIII Latin American},
  pages={257--262},
  year={2016},
  organization={IEEE}
}
```

[An Unconstrained Dataset for Non-Stationary Video Based Fire Detection](ieeexplore.ieee.org/document/7402136)
```
@inproceedings{steffens2015unconstrained,
  title={An unconstrained dataset for non-stationary video based fire detection},
  author={Steffens, Cristiano Rafael and Rodrigues, Ricardo Nagel and da Costa Botelho, Silvia Silva},
  booktitle={Robotics Symposium (LARS) and 2015 3rd Brazilian Symposium on Robotics (LARS-SBR), 2015 12th Latin American},
  pages={25--30},
  year={2015},
  organization={IEEE}
}
```

[Non-stationary VFD Evaluation Kit: Dataset and Metrics to Fuel Video-Based Fire Detection Development](https://link.springer.com/chapter/10.1007/978-3-319-47247-8_9)
```
@incollection{steffens2016non,
  title={Non-stationary VFD Evaluation Kit: Dataset and Metrics to Fuel Video-Based Fire Detection Development},
  author={Steffens, Cristiano Rafael and Rodrigues, Ricardo Nagel and da Costa Botelho, Silvia Silva},
  booktitle={Robotics},
  pages={135--151},
  year={2016},
  publisher={Springer}
}
```


