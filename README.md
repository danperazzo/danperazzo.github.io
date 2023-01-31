#+TITLE: Guilherme G. Schardong
#+AUTHOR: Guilherme G Schardong
#+DATE: 2021-03-31
#+startup: hideblocks
#+options: num:nil toc:nil

I'm currently a post-doctoral fellow at [[https://www.isr.uc.pt/][Institute of Systems and Robotics, University of Coimbra]], where I work on projects with the [[https://visteam.isr.uc.pt/home][Visual Information Security Team (VISTEAM)]]. Up to January 2022, I was a research fellow at GALGOS/PUC-Rio, with experience on oil&gas industry from projects with PETROBRAS on well-testing and reservoir model inference. I'm also a part-time post-doc at [[https://www.visgraf.impa.br/home/][Visgraf/IMPA]], where I work on computer graphics and machine learning, with emphasis on implicit function reconstruction and rendering.

* Background
I got my Bachelor's degree in Computer Science from UFSM in 2012 and a Master's degree in Informatics in the same university, in 2014, advised by prof. [[http://www.inf.ufsm.br/~pozzer][Cesar Pozzer]]. In 2018 I got my D.Sc. in Informatics at PUC-Rio, as a member of GALGOS. From 2014 to 2016 I worked as a developer under prof. [[http://www.inf.puc-rio.br/~celes][Waldemar Celes]] on the Reservoir Visualization group on Tecgraf/PUC-Rio Institute. In 2016 I started working with prof. [[https://www.inf.puc-rio.br/~lopes][Hélio Lopes]] (being advised by him since 2015) and was co-advised by prof. [[https://www.inf.puc-rio.br/~simone][Simone Barbosa]] during my doctorate. I'm currently a post-doctoral fellow at the Institute for Systems an Robotics, University of Coimbra at the [[https://visteam.isr.uc.pt/home][VISTEAM]] group, led by prof [[https://home.deec.uc.pt/~nunogon/][Nuno Gonçalves]]. I'm also a part-time post-doc collaborator, supervised by prof. [[https://www.impa.br/~lvelho][Luiz Velho]] from Visgraf/IMPA and prof. Hélio Lopes.

* Research
My current research interests involve mainly AI for Graphics and Implicit Function representation. Below is a selected list of projects and publications from the last 5 years.

** Exploring differential geometry in neural implicits [[[https://dsilvavinicius.github.io/differential_geometry_in_neural_implicits][Project page]]]
#+caption: Gaussian and Mean curvatures of the Stanford Armadillo. We calculated them from a smooth neural network trained on the Armadillo mesh. Afterwards, we used the analytical formulas of the curvatures on the neural network evaluated at the mesh vertices and plotted the results as colors.
#+attr_html: :width 800px
[[file:res/i3d.jpeg]]
*** Authors: Tiago Novello, *Guilherme Schardong*, Luiz Schirmer, Vinicius da Silva, Helio Lopes, Luiz Velho
*** Venue: Computers and Graphics (SIBGRAPI Special Issue 2022)

** Multiresolution Neural Networks for Imaging [[[https://visgraf.github.io/mrnet-img/][Project page]]]
#+caption: Learning progressively more details of the Cameraman Image. On top, the reconstructions of the cameramen at each level of the network. On the bottom, the FFT spectra of the corresponding images.
#+attr_html: :width 800px
[[file:res/m-net-3.png]]
*** Authors: Hallison Paz, Tiago Novello, Vinícius da Silva, Luiz Schirmer, *Guilherme Schardong*, Fabio Chagas, Helio Lopes, Luiz Velho
*** Venue: Main Track of SIBGRAPI 2022

** Neural Networks for Implicit Representations of 3D Scenes [[http://sibgrapi.sid.inpe.br/rep/8JMKD3MGPEW34M/45DPE5L][[Paper link]]]
#+caption: A survey on Neural Network methods for implicit representations
#+attr_html: :width 800px
[[file:res/nnir3d_sib2021.png]]
*** Authors: Luiz Schirmer, *Guilherme Schardong*, Vinícius da Silva, Tiago Novello, Daniel Yukimura, Thales Magalhães, Hallison Paz, Hélio Lopes, Luiz Velho
*** Venue: Tutorials of SIBGRAPI 2021

** Incorporating Dynamic Production-Logging Data to the Permeability-Estimation Workflow Using Machine Learning [[[https://onepetro.org/SJ/article-abstract/25/05/2765/454025/Incorporating-Dynamic-Production-Logging-Data-to?redirectedFrom=fulltext][Paper link]]]
#+caption: Estimating near-well Permeability given production, imaging and, gamma-ray data using neural networks.
#+attr_html: :width 800px
[[file:res/fig13.png]]
*** Authors: Ciro Guimarães, Luiz Schirmer, *Guilherme Schardong*, Abelardo Barreto, Hélio Lopes
*** Venue: Society of Petroleum Engineers Journal, issue 25, 2020
** Eras: Improving the quality control in the annotation process for Natural Language Processing tasks [[[https://doi.org/10.1016/j.is.2020.101553][Paper link]]] [[[https://github.com/jonatasgrosman/eras][Code repository]]]
#+caption: Adjudication interface for ERAS, used for consolidating the annotations of multiple users.
#+attr_html: :width 800px
[[file:res/eras.png]]
*** Authors: Jonatas Grosman, Pedro Furtado, Ariane Bueno, *Guilherme Schardong*, Simone Barbosa, Hélio Lopes
*** Venue: Information System, issue 93, 2020
** Visual exploration of an ensemble of classifiers [[[https://doi.org/10.1016/j.cag.2019.08.012][Paper link]]]
#+caption: Exploration of classification results for various algorithms using linked views and dimensionality reduction.
#+attr_html: :width 800px
[[file:res/sib2019.png]]
*** Authors: Paula Ribeiro, *Guilherme Schardong*, Simone Barbosa, Clarisse de Souza, Hélio Lopes
*** Venue: Computers and Graphics (SIBGRAPI Special Issue 2019)
** Visual interactive support for selecting scenarios from time-series ensembles [[[https://doi.org/10.1016/j.dss.2018.08.001][Paper link]]] [[[https://github.com/schardong/visual-scenario-reduction][Code repository]]]
#+caption: Main window of our prototype. Linked views and dimensionality reduction permit the navigation among complex, time-varying data, with the goal of picking the instances closest to an arbitrary goal (P10, P50 or P90 production percentiles in our case).
#+attr_html: :width 800px
[[file:res/dss2018.png]]
*** Authors: *Guilherme Schardong*, Ariane Rodrigues, Simone Barbosa, Hélio Lopes
*** Venue: Decision Support Systems, issue 113, 2018
