---
layout: page
permalink: /datasets/
title: Datasets
---

Affective Computing:

<ol>
  <li> MUStARD: Castro et al., [Towards multimodal sarcasm detection (an _obviously_ perfect paper)](https://arxiv.org/abs/1906.01815), ACL 2019

  </li>
  
  <li>CMU-MOSI: Zadeh et al., [MOSI: multimodal corpus of sentiment intensity and subjectivity analysis in online opinion videos](https://arxiv.org/abs/1606.06259), IEEE Intelligent Systems 2016 

  </li>
  
  <li> UR-FUNNY: Hasan et al., [UR-FUNNY: A multimodal language dataset for understanding humor](https://arxiv.org/abs/1904.06618), EMNLP 2019

  </li>
    
  <li> CMU-MOSEI: Zadeh et al., [Multimodal language analysis in the wild: CMU-MOSEI dataset and interpretable dynamic fusion graph](https://www.aclweb.org/anthology/P18-1208/), ACL 2018
  
  </li>
</ol>

Healthcare:

<ol>
  <li> MIMIC: Johnson et al., [MIMIC-III, a freely accessible critical care database](https://pubmed.ncbi.nlm.nih.gov/27219127/), Nature Scientific Data 2016.
       MIMIC is a large, freely-available database comprising de-identified health-related data associated with over 40,000 patients who stayed in critical care units of the Beth Israel Deaconess Medical Center between 2001 and 2012. We organized numerous patient data into two major modalities: time series modality, which is a set of medical measurements of the patient taken every hour in a period of 24 hours where each measurement and static modality, which is a set of medical information about the patient. We use these modalities for $3$ tasks: mortality prediction and 2 ICD-9 code predictions.
</li>
</ol>

Robotics:

<ol>
  <li> MuJoCo Push: Lee et al., [Multimodal sensor fusion with differentiable filters](https://arxiv.org/abs/2010.13021), IROS 2020
      MuJoCo Push is a planar pushing task, in which a 7-DoF Panda Franka robot is pushing a circular puck with its end-effector in simulation. We estimate the 2D position of the unknown object on a table surface, while the robot intermittently interacts with the object. Similar to Vision&Touch, planar pushing is a contact-rich task. However, instead of estimating robot states, this dataset is estimating the state of the object the robot is currently interacting with.
    </li>

  <li> Vision & Touch: Lee et al., [Making sense of vision and touch: Self-supervised learning of multimodal representations for contact-rich tasks](https://arxiv.org/abs/1810.10191), ICRA 2019
      Vision & Touch is a real-world robot manipulation dataset that collects visual, force, and robot proprioception data (as well as the robot actions) for a peg insertion task. The robot is a 7-DoF, torque-controlled Franka Panda robot, which has a triangle peg attached to its end-effector. Rigidly attached to the table in front of the robot is a box with a triangle hole. The robot attempts to insert the peg into the hole, a contact-rich manipulation task that has been studied for decades due to its relevance in manufacturing. Vision, force, and proprioception are feedback modalities shown to be complementary and concurrent during contact-rich manipulation.
    </li>
</ol>

Finance:

<ol>
  <li> Stocks-F&B consists of 8 selected stocks from S&P 500 stocks categorized by GICS as Restaurants or Packaged Foods & Meats. We select MCD, SBUX, HSY, and HRL for initial experiments on this dataset, record their opening prices and preprocess the data.
</li>
  <li> Stocks-Health consists of 63 selected stocks from S&P $500$ stocks categorized by GICS as Health Care. We select MRK, WST, CVS, MCK, ABT, UNH, and TFX for initial experiments on  this dataset, record their opening prices, and preprocess the data.
</li>
  <li> Stocks-Tech consists of 100 selected stocks from S&P 500 stocks categorized by GICS as Information Technology or Communication Services. We select AAPL, MSFT, AMZN, INTC, AMD, and MSI for initial experiments on this dataset, record their opening prices, and preprocess the data.
</li>
</ol>
    
HCI:

<ol>
  <li> ENRICO: Leiva et al., [Enrico: A dataset for topic modeling of mobile UI designs](https://userinterfaces.aalto.fi/enrico/resources/enrico.pdf), MobileHCI 2020
ENRICO is a dataset of Android app screens categorized by their design motifs. ENRICO was collected to help data-driven design applications such as design search, UI layout generation, UI code generation, and user interaction modeling. ENRICO is a subset of RICO, which is a large dataset of app screens collected by the automated and semi-automated crawling of Android apps available on the Google Play Store.
</li>
</ol>
    
Multimedia:

<ol>
  <li> MM-IMDb: Arevalo et al., [Gated multimodal units for information fusion](https://arxiv.org/abs/1702.01992), ICLR workshop 2017

      </li>
  <li> AV-MNIST: Vielzeuf et al., [Centralnet: a multilayer approach for multimodal fusion](https://arxiv.org/abs/1808.07275), ECCV workshop 2018

      </li>
  <li> Kinetics-400: Kay et al., [The kinetics human action video dataset](https://arxiv.org/abs/1705.06950), arXiv 2017
    </li>
</ol>
