# Fundus images segmentation using Attention-CBAM-Unet3+
![att](https://github.com/eyatab/Fundus-images-segmentation-using-Attention-CBAM-Unet3-/assets/79045818/4ca20e2d-5cc7-4e04-9c42-e7dd94bf27fa)    


![uc](https://github.com/eyatab/Fundus-images-segmentation-using-Attention-CBAM-Unet3-/assets/79045818/8bed1ecf-3d24-4450-aafd-883a15873f80)     
Architecture Unet 3+: Pour la segmentation sémantique, il est crucial de combiner les caractéristiques de différentes échelles pour améliorer la précision. C’est précisément là qu'intervient Unet 3+ qui suggère tirer parti de la variété des données provenant de diverses échelles. Il s’agit d’une version évoluée de Unet comprenant l’introduction de connexion à différentes échelles (Full Scale Skip Connection). Les connexions skip à grande échelle intègrent des informations provenant de multiples échelles, ce qui renforce la précision de la segmentation, notamment pour les organes de tailles variables.      

En comparaison, tant Unet avec des connexions simples que Unet++ avec des connexions imbriquées et denses rencontrent des difficultés à exploiter suffisamment d’informations à toutes les échelles, échouent à apprendre de manière explicite la position et les limites des organes dans les images médicales. En revanche, Unet 3+ excelle dans cette tâche en tirant pleinement parti des informations à toutes les échelles, ce qui permet une compréhension plus précise de la localisation et de la délimitation des organes (H. Huang et al., 2020).


