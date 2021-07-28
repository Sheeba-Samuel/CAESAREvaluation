# Evaluation of CAESAR
Materials used for the development and evaluation of [CAESAR](https://github.com/CaesarReceptorLight) (CollAborative Environment for
Scientific Analysis with Reproducibility).

The repository contains two folders:  
  * ProvBook  
    *  The folder contains the Jupyter notebooks used in the evaluation of [ProvBook](https://github.com/Sheeba-Samuel/ProvBook). Each notebook are shared with the provenance information of the execution of Jupyter Notebook. Each notebook with its provenance is also shared in RDF (Resource Description Framework) in the turtle format. The provenance information stored in the notebook help users to compare the results of the original execution of the notebook with our execution.
  * REPRODUCE-MEOntolgy  
    * CompetencyQuestionResults: The folder contains 10 sample competency questions and their answers used in the evaluation of [REPRODUCE-ME ontolgy](https://w3id.org/reproduceme/) with the data stored in CAESAR. 
    The sample competency questions are:
      * What are the input and output variables of an experiment?
      * Which are the methods and standard operating procedures used?
      * Which are the files and materials that were used in a particular step?
      * Which are the steps involved in an experiment which used a particular material?
      * What is the complete path taken by a scientist for an experiment?
      * Which are the instruments that are associated with an experiment and their settings when the output was generated?
      * Which are the agents directly or indirectly responsible for an experiment?
      * Who created this experiment and when? Who modified it and when?
      * Which are the publications or external resources that were referenced?
      * List all the experiments which uses growth protocol (EFO_0003789) and studies on "Homo sapiens" and resulted in phenotype "shorter prophase" which passed the quality control.    
    * ExperimentDatasets: The folder contains the metadata from [IDR](https://github.com/IDR/idr-metadata) used for the evaluation of CAESAR. The metadata from IDR is expressed in RDF. The example data converted to RDF are from the experiments IDR 2, 20, 32, and 38.
    
  * UserEvaluation: The folder contains the CAESAREvaluation file which contains the results from the user evaluation study of CAESAR. The study is conducted with 6 users. The file contains the raw data responses.

Detailed information on each resource used in the evaluation is available here: https://w3id.org/reproduceme/

Paper: [A provenance-based semantic approach to support understandability, reproducibility, and reuse of scientific experiments](https://doi.org/10.22032/dbt.40396)
