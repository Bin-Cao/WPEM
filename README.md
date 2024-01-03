
<h1 align="center">
  <a href=""><img src="https://github.com/Bin-Cao/WPEM/assets/86995074/3b05f104-364e-4cd2-9d21-f40b77e0ef10" alt="WPEM" width="250"></a>
  <br>
  <br>
</h1>

Whole Pattern fitting of powder X-ray diffraction by Expectation Maximum (WPEM) package!

My master dissertation give a detailed introduction of the beta version of WPEM : see [Link](https://github.com/Bin-Cao/MPhil_SHU)

The official release version will meet with you as soon as possible

---

WPEM specializes in determining the complex crystal structures and decoupling heavily overlapped Bragg peaks from mixed X-rays and polycrystalline powder diffraction. We have acquired several excellent research results including quantitative detection of similar structures with tiny differences i.e., α phase and α' phase of Ti-Ni alloy, separating contributions of amorphous and crystalline in Polybutene, etc. We are willing to cooperate extensively and provide assistance with X-ray diffraction pattern refinement. Please contact us if you have any queries or need help: bcao686@connect.hkust-gz.edu.cn (Mr. CAO Bin).



![WechatIMG954](https://github.com/Bin-Cao/WPEM/assets/86995074/65b44e3f-257b-4ea7-8b54-174a1359449f)


# cite
    Cao, B. Whole Pattern fitting of powder X-ray diffraction by Expectation Maximum algorithm, <https://github.com/Bin-Cao/WPEM> (2022).
    
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
``` 
