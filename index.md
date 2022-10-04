[About](#about) - [Call for Papers](#call-for-papers) - [Speakers](#speakers) - [Schedule](#schedule) - [Registration](#registration) - [Important Dates](#important-dates) - [Poster Session](#poster-session)

Big successes of machine learning (ML) for molecules have been achieved recently, e.g. the accurate prediction of protein 3D structure (Jumper 2021; Thornton, 2021), discovery of novel antibiotics (Stokes, 2020; Das, 2021), or chemical synthesis planning (Segler, 2018). These successes make molecular machine learning one of the prime candidates to tackle the climate-, energy- and pandemic-related crisis that we are facing. Nevertheless, there are still major challenges and  substantial critique is voiced on current methods that are based mostly on deep learning (Marcus, 2018). Deep learning (DL) methods are data hungry, have limited knowledge transfer capabilities, do not quickly adapt to changing tasks or distributions, insufficiently incorporate world and prior knowledge, and cannot inherently distinguish causation from correlation (Bengio, 2021; Chollet, 2019; Marcus, 2018; Schölkopf, 2019). Furthermore, the current models are usually not composable in a sense that sub-components or different modules can be combined in a new way. With these characteristics, the machine learning systems currently employed for molecules are of the type of a narrow artificial intelligence (AI) (Chollet, 2019; Hochreiter, 2022). The above-mentioned drawbacks hold in particular for molecular machine learning, such as activity and property prediction, generative modeling (Yang, 2017; Bender, 2021; Fan, 2022), chemical reactivity and synthesis (Segler, 2018; Seidl, 2022), and molecular modeling (Bereau, 2013) and representation learning.    

Therefore, this workshop focuses on exposing the current limitations of machine learning methods for molecules by critically assessing them, either theoretically or in applied and in industrial settings. The methods contributed to this workshop can focus on architectures that are robust against domain shifts, such as new biotechnologies or types of molecules. The proposed methods can also focus on quickly adapting to newly acquired data with potentially expensive biotechnologies, concretely few- and zero-shot learning methods. A further theme of the workshop is on methods that lead to new levels of abstractions of molecule representations, such that broader generalization capabilities are enabled. A potential step in this direction are machine learning methods for creating relevant physical abstractions, e.g. for improving molecular dynamics simulations or force fields. Advancing machine learning for molecules also means that these new systems should be able to interact with humans and transfer knowledge between them and the system, which is covered by the workshop theme on interpretability and explainability methods. The workshop also includes considerations and methodologies that allow for modularity or compositionality of architectures for molecular machine learning. 
<p align="center">
  <img src="[https://user-images.githubusercontent.com/38696018/137133589-1a5d3f07-170b-40d2-b35a-2ac731a5b36e.jpg](https://github.com/moleculediscovery/workshop2022/blob/5c2ca6e4ef85deff87180003c2a1530f01a9f9f7/ellis%20logo-%20cambridge%20linz.png)"> </p> 
The workshop will be hosted by the [ELLIS unit Cambridge](http://www.ellis.eng.cam.ac.uk/) and [ELLIS unit Linz](https://www.jku.at/en/lit-artificial-intelligence-lab/ellis-unit-linz/) as a side-event to NeurIPS2022 and held in VIRTUAL mode via [Zoom](https://zoom.us) and [GatherTown](https://www.gather.town).

### Call for papers
We are calling for papers advancing or critically assessing molecular machine learning. Topics include (but not limited to):  

- Critical assessment of molecular machine learning
- Benchmarking machine learning methods for molecules and new data sets or tasks
- Zero- and few-shot learning methods for molecules, data-efficient learning 
- Domain shifts and out-of-distribution handling 
- Abstraction and improved representations of molecules
- Interpretability and explainability methods for molecules
- Multi-modal learning and modular architectures
- Causality and physics-based machine learning for molecules

Please submit your contributions on [OpenReview](https://openreview.net/group?id=ELLIS.eu/2022/Workshop/ML4Molecules) until Oct 18 2022 12:00AM UTC-0 (abstract registration deadline) and Oct 20 2022 12:00AM UTC-0 (paper deadline). The submissions should be in PDF and follow the [NeurIPS template](https://nips.cc/Conferences/2022/PaperInformation/StyleFiles) with a maximum of 4 pages (not including references and appendices). Please anonymize your paper since the review process is dual-anonymous. 

### Speakers
- Janet Thornton, EBI Hinxton, UK (confirmed)
- Tao Qin, Microsoft Research, China 
- Andreas Bender, University Cambridge, UK (confirmed)
- Lucy Colwell, Google Research, US  (confirmed) 
- Koji Tsuda, University of Tokyo, Japan (confirmed)
- Francesca Grisoni, TU Eindhoven, Netherlands (confirmed)
- Payel Das, IBM NYC, US (confirmed)
- Christian Kramer, Roche, Switzerland

### Schedule 
- Opening remarks
- Invited talks
- Contributed talks
- Poster session
- Invited talks
- Contributed talks
- Closing remarks

### Registration
The workshop will be open for everyone without registration fee. Details on the registration will follow soon!

### Important dates
 - October 18, 2022: submission deadline
 - Mid November, 2022: author notification
 - November 28, 2022: workshop

### Organizing Committee and Contact
Chairs: Jennifer Wei, Nadine Schneider, Günter Klambauer, Marwin Segler, and Jose Miguel Hernandez Lobato  
Contact: ml4molecules@ml.jku.at

### Program Committee
TBA

### References
Bender, A., & Cortés-Ciriano, I. (2021). Artificial intelligence in drug discovery: what is realistic, what are illusions? Part 1: ways to make an impact, and why we are not there yet. Drug discovery today, 26(2), 511-524.  
Bengio, Y., Lecun, Y., & Hinton, G. (2021). Deep learning for AI. Communications of the ACM, 64(7), 58-65.  
Bereau, T., Kramer, C., & Meuwly, M. (2013). Leveraging symmetries of static atomic multipole electrostatics in molecular dynamics simulations. Journal of Chemical Theory and Computation, 9(12), 5450-5459.  
Chen, H., Engkvist, O., Wang, Y., … & Blaschke, T. (2018). The rise of deep learning in drug discovery. Drug discovery today, 23(6), 1241-1250.  
Chollet, F. (2019). On the measure of intelligence. arXiv preprint arXiv:1911.01547.  
Das, P., Sercu, T., Wadhawan, K., Padhi, I., Gehrmann, S., Cipcigan, F., ... & Mojsilovic, A. (2021). Accelerated antimicrobial discovery via deep generative models and molecular dynamics simulations. Nature Biomedical Engineering, 5(6), 613-623.  
Fan, Y., Xia, Y., Zhu, J., Wu, L., Xie, S., & Qin, T. (2022). Back translation for molecule generation. Bioinformatics, 38(5), 1244-1251.  
Hochreiter, S. (2022). Toward a broad AI. Communications of the ACM 65, no. 4: 56-57.  
Jumper, J., Evans, R., Pritzel, A.,  ... & Hassabis, D. (2021). Highly accurate protein structure prediction with AlphaFold. Nature, 596(7873), 583-589.  
Segler, M. H., Preuss, M., & Waller, M. P. (2018). Planning chemical syntheses with deep neural networks and symbolic AI. Nature, 555(7698), 604-610.  
Klambauer, G. (2021). Moving beyond narrow AIs in Drug Discovery -- a perspective. ELLIS ML4Molecules workshop Dec 13, 2021. Virtual, https://moleculediscovery.github.io/workshop2021/.   
Marcus, G. (2018). Deep learning: A critical appraisal. arXiv preprint arXiv:1801.00631.  
Schölkopf, B. (2019). Causality for machine learning. arXiv preprint arXiv:1911.10500.  
Seidl, P., Renz, P., Dyubankova, N., Neves, P ,... & Klambauer, G. (2022). Improving Few-and Zero-Shot Reaction Template Prediction Using Modern Hopfield Networks. Journal of chemical information and modeling.  
Stokes, J. M., Yang, K., Swanson, K., Jin, W.,... & Collins, J. J. (2020). A deep learning approach to antibiotic discovery. Cell, 180(4), 688-702.  
Thornton, J. M., …,, & Borkakoti, N. (2021). AlphaFold heralds a data-driven revolution in biology and medicine. Nature Medicine, 27(10), 1666-1669.  
Yang, X., Zhang, J., Yoshizoe, K., Terayama, K., & Tsuda, K. (2017). ChemTS: an efficient python library for de novo molecular generation. Science and technology of advanced materials, 18(1), 972-976.   

