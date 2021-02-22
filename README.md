# Awesome Biomechanics [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)   ![visitors](https://visitor-badge.glitch.me/badge?page_id=modenaxe.awesome-biomechanics)<!-- omit in toc -->
![logo](./images/awesome_biomechanics_logo.png)
### A curated repository of biomechanical resources  <!-- omit in toc -->
#### Still a work in progress (might include incomplete descriptions), but [contributions](#contributing) are welcome at any stage! :heart_eyes:<!-- omit in toc -->

## Table of contents <!-- omit in toc -->
- [Learning](#learning)
  - [Online Courses :clapper:](#online-courses-clapper)
  - [YouTube Channels :tv:](#youtube-channels-tv)
  - [Videos :video_camera:](#videos-video_camera)
  - [Teaching Resources :triangular_ruler:](#teaching-resources-triangular_ruler)
  - [Books :blue_book:](#books-blue_book)
- [Datasets :dvd:](#datasets-dvd)
  - [Human Anatomy :bone:](#human-anatomy-bone)
  - [Animal Anatomy :crocodile:](#animal-anatomy-crocodile)
  - [Balance :balance_scale:](#balance-balance_scale)
  - [Energetics :fire:](#energetics-fire)
  - [Walking :walking:](#walking-walking)
  - [Running :running:](#running-running)
  - [Instrumented Prostheses :chart_with_upwards_trend:](#instrumented-prostheses-chart_with_upwards_trend)
  - [Upper Limb :muscle:](#upper-limb-muscle)
  - [Hand :palms_up_together:](#hand-palms_up_together)
  - [Soft Tissue Artefacts :leg:](#soft-tissue-artefacts-leg)
  - [Health Datasets :heart:](#health-datasets-heart)
- [Gait Analysis and Motion Capture :cartwheeling:](#gait-analysis-and-motion-capture-cartwheeling)
  - [Gait Analysis Markersets [TODO: add references and resources]](#gait-analysis-markersets-todo-add-references-and-resources)
  - [Motion Capture Data Import and Processing [WIP]](#motion-capture-data-import-and-processing-wip)
    - [Marker Trajectory Gap filling](#marker-trajectory-gap-filling)
    - [Inertial Measurement Units](#inertial-measurement-units)
- [Ultrasound Fascicle Tracking](#ultrasound-fascicle-tracking)
- [Modelling and Simulation :computer:](#modelling-and-simulation-computer)
  - [Anthropometric Models :standing_person:](#anthropometric-models-standing_person)
  - [Multibody and Physics Engines :sleeping::arrow_lower_left::apple:](#multibody-and-physics-engines-sleepingarrow_lower_leftapple)
  - [Computational Muscle Models 	:mechanical_arm:](#computational-muscle-models-mechanical_arm)
  - [Neuro-musculoskeletal Simulation Software :brain::arrow_right::leg:](#neuro-musculoskeletal-simulation-software-brainarrow_rightleg)
  - [Neuromusculoskeletal Simulation Tools :brain::hammer:](#neuromusculoskeletal-simulation-tools-brainhammer)
- [Optimal Control and Trajectory Optimization :rocket:](#optimal-control-and-trajectory-optimization-rocket)
- [Subject-Specific Modelling](#subject-specific-modelling)
  - [Segmentation of Medical Images :art:](#segmentation-of-medical-images-art)
  - [Automatic Segmentation](#automatic-segmentation)
  - [Manipulation, Processing and Comparison of Surface Meshes](#manipulation-processing-and-comparison-of-surface-meshes)
  - [Resources for Building Biomechanical Models from Medical Images](#resources-for-building-biomechanical-models-from-medical-images)
  - [Automatic Definition of Bony Landmarks and Reference Systems :skull:](#automatic-definition-of-bony-landmarks-and-reference-systems-skull)
  - [Uncertainty Quantification in Musculoskeletal Simulations](#uncertainty-quantification-in-musculoskeletal-simulations)
  - [Meshers of Surface Models](#meshers-of-surface-models)
  - [Statistical Shape Modelling :bone:](#statistical-shape-modelling-bone)
- [Finite Element Analysis](#finite-element-analysis)
  - [Finite Element Analysis Software](#finite-element-analysis-software)
  - [Finite Element Analysis Software Tools](#finite-element-analysis-software-tools)
  - [Finite Element Models](#finite-element-models)
- [Statistical Analysis](#statistical-analysis)
- [Scientific Data Visualization](#scientific-data-visualization)
- [Reproducibility :gem:](#reproducibility-gem)
- [Good practices for credible modeling](#good-practices-for-credible-modeling)
- [Societies and Initiatives :classical_building:](#societies-and-initiatives-classical_building)
- [Miscellaneous Online Resources](#miscellaneous-online-resources)
- [More Datasets and repositories](#more-datasets-and-repositories)
- [Contributing](#contributing)
  - [How to contribute](#how-to-contribute)
  - [Resources for learning how to contribute](#resources-for-learning-how-to-contribute)
  - [Items suggested template](#items-suggested-template)
- [License](#license)

----

## Learning

### Online Courses :clapper:
* [Lectures on animal locomotion](https://mchenrylab.bio.uci.edu/e139) by Manny Azizi and Matt McHenry, UC Irvine (2020).
* [Lectures on optimal control](http://www.anilvrao.com/Optimal-Control-Videos.html) by Anil Rao (University of Florida).
* [Lectures on multibody dynamics](https://www.youtube.com/watch?v=1Tyxgv7RUdk&list=PLzAwokZEM7auZEBOJKNa_lCgz2rdgpYLL) by [Jason Moore](https://www.moorepants.info/) at UC Davis (2017).
* [KNES 789W - Advanced Projects in Kinesiology; Modeling & Simulation of Human Movement](https://www.youtube.com/watch?v=JXz5BHQBJhk&list=PLFNfmB3IG2Cf_0V5N9w_ZBKIHD2xg1H_g) by Ross Miller, University of Maryland (2020).
* [Neuromechanics course material](https://github.com/joshcash9/Neuromechanics_Course) by Joshua Cashaback (University of Delaware).
* [Neuromatch Academy](https://www.youtube.com/channel/UC4LoD4yNBuLKQwDOV6t-KPw): [the Neuromatch Academy](https://www.neuromatchacademy.org/) aims to introduce traditional and emerging tools of computational neuroscience to trainees.
* [Robotics 101: Computational Linear Algebra](https://robotics.umich.edu/2020/now-available-robotics-101-online/) by University of Michigan Robotics Institute (Fall 2020). The course includes [lecture videos](https://www.youtube.com/playlist?list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv) and [GitHub resources](https://github.com/michiganrobotics/rob101), including the [lecture notes](https://github.com/michiganrobotics/rob101/tree/main/Lecture%20Notes).
* [Sport Biomechanics Lecture Series](https://www.youtube.com/channel/UCmG-bd1JL1ACP7hMzIUXwOg) curated by Stuart McErlain-Naylor. Includes introductory topics like  presentations of motion capture techniques by Vicon ([lecture 1](https://www.youtube.com/watch?v=1zJ14cW-JqY) and [lecture 2](https://www.youtube.com/watch?v=hM7xEoyP-4o)) and an [introduction](https://www.youtube.com/watch?v=2xgyTpsa14M#) of electromyography (EMG) by Delsys.
* [BPK 409: Wearable Technology and Human Physiology](https://www.youtube.com/channel/UClU9XVBC0mDwJBIVJTUbtwg/videos) by Max Donelan (Simon Fraser University). The course teaches to use state-of-the-art wearable technology to measure, analyze, and understand human physiological systems including muscular, nervous, and cardiovascular systems.</br>
:page_facing_up: [description of labs](https://docs.google.com/document/d/e/2PACX-1vTr1zOyrUedA1yx76olfDe5jn88miCNb3EJcC3INmy8nDmbJ8N5Y0B30EBoOunsWbA2DGOVWpgJzIs9/pub) |
:floppy_disk: [code](https://github.com/patmorli/BPK-409)
* [Introduction to Reinforcement Learning with David Silver](https://deepmind.com/learning-resources/-introduction-reinforcement-learning-david-silver) by David Silver, DeepMind (2015).


### YouTube Channels :tv:
* [AnyBody Technology Videos and Webcasts](https://www.youtube.com/channel/UCbgDnEKXyYOETR_Nb6YdehA)
* [American Society Biomechanics (ASB)](https://www.youtube.com/channel/UC0_WoykR3nSBrHAwyfLPzzw)
* [BassettBiomechanics](https://www.youtube.com/c/Bassettbiomechanics/videos): includes a _Biomechanics of the Musculoskeletal System_ course and Visual3D tutorials.
* [Biomch-V](https://www.youtube.com/channel/UCcv9iv6v4_l9dfDDW1PTZCA): includes videos from International Society of Biomechanics conferences.
* [European Society of Biomechanics (ESB)](https://www.youtube.com/channel/UCFkgDwfks-UkG7IDk8cBMMQ)
* [International Society of Biomechanics (tutorials and lectures)](https://isbweb.org/about-us/61-videos): It includes those recorded at the ISB congresses from 2007 and those provided by others.
* [International Society of Biomechanics in Sports (ISBS)](https://www.youtube.com/channel/UCYkzE6y_eKWa7KQOqZ6ZQUA/featured?disable_polymer=1): videos from ISBS2020 virtual conference.
* [Journal of Foot and Ankle Research](https://www.youtube.com/channel/UCuIdGMZMaDKRM7vyJ6Dbcwg)
* [OpenSim Videos and Webinars](https://www.youtube.com/user/OpenSimVideos/videos)
* [UCalgary Human Performance Lab](https://www.youtube.com/channel/UCxAOMJHF-5xQMFkLAutV7Dg/videos): videos from ISB/ASB2019 and Dynamic Walking 2019 conferences.
* [Manoj Srinivasan's channel](https://www.youtube.com/user/sjonam/videos)
* [Ross Miller's channel](https://www.youtube.com/channel/UCO_H7aZoIcwZiNc4KjiQQkg/videos) 
* [Stuart McErlain-Naylor channel](https://www.youtube.com/channel/UCmG-bd1JL1ACP7hMzIUXwOg)
* [Analysis of upright posture by force platform](https://www.youtube.com/playlist?list=PLw8zLrKDgyodwSxhtVFaFMrdhaS1H6jzB): videos produced by Felipe Fava de Lima about the use of force plataforms.

### Videos :video_camera:
* [CNB-ASB Muscle Workshop](https://www.youtube.com/watch?v=Ur9wYYR0nac&feature=youtu.be): presentations on the topic `Integrative Muscle Modelling for Neuromechanics`.
* [A critique of Induced Acceleration Analysis](https://www.youtube.com/watch?v=2EmwIM_uQnk&t=18s) by Andy Ruina (WCB2014).
* [Biomechanics playlist](https://www.youtube.com/playlist?list=PLH144fs5LXOPFtafyiTVpXQBEpdrnfn3m) by Kath Boyer. Playlist of Youtube videos of biomechanical interest.
* [F8 2019 - VR Full Body Tracking & Avatars](https://www.youtube.com/watch?v=FhiAFo9U_sM) and [blog post](https://uploadvr.com/facebook-f8-2019-body-tracking/)
* [Running with bone pins](https://www.youtube.com/watch?v=nf6jkyNgkwE): video of data collection in subject running with bone pins shared by Ton Van den Bogert.
* [Introduction to Trajectory Optimization](https://www.youtube.com/watch?v=wlkRYMVUZTs) by [Matthew Kelly](http://www.matthewpeterkelly.com/index.html). Very clear introduction to the topic with MATLAB resources linked in the video description.
* [Version Control for Researchers](https://www.youtube.com/watch?v=6OkOmPqumWo&feature=emb_title) by [Ryan Alcantara](https://www.ryan-alcantara.com). Tutorial for ASB2020 introducing GitHub and version control for biomechanists. Accompanying tutorial material located at the [ASB_Tutorial repository](https://github.com/alcantarar/asb_tutorial).</br> 
* [A free/opensource workflow from CT scan to FEA](https://peterfalkingham.com/2020/11/06/a-free-opensource-workflow-from-ct-scan-to-fea/) by [Peter L. Falkingham](https://peterfalkingham.com/):  workflow for carrying out finite element analysis (FEA) using free and open-source software (Dragonfly for segmentation, Blender for mesh refinement and FEBio for finite element analysis. Quick overview of the main steps.<br/>
<!-- * https://www.goatstream.com/research/ -->


### Teaching Resources :triangular_ruler:
* [Anatomy Standard](https://www.anatomystandard.com/) by Jānis Šavlovskis and Kristaps Raits (2020). Project aiming at creating an evidence-based 3D model of the human body, create high-quality, interactive illustrations of the model, and share them here to provide a resource for teaching and explaining anatomy. Images are licensed under the [Creative Commons Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc/4.0/). </br>
* [Biomch-L discussions](https://biomch-l.isbweb.org/forum/biomch-l-forums/biomch-l-1988-2010): classic discussions from the archives of the LISTSERV Biomch-L database:
    - [Joint Attitude Debate Summary](https://biomch-l.isbweb.org/forum/biomch-l-forums/biomch-l-1988-2010/189-joint-attitude-debate-final-reply-summary) by H. J. Woltring (1990).
    - [3D Joint Power Debate Summaary](https://biomch-l.isbweb.org/forum/biomch-l-forums/biomch-l-1988-2010/14921-summary-3d-joint-power) by J. Rubenson (2004).
* [Muscle Atlas](https://rad.washington.edu/muscle-atlas/) by the Dept of Radiology of the University of Washington. The medical illustrations contained in this online atlas are copyrighted © 1997 by the University of Washington but receiving a license to use these images is generally quite easy, particularly for academic and scholarly purposes. For more information and obtaining a license [see this link](https://els2.comotion.uw.edu/product/musculoskeletal-atlas).
* [ASB Teaching Repository](http://asbteachingrepository.herokuapp.com/) by the American Society of Biomechanics. Does not require membership to access.
* [Biomechanics Toolbar](http://www.biomechanicstoolbar.org/) by [Jos Vanrenterghem](https://www.kuleuven.be/wieiswie/en/person/00103997) (2016). The Biomechanics Toolbar is freeware designed to make data processing more accessible for undergraduate  teaching. It works as a traditional toolbar in Microsoft Excel.
* [Scientific Animation of Muscle Contraction](http://brule.co/lab/UGA/Contraction-musculaire-2/) by [Brule Design Studio](http://brule.co).  Press `Demo` to try it.
* [Scientific Animation of Human Locomotion](http://brule.co/faire-comprendre/projet/locomotion) by [Brule Design Studio](http://brule.co). Press `Demo` to try it.
* [Kwon3d website](http://www.kwon3d.com/theory/prac.html): website with theory about most basic topics in biomechanics.
* [GitHub resources for teaching](https://classroom.github.com/classrooms): GitHub offers support for automating certain aspects of teaching.
* [How to review a paper](https://www.sciencemag.org/careers/2016/09/how-review-paper) from Science Magazine.
* [How to write a systematic review for Health](https://utas.libguides.com/SystematicReviews/) by the University of Tasmania.
* [Kuo's course homeworks](https://github.com/kuo-courses): interesting homework materials used in Art Kuo's courses (public on GitHub).
* [MoLib (Motion Library)](https://www.biomechanist.net/multimedia-libraries/motion-library/) from [The Biomechanist](https://www.biomechanist.net/): sample experimental data collected on one participant intended as tutorial for OpenSim processing. See related [post](https://www.biomechanist.net/how-to-use-motion-library/) by Markus Kurz.
* [Trajectory Optimization Toolbox](https://github.com/MatthewPeterKelly/OptimTraj) by Matthew Kelly, including some [excellent examples](https://github.com/MatthewPeterKelly/dscTutorials) and some [course materials](https://github.com/MatthewPeterKelly/ME149_Spring2018).
* [Notes on Scientific Computing for Biomechanics and Motor Control](https://github.com/BMClab/BMC) by Marcos Duarte and Renato Watanabe. A beautiful collection of lecture notes and code on scientific computing and data analysis for Biomechanics and Motor Control in the form of Jupyter notebooks (python).
* [Optimal Control Workshop](https://simtk.org/projects/ocworkshop/) by BJ Fregly. Files distributed at the NSF-funded Optimal Control Workshop held on July 9, 2015 at the University of Edinburgh as part of the XV International Symposium on Computer Simulation in Biomechanics.
* [OpenSim teaching Hub](https://simtk-confluence.stanford.edu/display/OpenSim/Teaching+Hub) by the OpenSim Team. Includes materials from the Neuromuscular Biomechanics Lab in the Department of Bioengineering at Stanford University. Does not require membership to access.
* [ODE Integration Best Practices With Octave/Matlab](https://moorepants.github.io/eme171/ode-integration-best-practices-with-octavematlab.html) by by [Jason Moore](https://www.moorepants.info/) from his [EME 171: Analysis, Simulation and Design of Mechatronic Systems](https://moorepants.github.io/eme171/) course at UC Davis.
* [Teaching and Learning with Jupyter](https://jupyter4edu.github.io/jupyter-edu-book/) by Lorena Barba et al. (2019). This is a collaboratively written book including explanations and examples on many key topics of interest for those interested in using [Jupyter](https://jupyter.org/) in the classroom. 
* [Tips for setting up remote lessons](https://www.3blue1brown.com/blog/livestream-setup) by Grant Sanderson, from the [3blue1brown Youtube Channel](https://www.youtube.com/channel/UCYO_jab_esuFRV4b17AJtAw/videos).
* [Tutorial: 3D Kinematics and Inverse Dynamics MATLAB scripts](https://uk.mathworks.com/matlabcentral/fileexchange/58021-3d-kinematics-and-inverse-dynamics?s_tid=prof_contriblnk) by Raphael Dumas, including some examples.
* [Tutorial: Musculoskeletal Model for Simulation of Walking](https://www.youtube.com/watch?v=Z4BoVVpju88) by Van den Bogert's tutorial (Dynamic Walking, 2011), including a section on computational muscle modelling and one on walking simulation using a 2D musculoskeletal model.
* [Tutorial: Kane’s Method for an inverted pendulum](https://figshare.com/articles/journal_contribution/Kane_pdf/7791647) by Ross Miller. A tutorial on Kane's Method for deriving equations of motion, demonstrated on an inverted pendulum.
* Set of MATLAB/Python models shared by Ross Miller (2019-2020): 
    - [Jumping model (5 dof)](https://figshare.com/articles/Jumping_model/7855673) 
    - [Jumping model with foot (6 dof)](https://figshare.com/articles/dataset/Jumping_model_with_foot/7856141)
    - [Sit-to-stand model](https://figshare.com/articles/software/Sit-to-stand_model/11987277)
    - [Elbow model in Matlab](https://figshare.com/articles/software/Elbow_model_in_Matlab/9983402)
* [Bayesian Data Analysis course](https://avehtari.github.io/BDA_course_Aalto) by AKi Vehtari at Aalto University (2020).</br>
:floppy_disk: [code](https://github.com/avehtari/BDA_course_Aalto) |
:page_facing_up: [book](https://users.aalto.fi/~ave/BDA3.pdf)
* [Anybodyrun](https://anybodyrun.com) by AnyBody Technology. This is a website where you can generate videos of full-body models of running based on principal components analysis. The approach behind the application is described on John Rasmussen's [blog](https://biomechanicsforeverybody.wordpress.com/).


### Books :blue_book:

* [Biomechanics and Motor Control of Human Movement (4th Edition)](https://edisciplinas.usp.br/pluginfile.php/4174628/mod_resource/content/2/David%20A.%20Winter-Biomechanics%20and%20Motor%20Control%20of%20Human%20Movement-Wiley%20%282009%29.pdf) by David A. Winter.
* [Calculus made Easy](http://calculusmadeeasy.org) by Silvanus P. Thompson.
* [Computer-Aided Analysis of Mechanical Systems](http://www.u.arizona.edu/~pen/ame553/) by P.E. Nikravesh (1998).
* [Computer Aided Kinematics And Dynamics Of Mechanical Systems](https://archive.org/details/computeraidedkinematicsanddynamicsofmechanicalsystems_202004/mode/2up) by Edward J. Haug (1989).
* [Convex Optimization](https://web.stanford.edu/~boyd/cvxbook/bv_cvxbook.pdf) by Steven Boyd and Lieven Vandenberghe (2004).
* [Dynamics: Theory and Applications](https://ecommons.cornell.edu/handle/1813/638) by Kane and Levinson (1985).
* [Dynamics of Human Gait (2nd Edition)](http://www.analizaruchu.awf.wroc.pl/materialy/vaughan-gaitbook.pdf) by Christopher Vaughan, Brian Davis and Jeremy O'Connor (1999).
* [Experimental Methods in Biomechanics (link)](https://www.springer.com/us/book/9783030522551) by John Challis (2021).
* [Reinforcement Learning: An Introduction](http://www.incompleteideas.net/book/the-book-2nd.html) by Richard S. Sutton and Andrew G. Barto (2018).
* [The ABC of EMG](https://hermanwallace.com/download/The_ABC_of_EMG_by_Peter_Konrad.pdf) by Peter Konrad (2005).

## Datasets :dvd:

### Human Anatomy :bone:

* **Visible Human Project**: public-domain library of cross-sectional cryosection, CT, and MRI images obtained from one male cadaver and one female cadaver. The dataset in NIfTI format, easier to import and use in segmentation software, were provided by Bart Bolsterlee (see further details [here](https://twitter.com/bartbolsterlee/status/1296594646898892800) and code for conversion [here](https://github.com/bartbols/VH2NIfTI)).      
:page_facing_up: [paper](https://doi.org/10.1109/5.662875) |
:dvd: [dataset](https://www.nlm.nih.gov/databases/download/vhp.html) |
:dvd: [dataset in NIfTI format](https://drive.google.com/drive/folders/1LBBIax6wpWBsiEcyXDrXNqyDSEB9rinO) |
:computer: [website](https://www.nlm.nih.gov/research/visible/visible_human.html) 
   
* **Visible Korean Human**: similar to the Visible Human Project but on Korean cadavers. Segmentated images are provided together with the section images.  
:page_facing_up: [paper](https://doi.org/10.1109/TMI.2004.842454) |
:dvd: [dataset](http://vkh.ajou.ac.kr/#vk) |
:computer: [website](http://vkh.ajou.ac.kr) (scroll down for English version)

* ~~**Chinese Visible Human**: similar to the Visible Human Project but on Chinese cadavers.~~ **the dataset does not seem to be available anymore**, despite being still listed on a [related website](https://appsrv.cse.cuhk.edu.hk/~vrcentre/index.html).  
:page_facing_up: [paper](https://dx.doi.org/10.1111%2Fj.0021-8782.2004.00274.x) |
:computer: [website](http://www.chinesevisiblehuman.com)

* **fastMRI dataset** by Facebook AI and NYU (2019-2020). Data from more than 1,500 fully sampled knee MRIs obtained on 3 and 1.5 Tesla magnets and DICOM images from 10,000 clinical knee MRIs also obtained at 3 or 1.5 Tesla. Includes also brain scans. **No segmentation available.**</br>
:page_facing_up: [paper](https://arxiv.org/abs/1811.08839?fbclid=IwAR1MuusEHDfRwQYb72OHKfdsL5F0OkCbdiI5wQsjJIQKMyAK-cao_wPYUN0) |
:computer: [website](https://fastmri.org/dataset) |
:star: [resources](https://github.com/facebookresearch/fastMRI/)

* **MRNet Dataset** by Stanford University Medical Center. The MRNet dataset consists of 1,370 knee MRI exams: 1,104 (80.6%) abnormal exams, with 319 (23.3%) ACL tears and 508 (37.1%) meniscal tears; labels were obtained through manual extraction from clinical reports. </br>
* :page_facing_up: [paper](https://journals.plos.org/plosmedicine/article?id=10.1371/journal.pmed.1002699) |
:dvd: [dataset](https://stanfordmlgroup.github.io/competitions/mrnet/) |
:computer: [website](https://stanfordmlgroup.github.io/competitions/mrnet/)

* **New Mexico Decedent Image Database (NMDID)** by HJH Edgar et al. (2020). NMDID includes whole body CT scans of over 15,000 New Mexicans who died between 2010-2017. Each individual is represented by approximately 10,000 images in DICOM format. Slice thickness is 1 mm with 0.5 mm overlap. Normal and thin slice reconstructions are available for bone, lung, and brain. 3D reconstructions are possible with this data, depending on what viewer you use. Metadata includes almost 60 variables about the individuals’ demography, life and death (accessible for research separately from the CT scans). </br>
:page_facing_up: [how to cite](https://nmdid.unm.edu/about/citation) |
[:dvd: dataset | :computer: website](https://nmdid.unm.edu)

* **Cancer Imaging Archive** is a service which de-identifies and hosts a large archive of medical images of cancer accessible for public download. The data are organized as “collections”; typically patients’ imaging related by a common disease (e.g. lung cancer), image modality or type (MRI, CT, digital distopathology, etc) or research focus. DICOM is the primary file format used by TCIA for radiology imaging. Supporting data related to the images such as patient outcomes, treatment details, genomics and expert analyses are also provided when available.</br>
[:dvd: dataset | :computer: website](https://www.cancerimagingarchive.net/)

* **An image-based kinematic model of the tibiotalar and subtalar joints and its application to gait analysis in children with Juvenile Idiopathic Arthritis** by Erica Montefiori et al. (2019). Study with twenty enrolled participants. For each participant, the opensim model of the foot and ankle joint complex and the relative bone geometries were shared, together with motion capture data (marker data) and results of inverse kinematics simulations for around six gait trials per participant.</br>
:page_facing_up: [paper](https://doi.org/10.1016/j.jbiomech.2018.12.041) |
:dvd: [dataset](https://figshare.shef.ac.uk/articles/Data_for_paper_An_image-based_kinematic_model_of_the_tibiotalar_and_subtalar_joints_and_its_application_to_gait_analysis_in_children_with_Juvenile_Idiopathic_Arthritis_/5863443/1)

* **Development and validation of statistical shape models of the primary functional bone segments of the foot.** by Tamara Grant et al. (2019). Dataset includes manually segmented three-dimensional bone geometry models (.STL) from magnetic resonance images of 34 subjects of first metatarsal (29 geometries), midfoot (second-to-fifth metatarsals, cuneiforms, cuboid, and navicular) (33 geometries), calcaneus (27 geometries), and talus (34 geometries). **not all geometries are used**.
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3464747.svg)](https://doi.org/10.5281/zenodo.3464747)</br>
:page_facing_up: [paper](https://doi.org/10.7717/peerj.8397) |
:dvd: [dataset](https://zenodo.org/record/3464747#.X0P2qMhKgdU)

* **Are Subject-Specific Musculoskeletal Models Robust to the Uncertainties in Parameter Identification?** by  by Giordano Valente et al. (2014). Dataset includes MRI scans on a single healthy male participant and gait lab data of a single gait cycle.</br>
:page_facing_up: [paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0112625) |
:dvd: [dataset](https://simtk.org/projects/subspecmodeling)

* **MB Knee: Multibody Models of the Human Knee** by Trent Guess. The data set includes four knee models, one based on in vivo measurements from a 29 year old female and three based on cadaver knees that were physically tested in a dynamic knee simulator. Knee geometries (bone, cartilage, and menisci) were derived from Magnetic Resonance Imaging (MRI) and ligament insertions come from MRI, the literature, and probing the cadaver knees. The site also contains information on ligament modeling, such as bundle insertion locations and zero load lengths.  
:dvd: [dataset](https://simtk.org/projects/mb_knee)

* **OpenKnee** by Ahmet Erdemir et al. Open Knee(s) is aimed to provide free access to three-dimensional finite element representations of the knee joint. Dataset includes one knee specimen from the first generation of data collected and 21 specimens (knee id up to 22, missing one) for second generation.</br>
:page_facing_up: [paper 2021 (MRI and mechanical testing)](https://doi.org/10.1016/j.dib.2021.106824) |
:page_facing_up: [paper 2016](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4876308/) |
:page_facing_up: [paper 2013](https://doi.org/10.1115/FMD2013-16033) |
:page_facing_up: [ASB abstract 2010](http://www.asbweb.org/conferences/2010/abstracts/181.pdf) |
:page_facing_up: [User's Guide 2010](https://simtk.org/websvn/wsvn/openknee/_gen1/doc/guide.pdf) |
:dvd: [dataset](https://simtk.org/projects/openknee)

* **Subject-specific muscle properties from diffusion tensor imaging significantly improve the accuracy of musculoskeletal models** by James Charles et al. (2020). Includes MRI scans (T1‐weighted anatomical turbo spin‐echo and diffusion tensor imaging) and Isokinetic and isometric torque measurement from 10 subjects (5 female). MRI images are segmented and processed to obtain muscle architecture.  
:page_facing_up: [paper](https://doi.org/10.1111/joa.13261) |
:dvd: [dataset](http://datacat.liverpool.ac.uk/1105/)

* **The Virtual Skeleton Database: An Open Access Repository for Biomedical Research and Collaboration** by Michael Kistler et al. (2013). Dataset including post mortem CT images of 50 subjects. **Despite several attempts I was never granted access to these data, although I know of others who did.**  
:page_facing_up: [paper](https://dx.doi.org/10.2196%2Fjmir.2930) |
:dvd: [dataset](https://www.smir.ch/objects/214315) |
:computer: [website](https://www.smir.ch/)
   * _SMIR pelves and selected pelvic landmarks_ from five experienced raters (20 pelves). ![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3384055.svg)</br>
   :page_facing_up: [paper](https://www.nature.com/articles/s41598-019-49573-4) |
   :dvd: [dataset](https://doi.org/10.5281/zenodo.3384055)
   * _SMIR pelves and femurs_ segmented bone from 20 CT scans available in MATLAB format.  
   :dvd: [dataset](https://github.com/RWTHmediTEC/VSDFullBodyBoneModels)

* **The Osteoarthritis Initiative** The Osteoarthritis Initiative (OAI) is a multi-center, ten-year observational study of men and women, sponsored by the National Institutes of Health (part of the Department of Health and Human Services). The goals of the OAI are to provide resources to enable a better understanding of prevention and treatment of knee osteoarthritis, one of the most common causes of disability in adults. The dataset contains the permanent archive of the clinical data, patient reported outcomes, biospecimen analyses, quantitative image analyses, radiographs (X-Rays) and magnetic resonance images (MRIs) acquired during this study. There are longitudinal assessments and measurements from 4,796 subjects, with data from over 431,000 clinical and imaging visits, and almost 26,626,000 images.</br>
:computer: [website](https://nda.nih.gov/oai)

* **BodyParts3D** by Nobutaka Mitsuhashi et al. (2003). This is a 3D structure database for anatomical concepts that extends beyond biomechanics.  
:page_facing_up: [paper](https://doi.org/10.1093/nar/gkn613) |
:dvd: [dataset](http://lifesciencedb.jp/bp3d/) 

* **Femur and tibia surface mesh set** by Daniel Nolte et al. (2020). The data set contains bone geometries of the left and right thigh (femur) and shank (tibia and fibula) segmented from magnetic resonance (MR) scans of 35 healthy volunteers (22 male, 13 female). [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.167808.svg)](https://doi.org/10.5281/zenodo.167808)</br>
:page_facing_up: [paper](https://doi.org/10.1016/j.gaitpost.2020.02.010) |
:dvd: [dataset](https://zenodo.org/record/167808#.X0O4kMhKgdV)

* **MRI-based anatomical characterisation of lower-limb muscles in older women** by Erica Montefiori et al. (2020). The dataset contains segmentations for the eleven subjects investigated in the study (mean (sd), age: 69 (7), mass: 66.9 (7.7) kg, height: 159 (3) cm). Segmentations include 1) bone and soft tissue (skin), 2) muscle volumes and 3) muscle centrelines. The first two are in stl format, the latter in vtk format.</br>
:page_facing_up: [paper](https://doi.org/10.1371/journal.pone.0242973) |
:dvd: [dataset](https://figshare.shef.ac.uk/articles/dataset/Data_for_paper_MRI-based_anatomical_characterisation_of_lower-limb_muscles_in_older_women_/9934055/2)

* **Natural Knee Data** by University of Denver Center for Orthopaedic Biomechanics. CT and MRI images are provided for 7 knee specimens (5 cadaveric subjects) plus solid models  created from the CT images. In addition, during dissection of the knees, surfaces and ligament insertions and origins were outlined on the bones and recorded as probed points.  
:dvd: [dataset](https://digitalcommons.du.edu/natural_knee_data) |
:computer: [website](https://simtk.org/projects/knee_model)

* **Living Biomechanics of the Knee** by University of Denver Center for Orthopaedic Biomechanics.  Kinematic and loading data from an experiment that used quadriceps force to extend the knee. The objective of this data was to provide a foundation to create a computer model representation of the patella joint in order to predict motion and forces across healthy and pathological specimens.</br>
:dvd: [dataset](https://digitalcommons.du.edu/living_kinematics_knee/) |
:computer: [website](https://simtk.org/projects/knee_model)

* **Twente Lower Extremity (TLEM) Dataset** by Martin Klein Horsman et al. (2007). Anatomical data intended for musculoskeletal modelling obtained by the dissection of a single male cadaver.  
:page_facing_up: [PhD thesis](https://research.utwente.nl/en/publications/the-twente-lower-extremity-model-consistent-dynamic-simulation-of)
:page_facing_up: [paper](https://doi.org/10.1016/j.clinbiomech.2006.10.003) |
:dvd: [dataset (paywalled)](https://ars.els-cdn.com/content/image/1-s2.0-S0268003306001896-mmc1.doc)

* **TLEM2.0: A New Complete and Consistent Musculoskeletal Geometry Dataset for Subject-Specific Modelling of the Lower Extremity** by Vincenzo Carbone and René Fluit et al. (2015. New comprehensive dataset of the musculoskeletal geometry of the lower extremity, which is based on medical imaging data and dissection performed on the right lower extremity of a fresh male cadaver. A complete cadaver dissection was performed, in which bony landmarks, attachments sites and lines-of-action of 55 muscle actuators and 12 ligaments, bony wrapping surfaces, and joint geometry were measured.  
:page_facing_up: [paper](https://doi.org/10.1016/j.jbiomech.2014.12.034) |
:dvd: [dataset (requires registration)](https://tlemsafe.eu/) |
:computer: [website](https://tlemsafe.eu/)

* **Shoulder morphological data** by the Dutch Shoulder Group. Includes data about mass and inertia, muscle contraction parameters and muscle geometries collected during several studies performed in 1988-2002 period.</br>
:page_facing_up: [paper1991](http://homepage.tudelft.nl/g6u61/repository/shoulder/files_to_link/JB1991_Veeger.pdf) |
:page_facing_up: [paper1992](http://homepage.tudelft.nl/g6u61/repository/shoulder/files_to_link/JB1992_Helm.pdf) |
:dvd: [dataset](http://homepage.tudelft.nl/g6u61/repository/shoulder/overview.htm)

* **Twente spine model** by Riza Bayoglu et al. (2017). This dataset represents a complete and coherent dataset for the lumbar spine, based on medical images and dissection measurements from one embalmed human cadaver. </br>
:page_facing_up: [paper-lumbar spine](https://doi.org/10.1016/j.jbiomech.2017.01.009) |
:page_facing_up: [paper-thoracic and cervical](https://doi.org/10.1016/j.jbiomech.2017.04.003) |
:page_facing_up: [PhD thesis](https://research.utwente.nl/en/publications/twente-spine-model-development-validation-and-application-of-a-co) |
[:computer: website | :dvd: dataset](https://www.twentespinemodel.eu/) 

* **Hand and Wrist Dataset** by Goislard de Monsabert et al. (2018). Data set intended for modelling including the musculoskeletal geometry and muscle morphology from the elbow to the finger tips. Clinical imaging, optical motion capture and microscopy were used to create a dataset from a single specimen.  
:page_facing_up: [paper](https://link.springer.com/article/10.1007/s10439-017-1936-z#SecESM1) |
:dvd: [dataset](https://static-content.springer.com/esm/art%3A10.1007%2Fs10439-017-1936-z/MediaObjects/10439_2017_1936_MOESM1_ESM.pdf)

* **The digital human forearm and hand** by Faes D. Kerkhof et al. (2018). An un‐embalmed cadaveric arm was digitized using 7T MRI and CT scans and 3D geometrical models of bones, cartilage, muscle and muscle pathways were generated.  Muscle volume, mass, length, pennation angle, physiological cross‐sectional area, tendon length were measured during dissection and, after that, muscle biopsies were used to visualize and measure sarcomere lengths with confocal microscopy. The result is an integrated anatomical dataset that can be used for creating complete and accurate musculoskeletal models of the hand.</br>
:page_facing_up: [paper](https://doi.org/10.1111/joa.12877) |
:dvd: [dataset](https://www.morphosource.org/Detail/MediaDetail/Show/media_id/21064)

* **Hand muscles attachments: A Geometrical model** by Havelková L et al. (2020).  Sixteen cadaveric preparations were dissected to draw up the anatomical maps including the position of muscle attachments, dimensions, shapes, cross section areas and variations. The magnetic resonance imaging of cadaveric upper extremity was performed to reconstruct the geometry of all bones and hand muscles.</br>
:page_facing_up: [dataset paper (not published yet)]() |
:page_facing_up: [AnyBody model's paper](https://doi.org/10.1080/10255842.2020.1851367) |
:dvd: [dataset](https://zenodo.org/record/3954024#.X-zKitj7QdV)

* **Muscle Modelling Database** by Ross Miller (2018). A summary of muscle mechanical parameters in the human lower limb from the anatomy, muscle/exercise physiology, and biomechanics literature for use in Hill-based muscle model.  
:page_facing_up: [paper](https://link.springer.com/referenceworkentry/10.1007%2F978-3-319-30808-1_203-2) |
:dvd: [dataset](https://figshare.com/articles/dataset/Muscle_model_parameters/4275854)

<!--* **Cal Poly Human Motion Biomechanics Lab Knee Joint Finite Element Model** https://simtk.org/projects/cphmbkneefem/ -->

### Animal Anatomy :crocodile:

* **CT scans of various animals** from John Hutchinson's group. </br> 
:dvd: [dataset](https://osf.io/4sc96/)

* **Digital Morphology Museum of Kyoto University (KUPRI)**: The Digital Morphology Museum (DMM) provides an environment in which you can readily examine skeletal anatomy using the Primate Research Institute’s (PRI) collection of CT and MRI tomography scans. The goal of this site is to enable you to view the scans of non-human primates and mammals and to download scan data from our database for your original research. </br>
:computer: [website](http://dmm.pri.kyoto-u.ac.jp/dmm/WebGallery/index.html)

* **DigiMorph**: Digital Morphology library is a dynamic archive of information on digital morphology and high-resolution X-ray computed tomography of biological specimens. </br> 
:computer: [website](http://digimorph.org)

* **eLucy** by the Dept of Anthropology of University of Texas at Austin. eLucy is dedicated to sharing information about 'Lucy', an early fossil hominin represented by the 3.2 million year old remains of a relatively complete skeleton. Through this website is possible to request access for research and teaching purposes to the digital reconstruction (STL files) of right shoulder and left knee of ‘Lucy’, an early fossil hominin (_Australopithecus afarensis_) represented by the 3.2 million year old remains of a relatively complete skeleton.</br>
:page_facing_up: [paper](http://dx.doi.org/10.1038/nature19332) |
:computer: [website](https://elucy.org/) 

* **Genetics of craniofacial shape in Mus** by Murat Maga (2017). This dataset includes ~500 high-resolution 3D mouse head microCT scans, associated anatomical landmarks, and individual genotypes suitable to study quantitative genetics of head shape. Scans are of a mouse panel between C57BL/6J and A/J mouse strains and associated genotype data.</br>
:computer: [website](https://osf.io/w4wvg/)

* **GB3D Type Fossils Online project** aims to develop a single database of the type specimens, held in British collections, of macrofossil species and subspecies found in the UK, including links to photographs (including 'anaglyph' stereo pairs) and a selection of 3D digital models.</br>
:dvd: [dataset](http://www.3d-fossils.ac.uk/search.cfm) |
:computer: [website](http://www.3d-fossils.ac.uk/home.html)|
:camera: [introductory video](https://www.youtube.com/watch?v=bXhhmS-HGEI&feature=emb_logo)

* **Phenome10K**: A free online repository for 3-D scans of biological and palaeontological specimens. This site provides 3D scans – CT and surface – of biological and palaeontological specimens for free download by the academic and educational community.</br> 
:dvd: [dataset](http://pantodon.science.helsinki.fi/morphobrowser/sp_list.php) |
:computer: [website](https://phenome10k.org)

* **MorphoBrowser** by Jukka Jervall et al. MorphoBrowser is a 3D visualisation and searching tool for mammalian teeth, accessible over the web. It allows the user to ‘browse’ through the diverse range of tooth morphologies found in mammals, both extinct and extant.</br>
:computer: [website](http://morphobrowser.biocenter.helsinki.fi/)

* **MorphoMuseuM (M3)**: is a peer reviewed, online journal that publishes 3D models of vertebrates, including models of type specimens, anatomy atlases, reconstruction of deformed or damaged specimens, and 3D datasets. </br>
:computer: [website](https://morphomuseum.com/collections)

* **MorphoSource** by Duke University. MorphoSource has approximately 27,000 published 3D models of biological specimens (largely skeletal material). You can view all of these in your web browser with no required software. Around 13,000 of these are open access and can be freely downloaded for further visualization or measurement.</br>
:computer: [website](https://www.morphosource.org)

* **The Open Research Scan Archive (formerly: Penn Cranial CT Database)** by the University of Pennsylvania Museum of Archaeology and Anthropology (curators: Thomas Schoenemann and Janet Monge). contains high resolution (sub-millimeter) scans of human and non-human crania from the Penn University Museum and other institutions. The collection includes approximately 1800 crania (1200 from the Samuel George Morton Collection, then extended by J. Aitken Meigs).</br>
:computer: [website](https://penn.museum/sites/orsa/Overview.html)


### Balance :balance_scale:

* **Standing Balance Experiment with Long Duration Random Pulses Perturbation** by Huawei Wang and Ton van den Bogert (2020). The data-set includes the perturbation reaction data from eight subjects. Each subject performed four experiment trials, including two quiet standing and two perturbed trials. Each trial lasted five minutes for a total of 80 minutes quiet standing and 80 minutes perturbed standing data. Recorded information including three dimensional trajectories of thirty-two markers (27 on subjects' trunk and legs and 5 on the treadmill frame), six dimensional ground reaction forces, and nine Electromyography signals (EMGs, on subjects' right leg). [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3819630.svg)](https://doi.org/10.5281/zenodo.3819630) </br>
:page_facing_up: [paper](https://doi.org/10.1016/j.jneumeth.2020.108580) |
:dvd: [dataset](https://zenodo.org/record/3819630#.X2JMTmhKgdU) 

* **BDS: A public data set of human balance evaluations** by Damiana dos Santos and Marco Duarte (2016). The data set comprises signals from the force platform (raw data for the force, moments of forces, and centers of pressure) of 163 subjects plus one file with information about the subjects and balance conditions and the results of the other evaluations. Subject’s balance was evaluated by posturography using a force platform and by the Mini Balance Evaluation Systems Tests in four conditions (standing still for 60 s on a rigid surface with eyes open; on a rigid surface with eyes closed; on an unstable surface with eyes open; on an unstable surface with eyes closed). Each condition was performed three times and the order of the conditions was randomized among subjects.</br>
:page_facing_up: [paper](https://peerj.com/articles/2648/) |
:dvd: [dataset](https://figshare.com/articles/A_public_data_set_of_quantitative_and_qualitative_evaluations_of_human_balance/3394432) |
:computer: [website](http://pesquisa.ufabc.edu.br/bmclab/datasets/bds/) |
:star: [resources](https://github.com/BMClab/datasets/tree/master/BDS)

* **PDS: A data set with kinematic and ground reaction forces of human balance** by Damiana dos Santos et al. (2017). This data set comprises signals from two force platforms (raw data for the force, moments of forces, and center of pressure) and the full-body three-dimensional kinematics of 49 subjects plus one file with meta data about the subjects and balance conditions and the results. </br>
:page_facing_up: [paper](https://peerj.com/articles/3626/) |
:dvd: [dataset](https://figshare.com/articles/A_data_set_with_kinematic_and_ground_reaction_forces_of_human_balance/4525082) |
:computer: [website](http://pesquisa.ufabc.edu.br/bmclab/datasets/pds/)

### Energetics :fire:

* **ISB2019 Metabolic cost session_: Data for participants in ISB2019 session on model-based prediction of the metabolic cost of human locomotion.** by Ross Miller (2019).</br>
:page_facing_up: [users' guide](https://figshare.com/articles/journal_contribution/User_Guide/7086770) |
:dvd: [dataset](https://figshare.com/projects/ISB2019_Metabolic_cost_session/38738)

* **Dataset for Metabolic Cost Calculations of Gait using Musculoskeletal Energy Models, a Comparison Study** by Anne D. Koelewijn et al. (2019). The data set contains raw and processed data of gait analysis experiments of level and inclined walking at two speeds for 12 participants. The slopes were uphill and downhill with 8% incline. The raw data contains the output of the force plates and marker data, as well as raw measurements from an K4B2 system. [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1973799.svg)](https://doi.org/10.5281/zenodo.1973799)</br>
:page_facing_up: [paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0222037) |
:dvd: [dataset](https://zenodo.org/record/1973799#.X0PtVshKgdU)


### Walking :walking:

* **A database of human gait performance on irregular and uneven surfaces collected by wearable sensors** by Luo et al. (2020). Data from Inertial Measurement Units (IMU) from thirty participants (fifteen males and fifteen females, 23.5 ± 4.2 years, 169.3 ± 21.5 cm, 70.9 ± 13.9 kg) who wore six IMUs while walking on nine outdoor surfaces with self-selected speed (16.4 ± 4.2 seconds per trial). Intended for machine learning purposes.</br>
:page_facing_up: [paper](https://www.nature.com/articles/s41597-020-0563-y) |
:dvd: [dataset](https://doi.org/10.6084/m9.figshare.c.4892463) |
:dvd: [metadata](https://springernature.figshare.com/articles/Metadata_record_for_A_database_of_human_gait_performance_on_irregular_and_uneven_surfaces_collected_by_wearable_sensors/12505022) |
:star: [resources](https://github.com/UF-ISE-HSE/UnevenWalkingSurface)

* **An Open Data Set of Inertial, Magnetic, Foot–Ground Contact, and Electromyographic Signals From Wearable Sensors During Walking.** by Miraldo DC, Watanabe RN and Duarte M (2020).  Data were acquired from 22 healthy adults using wearable sensors and walking at self-selected comfortable, fast and slow speeds, and standing still. In total, there are data of 9,661 gait strides. The dataset includes gait events and notebooks exemplifying how to access and visualize the data.  
:page_facing_up: [paper](https://doi.org/10.1123/mc.2020-0023) |
:dvd: [dataset](https://figshare.com/articles/Dataset_of_gait_and_inertial_sensors/7778255) |
:computer: [website](http://pesquisa.ufabc.edu.br/bmclab/datasets/geds/) |
:star: [resources](https://github.com/BMClab/datasets/tree/master/GEDS)

* **A multimodal dataset of human gait at different walking speeds established on injury-free adult participants** by Céline Schreiber & Florent Moissenet (2019). Dataset collected on 50 healthy and injury-free adults, with no lower and upper extremity surgery in the last two years. Participants walked at 5 speeds during one unique session. Three dimensional trajectories of 52 reflective markers spread over the whole body, 3D ground reaction forces and moment, and electromyographic signals were simultaneously recorded.  
:page_facing_up: [paper](https://www.nature.com/articles/s41597-019-0124-4) |
:dvd: [dataset](https://doi.org/10.6084/m9.figshare.7734767)

* **A public data set of overground and treadmill walking kinematics and kinetics of healthy individuals** by Claudiane A. Fukuchi et al. (2018). Dataset of 42 healthy volunteers (24 young adults and 18 older adults) who walked both overground and on a treadmill at a range of gait speeds.  
:page_facing_up: [paper](https://peerj.com/articles/4640) |
:dvd: [dataset](https://figshare.com/articles/dataset/A_public_data_set_of_overground_and_treadmill_walking_kinematics_and_kinetics_of_healthy_individuals/5722711/4) |
:computer: [website](http://pesquisa.ufabc.edu.br/bmclab/datasets/wbds/)

* **An elaborate data set on human gait and the effect of mechanical perturbations** by Jason Moore et al. (2015). Gait data set collected from fifteen subjects walking at three speeds on an instrumented treadmill. Each trial consists of 120 s of normal walking and 480 s of walking while being longitudinally perturbed during each stance phase with pseudo-random fluctuations in the speed of the treadmill belt.  
:page_facing_up: [paper](https://doi.org/10.7717/peerj.918) |
:dvd: [dataset](https://zenodo.org/record/13030#.Xz1FeehKgdU) |
:computer: [resources](https://github.com/csu-hmc/perturbed-data-paper) 

* **Human kinematic, kinetic and EMG data during level walking, toe/heel-walking, stairs ascending/descending** by Tiziana Lencioni et al. (2019). kinematic, kinetic and electromyographic (EMG) data acquired from 50 healthy subjects (age between 6 and 72 years) during level walking at different velocities, toe- and heel-walking, stairs ascending and descending.</br>
:page_facing_up: [paper](https://www.nature.com/articles/s41597-019-0323-z) |
:dvd: [dataset](https://springernature.figshare.com/collections/Human_kinematic_kinetic_and_EMG_data_during_level_walking_toe_heel-walking_stairs_ascending_descending/4494755/1)

* **Multiple Speed Walking Simulations** by May Liu et al. (2008). Data set with eight subjects (two males) walking overground at very slow, slow, free, and fast speeds.</br>
:page_facing_up: [paper](https://doi.org/10.1016/j.jbiomech.2008.07.031) |
:dvd: [dataset](https://simtk.org/projects/mspeedwalksims) 

* **Normative gait data** from Chris Kirtley's [website](http://www.clinicalgaitanalysis.com/) on clinical gait analysis. **Website does not seem maintained.**  
:computer: [website](http://www.clinicalgaitanalysis.com/data/) 

* **2-D walking: kinematics and force plate data** by David Winter. Originally published as Appendix in the book _Biomechanics and Motor Control of Human Movement_, 2nd edition, John Wiley & Sons, 1990.</br>
:computer: [website](https://isbweb.org/resources/data-resources/140-movement-data/508-gait-data) |
:dvd: [dataset](https://isbweb.org/docs/resources/data-resources/gait-data/266-winter-zip)


* **GaitRec, a large-scale ground reaction force dataset of healthy and impaired gait** by Horsak et al. (2020). GAITREC is a comprehensive and annotated large-scale dataset containing bi-lateral GRF walking trials of 2,084 patients with various musculoskeletal impairments and data from 211 healthy controls. The data sum up to a total of 75,732 bi-lateral walking trials.</br>
:page_facing_up: [paper](https://www.nature.com/articles/s41597-020-0481-z) |
:dvd: [dataset](https://doi.org/10.6084/m9.figshare.c.4788012)


### Running :running:

* **A public data set of running biomechanics and the effects of running speed on lower extremity kinematics and kinetics** by Reginaldo K. Fukuchi et al. (2017). The lower-extremity kinematics and kinetics data of 28 regular runners were collected using a three-dimensional (3D) motion-capture system and an instrumented treadmill while the subjects ran at 2.5 m/s, 3.5 m/s, and 4.5 m/s wearing standard neutral shoes.  
:page_facing_up: [paper](https://peerj.com/articles/3298) |
:dvd: [dataset](https://figshare.com/articles/A_comprehensive_public_data_set_of_running_biomechanics_and_the_effects_of_running_speed_on_lower_extremity_kinematics_and_kinetics/4543435/4) |
:computer: [website](http://pesquisa.ufabc.edu.br/bmclab/datasets/rbds/)

* **Ground reaction force metrics are not strongly correlated with tibial bone load when running across speeds and slopes: implications for science, sport and wearable tech**  by Emily Matijevich et al. (2019). Includes ten healthy individuals that performed running trials while GRFs and kinematics were collected. [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3460691.svg)](https://doi.org/10.5281/zenodo.3460691)    
:page_facing_up: [paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0210000) |
:dvd: [dataset and resources](https://zenodo.org/record/3460691#.Xz-1tuhKgdU)

* **Muscle contributions to mass center accelerations over a range of running speeds** by Samuel Hamner and Scott Delp (2013). Repository of experimental data (i.e., motion capture, EMG, GRFs), subject-specific models, and muscle-driven simulation results of 10 male subject running across a range of speeds: 2 m/s, 3 m/s, 4 m/s, and 5 m/s.   
:page_facing_up: [paper](https://doi.org/10.1016/j.jbiomech.2012.11.024) |
:dvd: [dataset](https://simtk.org/projects/nmbl_running/)

* **Simulated muscle fiber lengths and velocities during walking and running** by Edith Arnold et al. (2013). Models and results for simulations of muscle fiber dynamics for five subjects walking at four speeds and running at four speeds. **The subject numbers are noncontiguous to maintain alignment with the related project: https://simtk.org/projects/nmbl_running**.  
:page_facing_up: [paper](https://jeb.biologists.org/content/216/11/2150) |
:dvd: [dataset](https://simtk.org/projects/muscfib_walkrun)

* **Muscle function of overground running across a range of speeds** by Tim Dorne et al. (2012). Running data and musculoskeletal models for a single representative subject (JA1). Actual running speeds: 3.56 m/s, 5.20 m/s, 7.00 m/s and 9.49 m/s.  
:page_facing_up: [paper](https://doi.org/10.1242/jeb.064527) |
:dvd: [dataset](https://simtk.org/projects/runningspeeds)

### Instrumented Prostheses :chart_with_upwards_trend:

* **Grand Challenge Competition to Predict In Vivo Knee Loads** By BJ Fregly et al. (2012). Data sets from instrumented knee prostheses used in the "Grand Challenge Competition". Data include medical images and segmentations (for most participants), tibial contact force, video motion, ground reaction, muscle EMG, muscle strength, static and dynamic imaging, and implant geometry data for six patients. This is the most completely and easily accessible dataset of measurements from instrumented prostheses.   
:page_facing_up: [paper1](https://doi.org/10.1002/jor.22023) |
:page_facing_up: [paper2](https://doi.org/10.1115/1.4023255) |
:dvd: [dataset](https://simtk.org/projects/kneeloads)

* **Orthoload** by the Julius Wolff Institute of the Charité in Berlin. This online dataset includes loads occuring in human joints measured directly in patients by using instrumented hip, knee, shoulder and spinal implants. OrthoLoad supplies numerical load data and videos, which contain load-time diagrams and synchronous images of the subject’s activities. **No joint kinematics available outside `larger cooperative projects`, except few sample data:**.  
:page_facing_up: [publication list](https://orthoload.com/publications/) |
:dvd: [dataset hip](http://www.wiki.orthoload.com/index.php?title=Hip_joint_III) |
:dvd: [dataset knee](http://www.wiki.orthoload.com/index.php?title=Knee_joint) |
:dvd: [dataset shoulder](http://www.wiki.orthoload.com/index.php?title=Shoulder_joint) |
:dvd: [dataset spine](http://www.wiki.orthoload.com/index.php?title=Vertebral_body_replacement) |
:dvd: [sample comprehensive](https://orthoload.com/comprehensive-data-sample) |
:computer: [website](https://orthoload.com/)

* **HIP98** by Georg Bergmann et al. (1998). The data collection CD-ROM HIP98 contains the forces acting in the hip joint during the most common activities of daily living. Measurements were taken 1998 in 4 subjects (implant loads, synchronous videos, gait analysis data, calculated muscle forces, EMG signals and numbers for the frequencies of the different activities).The loads acting in a ’typical’ or representative subject are also provided. **Issues in installing the database in recent Microsoft operative systems. The data will be extracted but the GUI will not work.**  
:page_facing_up: [paper](https://doi.org/10.1016/s0021-9290(01)00040-9) |
:dvd: [dataset](https://orthoload.com/wp-content/uploads/hip98.zip) |
:computer: [website](https://orthoload.com/test-loads/data-collection-hip98)

* **CAMS-KNEE** by William Taylor et al. (2017). Datasets collected on a cohort of 6 subjects with instrumented knee implants (Charité – Universitätsmedizin Berlin) synchronized with a moving fluoroscope (ETH Zürich) and other measurement techniques (whole body kinematics, ground reaction forces, video data, and electromyography data) for multiple complete cycles of 5 activities of daily living. **Data must be requested submitting a project description.** I was NOT granted access to the entire data set for exploring the dataset.  
**Link to live dataset is broken.**  </br>
:page_facing_up: [paper](https://doi.org/10.1016/j.jbiomech.2017.09.022) |
:cd: [data request](https://cams-knee.orthoload.com/data/data-request/) |
:cd: [live dataset (CAMS-KNEE workshop)](https://cams-knee.orthoload.com/workshop-data/) |
:computer: [website](https://cams-knee.orthoload.com/)

### Upper Limb :muscle:

* **Shoulder movements database** by Bart Bolsterlee et al. (2013). Data for five subjects (2 females, age 29.2 ± 2.3 year, height 176.3 ± 7.2 cm) performing range of motion and activities of daily living for the shoulder. Dataset includes kinematic, force and EMG data. A user guide and Matlab scripts are also available. </br>
:page_facing_up: [paper](https://link.springer.com/article/10.1007%2Fs11517-013-1065-2) |
:dvd: [dataset](https://simtk.org/frs/?group_id=465) |
:computer: [website](https://simtk.org/projects/dsem)

### Hand :palms_up_together:

* **A large calibrated database of hand movements and grasps kinematics** by Néstor J. Jarque-Bou et al. (2020). The dataset includes calibrated kinematic data for 77 subjects and 40 movements (each repeated several times), resulting in the largest available kinematic dataset. The dataset derives from three multimodal datasets, previously released (Ninapro DB1, DB2 and DB5, that include electromyography, inertial and dynamic data). Hand kinematics was measured for all subjects using a 22-sensor CyberGlove II data glove. [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3357966.svg)](https://doi.org/10.5281/zenodo.3357966)</br>
:page_facing_up: [paper](https://www.nature.com/articles/s41597-019-0349-2) |
:dvd: [dataset](https://zenodo.org/record/3480074#.X1_ocWhKgdU) |
:star: [code](https://zenodo.org/record/3357966#.X1_n9mhKgdU)

### Soft Tissue Artefacts :leg:

* **Standardization proposal of soft tissue artefact description for data sharing in human motion measurements** by Andrea Cereatti et al. (2017). This dataset includes open-access and standard-format soft tissues artefact data from several previous studies (both upper and lower limbs) that will be useful for the evaluation and development of bone pose estimators in three-dimensional human movement analysis. </br>
:page_facing_up: [paper](https://doi.org/10.1016/j.jbiomech.2017.02.004) |
:dvd: [dataset (journal website)](https://ars.els-cdn.com/content/image/1-s2.0-S0021929017301008-mmc2.zip) |
:dvd: [dataset (GitHub](https://github.com/STAOpenData/Data) |
:page_facing_up: [description of included datasets](https://ars.els-cdn.com/content/image/1-s2.0-S0021929017301008-mmc1.docx)

* **To what extent is joint and muscle mechanics predicted by musculoskeletal models sensitive to soft tissue artefacts?** by Giuliano Lamberto et al. (2017). Models and data used in the the paper to simulate the soft tissue artefacts occurring during gait and their influence on the internal forces estimated by three musculoskeletal models of the lower limb.</br>
:page_facing_up: [paper](https://doi.org/10.1016/j.jbiomech.2016.07.042) |
:dvd: [simulations data](https://figshare.shef.ac.uk/articles/dataset/To_what_extent_is_joint_and_muscle_mechanics_predicted_by_musculoskeletal_models_sensitive_to_soft_tissue_artefacts_/3502652)


### Health Datasets :heart:

* **Secure Anonymised Information Linkage (SAIL) Databank**: databank of anonymised data about the population of Wales. It ensures robust secure storage and use of anonymised person-based data for research to improve health, well-being and services.The Health section includes many aspects of population health, primary and secondary care, and social care services.</br>
:dvd: [Health datasets](https://data.ukserp.ac.uk/Organisation/Category?nodeId=1&orgId=0) |
:computer: [website](https://saildatabank.com/)

* **UK Biobank** is a health resource that follows the health and well-being of 500,000 volunteer participants and provides health information, which does not identify them, to approved researchers in the UK and overseas. The aim of UK Biobank is to improve the prevention, diagnosis and treatment of a wide range of serious and life-threatening illnesses – including cancer, heart diseases, stroke, diabetes, arthritis, osteoporosis, eye disorders, depression and forms of dementia. </br>
:computer: [website](https://www.ukbiobank.ac.uk/)


## Gait Analysis and Motion Capture :cartwheeling:

### Gait Analysis Markersets [TODO: add references and resources]

* CAST
* IORGait
* [LAMB](https://journals.sagepub.com/doi/10.1177/0954411919827033) by Marco Rabuffetti et al. (2019).
* SAFLo
* T3Dg

### Motion Capture Data Import and Processing [WIP]

* [c3dserver](https://www.c3dserver.com/) C++/MATLAB)

* **PyC3Dserver** by Moon Ki Jung (2020). Python interface of C3Dserver software for reading and editing C3D motion capture files. [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3942388.svg)](https://doi.org/10.5281/zenodo.3942388)</br>
:floppy_disk: [source](https://github.com/mkjung99/pyc3dserver)

* [ezc3d: An easy C3D file I/O cross-platform solution for C++, Python and MATLAB](https://github.com/pyomeca/ezc3d) (C++/MATLAB/Python) by Benjamin Michaud et al. (2021). Ezc3d is a light and comprehensive library that allows to easily read and write c3d files. The C++ core includes an API for fast file I/O library, and convenient MATLAB and Python3 interfaces for researchers. It supports c3d files from the main biomechanics companies, namely: Vicon, Qualisys, Optotrak, BTS and XSens.</br>
:page_facing_up: [paper](https://joss.theoj.org/papers/10.21105/joss.02911) |
:computer: [documentation website](https://pyomeca.github.io/Documentation/ezc3d/) |
:floppy_disk: [source](https://github.com/pyomeca/ezc3d)

* **BTK - Biomechanical ToolKit** by Arnault Barre and Stephane Armand (2014). One of the most versatile, robust and reliable libraries for reading, importing nad handling motion capture data. Written in C++ with MATLAB and Python bindings. A fork of this library is used for importing c3d in OpenSim. </br>
:page_facing_up: [paper](https://doi.org/10.1016/j.cmpb.2014.01.012) |
:computer: [website](http://biomechanical-toolkit.github.io/)
:floppy_disk: [source](https://github.com/Biomechanical-ToolKit/BTKCore) |
:floppy_disk: [conda](https://anaconda.org/conda-forge/btk) |
:floppy_disk: [pyBTK (Python>=3.7)](https://pypi.org/project/pyBTK/)

* [MOKKA](https://biomechanical-toolkit.github.io/mokka/): GUI built on BTK functionalities. 
Allows visualisation of c3d contents and basic processing, such as filtering and event detection. Great open source alternative to Vicon Nexus for these functionalities.</br>
:computer: [(unofficial) tutorial by biomechanist.net](https://www.biomechanist.net/btk-and-mokka/)

* **CMAS open-code** by CMAS (Clinical Movement Analysis Society - UK & Ireland) is a project with the goal of creating an online platform where everyone interested in movement analysis can share coding resources. Include tools for anonymization, importing, calculating gait profile scores, etc. </br>
:floppy_disk: [source](https://github.com/cmasuki/open-code)

* **fairmotion** by Deepak Gopinath and Jungdam (2020). Fairmotion provides easy-to-use interfaces and tools to work with motion capture data. The objective of the library is to manage the complexity of motion representation, 3D transformations, file formats and visualization, and let users focus on high level learning tasks. **Scarse documentation**</br>
:floppy_disk: [code](https://github.com/facebookresearch/fairmotion)

* **motoNMS** by Alice Mantoan et al. (2015). MATLAB tool that provides a complete, user friendly and highly configurable tool to automatically process experimental motion data from different laboratories in C3D format for their use into the OpenSim neuromusculoskeletal software. </br>
:page_facing_up: [paper](https://link.springer.com/article/10.1186/s13029-015-0044-4) |
:computer: [website](https://simtk.org/projects/motonms) |
:floppy_disk: [source](https://github.com/RehabEngGroup/MOtoNMS)

* **BiomechZoo** by Philippe C Dixon. BiomechZoo is a user-customizable toolbox for the analysis of biomechanical data within the MatLab programming environment. Please take a look at the Wiki for setup information and user instructions.</br>
:page_facing_up: [paper](https://doi.org/10.1016/j.cmpb.2016.11.007) |
:computer: [website](https://www.biomechzoo.com) |
:floppy_disk: [source](https://github.com/PhilD001/biomechZoo)

* **The CGM 2.i Project** by Fabian Leboeuf et al. (2019). Python :snake: implementation of an evolved conventional gait model.</br>
:page_facing_up: [paper](https://doi.org/10.1016/j.gaitpost.2019.01.034) |
:computer: [website](https://pycgm2.github.io/) |
:floppy_disk: [source](https://github.com/pyCGM2/pyCGM2)

* **Pyomeca** by the [S2M Lab](https://www.facebook.com/s2mlab/). Pyomeca is a Python :snake: library allowing you to carry out a complete biomechanical analysis; in a simple, logical and concise way. It enables extraction, processing and visualization of biomechanical data for use in research and education.</br> 
:page_facing_up: [paper](https://joss.theoj.org/papers/10.21105/joss.02431) |
:computer: [website](https://pyomeca.github.io/) |
:floppy_disk: [source](https://github.com/pyomeca/pyomeca)

* **Dryft** by [Ryan Alcantara](https://www.ryan-alcantara.com). Dryft is an open-source Python :snake: and MATLAB package that corrects running ground reaction force signal drift. It also contains an optimized utility function `dryft.signal.splitsteps()` for identifying start/end of stance phase from vertical ground reaction force data without loops.</br> 
:page_facing_up: [publication](https://joss.theoj.org/papers/10.21105/joss.01910) |
:computer: [website](https://www.ryan-alcantara.com/dryft/) |
:floppy_disk: [source](https://github.com/alcantarar/dryft)

* **Practical Guide to Data Smoothing and Filtering** written by Ton Van den Bogert. </br>
:page_facing_up: [publication](https://d1wqtxts1xzle7.cloudfront.net/49975323/filter.pdf)

#### Marker Trajectory Gap filling

* **Automated Gap Filling and Tools for Motion Capture** by the Sensor-Fusion team from EPIC lab @GeorgiaTech. Gap filling is based on inverse kinematics approach. </br>
:page_facing_up: [paper](https://doi.org/10.1080/10255842.2020.1789971) |
:computer: [website](https://simtk.org/projects/opensense) |
:floppy_disk: [source](https://github.com/JonathanCamargo/MoCapTools)

* **MoGapFill** implemented by Fabian Leboeuf (Python :snake:). Low dimensional Kalman smoother that fills gaps in motion capture marker trajectories based on Burke and Lasenby 2016 paper.</br>
:page_facing_up: [Burke's paper 2016](http://dx.doi.org/10.1016/j.jbiomech.2016.04.016) |
:floppy_disk: [source](https://github.com/pyCGM2/MoGapFill)

#### Inertial Measurement Units

* **GaitPy** by Matthew Czech. Read and process raw vertical accelerometry data from a sensor on the lower back during gait; calculate clinical gait characteristics.  
:computer: [website](https://pypi.org/project/gaitpy/) |
:floppy_disk: [source](https://github.com/matt002/GaitPy)

* **OpenSense** is a workflow for analyzing movement with inertial measurement unit (IMU) data. It computes the motions of body segments based on inertial measurement unit (IMU) data in OpenSim. OpenSense provides tools for (i) reading and converting IMU sensors data into a single orientation format, (ii) associating and registering IMU sensors with body segments of an OpenSim model (as an IMU Frame), and (iii) performing inverse kinematics studies to compute joint angles. The OpenSense capabilities are available through the command line and through Matlab and Python scripting.</br>
:page_facing_up: [documentation and examples](https://simtk-confluence.stanford.edu:8443/display/OpenSim/OpenSense+-+Kinematics+with+IMU+Data) |
:computer: [website](https://simtk.org/projects/opensense) |
:floppy_disk: [source](https://github.com/opensim-org/opensim-core)


## Ultrasound Fascicle Tracking

* **StradWin** Stradwin is an experimental, cross-platform tool primarily for freehand 3D ultrasound acquisition, visualisation and elastography. However, Stradwin can also be used with 3D medical data of any sort: its segmentation and surface extraction facilities are particularly powerful. It can load most types of DICOM image files and has unique facilities to measure bone cortical thickness from CT data. </br>
:computer: [website](https://mi.eng.cam.ac.uk/Main/StradWin)

* **UltraTrack** by Dominic Farris and Glen Lichtwark (2016). UltraTrack implements an affine extension to an optic flow algorithm to track movement of the muscle fascicle end-points throughout dynamically recorded sequences of images. The algorithm )previously described and tested for reliability) is implemented as software for tracking multiple fascicles in multiple muscles at the same time; correcting temporal drift in measurements; manually adjusting tracking results; saving and re-loading of tracking results and loading a range of file formats.</br>
:page_facing_up: [paper](https://doi.org/10.1016/j.cmpb.2016.02.016) |
:computer: [website-software]( https://sites.google.com/site/ultratracksoftware/file-cabinet) |
:floppy_disk: [source-algorithm](https://uk.mathworks.com/matlabcentral/fileexchange/32770-muscle-fascicle-tracking-ultrasound?s_tid=prof_contriblnk)

* **Automatic fascicle tracking algorithm** by Drazan et al. (2019). The links include all the experimental data, tracking code, and tracked trials reported in the publication, presenting an automatic fascicle tracking algorithm quantifying gastrocnemius architecture during maximal effort contractions. [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.2598553.svg)](https://doi.org/10.5281/zenodo.2598553)</br>
:page_facing_up: [paper](https://doi.org/10.7717/peerj.7120) |
:dvd: [dataset and paper code](https://zenodo.org/record/2598553#.X1o-b3lKgdU) |
:floppy_disk: [source](https://github.com/joshrbaxter/ultrasound_tracking)

* **DL_Track** by Neil Cronin et al. (2020). A deep learning approach for analysing muscle architecture from musculoskeletal ultrasound images. It allows to train new models, using new images or labelling those provided. It provides a trained model as well. </br>
:page_facing_up: [preprint](https://arxiv.org/pdf/2009.04790.pdf) |
[:dvd: dataset | :floppy_disk: source](https://github.com/njcronin/DL_Track)


## Modelling and Simulation :computer:

### Anthropometric Models :standing_person:

* **Repository of body segment parameter models** by Will Robertson. Contains the raw data for a multitude of body segment parameter models (see repository for list).  
:computer: [website](http://wspr.io/body-segment-param/) |
:floppy_disk: [source](https://github.com/wspr/body-segment-param)

* **Yeadon's model** by Chris Dembia et al. (2015). The human inertia model developed by Fred Yeadon in 1990.  
:page_facing_up: [paper](https://dx.doi.org/10.12688%2Ff1000research.5292.2) |
:floppy_disk: [source](https://github.com/chrisdembia/yeadon)

* **Hatze's model** by Will Robertson. A Matlab implementation of Hatze's 1980 anthropometric body segment parameter model.  
:page_facing_up: [Hatze's paper](https://doi.org/10.1016/0021-9290(80)90171-2) |
:floppy_disk: [source](https://github.com/wspr/hatze-biomech)


### Multibody and Physics Engines :sleeping::arrow_lower_left::apple:

* **Biorbd** by Benjamin Michaud and Mickaël Begon (2020). This is a Biomechanical add-ons to the RigidBody Dynamics Library by Martin L. Felis. Written in C++, includes Python and MATLAB binders. A visualizer and an optimal control framework have been developed around this library. </br>
:page_facing_up: [paper](https://joss.theoj.org/papers/10.21105/joss.02562) |
:floppy_disk: [source](https://github.com/pyomeca/biorbd)

* **Bullet Physics** by Erwin Coumans and Yunfei Bai (2016). Real-time collision detection and multi-physics simulation for VR, games, visual effects, robotics, machine learning etc.   
:page_facing_up: [Quick Start Guide](https://docs.google.com/document/d/10sXEhzFRSnvFcl3XxNGhnD4N2SedqwdAvK3dsihxVUA/edit#heading=h.2ye70wns7io3) |
:computer: [website](https://pybullet.org/wordpress/) |
:floppy_disk: [source](https://github.com/bulletphysics/bullet3)

* **Drake** :dragon: by Russ Tedrake and the Drake Development Team (2019). C++ toolbox for analyzing the dynamics of our robots and building control systems for them, with a heavy emphasis on optimization-based design/analysis. Core development is now led by the Toyota Research Institute.  
:computer: [website](https://drake.mit.edu/) |
:floppy_disk: [source](https://github.com/RobotLocomotion/drake)

* **MuJoCo** by Emo Todorov for Roboti LLC. Initially it was used at the Movement Control Laboratory, University of Washington. MuJoCo is a  commercial physics engine aiming to facilitate research and development in robotics, biomechanics, graphics and animation, and other areas where fast and accurate simulation is needed.  
:computer: [website](http://www.mujoco.org) |
:star: [plugin for importing OpenSim models](https://github.com/aikkala/O2MConverter)

* **ODE (Open Dynamics Engine)** by Russell L. Smith. Open source, high performance library for simulating rigid body dynamics. It is fully featured, stable, mature and platform independent with an easy to use C/C++ API. It has advanced joint types and integrated collision detection with friction. ODE is useful for simulating vehicles, objects in virtual reality environments and virtual creatures. It is currently used in many computer games, 3D authoring tools and simulation tools.  
:computer: [website](https://www.ode.org) |
:floppy_disk: [source](https://bitbucket.org/odedevs/ode/src/master)

* **Pinocchio** by Carpentier et al. (2019). Pinocchio is an open-source library (C++ with Python :snake: bindings) for efficiently computing the dynamics (and derivatives) of articulated rigid-body models (robot, avatars, skeletal models, etc.). It implements algorithms following the methods described in Featherstone's 2008 [book](https://www.springer.com/gp/book/9780387743141), and their derivatives.  
:page_facing_up: [paper](https://hal.archives-ouvertes.fr/hal-01866228) |
:computer: [website](https://gepettoweb.laas.fr/doc/stack-of-tasks/pinocchio/master/doxygen-html/) |
:floppy_disk: [source](https://github.com/stack-of-tasks/pinocchio)

* **PyDy** by Jason Moore. A tool kit written in the Python programming language that utilizes an array of scientific programs to enable the study of multibody dynamics.  
:page_facing_up: [paper](http://dx.doi.org/10.1115/DETC2013-13470) |
:floppy_disk: [source](https://rbdl.github.io) |
:star: [Human Standing Tutorial](https://github.com/pydy/pydy-tutorial-human-standing) |
:movie_camera: [YouTube tutorials](https://www.youtube.com/watch?v=r4piIKV4sDw)

* **RBDL (Rigid Body Dynamics Library)** by Martin L. Felis (Heidelberg University). A multibody engine heavily inspired by the pseudo code of the book "Rigid Body Dynamics Algorithms" of [Roy Featherstone](http://royfeatherstone.org/).  
:page_facing_up: [paper](https://link.springer.com/article/10.1007/s10514-016-9574-0) |
:computer: [website](https://rbdl.github.io/) |
:floppy_disk: [source](https://github.com/rbdl/rbdl)

* **SimBody** by Michael Sherman et al. (2011). Simboby is an open source, extensible, high performance toolkit including a multibody mechanics library aimed at the needs of biomedical researchers working in a variety of fields including neuromuscular, prosthetic, and biomolecular simulation.   
:page_facing_up: [paper](https://www.sciencedirect.com/science/article/pii/S2210983811000241) |
:computer: [website](https://simtk.org/projects/simbody) |
:floppy_disk: [source](https://github.com/simbody)

### Computational Muscle Models 	:mechanical_arm:

* **Flexing Computational Muscle: Modeling and Simulation of Musculotendon Dynamics** by Matthew Millard et al. (2013). Source code and benchmarks to compare computational speed and physiological accuracy of several muscle models in OpenSim. </br>
:page_facing_up: [paper](https://doi.org/10.1115/1.4023390) |
:floppy_disk: [source](https://simtk.org/projects/opensim_muscle) |
:floppy_disk: [Matlab version](https://github.com/mjhmilla/Millard2012EquilibriumMuscleMatlabPort) |
:video_camera: [Webinar](https://www.youtube.com/watch?v=Q1rId1fOkjw)

* **MyoSim** by the [Campbell Lab](https://sites.google.com/g.uky.edu/campbellmusclelab). MyoSim is an open source computer software for modeling the mechanical properties (force, shortening, power output) of striated muscles. The software models the behavior of half-sarcomeres by extending Huxley-based cross-bridge distribution techniques with Ca2+ activation and cooperative effects. MyoSim can also simulate arbitrary cross-bridge schemes set by the researcher.</br>
:page_facing_up: [paper](https://rupress.org/jgp/article/143/3/387/43232/Dynamic-coupling-of-regulated-binding-sites-and) |
:computer: [webpage](http://myosim.campbellmusclelab.org/home) |
:floppy_disk: [installation package (includes source)](http://myosim.campbellmusclelab.org/download)
:floppy_disk: [source (MATLAB version)](https://github.com/Campbell-Muscle-Lab/MATMyoSim)

* **Virtual Muscle** by Chen et al. (2000). Virtual Muscle provides a framework for constructing accurate muscle models that can be incorporated easily into complete
neuromusculoskeletal systems. The muscle model includes motor nuclei that accept a single command input (e.g. net synaptic drive or EMG envelope) and apportion it into recruitment and frequency modulation of subgroups of motor units with type-specific properties, type-specific contractile elements that produce force as a function of firing frequency, length and velocity, passive elastic elements for passive muscle force, passive elastic elements for series-compliance of tendons and aponeuroses. </br> 
:page_facing_up: [paper](http://e.guigon.free.fr/rsc/article/ChengEJEtAl00.pdf) |
:floppy_disk: [source](https://1otylmrj2pd20xsmv2kci0wn-wpengine.netdna-ssl.com/wp-content/uploads/2017/11/VM-4.0.1.zip) |
:page_facing_up: [Manual](https://1otylmrj2pd20xsmv2kci0wn-wpengine.netdna-ssl.com/wp-content/uploads/2017/11/VM-4.0.1-Users-Manual.pdf)

* **Volume Invariant Position-based Elastic Rods (VIPER)** by Baptiste Angles et al. (2019). VIPER is a modified formulation of position-based rods to include elastic volumetric deformations. Rods can provide a compact alternative to tetrahedral meshes for the representation of complex muscle deformations, as well as providing a convenient representation for collision detection. Muscles can be modelled as a bundle of rods, for which a technique to automatically convert a muscle surface mesh into a rods-bundle is also presented. The method can run in real time.</br>
:page_facing_up: [paper](https://dl.acm.org/doi/10.1145/3340260) |
:floppy_disk: [source](https://github.com/vcg-uvic/viper) |
:video_camera: [video](https://www.youtube.com/watch?v=2CGRfJJEu38)

### Neuro-musculoskeletal Simulation Software :brain::arrow_right::leg:

* **The AnyBody Modeling System** by AnyBody Technology. Commercial software for musculoskeletal modelling and simulation.</br>
:page_facing_up: [paper](https://doi.org/10.1016/j.simpat.2006.09.001) |
:computer: [website](http://www.anybodytech.com) |
:page_facing_up: [tutorials](https://t.co/5vG76al6jv) |
:page_facing_up: [Wiki](https://t.co/IkVRN1WKWB) |
:star: [model repository](http://www.anybodytech.com/software/model-repository-ammr) |
:star: [Python tools](https://pypi.org/project/AnyPyTools/)

* **AnimatLab** - neuromechanical and neurorobotic simulator for building the body of a robot or biolgical organism in a physically accurate 3-D virtual world, and then layout a biologically realistic nervous system to control the animats behavior.   
:page_facing_up: [paper](https://www.sciencedirect.com/science/article/pii/S0165027010000087) |
:computer: [website](http://animatlab.com) |
:floppy_disk: [source](https://github.com/NeuroRoboticTech/AnimatLabPublicSource)

* **Artisynth** by John Lloyd et al. Artisynth is a 3D mechanical modeling system implemented in Java that supports the combined simulation of multibody and finite element models (linear and nonlinear materials), together with contact and constraints. </br> 
:page_facing_up: [paper](https://link.springer.com/chapter/10.1007/8415_2012_126) |
:page_facing_up: [paper-downloadable](https://www.cs.usask.ca/faculty/stavness/papers/lloyd2012-artisynth-a-fast-interactive-biomechanical-modeling-toolkit.pdf) |
:computer: [website](https://www.artisynth.org/Main/HomePage) |
:floppy_disk: [source](https://github.com/artisynth/artisynth_core)

* **Biomechanics of Bodies** - biomechanical modelling package implemented in MATLAB that contains a human musculoskeletal model and enables biomechanical and musculoskeletal calculations.   
:page_facing_up: [paper](https://pure.coventry.ac.uk/ws/portalfiles/portal/22762734/Shippen_et_al_BoB_Biomechanics_MATLAB.pdf) |
:computer: [website](https://www.bob-biomechanics.com)

* **GaitSym** by William Sellers (2014). Software for simulation of human and animal musculoskeletal biomechanics.  
:page_facing_up: [Config Reference Manual](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.705.9682&rep=rep1&type=pdf) |
:computer: [Animal Simulation Laboratory website](https://www.animalsimulation.org/) |
:floppy_disk: [source](https://github.com/wol101/GaitSym_2017)

* **MSMS Software for VR Simulations of Neural Prostheses and Patient Training and Rehabilitation** by Rahman Davoodi and Gerald E. Loeb. MSMS is a software for modeling of paralyzed and prosthetic limbs and simulation of their movement under various neural control strategies. The simulations of MSMS models can be run in typical PCs to test and evaluate different prosthetic control strategies or in real-time PCs with stereoscopic displays to enable design engineers and prospective users to evaluate candidate neural prosthetic systems and learn to operate them before actually receiving them.</br>
:page_facing_up: [paper](https://viterbi.usc.edu/pdfs/gloeb/95737.pdf) |
:computer: [website](https://bme.usc.edu/msms-software-downloads/)

* **OpenSim** by the National Center for Simulation in Rehabilitation Research, Stanford University. Open source software for biomechanical analysis and neuromusculoskeletal simulations.   
:page_facing_up: [paper2007](https://ieeexplore.ieee.org/document/4352056) |
:page_facing_up: [paper2019](https://doi.org/10.1371/journal.pcbi.1006223) |
:computer: [website](https://opensim.stanford.edu) |
:computer: [binaries](https://simtk.org/projects/opensim) |
:floppy_disk: [source](https://github.com/opensim-org/opensim-core)

* **SCONE** by Thomas Geijtenbeek. Open source software for predictive simulation of biological motion. It generates actuator patterns and motion trajectories that optimally perform a specific task, according to high-level objectives such as walking speed, pain avoidance, and energy efficiency.   
:page_facing_up: [paper](https://joss.theoj.org/papers/10.21105/joss.01421) |
:computer: [website](https://scone.software/doku.php) |
:computer: [binaries](https://simtk.org/projects/scone) |
:floppy_disk: [source](https://github.com/opensim-org/SCONE)

### Neuromusculoskeletal Simulation Tools :brain::hammer:

* **Batch OpenSim Processing Scripts (BOPS)** by Alice Mantoan et al. (2020). MATLAB based, user friendly and easy-to-use tool to perform batch process of the most commonly used OpenSim Tools (IK, ID, MA, SO and JRA).</br>
:page_facing_up: [paper](https://doi.org/10.1080/10255842.2020.1867978) |
:computer: [website](https://simtk.org/projects/bops) |
:floppy_disk: [source](https://github.com/RehabEngGroup/BOPS)

* **OpenSim JAM: A framework to simulate Joint and Articular Mechanics in OpenSim** by Colin Smith (2020). OpenSim JAM is a collection of force component plugins, models, and executables (tools) that are designed to enable OpenSim musculoskeletal simulations that include detailed joint mechanics. The project extends the opensim-core capabilities to enable joint representations that include 6 degree of freedom (DOF) joints (without kinematic constraints) and explicit representations of articular contact and ligament structures.  
:page_facing_up: [reference papers for each component](https://github.com/clnsmith/opensim-jam/tree/master/opensim-jam-release) |
:computer: [website and binaries](https://simtk.org/projects/opensim-jam) |
:floppy_disk: [source](https://github.com/clnsmith/opensim-jam)

* **EMGD-FE: EMG Driven Force Estimator** by Luciano Menegaldo et al. (2014). EMG-FE is a MATLAB tool consisting of an open source graphical user interface for estimating isometric muscle forces in the lower limb using an EMG-driven model. Includes a graphical user interface. </br>
:page_facing_up: [paper](https://biomedical-engineering-online.biomedcentral.com/articles/10.1186/1475-925X-13-37) |
:computer: [website](http://www.peb.ufrj.br/docentes/Luciano/EMG-FE.htm) |
:page_facing_up: [users guide](http://www.peb.ufrj.br/docentes/Luciano/user_guide.pdf) |
:floppy_disk: [source](http://www.peb.ufrj.br/docentes/Luciano/EMGDM_FEv1R7_dist1.zip)

* **CEINMS: Calibrated EMG-Informed Neuromusculoskeletal Modelling Toolbox** by Claudio Pizzolato et al. (2015). OpenSim toolbox that implements various techniques for running musculoskeletal simulations from experimental measurements of electromyography (EMG). See CEINMS paper for list and examples.</br>
:page_facing_up: [paper](https://doi.org/10.1016/j.jbiomech.2015.09.021) |
:computer: [website](https://simtk.org/projects/ceinms) |
:floppy_disk: [source](https://github.com/CEINMS/CEINMS)

* **OpenSim Marker Placement Toolbox** by Mark Price. An OpenSim toolbox implementing a motion capture marker placement refinement algorithm based on minimizing inverse kinematics tracking errors. </br>
:page_facing_up: [paper](https://doi.org/10.1002/cnm.3283) |
:floppy_disk: [source](https://github.com/UMass-OpenSim/opensim-marker-place-toolbox)

* **CusToM: a Matlab toolbox for musculoskeletal simulation** by Antoine Muller (2019). The Customizable Toolbox for Musculoskeletal simulation (CusToM)  is a MATLAB toolbox aimed at performing inverse dynamics based musculoskeletal analyzes. It can perform inverse kinematics, inverse dynamics, prediction of ground reaction forces and muscle forces, compute kinematics from inertial measurement units, etc.</br>
:page_facing_up: [paper](https://joss.theoj.org/papers/10.21105/joss.00927) |
:floppy_disk: [source](https://github.com/anmuller/CusToM) |
:star: [workshop materials](https://github.com/cpontonn/CusToM-Workshop)

* **FreeBody** by the Daniel Cleather and Anthony Bull, MSk Dynamics group, Imperial College London. FreeBody is a segment-based musculoskeletal model of the lower limb implementing TLEM anatomical dataset. FreeBody is a fully-open source Windows application and Matlab code that may be used as given or as a framework for the development of your own bespoke models.</br>
:page_facing_up: [paper](https://doi.org/10.1098/rsos.140449) |
:computer: [website](https://www.msksoftware.org.uk/software/freebody/)

* **Geyer's 2010 neuromuscular model** by Hermut Geyer (2010). Simulink implementation of a neuromusculoskeletal model used in walking simulation with stretch reflexes.</br>
:page_facing_up: [paper](https://www.cs.cmu.edu/~hgeyer/Publications/Geyer&Herr-ReflexModel2Column.pdf) |
:floppy_disk: [source](https://www.cs.cmu.edu/~hgeyer/Software/Neuromuscular%20Model/Geyer%20Neuromuscular%20Model.zip) 

* **Modeling musculoskeletal kinematic and dynamic redundancy using null space projection** by Dimitar Stanev and Konstantinos Moustakas (2019). Python :snake: methods for modeling, simulation and analysis of redundant musculoskeletal systems based on muscle space projection on segmental level reflexes and the computation of the feasible muscle forces for arbitrary movements. [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.2000421.svg)](https://doi.org/10.5281/zenodo.2000421)  
:page_facing_up: [paper](https://doi.org/10.1371/journal.pone.0209171) |
:computer: [website](https://simtk.org/projects/redundancy) |
:floppy_disk: [source](https://github.com/mitkof6/musculoskeletal-redundancy)

* **Stiffness modulation of redundant musculoskeletal systems** by Dimitar Stanev and Konstantinos Moustakas (2019). Python tool :snake: implementing an approach that explores the entire space of possible solutions of the muscle redundancy problem using the notion of null space and rigorously accounts for the effect of muscle redundancy in the computation of the feasible stiffness characteristics. [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.2575332.svg)](https://doi.org/10.5281/zenodo.2575332)  
:page_facing_up: [paper](https://doi.org/10.1016/j.jbiomech.2019.01.017) |
:computer: [website](https://simtk.org/projects/stiffness) |
:floppy_disk: [source](https://github.com/mitkof6/musculoskeletal-stiffness/tree/v1.0)

* **SynO: Synergy Optimization** by Mohammad Shourijeh ad Benjamin Fregly (2020). SynO is a collection of MATLAB codes implementing a novel approach for estimating muscle forces/activations by imposing a synergy structure within optimization (termed “synergy optimization”).</br>
:page_facing_up: [paper](https://doi.org/10.1115/1.4044310) |
:floppy_disk: [source](https://simtk.org/projects/syno/)


## Optimal Control and Trajectory Optimization :rocket:

* **OpenSim Moco** by Chris Dembia, Nick Bianco and the OpenSim team (2019). OpenSim Moco is a software toolkit to solve optimal control problems with musculoskeletal models defined in OpenSim, including those with kinematic constraints. Using the direct collocation method, Moco can solve a wide range of problems, including motion tracking, motion prediction, and parameter optimization. The design of Moco focuses on ease-of-use, customizability, and extensibility. Just like OpenSim itself, Moco has interfaces in XML/command-line, Matlab, Python, Java, and C++.  
:page_facing_up: [preprint](https://www.biorxiv.org/content/10.1101/839381v1) |
:computer: [website](https://simtk.org/projects/opensim-moco) |
:floppy_disk: [source](https://github.com/opensim-org/opensim-moco) |
:star: [materials from preprint](https://github.com/stanfordnmbl/mocopaper) |
:movie_camera: [webinar](https://www.youtube.com/watch?v=IYYZgyE33pU&feature=youtu.be)
    - **Moco simulations at University of Maryland** by Ross Miller (2020). Models and codes from the University of Maryland "Neuromechanics Research Core" for performing optimal control simulations of human movement with OpenSim Moco software: 2D and 3D versions of the Rajagopal et al. (2016) model and code for performing "tracking" and "predictive" simulations of locomotion.</br>
    :computer: [website](https://simtk.org/projects/umocod)

* **Rapid 3D muscle-driven predictive simulations** by Antoine Falisse et al. (2019). This framework relies on numerical tools including direct collocation, implicit differential equations, and algorithmic differentiation, and generates predictive simulations of gait in about 35 minutes (single core of a standard laptop computer) with muscle-driven 3D models (29 degrees of freedom and 92 muscles). The code contains a series of example predictive simulations in which we varied objective function, musculoskeletal properties, and gait speed. </br>
:page_facing_up: [paper](https://doi.org/10.1098/rsif.2019.0402) |
:computer: [website](https://simtk.org/projects/3dpredictsim) |
:floppy_disk: [source](https://github.com/antoinefalisse/3dpredictsim) 

* **FROST: Fast Robot Optimization and Simulation Toolkit** by Hereid et al. (2016). FROST for MATLAB provides a general full-body dynamics gait optimization and simulation framework for bipedal walking robots using virtual constraints based feedback controllers. The Wolfram Mathematica backend enables generation of analytic expressions for multi-domain system dynamics and kinematics symbolically, compiled as .MEX files under MATLAB. FROST also features state-of-the-art direct collocation approaches for the full-order dynamics gait optimization problems to guarantee fast and reliable convergence. </br>
:page_facing_up: [paper](https://ieeexplore.ieee.org/document/8202230) |
:computer: [website](http://ayonga.github.io/frost-dev/) |
:floppy_disk: [source](https://github.com/ayonga/frost-dev) 

* **Muscle Redundancy Solver** by Friedl de Groote et al. (2016). An algorithm to estimate muscle tendon properties and/or compute muscle coordination by tracking experimental data with a musculoskeletal model assuming optimal control to solve for the muscle redundancy. </br>
:page_facing_up: [paper](https://link.springer.com/article/10.1007/s10439-016-1591-9) |
:computer: [website](https://simtk.org/projects/optcntrlmuscle) |
:floppy_disk: [source](https://github.com/KULeuvenNeuromechanics/MuscleRedundancySolver) |
:floppy_disk: [dev_repo](https://github.com/antoinefalisse/solvemuscleredundancy_dev)

* **opty** by Jason Moore and Ton van den Bogert (2018). Opty utilizes symbolic descriptions of ordinary differential equations expressed with [SymPy](https://www.sympy.org/en/index.html) to form the constraints needed to solve optimal control and parameter identification problems using the direct collocation method and non-linear programming. </br>
:page_facing_up: [paper](https://joss.theoj.org/papers/10.21105/joss.00300) |
:computer: [documentation](https://opty.readthedocs.io/en/latest/) |
:floppy_disk: [source](https://github.com/csu-hmc/opty) 

* **Data-tracking optimization using collocation** by Yi-Chung Lin and Marcus Pandy (2017). This is a MATLAB package that can be used to perform data-tracking optimization using collocation method. The codes and models are available. The tracking results for one subject during walking and running are also provided. </br>
:page_facing_up: [paper](https://www.ncbi.nlm.nih.gov/pubmed/28583674) |
[:computer: website | :floppy_disk: source ](https://simtk.org/projects/datatracking)

* **Optimal Control of Musculoskeletal Movement Using OpenSim & MATLAB** by Leng-Feng Lee and Brian R. Umberger (2016). This package includes an approach for generating optimal control simulations of human movement using OpenSim and MATLAB based on the direct collocation approach. Models, results and a complete working example are provided. </br>
:page_facing_up: [paper](https://peerj.com/articles/1638.pdf) |
[:computer: website | :floppy_disk: source ](https://simtk.org/projects/directcolloc)


## Subject-Specific Modelling

### Segmentation of Medical Images :art:
* **[3DSlicer](https://www.slicer.org/)** 3D Slicer is an open source software platform for medical image informatics, image processing, and three-dimensional visualization.</br> 
:page_facing_up: [paper (Slicer v4)](https://dx.doi.org/10.1016%2Fj.mri.2012.05.001) |
:computer: [website](https://www.slicer.org/wiki/Main_Page) |
:page_facing_up: [Documentation](https://www.slicer.org/wiki/Documentation/Nightly/Training) | 
:video_camera: [Youtube tutorials](https://www.youtube.com/channel/UC11x1iQ7ydSIFYw4L6wveXg)
    * Extensions of 3DSlicer:
        * **SlicerMorph** by Sara Rolfe et al. (2020). SliceMorph is a toolkit with the aim of  retrieve, visualize, measure, annotate, and perform geometric morphometric analyses from high-resolution specimen data both from volumetric scans (CTs and MRs) as well as from 3D surface scanners effectively within 3D Slicer.</br>
        :page_facing_up: [preprint](https://www.biorxiv.org/content/10.1101/2020.11.09.374926v1) |
        :computer: [website](https://slicermorph.github.io/) |
        :floppy_disk: [source](https://github.com/SlicerMorph/SlicerMorph) |
        :video_camera: [tutorials](https://www.youtube.com/channel/UCy3Uz1ikRH1B7WSMfaldcjQ)
       * **SlicerSALT (Slicer Shape AnaLysis Toolbox)** by Vicory et al. (2018). SlicerSALT is open-source, free comprehensive software design for biomedical scientists to precisely locate shape changes in their imaging studies. SlicerSALT will enhance the intuitiveness and ease of use for such studies, as well as allow researchers to find shape changes with higher statistical power. </br>
       :page_facing_up: [paper](https://link.springer.com/chapter/10.1007/978-3-030-04747-4_6) |
       :computer: [website and tutorials](http://salt.slicer.org/) |
       :floppy_disk: [source](https://github.com/Kitware/SlicerSALT)
* **[Dragonfly](https://www.theobjects.com/dragonfly/index.html)** by Object Research Systems. Dragonfly is a software platform for the intuitive inspection and processing of multi-scale multi-modality image data. Includes a Deep Learning tool for training deep models for image segmentation and regression tasks. It also offers rendering capabilities and extensibility through Python.</br>
:computer: [website](https://www.theobjects.com/dragonfly/index.html) |
:video_camera: [Video tutorials](http://www.theobjects.com/dragonfly/tutorials.html)
* **[ITK-Snap](http://www.itksnap.org/pmwiki/pmwiki.php)** - 
:page_facing_up: [paper](https://doi.org/10.1016/j.neuroimage.2006.01.015) |
:video_camera: [Video tutorials](http://www.itksnap.org/pmwiki/pmwiki.php?n=Videos.SNAP3)
* **[InVesalius](https://invesalius.github.io/)** - 
:page_facing_up: [paper list](https://invesalius.github.io/publication.html) | 
:video_camera: [Youtube tutorials](https://www.youtube.com/channel/UChTsspNY3aO-nYmNnB2DPyA/featured)
* **[Materialise Mimics](https://www.materialise.com/en/medical/mimics-innovation-suite) (commercial)**
* **[MITK](https://docs.mitk.org/2016.11/index.html)** - 
:page_facing_up: [paper](https://doi.org/10.1117/12.535112) |
:page_facing_up: [tutorials](https://www.mitk.org/wiki/Tutorials)
* **[MITK-GEM](http://araex.github.io/mitk-gem-site/)** is based on MITK but includes also mesh processing functionalities. Aimed to generation of finite element models. </br>
:page_facing_up: [paper](https://doi.org/10.1080/10255842.2016.1181173) |
:computer: [website](https://simtk.org/projects/mitk-gem) |
:star: [resources](https://github.com/araex/mitk-gem/tree/master/Scripts)
* **[Rhino3Dmedical](https://rhino3dmedical.com/)** commercial.</br>
:camera: [webinar](https://www.youtube.com/watch?v=MYuX2iGxU-Y&feature=youtu.be&ab_channel=McNeelEurope)
* **[SASHIMI Segmentation](https://github.com/bartbols/SASHIMI) :sushi:** by Bart Bolsterlee. SASHIMI Segmentation is a MATLAB App for segmentation of multi-slice images. </br> 
* **[Seg3D](https://www.sci.utah.edu/cibc-software/seg3d.html)**    
* **[Simpleware ScanIP](https://www.synopsys.com/simpleware/software/scanip.html) (commercial)**.  

### Automatic Segmentation 

* **Personalized knee geometry modelling based on multi-atlas segmentation and mesh refinement** by Nikolopoulos et al. (2020). Tools for performing automatic segmentation from MRI and geometry refinement targeting the human knee joint. The user can import an unsegmented MRI sequence and obtain the label maps as well as .stl and .msh files of the individual parts. This includes the femur, tibia and fibula bones, femoral and tibial cartilages, menisci and ligaments.</br>
:page_facing_up: [paper](https://doi.org/10.1109/ACCESS.2020.2982061) |
:floppy_disk: [code](https://gitlab.com/vvr/OActive/knee_segmentation_tools)

* **Automatic subregional assessment of knee cartilage degradation** by Thomas et al. (2020).  286 MRI volumes (multi-echo spin-echo T2-weighted) from 143 subjects from the Osteoarthritis Initiative (Kellgren-Lawrence grade of 0). Each MRI was segmented with a semi-automated process and refined by a radiologist. These segmentations were used as ground truth. A Convolutional Neural Network was used to learn MRI features predictive of cartilage location.  Segmented cartilage was divided into 12 subregions. </br>
:page_facing_up: [pre-print](https://arxiv.org/ftp/arxiv/papers/2012/2012.12406.pdf) |
:floppy_disk: [code](https://github.com/kathoma/AutomaticKneeMRISegmentation)

### Manipulation, Processing and Comparison of Surface Meshes
* [**Autodesk Netfabb**](https://www.autodesk.com/products/netfabb/overview)
* [**Blender**](https://www.blender.org/)</br>
    * [Blender Remeshing Guide](https://github.com/evaherbst/Blender_remeshing_guide) by Eva Herbst.
* [**Gmsh**](https://gmsh.info/)
* [**MeshLab**](https://www.meshlab.net/) - **TO ADD PAPER**
* [**MeshMixer**](http://www.meshmixer.com/)
* **OpenFlipper** by RWTH Aachen University (Prof Leif Kobbelt). OpenFlipper is an OpenSource multi-platform application and programming framework designed for processing, modeling and rendering of geometric data. More tools are available at the [Graphics, Geometry and Multimedia software page](https://www.graphics.rwth-aachen.de/software/)</br>
:computer: [website](https://www.graphics.rwth-aachen.de/software/openflipper/) |
:floppy_disk: [source](https://www.graphics.rwth-aachen.de:9000/OpenFlipper-Free/OpenFlipper-Free)

* [**Salome**](https://www.salome-platform.org/user-section/about/mesh)
* [**CloudCompare**](http://www.cloudcompare.org) - allows quantitative comparison of surface meshes.

* **SlicerSALT (Slicer Shape AnaLysis Toolbox)** by Vicory et al. (2018). See description on 3DSlicer extensions section.

* **Trimesh**  by Michael Dawson-Haggerty et al. (2019). Trimesh is a pure Python (2.7-3.4+) :snake: library for loading and using triangular meshes with an emphasis on watertight surfaces. The goal of the library is to provide a full featured and well tested Trimesh object which allows for easy manipulation and analysis. </br>
:computer: [website](https://trimsh.org/index.html) |
:floppy_disk: [source](https://github.com/mikedh/trimesh)


### Resources for Building Biomechanical Models from Medical Images

* **mri2psm** by Manish Sreenivasa (2016). Open-source toolchain to create patient-specific models from MRI images.  
:page_facing_up: [paper](https://doi.org/10.1016/j.jbiomech.2016.05.001) (_MRI2PSM, an open-source toolchain to create patient-specific rigid body models from MRI images._ is cited in the paper, but not retrievable). |
:floppy_disk: [source](https://github.com/manishsreenivasa/mri2psm)

* **ModelFactory** by Manish Sreenivasa (2018). A Matlab/Octave toolbox to create human body models.   
:page_facing_up: [preprint](https://arxiv.org/abs/1804.03407) |
:floppy_disk: [source](https://github.com/manishsreenivasa/ModelFactory)

* **Musculotendon parameter optimizer** by Luca Modenese et al. (2016). Optimization based technique that adjusts muscle parameters of musculoskeletal models. It can be used to improve linearly scaled models or to obtain reasonable estimation of optimal fiber lengths and tendon slack lengths in models generated from medical images.  
:page_facing_up: [paper](https://doi.org/10.1016/j.jbiomech.2015.11.006) |
:dvd: [dataset](link_to_dataset) |
:computer: [website](https://simtk.org/projects/opt_muscle_par) |
:floppy_disk: [source (MATLAB)](https://github.com/modenaxe/MuscleParamOptimizer) |
:floppy_disk: [source (OpenSim plugin)](https://github.com/MuscleOptimizer/MuscleOptimizer) with [documentation](http://muscleoptimizer.github.io/MuscleOptimizer/)

* **NMSBuilder** by Giordano Valente et al. (2017). Freely available software to create subject-specific musculoskeletal models for OpenSim from 3D geometries. NMSBuilder is based on ALBA (Agile Library for Biomedical Applications) an open-source rapid application development framework for computer-aided medicine written in C++.</br>
:page_facing_up: [paper](https://doi.org/10.1016/j.cmpb.2017.09.012) |
:computer: [website](http://www.nmsbuilder.org/) |
:movie_camera: [YouTube tutorial](https://www.youtube.com/watch?v=UtAMTFM1vsI)

* **Resources for creating musculoskeletal models from segmentations** by Luca Modenese et al. (2018). This includes materials (step-to-step guide and Matlab scripts) to guide users in creating musculoskeletal models of the lower limb from medical images using a workflow that includes MeshLab, MATLAB and NMSBuilder.</br>
:page_facing_up: [paper](https://doi.org/10.1016/j.jbiomech.2018.03.039) |
:computer: [website](https://simtk.org/projects/subj-spec-model/) |
:page_facing_up: [step-by-step guide](https://figshare.shef.ac.uk/articles/dataset/Data_for_paper_Investigation_of_the_dependence_of_joint_contact_forces_on_musculotendon_parameters_using_a_codified_workflow_for_image-based_modelling_/5863422) |
:floppy_disk: [scripts (MATLAB)](https://figshare.com/articles/Code_for_paper_Investigation_of_the_dependence_of_joint_contact_forces_on_musculotendon_parameters_using_a_codified_workflow_for_image-based_modelling_/6392423)

* **STAPLE toolbox** by Luca Modenese and Jean-Baptiste Renault et al. (2020). STAPLE (Shared Tools for Automatic Personalised Lower Extremity modelling) consists of a collection of methods for generating skeletal models from three-dimensional bone geometries, usually segmented from medical images. The methods are currently being expanded to create complete musculoskeletal models. Toolbox is currently in beta version. [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4275285.svg)](https://doi.org/10.5281/zenodo.4275285)</br>
:page_facing_up: [preprint](https://www.biorxiv.org/content/10.1101/2020.06.23.162727v2) |
:floppy_disk: [source (beta)](https://github.com/modenaxe/msk-STAPLE)


### Automatic Definition of Bony Landmarks and Reference Systems :skull:

* **Subburaj's curvature/spatial relation matrix method** by Maximilian Fischer et al. (2019). MATLAB implementation of Subburaj's curvature/spatial relation matrix method for the automatic identification of pelvic landmarks.  
:page_facing_up: [Subburaj's paper 2008](https://doi.org/10.3722/cadaps.2008.153-160) |
:page_facing_up: [Subburaj's paper 2009](https://doi.org/10.1016/j.compmedimag.2009.03.001) |
:floppy_disk: [source](https://github.com/RWTHmediTEC/PelvicLandmarkIdentification_Subburaj)

* **Pelvic Landmark Identification** by Maximilian Fischer et al. (2019). This is a fully automatic methods for identification of landmarks on surface models of the pelvis. [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3384110.svg)](https://doi.org/10.5281/zenodo.3384110)  
:page_facing_up: [paper](https://www.nature.com/articles/s41598-019-49573-4) |
:floppy_disk: [source](https://github.com/RWTHmediTEC/PelvicLandmarkIdentification)

* **GIBOC-Knee toolbox** by Jean-Baptiste Renault et al. (2018). The toolbox includes three automatic algorithms for reference system identification on femur, tibia and patella. Each algorithm is implemeted with 3 variants, and compared against five other methods from the literature on a dataset of 24 lower-limb CT-scans (not included in the repository).  
:page_facing_up: [paper](https://doi.org/10.1016/j.jbiomech.2018.08.028) |
:floppy_disk: [source](https://github.com/renaultJB/GIBOC-Knee-Coordinate-System)

### Uncertainty Quantification in Musculoskeletal Simulations

* **Probabilistic Tool for Considering Patient Populations & Model Uncertainty** by Casey A. Myers et al. (2015). This is a probabilistic tool to assess model parameter uncertainty and intersubject variability.</br>  
:page_facing_up: [paper](https://link.springer.com/article/10.1007%2Fs10439-014-1181-7) |
:page_facing_up: [Users Guide](https://simtk.org/docman/view.php/886/1884/OpenSim+Probabilistic+Plugin+Users+Guide+%28v1.0%29.pdf) |
:computer: [website](https://simtk.org/projects/prob_tool)

* **Probabilistic Musculoskeletal Modeling module (PMM)** by Giordano Valente et al. (2014).  A description is on the supplementary materials of the paper. </br>
:page_facing_up: [paper](https://doi.org/10.1371/journal.pone.0112625) |
:computer: [website](https://simtk.org/frs/download_confirm.php/file/4298/PMM_module.rar?group_id=978)


### Meshers of Surface Models
* [CUBIT (The CUBIT™ Geometry and Mesh Generation Toolkit)](https://cubit.sandia.gov/) - TODO description
* [TetGen](http://wias-berlin.de/software/index.jsp?id=TetGen&lang=1)
* [NetGen](https://sourceforge.net/projects/netgen-mesher/) [source](https://github.com/NGSolve/netgen)


### Statistical Shape Modelling :bone:

* **Deformetrica** is a software (Python tool :snake:) for the statistical analysis of 2D and 3D shape data. Deformetrica comes with three main applications: registration, atlas construction and geodesic regression. </br>
:page_facing_up: [list of papers](http://www.deformetrica.org/#references) |
:computer: [website](https://www.deformetrica.org/) |
:floppy_disk: [source](https://gitlab.com/icm-institute/aramislab/deformetrica)

* **Musculoskeletal Atlas Project (MAP)** by Ju Zhang et al. (2014). Open-source software framework in Python :snake: with plug-in architecture for creating musculoskeletal models. The client-side application (MAP Client) facilitates dicom and motion capture integration, registration tools, and meshing capabilities, and uses statistical shape modelling (based on the Melbourne Femur Collection, which consists of 320 full body CT scans) to provide a best-match to mocap and medical imaging data and generate surface geometry to generate an OpenSim model. **Not maintained.**</br>
:page_facing_up: [paper](https://www.researchgate.net/profile/Ju_Zhang15/publication/301951056_The_MAP_Client_User-Friendly_Musculoskeletal_Modelling_Workflows/links/5735044508ae298602df08c8/The-MAP-Client-User-Friendly-Musculoskeletal-Modelling-Workflows.pdf) |
:computer: [website](https://simtk.org/projects/map) |
:computer: [docs](https://map-client.readthedocs.io/en/latest/) |
:floppy_disk: [source](https://github.com/MusculoskeletalAtlasProject/) |
:star: [plugins](https://github.com/mapclient-plugins)

* **Scalismo** by the [Graphics and Vision Research Group](http://gravis.cs.unibas.ch/) at the University of Basel. Scalismo is a library for statistical shape modeling and model-based image analysis in Scala. </br>
:computer: [website (includes tutorials)](https://scalismo.org/) |
:floppy_disk: [source](https://github.com/unibas-gravis/scalismo)

* **SPHARM-PDM Toolbox** is a tool that computes point-based models using a parametric boundary description for the computing of Shape analysis. It is now available as a [3D Slicer](http://www.slicer.org) extension and as part of [SlicerSALT](salt.slicer.org) module. </br>
:computer: [SPHARM-PDM website](https://www.nitrc.org/projects/spharm-pdm) |
:computer: [SlicerSALT website](http://salt.slicer.org/) |
:floppy_disk: [source](https://github.com/NIRALUser/SPHARM-PDM)

* **Statistical Shape Model of the Knee** by Lowell Smoger et al. (2019). A statistical shape and alignment model was created for the structures of the knee: the femur, tibia and patella, associated articular cartilage, and soft tissue structures for a training set of 50 subjects/specimens. The statistical model describes intersubject anatomic variability in the shape and alignment of the knee structures and provides the ability to automatedly generate the geometry for a joint-level finite element analysis for members of the training set or virtual subjects derived from the statistical model, thus facilitating population-based evaluations.</br>
:computer: [website](https://simtk.org/projects/ssm_knee)

* **Statistical Shape Modelling Research Toolkit (SSMRT)** by Daniel Nolte and the MSk Dynamics group, Imperial College London (2016). The toolkit packages a set of powerful technologies that may be used to predict shape using one of the provided models or to create your own SSM. </br>
:page_facing_up: [paper](https://doi.org/10.1016/j.jbiomech.2016.09.005) |
:computer: [website](https://www.msksoftware.org.uk/software/ssmrt/) 

* **ShapeWorks** by the University of Utah. The ShapeWorks software is an open-source distribution of a new method for constructing compact statistical point-based models of ensembles of similar shapes that does not rely on any specific surface parameterization. </br>
:computer: [website](https://www.sci.utah.edu/software/shapeworks.html) |
:floppy_disk: [source](https://github.com/SCIInstitute/ShapeWorks)

* **Shape Model Builder** by Emmanuel Audenaert (2019). Framework to develop shape models in MATLAB. </br>
:page_facing_up: [paper](https://doi.org/10.1080/10255842.2019.1577828) |
:floppy_disk: [source](https://uk.mathworks.com/matlabcentral/fileexchange/49940-shape-model-builder?s_tid=prof_contriblnk)

* **Statistical Shape Models and Statistical Density Models of the Shoulder Bones** by Pendar Soltanmohammadi et al. J Biomech Eng. (2020). Project making available a statistical shape model (SSM) and statistical density model (SDM) of the humerus and scapula bones through a MATLAB app. Models are based on  57 male (20 pairs) and 18 female shoulders (1 pair) from 54 donors. The SSM will create a surface model whose shape is sensitive to the normalized principal component (PC) scores chosen in the app. The SDM will apply node-by-node HU values to a 3D template volumetric mesh (from the average geometry), allowing you to visualize the bone density distribution. The output files can be visualized using open-source software like [ParaView](www.paraview.org).</br>
:page_facing_up: [paper](https://doi.org/10.1115/1.4047664) |
:computer: [website](https://simtk.org/projects/shoulder-ssdm)

* **A statistical shape model of the healthy first carpometacarpal joint** by Marco Schneider et al. (2015). CT image data and segmented point clouds of 50 carpometacarpal (CMC) bones from the dominant wrists and thumbs of 40 right hands and 10 left hands of 50 healthy non-osteoarthritic volunteers. This project contains instructions, python scripts, and example data for generating statistical shape models (SSM) using the [GIAS2 library](https://bitbucket.org/jangle/gias2).</br>
:page_facing_up: [paper](https://doi.org/10.1016/j.jbiomech.2015.05.031) |
:computer: [website](https://simtk.org/projects/cmc-ssm)

## Finite Element Analysis

### Finite Element Analysis Software 
* [Abaqus](https://www.3ds.com/products-services/simulia/products/abaqus/) (commercial)

* [Ansys](https://www.ansys.com/en-gb) (commercial)

* **CMISS**, an interactive computer program for **C**ontinuum Mechanics, **Im**age analysis, **S**ignal processing and **S**ystem Identification, by the Auckand Bioengineering Institute (ABI). Development stopped in 2012 but it is still employed in several publications. Examples and documentation are available at the main website.</br>
:page_facing_up: [paper](https://link.springer.com/article/10.1007/s10237-003-0036-1) |
:computer: [website](https://www.cmiss.org/)


* [FEAP: A Finite Element Analysis Program](http://projects.ce.berkeley.edu/feap/) by University of Berkeley

* **MOFEM** by Lukasz Kaczmarczyk et al. (2019). MOFEM is an open source (GNU LGPL) C++ finite element library capable of dealing with complex multi-physics problems with arbitrary levels of approximation and refinement. MoFEM can read various input file formats, and work with preprocessors like Gmsh, Salome, Cubit, and many more. Also, it can be used for parallel processing on desktop computers and high-performance clusters.</br>
:page_facing_up: [paper](https://joss.theoj.org/papers/10.21105/joss.01441) |
:computer: [website](http://mofem.eng.gla.ac.uk/mofem/html/index.html?s=03)
:floppy_disk: [source](https://bitbucket.org/likask/mofem-cephas/src/master/)

* [Z88](https://en.z88.de/)
* **Code_Aster** - TO ADD DESCRIPTION</br>
:computer: [website](https://www.code-aster.org/) |
:computer: [Salome_meca](https://www.code-aster.org/spip.php?article303) |
:page_facing_up: [Aster-description](https://www.code-aster.org/UPLOAD/DOC/Presentation/plaquette_aster_en.pdf) |
:movie_camera: [tutorials](https://www.youtube.com/channel/UCWBV4PbsfizSkmcq88roGeQ/playlists) |
:movie_camera: [tutorials](https://www.youtube.com/watch?v=g9Kvv7PYF34&list=PLvkU6i2iQ2frC7YB1A9Pqcfhwe9T3Vuy-)

* **FEBio** **TODO - needs description and resources** </br>
:computer: [website](https://febio.org/) |
:movie_camera: [introductory webinar](https://www.youtube.com/watch?v=I3_PKL4x45g&t=944s)

### Finite Element Analysis Software Tools

* **BoneMat** mainly developed at [Istituto Ortopedico Rizzoli in Bologna](http://www.ior.it/en), Italy. Bonemat is a freeware that maps on a Finite Element mesh bone elastic properties derived from Computed Tomography images. Bonemat can import CT images and FE models, interactively visualise them, and export the updated FE mesh once bone properties have been mapped. From this 3.2 version, Bonemat supports import/export to and from both Ansys and Abaqus, perhaps the two most used commercial FE packages. </br>
:page_facing_up: [paper](https://doi.org/10.1016/j.medengphy.2006.10.014) |
:computer: [website](http://www.bonemat.org/)

* **GIBBON Toolbox** by [Kevin Moerman](https://kevinmoerman.org/). GIBBON (The Geometry and Image-Based Bioengineering add-On) is an open-source MATLAB toolbox that includes an array of image and geometry visualization and processing tools and is interfaced with free open source software such as TetGen, for robust tetrahedral meshing, and FEBio and Abaqus for finite element analysis. The combination provides a highly flexible image-based modelling environment and enables advanced inverse finite element analysis. </br> 
:page_facing_up: [paper](https://joss.theoj.org/papers/10.21105/joss.00506) |
:computer: [website](https://www.gibboncode.org/) |
:floppy_disk: [source](https://github.com/gibbonCode/GIBBON)

* **LMG: Lumbar Model Generator** by Carolina Lavecchia et al. (2017). LMG is a MATLAB toolbox for semi-automatic generation of lumbar finite element geometries. It generates the geometrical model of the lumbar spine (from the vertebrae L1 to the L5 including the intervertebral disc IVD), the surface models of the bodies involved (STL files) and the solid meshed model, generated with hexahedral elements for the IVD and tetrahedral elements for the vertebrae.</br>
:page_facing_up: [paper](https://royalsocietypublishing.org/doi/pdf/10.1098/rsif.2017.0829) |
:floppy_disk: [source](https://github.com/CELavecchia/LMG)

* **MuscleForceDirection OpenSim plugin** by Luca Modenese et al. (2013). This is an OpenSim plugin that extracts the muscle lines of action of user-selected muscles for a given kinematics. It was created to help setting up finite element models that are consistent with musculoskeletal models. **TODO: ADD SOURCE</br>
:page_facing_up: [paper2013](https://onlinelibrary.wiley.com/doi/full/10.1002/jor.22364) |
:page_facing_up: [paper2015](https://www.tandfonline.com/doi/full/10.1080/23335432.2015.1017609#.VWFr6k-qpBc) |
:computer: [website](https://simtk.org/projects/force_direction) |
:floppy_disk: [source-COMING-SOON](tba)

* **ReadySim** by Donald Hume et al. (2020). ReadySim provides a means for researchers to perform musculoskeletal simulations directly in a finite element framework. The software uses MATLAB and Python to interface with ABAQUS/Explicit input and output files and includes modules for model segment scaling, kinematics estimation, and muscle force optimization. The JobQueue API allows for asynchronous process control via MATLAB to parallelize optimization problems and improve computational runtime when possible.</br>
:page_facing_up: [paper](https://doi.org/10.1002/cnm.3396) |
:computer: [website](https://simtk.org/projects/readysim) 

* **Surrogate Contact Modeling Toolbox** by Ilan Eskinazi and Benjamin Fregly (2016). This opensource toolbox provides researchers with the capabilities to construct and use surrogate contact models, including multiple domains for sampling including out-of-contact configurations, a multi-threaded sampler that makes use of FEBio's contact modeling capabilities, flexible specification of surrogate model inputs and outputs, and architecture, parallelized training, testing module and surrogate models portable as DLLs.</br>
[:computer: website | :floppy_disk: source ](https://doi.org/10.1109/TBME.2015.2455510)
:computer: [website](https://simtk.org/projects/scmt/) 

* **Gridap: An extensible Finite Element toolbox in Julia** by Santiago Badia1 and Francesc Verdugo (2020). </br>
:page_facing_up: [paper](https://joss.theoj.org/papers/10.21105/joss.02520) |
:page_facing_up: [Users' Guide](https://arxiv.org/abs/1910.01412) |
:floppy_disk: [code/source](lhttps://github.com/gridap/Gridap.jl)

### Finite Element Models

* **PIPER Child Human Body Model**: Child finite element model scalable to different ages and posture, used to to study pediatric response to impact. This model is used for crash reconstruction studies.</br>
:page_facing_up: [paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0187916) |
:floppy_disk: [source](https://gitlab.inria.fr/piper/child) 

* **Orthotropic Femur Model** by Diogo Geraldes et al. (2015). A complete continuum heterogeneous orthotropic finite element model of the standardised femur, with material properties and directionality resulting from a mechanical loading environment incorporating multiple daily living activities. It is provided as mesh with material properties (similar to Abaqus input file). </br>
:page_facing_up: [paper](https://link.springer.com/article/10.1007/s10237-015-0740-7) |
:floppy_disk: [source](https://figshare.com/articles/dataset/Orthotropic_Femur_Model/1419589)

* **The "Standardised Femur" model** by Marco Viceconti.  The standardized femur is the 3D surface model of a femoral bone analogue (mod. #3103) produced by Pacific Research Labs (Vashon Island, Washington, USA) which was for a long while the "de facto" standard in experimental orthopaedic biomechanics. Much experimental data based on this bone analogue are available in the literature; this geometry is proposed as a reference for orthopaedic biomechanics finite element studies. </br>
:page_facing_up: [paper](https://pubmed.ncbi.nlm.nih.gov/8872285/) |
:floppy_disk: [source](https://figshare.shef.ac.uk/articles/The_Standardised_Femur_model/3839766)

* **The "Muscle Standardised Femur" model** by Marco Viceconti. This is a version of the Standardised Femur with muscle insertions modelled as separate regions (surface patches). This makes much easier to create finite element models in which the muscles insertion areas are accurately modelled. </br>
:page_facing_up: [paper1](https://doi.org/10.1016/S0021-9290(02)00175-6) |
:page_facing_up: [paper2](https://doi.org/10.1243%2F09544110360579312) |
:floppy_disk: [source](https://figshare.shef.ac.uk/articles/The_Muscle_Standardised_Femur_model/4578298)

## Statistical Analysis
This section needs to be improved.
* [**G*Power**](https://www.psychologie.hhu.de/arbeitsgruppen/allgemeine-psychologie-und-arbeitspsychologie/gpower.html)
* [**spm1d**](https://spm1d.org/): package for one-dimensional [Statistical Parametric Mapping](http://www.scholarpedia.org/article/Statistical_parametric_mapping)
* [**SPSS Statistics**](https://www.ibm.com/uk-en/products/spss-statistics) (commercial)
* **PCA of Waveforms and Functional PCA: A Primer for Biomechanics** by John Warmenhoven et al. (2020). Scripts presenting functional principal components analysis (fPCA) and PCA of waveforms on an exemplar biomechanical data set. </br>
:page_facing_up: [paper](https://doi.org/10.1016/j.jbiomech.2020.110106) |
:floppy_disk: [code](https://github.com/johnwarmenhoven/PCA-FPCA)

## Scientific Data Visualization
* [**Paraview**](https://www.paraview.org)
* [**Mayavi**](https://docs.enthought.com/mayavi/mayavi/) - Python tool :snake:
* [**OpenCmiss**](http://opencmiss.org/)
* **ImageJ** - TO ADD DESCRIPTION </br>
:computer: [website](https://imagej.net/) |
:floppy_disk: [source](https://github.com/imagej/imagej)
* **Fiji** - version of ImageJ with pre-built plugins. </br>
:computer: [website](https://imagej.net/Fiji) |
:floppy_disk: [source](https://github.com/fiji/fiji)
* **StradView** by Machine Intelligence Laboratory of Cambridge University, Department of Engineering. StradView was developed from Stradwin, which is a tool for freehand 3D ultrasound recording and visualisation. Stradwin is also a useful tool for visualisation from 3D medical data of any sort. It can load most types of DICOM data or image sequences, and produce very high quality surface models which can also be turned into movies using scripts. It can also be used for cortical bone mapping from DICOM CT data. </br>
:computer: [website](https://mi.eng.cam.ac.uk/Main/StradView) |
:page_facing_up: [How-To](http://mi.eng.cam.ac.uk/~gmt11/stradview/howto.htm)
* [**MicroDicom**](https://www.microdicom.com/): MicroDicom is application for primary processing and preservation of medical images in DICOM format. It is equipped with most common tools for manipulation of DICOM images and it has an intuitive user interface. Free for use and accessible to everyone for non-commercial use.

## Reproducibility :gem:

* **Challenge to scientists: does your ten-year-old code still run?** by Jeffrey M. Perkel (2020). Article including a reproducibility checklist and other interesting considerations orinating from the `ten year challenge`. </br>
:page_facing_up: [paper](https://www.nature.com/articles/d41586-019-03366-x) |
:page_facing_up: [ten-years-challenge](https://rescience.github.io/ten-years/)

* **Commentary on the Integration of Model Sharing and Reproducibility Analysis to Scholarly Publishing Workflow in Computational Biomechanics** by Erdemir et al. (2016). Two manuscripts on computational biomechanics were submitted together with the employed models and shared with the scientific reviewers. In addition to the standard review of the manuscripts, the reviewers downloaded the models and contributed to a simulation reproducibility report.</br>
:page_facing_up: [paper](https://doi.org/10.1109/TBME.2016.2602760)

* **Sustainable computational science: the ReScience initiative** is a platinum open-access peer-reviewed journal that targets computational research and encourages the explicit replication of already published research, promoting new and open-source implementations in order to ensure that the original research is reproducible.</br>
:computer: [RESCIENCE C website](http://rescience.github.io/)
:page_facing_up: [paper](https://peerj.com/articles/cs-142/) |
:floppy_disk: [GitHub page](https://github.com/rescience/)

* **Reproducibility PI Manifesto** by Lorena Barba (2012). Slides of the talk `Reproducibility in Computational and Experimental Mathematics` at the ICERM workshop outlining a list of commitment that principal investigators could take to ensure reproducibility. </br>
:computer: [website](https://lorenabarba.com/gallery/reproducibility-pi-manifesto/) |
:page_facing_up: [blog-repro-pack-example](https://lorenabarba.com/blog/how-repro-packs-can-save-your-future-self/) |
:bar_chart: [slides](https://figshare.com/articles/presentation/Reproducibility_PI_Manifesto/104539)

* **Reproducible computational environments using containers** workshop by Software Carpentries, held at Imperial College London in 2020. The workshop focused on the use of containers with the goal of using them to effect reproducible computational environments. Such environments are useful for ensuring reproducible research outputs and for simplifying the setup of complex software dependencies across different systems.</br>
:computer: [website](https://imperialcollegelondon.github.io/2020-07-13-Containers-Online/)

* **Make code accessible with cloud services** by Jeffrey M. Perkel. This Nature article describes some technical solutions applicable for making the results of a paper accessible and reproducible for other scientistis.</br>
:page_facing_up: [paper](https://www.nature.com/articles/d41586-019-03366-x) |
:computer: **Suggested Services**:
    - [Docker](https://www.docker.com/) |
    - [Binder](https://mybinder.org/) |
    - [Colab](https://colab.research.google.com/)

* **Resources that helps in choosing a license for shared resources**:
    - **[Choose a license](https://choosealicense.com/)** by GitHub Inc. This is a website with can help you choosing the license for your shared data based the intended use that you want to allow. </br> 
    - **[CreativeCommons](https://creativecommons.org/choose/)** by Creative Commons. This website can guide you in the process of choosing a Creative Commons license based on your preferences.</br> 

## Good practices for credible modeling

* **Credible practice of modeling and simulation in healthcare: ten rules from a multidisciplinary perspective** by Erdemir et al. (2020). The paper provides Ten Rules for credible practice of modeling and simulation in healthcare developed from a comparative analysis by the Committee’s multidisciplinary membership, followed by a large stakeholder community survey.</br>
:page_facing_up: [paper](https://translational-medicine.biomedcentral.com/articles/10.1186/s12967-020-02540-4) |
:computer: [examples](https://simtk.org/plugins/moinmoin/cpms/Ten%20Simple%20Rules%20Examples)

* **Good Simulation Practices** by In Silico World. Good Practices are consensus documents produced by a group of experts – organised in a formal or informal Community of Practice. A group of experts coordinated by the Avicenna Alliance and the VPH Institute is developing the first proposal for Good Simulation Practice. At the link a list of relevant documents is presented.</br>
:computer: [list of documents](http://insilico.world/practice/good-simulation-practices/)

## Societies and Initiatives :classical_building:
* [Americal Society of Biomechanics](https://www.asbweb.org/)
* [European Society of Biomechanics](https://esbiomech.org/)
* [International Society of Biomechanics](https://isbweb.org/)
   * [3-D Analysis of Human Movement](http://www.geocities.ws/3d-ahm/)
   * [Comparative Neuromuscular Biomechanics](https://sites.psu.edu/cnbgroup/)
   * [Footware Biomechanics Group](https://www.footwearbiomechanics.org/)
   * [Hand and Wrist Biomechanics International](https://www.hwbi.org/)
   * [International Shoulder Group](https://isbweb.org/isg)
   * [Motor Control Group](http://www.mcg.isbweb.org/)
   * [Technical Group on Computer Simulation (TGCS)](https://isbweb.org/~tgcs/iscsb-2019/canmore.html)
* [International Society of Biomechanics in Sports](https://isbs.org)
* [National Biomechanics Day](http://thebiomechanicsinitiative.org/)

## Miscellaneous Online Resources 
* https://www.biomch-l.isbweb.org/
* https://www.biomechanist.net/
* https://biomechsa.wordpress.com/resources
* [ISB Data Resources](http://isbweb.org/data/)
* [Richard Baker's blog](https://wwrichard.net/) (unmaintained).
* [Stuart McErlain-Naylor's personal website](https://www.stuartmcnaylor.com/): includes [a list of resources](https://www.stuartmcnaylor.com/resources/) for PhD students.
* Websites of interest for Machine Learning and Deep Learning topics:
    - https://distill.pub/
    - https://paperswithcode.com/
    
## More Datasets and repositories
* [Biomechanical Datasets](https://github.com/mkjung99/biomechanics_dataset) by Moon Ki Jung (Imperial College London).
* [Datasets of complex physiological signals](https://www.physionet.org/about/database/) from [Physionet](https://www.physionet.org/).
* [GitHub Biomechnical repositories](https://github.com/topics/biomechanics)
* [Open-Access Medical Image Repositories](http://www.aylward.org/notes/open-access-medical-image-repositories)
* [Data Sources from Stanford's Mobilize Center](http://mobilize.stanford.edu/data-sources/)


## Sandbox <!-- omit in toc -->


 
* **SPIERS (Serial Palaeontological Image Editing and Rendering System)** by Mark Sutton et al. (2012). SPIERS is a package of three programs for the digital visualisation and analysis of tomographic (serial image) datasets, such as those obtained from serial-grinding of specimens, or from CT scanning.</br>
:computer: [website](https://spiers-software.org)
[paper](https://palaeo-electronica.org/content/issue-2-2012-technical-articles/226-virtual-palaeontology-toolkit)
:floppy_disk: [source](https://github.com/palaeoware/SPIERS) |


* **Kinovea** by Joan Charmant. Kinovea is a video player for sport analysis. It provides a set of tools to capture, slow down, study, compare, annotate and measure technical performances.</br>
:computer: [website](https://www.kinovea.org/) |
:floppy_disk: [source](https://github.com/Kinovea/Kinovea) |
:star: [resources]( https://www.kinovea.org/help/en/index.htm)

* **MoJoXlab** by Riasat Islam et al. (2020). MoJoXlab is a MATLAB based custom motion capture analysis software toolkit whose aim is to produce freely available motion capture analysis software to be used by anyone interested in generating lower limb joint kinematics waveforms using any suitable wearable inertial measurement units (IMUs).</br>
:page_facing_up: [paper](https://mhealth.jmir.org/2020/6/e17872/pdf) |
:floppy_disk: [source](https://ordo.open.ac.uk/collections/MoJoXlab/4815567)

* **Chordata** by Bruno Laurencich et al. Chordata is a motion capture system that can be easily assembled by anyone in order for them to start capturing as soon as they are able to build it. Additionally, it is an open hardware-software framework that can be freely tweaked, enhanced, or used as part of another project. </br>
:page_facing_up: [project introduction](https://hackaday.com/2018/09/24/a-motion-capture-system-for-everyone/) |
:computer: [website](https://chordata.cc/) |
:star: [website with links](https://hackaday.io/project/27519-motion-capture-system-that-you-can-build-yourself)

* **Meshroom**: Meshroom is a free, open-source 3D Reconstruction Software based on the AliceVision framework.
:computer: [website](https://alicevision.org/#meshroom) 

* **GeoGram** is a programming library of geometric algorithms.
http://alice.loria.fr/index.php/home.html
https://homepages.loria.fr/BLevy/GEOGRAM/
http://alice.loria.fr/software/geogram/doc/html/index.html
https://gforge.inria.fr/frs/?group_id=5833

* **pyomo** Python-based, open-source optimization modeling language with a diverse set of optimization capabilities.
http://www.pyomo.org/
https://github.com/Pyomo/PyomoGallery

* **Motor-Unit-Model-Fuglevand**
:floppy_disk: [source](https://github.com/anagamori/Motor-Unit-Model-Fuglevand)

* **pymuscle**: Used to simulate the input-output relationship between motor neuron excitation and muscle fibers contractile state over time.
:floppy_disk: [source](https://github.com/iandanforth/pymuscle)
https://iandanforth.github.io/pymuscle-docs/

* **PyMUS v2.0** PyMUS v2.0 allows the simulations to be fully operated using a graphical user interface (GUI). The GUI was designed to allow for a generic computational procedure to be performed using modeling and simulation approaches. The Main Window of PyMUS v2.0 consists of one state window and six buttons for controlling simulation of motor unit system. 
:floppy_disk: [source](https://github.com/NMSL-DGIST/PyMUS)
 
 * **Developing a fatigable muscle model** by Apoorva Rajagopal and Jennifer Yong (2013).</br>
 :floppy_disk: [plugin files](https://simtk.org/frs/?group_id=863)
 
* **optim2d** by Ton van den Bogert and Anne Koelewijn. Matlab code to do trajectory optimization on a 2D gait model. The musculoskeletal dynamics can be augmented with prosthetic components (above knee, below knee), and the corresponding muscles can be amputated.</br>
 https://github.com/csu-hmc/optim2d
 
 * **UG stats Lectures** by Andy Field (2020): 
 https://www.youtube.com/playlist?list=PLEzw67WWDg81n3N3yfr_MW7f6cEl_XibX&feature=share
 
 * **Hypothesis testing demonstration** by Michael Pyrcz 
  youtube: https://www.youtube.com/watch?v=bcb3m3LBtRk
  github: https://github.com/GeostatsGuy/PythonNumericalDemos/blob/master/Interactive_Hypothesis_Testing.ipynb
 
 * **Python for Everybody**
 https://www.py4e.com/book
 
 * **ipycanvas** by Martin Renou. Ipycanvas is a lightweight, fast and stable library exposing the browser's Canvas API to IPython. It allows you to draw simple primitives directly from Python like text, lines, polygons, arcs, images etc. This simple toolset allows you to draw literally anything!</br>
 https://github.com/martinRenou/ipycanvas
 
 * reproducibility initiatives
 [reprohack]: https://reprohack.github.io/reprohack-hq/
[reproducibilitea]: https://reproducibilitea.org/
[turing-way]: https://www.turing.ac.uk/research/research-projects/turing-way-handbook-reproducible-data-science
[software carpentry]: https://swcarpentry.github.io/r-novice-gapminder/
 
 * FEM libraries
 * **FreeFEM** https://doc.freefem.org/introduction/index.html
 * **Firedrake** https://www.firedrakeproject.org/
 * **FEniCS Project** https://fenicsproject.org/
 * **deal.II** https://www.dealii.org/
 * **MFEM** https://mfem.org/
 * **GLVis** is a lightweight tool for accurate and flexible finite element visualization. 
 https://glvis.org/
 
 * *ANTHROPOLOGY
 * https://africanfossils.org/
 * https://www.nature.com/articles/497183a
 * http://paleo.eva.mpg.de/
 
 * https://morphobank.org/
 
 * **Blogging platforms**:
  - https://www.wix.com/
  - https://wordpress.com/
  - https://substack.com/
  - https://www.weebly.com/uk
  - https://blog.getpelican.com/
  - https://jekyllrb.com/
      - https://github.com/academicpages/academicpages.github.io
  - https://gohugo.io/
      - https://themes.gohugo.io/academic/
 * **JointTrack**
 https://sourceforge.net/projects/jointtrack/files/JointTrack/2.0%20%28stable%29/
 https://ufdcimages.uflib.ufl.edu/UF/E0/02/17/84/00001/mu_s.pdf
 
## DTI and fibre tractography <!-- omit in toc -->
* https://github.com/bartbols/muscle_architecture_DTI
* http://dsi-studio.labsolver.org/

* **MHEALTH (Mobile Health) dataset** by Oresti Banos et al. (University of Granada). MHEALTH is devised to benchmark techniques dealing with human behavior analysis based on multimodal body sensing (acceleration, rate of turn and magnetic field orientation at the limbs and 2-lead ECG measurements on the chest). It comprises body motion and vital signs recordings for ten volunteers of diverse profile while performing several physical activities.</br>
:dvd: [dataset](https://archive.ics.uci.edu/ml/datasets/MHEALTH+Dataset)

-----
## Contributing
Have anything in mind that you think is awesome biomechanics and would fit in this list? 
Feel free to send a pull request or open an Issue.  

### How to contribute

Feel free of contributing as by standard [GitHub workflow](https://guides.github.com/activities/forking/):
1. forking this repository
2. creating your own branch, where you make your modifications and improvements
3. once you are happy with the new feature you have implemented create a pull request

### Resources for learning how to contribute
* If you want to contribute but you are not familiar with [Git](https://git-scm.com/), the [Software Carpentry Lessons](https://swcarpentry.github.io/git-novice/) are a perfect place to start with Git and GitHub.
* If you have used Git before but you are not familiar with GitHub, you can check resources like ["First Contributions"](https://github.com/firstcontributions/first-contributions) and learn how to contribute to existing projects.
* If you are not familiar with the Markdown format used in this document you can quickly learn it from cheatsheets [like this one](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

### Items suggested template

If you are adding elements please use (roughly) this template or the format of similar items in the same subsection of the list:

```
* **Template: DatasetName** by Authors (year). Description. [![DOI](yourZenodoDOI)]</br>
:page_facing_up: [paper](doi/link_to_paper) |
:dvd: [dataset](link_to_dataset) |
:computer: [website](link_to_website) |
:floppy_disk: [code/source](link_to_source_code) |
:star: [resources](link_to_resources)
```

so that it will look roughly like this:

* **Template: DatasetName** by Authors (year). Description. [![DOI](yourZenodoDOI)]</br>
:page_facing_up: [paper](doi/link_to_paper) |
:dvd: [dataset](link_to_dataset) |
:computer: [website](link_to_website) |
:floppy_disk: [code/source](link_to_source_code) |
:star: [resources](link_to_resources)

-----

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Luca Modenese](https://uk.linkedin.com/in/luca-modenese-70a54546) has waived all copyright and related or neighboring rights to this work.
