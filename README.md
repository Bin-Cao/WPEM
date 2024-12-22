
<h1 align="center">
  <a href="https://bin-cao.github.io/caobin/-wpem"><img src="https://github.com/Bin-Cao/WPEM/assets/86995074/3b05f104-364e-4cd2-9d21-f40b77e0ef10" alt="WPEM" width="250"></a>
  <br>
  <br>
</h1>

### Whole Pattern fitting of powder X-ray diffraction by Expectation Maximum (WPEM) package!
### [Home Page](https://github.com/WPEM)
# cite
    CAO, Bin (2024). Whole Pattern fitting of powder X-ray diffraction by Expectation Maximum algorithm. figshare. Software. https://doi.org/10.6084/m9.figshare.25060175.v1.


My master dissertation give a detailed introduction of the beta version of WPEM : see [Link](https://github.com/Bin-Cao/MPhil_SHU)

The official release version will meet with you as soon as possible

- [WPEM book](https://www.overleaf.com/read/pfybccppvzjm#162054) The WPEM Project Manual

### WPEM papers
- `Chem Eng J 2024` [A Li-rich layered oxide cathode with remarkable capacity and prolonged cycle life](https://www.sciencedirect.com/science/article/pii/S1385894724030092) Tongxing Lei, **Bin Cao**, Wenbo Fu, Xiuling Shi, Zhiyu Ding, Qi Zhang, Junwei Wu, Kaikai Li, Tong-Yi Zhang,

- `MD 2024` [Active Learning Accelerates the Discovery of High Strength and High Ductility Lead-Free Solder Alloys](https://doi.org/10.1016/j.matdes.2024.112921) **B Cao**, T Su, S Yu, T Li, T Zhang, Z Dong, TY Zhang

- `JMRT 2024` [Machine learning-assisted composition design of W-free Co-based superalloys with high γ′-solvus temperature and low density](https://www.sciencedirect.com/science/article/pii/S2238785424000401?via%3Dihub)Linlin Sun, **Bin Cao**, Qingshuang Ma, Qiuzhi Gao, Jiahao Luo, Minglong Gong, Jing Bai, Huijun Li 

- `Nano Energy 2023` [Orthorhombic (Ru, Mn)2O3: A superior electrocatalyst for acidic oxygen evolution reaction](https://www.sciencedirect.com/science/article/pii/S2211285523005645?via%3Dihub)Yin Qin, **Bin Cao**, Xiao-Ye Zhou, Zhuorui Xiao, Hanxiang Zhou, Zhenyi Zhao, Yibo Weng, Jianshuai Lv, Yang Liu, Yan-Bing He, Feiyu Kang, Kaikai Li, Tong-Yi Zhang

- `Materials 2023` [Fabricated High-Strength, Low-Elastic Modulus Biomedical Ti-24Nb-4Zr-8Sn Alloy via Powder Metallurgy](https://www.mdpi.com/1996-1944/16/10/3845)Guo, A.X.Y., **Cao, B.**, Wang, Z., Ma, X., Cao, S.C. 


---

WPEM specializes in elucidating intricate crystal structures and untangling heavily overlapping Bragg peaks in mixed X-rays and polycrystalline powder diffraction. Our endeavors have yielded noteworthy research outcomes, including the precise detection of subtle structural differences, such as the α phase and α' phase of Ti-Ni alloy, the differentiation of amorphous and crystalline contributions in Polybutene, the investigation of complex solid solution structures, and the computation of scattering information within organized processes. We are eager to engage in extensive collaborations and offer support in X-ray diffraction pattern refinement. For inquiries or assistance, please don't hesitate to contact us at bcao686@connect.hkust-gz.edu.cn (Dr. CAO Bin).

Our development journey commenced in 2020, driven by a commitment to patience and perfection in our work. Upon the publication of our final paper, we plan to freely share all our code promptly.



<a href="https://bin-cao.github.io/caobin/-wpem" target="_blank">
    <img  alt="2222" src="https://github.com/Bin-Cao/WPEM/assets/86995074/65b44e3f-257b-4ea7-8b54-174a1359449f">
</a>


Organization & spectroscopy informatics studies : see https://github.com/WPEM
``` javascript
PyWPEM/
    __init__.py
    WPEM.py
    Extinction/ 
        __init__.py
        CifReader.py
        XRDpre.py
        wyckoff/
          __init__.py
          wyckoff_dict.py 
    Background/
        __init__.py
        BacDeduct.py
    EMBraggOpt/
        __init__.py
        EMBraggSolver.py
        BraggLawDerivation.py
        WPEMFuns/
            __init__.py
            SolverFuns.py
    Refinement/
        __init__.py
        VolumeFractionDertermination.py
    Amorphous/
        fitting/
            __init__.py
            AmorphousFitting.py
        QuantitativeCalculation/
            __init__.py
            AmorphousRDF.py
    DecomposePlot/
        __init__.py
        plot.py
    XRDSimulation/
        __init__.py
        Simulation.py
        DiffractionGrometry/
            __init__.py
            atom.py
    Raman/
        Decompose/
            __init__.py
            RamanFitting.py
    WPEMXAS/
            __init__.py
            EXAFS.py
            fftdemo.ipynb
    WPEMXPS/
            __init__.py
            XPSEM.py
    Plot/
            __init__.py
            UnitCell.py
    StructureOpt/
            __init__.py
            SiteOpt.py
    GraphStructure/ （Crystal2Graph Neural Network）
            __init__.py
            graph.py
``` 
