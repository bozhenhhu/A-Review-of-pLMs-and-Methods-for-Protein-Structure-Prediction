# List of papers about protein structure prediction (PSP) and proterin representation learning methods
We recently released a review about PSP models: past, current, and future, but the field changes fastly and there are so many new papers that needed to be recorded and categorized. Inspired by the previous work ([Machine-learning-for-proteins](https://github.com/yangkky/Machine-learning-for-proteins)), we build this repository to list related papers of pLMs and PSP methods.   

## Notes  
- Structural features include 1D features (SS, SA, torsion angles, contact density, etc.) and 2D features (contact map and distance map)
 
## Contents
- [Reviews](#reviews)
- [Benchmarks](#Benchmark)
- [PSP Methods](#PSP)
  + [Structural Features Prediction](#Structural)
  + [Traditional Methods](#Traditional)
  

- [Folding tools](#tool)


<a name="reviews"></a>
## Reviews
**Controllable protein design with language models**[[paper]](https://www.nature.com/articles/s42256-022-00499-z)    
Ferruz, N., Höcker, B      
*Nature Machine Intelligence (2022)*   

**Advancing protein language models with linguistics: a roadmap for improved interpretability**[[paper]](https://arxiv.org/abs/2207.00982)    
Mai Ha Vu, Rahmad Akbar, Philippe A Robert, Bartlomiej Swiatczak, Geir Kjetil Sandve, Victor Greiff, Dag Trygve and Truslew Haug.     
*Preprint, July 2022*  

**Different methods, techniques and their limitations in protein structure prediction: A review**[[paper]](https://www.sciencedirect.com/science/article/pii/S0079610722000475)  
Vrushali Bongirwar and A.S. Mokhade    
*Progress in Biophysics & Molecular Biology (2022)*  

**The road to fully programmable protein catalysis.** [[paper]](https://doi.org/10.1038/s41586-022-04456-z)  
Sarah L. Lovelock, Rebecca Crawshaw, Sophie Basler, Colin Levy, David Baker, Donald Hilvert, Anthony P. Green.    
*Nature, June 2022.*  


**Applications of artificial intelligence to enzyme and pathway design for metabolic engineering.** [[paper]](https://doi.org/10.1016/j.copbio.2021.07.024)   
Woo Dae Jang, Gi Bae Kim, Yeji Kim, Sang Yup Lee.    
*Current Opinion in Biotechnology, February 2022.*    

**Adaptive machine learning for protein engineering.**  
Brian L. Hie, Kevin K. Yang.  
*Current Opinion in Structural Biology, February 2022.*   
[[10.1016/j.sbi.2021.11.002](https://doi.org/10.1016/j.sbi.2021.11.002)]

**The language of proteins: NLP, machine learning & protein sequences
.**[[Paper]](https://www.sciencedirect.com/science/article/pii/S2001037021000945)     
Dan Ofer, Nadav Brandes and Michal Linial    
*Computational and structural biotechnology journal (2021)*    

**A Review of Protein Structure Prediction using Deep Learning.**[[Paper]](https://www.bio-conferences.org/articles/bioconf/abs/2021/13/bioconf_biomic2021_04003/bioconf_biomic2021_04003.html)   
Meredita Susanty, Tati Erawati Rajab and Rukman Hertadi.  
*BIO Web of Conferences 41, 04003 (2021)*  

**Machine learning in protein structure prediction**[[paper]](https://www.sciencedirect.com/science/article/pii/S1367593121000508)    
Author links open overlay panelMohammedAlQuraishi  
*Current Opinion in Chemical Biology (2021)*  

**Pre-trained Language Models in Biomedical Domain: A Systematic Survey**[[paper]](https://arxiv.org/abs/2110.05006)  
Benyou Wang, Qianqian Xie, Jiahuan Pei, Prayag Tiwari, Zhao Li and Jie Fu      
*arXiv: Computation and Language, Oct 2021* 

**Learning the protein language: Evolution, structure, and function**[[paper]](https://www.sciencedirect.com/science/article/pii/S2405471221002039)[[code]](https://github.com/tbepler/prose)  
Tristan Bepler and Bonnie Berger  
*Cell systems (2021)*

**AI challenges for predicting the impact of mutations on protein stability.** [paper](https://arxiv.org/abs/2111.04208v1)  
Fabrizio Pucci, Martin Schwersensky, Marianne Rooman.    
*Preprint, Nov 2021.*    

**Representation learning applications in biological sequence analysis.**[[paper]](https://doi.org/10.1016/j.csbj.2021.05.039)  
Hitoshi Iuchi, Taro Matsutani, Keisuke Yamada, Natsuki Iwano, Shunsuke Sumi, Shion Hosoda, Shitao Zhao, Tsukasa Fukunaga, Michiaki Hamada.    
*Computational and Structural Biotechnology Journal, May 2021.*    

**Protein sequence-to-structure learning: Is this the end(-to-end revolution)?.** [[paper]](https://arxiv.org/abs/2105.07407v1)   
Elodie Laine, Stephan Eismann, Arne Elofsson, Sergei Grudinin.    
*Preprint, May 2021.*    

**Deep learning methods in protein structure prediction.**[[paper]](https://www.sciencedirect.com/science/article/pii/S2001037019304441)    
Mirko Torrisi, Gianluca Pollastri and Quan Le.     
*Computational and structural biotechnology journal (2020)*  

**Learning from protein fitness landscapes: a review of mutability, epistasis, and evolution**[[Paper]](https://www.sciencedirect.com/science/article/pii/S2452310019300022)  
Emily C. Hartman and Danielle Tullman-Ercek.  
*Current Opinion in Systems Biology (2019)*

**Machine-learning-guided directed evolution for protein engineering**[[paper]](https://www.nature.com/articles/s41592-019-0496-6)  
Kevin K. Yang, Zachary Wu & Frances H. Arnold  
*Nature Methods (2019)*

<a name="Benchmark"></a>
## Benchmarks
**PEER: A Comprehensive and Multi-Task Benchmark for Protein Sequence Understanding**[[paper]](https://arxiv.org/abs/2206.02096)  
Minghao Xu, Zuobai Zhang, Jiarui Lu, Zhaocheng Zhu, Yangtian Zhang, Chang Ma, Runcheng Liu and Jian Tang    
*arXiv Sep 2022*  

**Learning functional properties of proteins with language models**[[paper]](https://www.nature.com/articles/s42256-022-00457-9)[[code]](https://github.com/kansil/PROBE)  
Serbulent Unsal, Heval Atas, Muammer Albayrak, Kemal Turhan, Aybar C. Acar & Tunca Doğan    
*Nature Machine Intelligence (2022)*  

**Evaluating Protein Transfer Learning with TAPE.** [[paper]](https://arxiv.org/abs/1906.08230)  
Roshan Rao, Nicholas Bhattacharya, Neil Thomas, Yan Duan, Xi Chen, John Canny, Pieter Abbeel, Yun S. Song.   
*Preprint, June 2019.*   

<a name="PSP"></a>  
## PSP methods     

<a name="Structural"></a>    
### Structural Features Prediction
**SPOT-1D-LM: Reaching Alignment-profile-based Accuracy in Predicting Protein Secondary and Tertiary Structural Properties without Alignment**[[paper]](https://www.nature.com/articles/s41598-022-11684-w)    
Jaspreet Singh, Kuldip K. Paliwal, Jaswinder Singh and Yaoqi Zhou.     
*scientific reports (2022)*   

**Single Layers of Attention Suffice to Predict Protein Contacts**[[paper]](https://www.biorxiv.org/content/10.1101/2020.12.21.423882v1)  
Nicholas Bhattacharya, Neil Thomas, Roshan Rao, Justas Daupras, Peter K. Koo, David Baker, Yun S. Song and Sergey Ovchinnikov.   
*bioRxiv (2021)*  

**SPOT-Contact-Single: Improving Single-Sequence-Based Prediction of Protein Contact Map using a Transformer Language Model**[[paper]](https://www.biorxiv.org/content/10.1101/2021.06.19.449089v1)[[code]](https://github.com/jas-preet/SPOT-Contact-Single)  
Jaspreet Singh, Thomas Litfin, Jaswinder Singh, Kuldip K. Paliwal and Yaoqi Zhou.   
*bioRxiv (2021)*

**Accurate prediction of inter-protein residue-residue contacts for homo-oligomeric protein complexes.**[[paper]](https://academic.oup.com/bib/article/22/5/bbab038/6159364?login=false)[[server]](http://huanglab.phys.hust.edu.cn/DeepHomo/)  
Yumeng Yan and Sheng-You Huang.     
*Briefings in Bioinformatics (2021)*  

**Study of real-valued distance prediction for protein structure prediction with deep learning**[[paper]](https://academic.oup.com/bioinformatics/article/37/19/3197/6271411?login=false)  
Jin Li and Jinbo Xu.   
*Bioinformatics (2021)*  

**Multi-task deep learning for concurrent prediction of protein structural properties**[[paper]](https://www.biorxiv.org/content/10.1101/2021.02.04.429840v1.full)[[server]](http://qianglab.scst.suda.edu.cn/crrnn2/)  
Buzhong Zhang, Jinyan Li, Lijun Quan and Qiang Lyu.   
*bioRxiv (2021)*  

**SPOT-1D-Single: Improving the Single-Sequence-Based Prediction of Protein Secondary Structure, Backbone Angles, Solvent Accessibility and Half-Sphere Exposures using a Large Training Set and Ensembled Deep Learning.**[[paper]](https://academic.oup.com/bioinformatics/article/37/20/3464/6275257?login=false)[[server]](https://sparks-lab.org/server/spot-1d-single/)  
Jaspreet Singh, Thomas Litfin, Kuldip K. Paliwal, Jaswinder Singh, Anil Kumar Hanumanthappa and Yaoqi Zhou.     
*Bioinformatics (2021)*    

**Deep learning-based prediction of protein structure using learned representations of multiple sequence alignments**[[paper]](https://www.biorxiv.org/content/10.1101/2020.11.27.401232v1)  
Shaun M. Kandathil, Joe G Greener, Andy M. Lau and David T. Jones.   
*bioRxiv (2020)*  

**Template-based prediction of protein structure with deep learning**[[paper]](https://bmcgenomics.biomedcentral.com/articles/10.1186/s12864-020-07249-8)[[code]](https://github.com/ShenLab/ThreaderAI)     
Haicang Zhang and Yufeng Shen.    
*BMC Genomics (2020)*  

**Combination of deep neural network with attention mechanism enhances the explainability of protein contact prediction**[[paper]](https://pubmed.ncbi.nlm.nih.gov/33538038/)  
Chen Chen, Tianqi Wu, Zhiye Guo and Jianlin Cheng.   
*Proteins (2020)*

**Deducing high-accuracy protein contact-maps from a triplet of coevolutionary matrices through deep residual convolutional networks**[[paper]](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1008865)[[server]](https://seq2fun.dcmb.med.umich.edu//TripletRes/)    
Yang Li, Chengxin Zhang, Eric W. Bell, Wei Zheng, Xiao-Gen Zhou, Dong-Jun Yu and Yang Zhang.     
*PLOS Computational Biology (2020)*    

**REALDIST: Real-valued protein distance prediction**[[paper]](https://www.biorxiv.org/content/10.1101/2020.11.28.402214v1.full)[[code]](https://github.com/multicom-toolbox/deepdist)  
Badri Adhikari.   
*bioRxiv (2020)*  

**A fully open-source framework for deep learning protein real-valued distances**[[paper]](https://www.nature.com/articles/s41598-020-70181-0)[[code]](https://github.com/ba-lab/pdnet/)  
Badri Adhikari.     
*Scientific Reports (2020)*  

**DeepDist: real-value inter-residue distance prediction with deep residual convolutional network**[[paper]](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-021-03960-9)[[code]](https://github.com/multicom-toolbox/deepdist)  
Tianqi Wu, Zhiye Guo, Jie Hou and Jianlin Cheng.   
*BMC Bioinformatics (2020)*  

**A multi-task deep-learning system for predicting membrane associations and secondary structures of proteins**[[paper]](https://www.biorxiv.org/content/10.1101/2020.12.02.409045v1)     
Bian Li, Jeffrey L. Mendenhall, John A. Capra and Jens Meiler.     
*Journal of Proteome Research (2020)*   

**PconsC4: fast, accurate and hassle-free contact predictions.**[[paper]](https://academic.oup.com/bioinformatics/article/35/15/2677/5259184?login=false)[[code]](https://github.com/ElofssonLab/PconsC4)  
Mirco Michel, David Menéndez Hurtado and Arne Elofsson.    
*Bioinformatics (2019)*    

**DeepPrime2Sec: Deep Learning for Protein Secondary Structure Prediction from the Primary Sequences**[[paper]](https://www.biorxiv.org/content/10.1101/705426v1)[[code]](https://github.com/ehsanasgari/DeepPrime2Sec)  
Nina Pörner, Ehsaneddin Asgari, Alice C. McHardy and Mohammad R. K. Mofrad.   
*bioRxiv (2019)* 

**Deep learning extends de novo protein modelling coverage of genomes using iteratively predicted structural constraints**[[paper]](https://www.nature.com/articles/s41467-019-11994-0)[[code]](https://github.com/psipred/DMPfold)  
Joe G Greener, Shaun M. Kandathil and David T. Jones.     
*Nature Communications (2018)*    

**Accurate prediction of protein contact maps by coupling residual two-dimensional bidirectional long short-term memory with convolutional neural networks**[[paper]](https://academic.oup.com/bioinformatics/article/34/23/4039/5040307?login=false)[[server]](http://sparks-lab.org/jack/server/SPOT-Contact/)  
Jack Hanson, Kuldip K. Paliwal, Thomas Litfin, Yuedong Yang and Yaoqi Zhou.   
*Bioinformatics (2018)*  

**High precision in protein contact prediction using fully convolutional neural networks and minimal sequence features.**[[paper]](https://pubmed.ncbi.nlm.nih.gov/29718112/)[[code]](https://github.com/psipred/DeepCov)    
David T. Jones and Shaun M. Kandathil.    
*Bioinformatics (2018)*  

**DeepCDpred: Inter-residue Distance and Contact Prediction for Improved Prediction of Protein Structure.**[[paper]](https://pubmed.ncbi.nlm.nih.gov/30620738/)  
Shuangxi Ji, Tuğçe Oruç, Liam Mead, Muhammad Fayyaz ur Rehman, Christopher M. Thomas, Sam Butterworth and Peter J. Winn.   
*PLOS ONE (2018)*

**Improved protein contact predictions with the MetaPSICOV2 server in CASP12**[[paper]](https://pubmed.ncbi.nlm.nih.gov/28901583/)[[server]](https://predictioncenter.org/)     
Daniel W. A. Buchan and David T. Jones.   
*Proteins (2018)*    

**NetSurfP-2.0: improved prediction of protein structural features by integrated deep learning**[[paper]](https://onlinelibrary.wiley.com/doi/abs/10.1002/prot.25674)[[server]](https://services.healthtech.dtu.dk/service.php?NetSurfP-2.0)    
Michael Schantz Klausen, Martin Closter Jespersen, Henrik Nielsen, Kamilla Kjærgaard Jensen, Vanessa Isabell Jurtz, Casper Kaae Sønderby, Morten Otto Alexander Sommer, Ole Winther, Morten Nielsen, Bent O. Petersen and Paolo Marcatili.     
*Proteins (2018)*    

**Porter 5: state-of-the-art ab initio prediction of protein secondary structure in 3 and 8 classes**[[paper]](https://www.biorxiv.org/content/10.1101/289033v4)[[server]](http://distilldeep.ucd.ie/porter/)  
Mirko Torrisi, Manaz Kaleel and Gianluca Pollastri.   
*bioRxiv (2018)*  

**Single-sequence-based prediction of protein secondary structures and solvent accessibility by deep whole-sequence learning**[[paper]](https://pubmed.ncbi.nlm.nih.gov/30368831/)[[server]](http://sparks-lab.org)     
Rhys Heffernan, Kuldip K. Paliwal, James Lyons, Jaswinder Singh, Yuedong Yang and Yaoqi Zhou.     
*Journal of Computational Chemistry (2018)*    

**Enhancing Evolutionary Couplings with Deep Convolutional Neural Networks**[[paper]](https://pubmed.ncbi.nlm.nih.gov/29275173/)[[code]](https://github.com/largelymfs/deepcontact)    
Yang Liu, Perry Palmedo, Qing Ye, Bonnie Berger and Jian Peng.   
*Cell systems (2017)*  

**DNCON2: Improved protein contact prediction using two-level deep convolutional neural networks**[[paper]](https://pubmed.ncbi.nlm.nih.gov/29228185/)[[code]](https://github.com/multicom-toolbox/DNCON2/)  
Badri Adhikari, Jie Hou and Jianlin Cheng.   
*Bioinformatics (2017)*

**Capturing non-local interactions by long short-term memory bidirectional recurrent neural networks for improving prediction of protein secondary structure, backbone angles, contact numbers and solvent accessibility.**[[paper]](https://academic.oup.com/bioinformatics/article/33/18/2842/3738544?login=false)[[server]](http://sparkslab.org)  
Rhys Heffernan, Yuedong Yang, Kuldip K. Paliwal and Yaoqi Zhou.       
*Bioinformatics (2017)* 

**Accurate De Novo Prediction of Protein Contact Map by Ultra-Deep Learning Model**[[paper]](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005324)    
Sheng Wang, Siqi Sun, Zhen Li, Renyu Zhang and Jinbo Xu.   
*PLOS Computational Biology (2016)*  

**A hybrid method for prediction of protein secondary structure based on multiple artificial neural networks**[[paper]](https://ieeexplore.ieee.org/document/7973605)  
Haris Hasic, Emir Buza and Amila Akagic.     
*international convention on information and communication technology electronics and microelectronics (2017)* 

**RaptorX-Property: a web server for protein structure property prediction**[[paper]](https://academic.oup.com/nar/article/44/W1/W430/2499323?login=false)[[server]](http://raptorx2.uchicago.edu/StructurePropertyPred/predict/)    
Li Wei, Sheng Wang, Shiwang Liu and Jinbo Xu.    
*Nucleic Acids Research (2016)*  

**MUST-CNN: a multilayer shift-and-stitch deep convolutional architecture for sequence-based protein structure prediction**[[paper]](https://dl.acm.org/doi/abs/10.5555/3015812.3015817)    
Zeming Lin, Jack Lanchantin and Yanjun Qi.    
*national conference on artificial intelligence (2016)*  

**Protein Secondary Structure Prediction Using Deep Multi-scale Convolutional Neural Networks and Next-Step Conditioning**[[paper]](https://arxiv.org/abs/1611.01503)  
Akosua Busia, Jasmine Collins and Navdeep Jaitly.   
*arXiv: Learning (2016)*

**A deep learning network approach to ab initio protein secondary structure prediction**[[paper]](https://pubmed.ncbi.nlm.nih.gov/25750595/)  
Matthew Spencer, Jesse Eickholt and Jianlin Cheng.   
*IEEE/ACM Transactions on Computational Biology and Bioinformatics (2015)*    

**Improving prediction of secondary structure, local backbone angles, and solvent accessible surface area of proteins by iterative deep learning.**[[paper]](https://www.nature.com/articles/srep11476)[[server]](http://sparks-lab.org/)  
Rhys Heffernan, Kuldip K. Paliwal, James Lyons, Abdollah Dehzangi, Alok Sharma, Jihua Wang, Abdul Sattar, Yuedong Yang and Yaoqi Zhou.        
*Scientific Reports (2015)* 

**Protein Secondary Structure Prediction with Long Short Term Memory Networks**[[paper]](https://arxiv.org/abs/1412.7828)    
Søren Kaae Sønderby and Ole Winther.   
*arXiv: Quantitative Methods (2014)*  

**SSpro/ACCpro 5: almost perfect prediction of protein secondary structure and relative solvent accessibility using profiles, machine learning and structural similarity**[[paper]](https://pubmed.ncbi.nlm.nih.gov/24860169/)[[server]](http://scratch.proteomics.ics.uci.edu/)  
Christophe Magnan and Pierre Baldi.     
*Bioinformatics (2014)*    

**Deep Supervised and Convolutional Generative Stochastic Network for Protein Secondary Structure Prediction**[[paper]](https://dl.acm.org/doi/abs/10.5555/3044805.3044890)  
Jian Zhou and Olga G. Troyanskaya.   
*international conference on machine learning (2014)*  

**A dynamic Bayesian network approach to protein secondary structure prediction**[[paper]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2266706/)       
Xin-Qiu Yao, Huaiqiu Zhu and Zhen-Su She.        
*BMC Bioinformatics (2008)*  

**Protein secondary structure prediction with a neural network.**[[paper]](https://www.pnas.org/doi/abs/10.1073/pnas.86.1.152)  
L H Holley and Martin Karplus.   
*Proceedings of the National Academy of Sciences of the United States of America (1989)*  

**Improved prediction of protein secondary structure by use of sequence profiles and neural networks**[[paper]](https://www.pnas.org/doi/10.1073/pnas.90.16.7558)      
Burkhard Rost and Chris Sander      
*Proceedings of the National Academy of Sciences of the United States of America (1993)*    
      

   





<a name="Traditional"></a>  
### Traditional methods  



<a name="tool"></a>
## Folding tools



