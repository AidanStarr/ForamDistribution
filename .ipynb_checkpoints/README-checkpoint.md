# ForamDistribution
Jupyter Notebooks to visualise core-top Foraminifera census data and compare to oceanographic data.

<img src='G_trunc_oceanographic_plots.png'>
<img src='G_trunc_sin_O2_400.png'>

----
## Create conda environment
To replicate the conda envionrment I used, ```cd``` into this folder and run ```conda env create -f environment.yml``` in terminal

To make this envionrment available as a Jupyter-Lab kernel, run the following:
```
conda activate ForDist
ipython kernel install --user --name=ForDist
```
## Using data from:
```
@article{siccha2017forcens,
    title={ForCenS, a curated database of planktonic foraminifera censu counts in marine surface sediment samples},
    author={Siccha, Michael and Kucera, Michal},
    journal={Scientific data},
    volume={4},
    number={1},
    pages={1--12},
    year={2017},
    publisher={Nature Publishing Group}
}
```

```
@article{lauvset2016new,
    title={A new global interior ocean mapped climatology: The 1$\times$ 1 GLODAP version 2},
    author={Lauvset, Siv K and Key, Robert M and Olsen, Are and Heuven, Steven van and Velo, Anton and Lin, Xiaohua and Schirnick, Carsten and Kozyr, Alex and Tanhua, Toste and Hoppema, Mario and others},
    journal={Earth System Science Data},
    volume={8},
    number={2},
    pages={325--340},
    year={2016},
    publisher={Copernicus GmbH}
}
```