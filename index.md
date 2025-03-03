---
conchImagenet: dhTTjjrxIcU
conchrobustness: 49d5OOnyW8w
cockImagenet: 06meJhFl0ME

tntpubfig: Klepca1Ny3c
tntrobust: q_wTmIyoqmY
tntmiscs: JncpN2t1Gzg
---

### Reference
```
B. G. Doan, M. Xue, S. Ma, E. Abbasnejad and D. C. Ranasinghe, "TnT Attacks! Universal Naturalistic Adversarial Patches Against Deep Neural Network Systems," in IEEE Transactions on Information Forensics and Security, 2022, doi: 10.1109/TIFS.2022.3198857.
```

Link to the research paper: [TnTattacks](https://arxiv.org/abs/2111.09999) 

Link to the artifacts: [Github](https://github.com/baogiadoan/TnT)
### Bibtex
```
@ARTICLE{9856683,
  author={Doan, Bao Gia and Xue, Minhui and Ma, Shiqing and Abbasnejad, Ehsan and C. Ranasinghe, Damith},
  journal={IEEE Transactions on Information Forensics and Security}, 
  title={TnT Attacks! Universal Naturalistic Adversarial Patches Against Deep Neural Network Systems}, 
  year={2022},
  volume={17},
  pages={3816-3830},
  doi={10.1109/TIFS.2022.3198857}}
```

# Physical World Deployment Demonstration Videos
## Summary

### Targeted Attacks on the PubFig Classification Task
- [The effectiveness of an example *flower* TnT](#TnTPubFigEffect)
- [The robustness of an example *flower* TnT](#TnTPubFigRobust)

### Targeted Attacks on ImageNet Large Scale Visual Recognition Task
- [The effectiveness of an example *flower* TnT](#TnTImagenetEffect)
- [The effectiveness and robustness of miscellaneous examples of *flower* TnTs](#TnTMiscs)
- [The effectiveness of a patch trigger](#PatchImagenetEffect)
- [The robustness of a patch trigger](#PatchImagenetRobust)

## Demo Videos

### Targeted Attack with an input-agnostic TnT, an example *flower*, from the TnT Generator - PubFig Face Recognition Task

#### The effectiveness of an example *flower* TnT 

<a name="TnTPubFigEffect"></a>

{% include youtubePlayer.html id=page.tntpubfig %}

#### The robustness of an example *flower* TnT 

<a name="TnTPubFigRobust"></a>

{% include youtubePlayer.html id=page.tntrobust %}



### Targeted Attack with an Input-Agnostic *flower* Trigger from the TnT Generator - ImageNet classification task

#### The effectiveness of an example *flower* TnT 
<a name="TnTImagenetEffect"></a>

{% include youtubePlayer.html id=page.cockImagenet %}

#### The effectiveness and robustness of miscellaneous examples of *flower* TnTs 
<a name="TnTMiscs"></a>

{% include youtubePlayer.html id=page.tntmiscs %}


### Targeted Attack with an Input-Agnostic Patch from the Adversarial Patch Generator - ImageNet classification task

#### The effectiveness of a patch trigger
<a name="PatchImagenetEffect"></a>

{% include youtubePlayer.html id=page.conchImagenet %}

#### The robustness of a patch trigger
<a name="PatchImagenetRobust"></a>

{% include youtubePlayer.html id=page.conchrobustness %}

