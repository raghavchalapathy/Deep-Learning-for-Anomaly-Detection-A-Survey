# Deep Learning for Anomaly Detection : A Survey

 The aim of this survey is two fold, firstly we present a structured and comprehensive reviewof research methods in deep anomaly detection (DAD). Furthermore, we also discuss the adoption of DAD methods across various application domains and assess their effectiveness.

# Table of contents
* [envirius](#envirius)
    * [Idea](#idea)
    * [Features](#features)
  * [Installation](#installation)
  * [Uninstallation](#uninstallation)
  * [Available plugins](#available-plugins)
  * [Usage](#usage)
    * [Check available plugins](#check-available-plugins)
    * [Check available versions for each plugin](#check-available-versions-for-each-plugin)
    * [Create an environment](#create-an-environment)
    * [Activate/deactivate environment](#activatedeactivate-environment)
      * [Activating in a new shell](#activating-in-a-new-shell)
      * [Activating in the same shell](#activating-in-the-same-shell)
    * [Get list of environments](#get-list-of-environments)
    * [Get current activated environment](#get-current-activated-environment)
    * [Do something in environment without enabling it](#do-something-in-environment-without-enabling-it)
    * [Get help](#get-help)
    * [Get help for a command](#get-help-for-a-command)
  * [How to add a plugin?](#how-to-add-a-plugin)
    * [Mandatory elements](#mandatory-elements)
      * [plug_list_versions](#plug_list_versions)
      * [plug_url_for_download](#plug_url_for_download)
      * [plug_build](#plug_build)
    * [Optional elements](#optional-elements)
      * [Variables](#variables)
      * [Functions](#functions)
    * [Examples](#examples)
  * [Example of the usage](#example-of-the-usage)
  * [Dependencies](#dependencies)
  * [Supported OS](#supported-os)
  * [Tests](#tests)
  * [Version History](#version-history)
  * [License](#license)
  * [README in another language](#readme-in-another-language)





# Table of contents


1 [Deep Learning for Anomaly Detection: A Survey]
      1.1 [Introduction](#introduction)
      1.2 [What are anomalies?] (#What are anomalies?)
      1.3 [What are novelties?]
      1.4 [Motivation and Challenges: Deep anomaly detection (DAD) techniques]
      1.5 [RelatedWork] 
      1.6 [OurContributions ]
      1.7 [Organization]
      1.8 [Different aspects of deep learning-based anomaly detection.]
        [1.8.1 Nature of Input Data]
      1.8.2 [Based on Availability of labels ]
        1.8.2.1 [Supervised deep anomaly detection]
        1.8.2.2 [Semi-supervised deep anomaly detection.]
        1.8.2.3 [Unsupervised deep anomaly detection ]
      1.8.3 [Based on training objective]
       1.8.3.1 [Deep Hybrid Models(DHM) ]
       1.8.3.2 [One-Class Neural Networks (OC-NN) ]
      1.8.4 [Type of Anomaly]
       1.8.4.1 [PointAnomalies]
       1.8.4.2 [Contextual Anomaly Detection ]
       1.8.4.3 [Collective or Group Anomaly Detection]


1.8.5 Output ofDADTechniques .................. 13 1.8.5.1 AnomalyScore: ................... 13 1.8.5.2 Labels:........................ 14
1.9 ApplicationsofDeepAnomalyDetection . . . . . . . . . . . . . . . 14
1.9.1 IntrusionDetection....................... 14
1.9.1.1 Host-Based Intrusion Detection Systems (HIDS): . 14
1.9.1.2 Network Intrusion Detection Systems (NIDS): . . . 15
1.9.2 FraudDetection......................... 18
1.9.2.1 Bankingfraud .................... 18
1.9.2.2 Mobilecellularnetworkfraud . . . . . . . . . . . . 19
1.9.2.3 Insurancefraud ................... 20
1.9.2.4 Healthcarefraud................... 20
1.9.3 MalwareDetection....................... 21
1.9.4 MedicalAnomalyDetection:.................. 21
1.9.5 Deep learning for Anomaly detection in Social Networks . . . 23
1.9.6 LogAnomalyDetection:.................... 24
1.9.7 Internet of things (IoT) Big Data Anomaly Detection . . . . . 24
1.9.8 IndustrialAnomaliesDetection ................ 25
1.9.9 AnomalyDetectioninTimeSeries . . . . . . . . . . . . . . 26
1.9.10 VideoSurveillance ....................... 27
1.10 DeepAnomalyDetection(DAD)Models . . . . . . . . . . . . . . . 28
1.10.1 Superviseddeepanomalydetection . . . . . . . . . . . . . . 29
1.10.2 Semi-supervised deep anomaly detection . . . . . . . . . . . 30
1.10.3 Hybriddeepanomalydetection ................ 31
1.10.4 One-class neural networks (OC-NN) for anomaly detection . . 34
1.10.5 Un-supervised Deep Anomaly Detection . . . . . . . . . . . 35
1.10.6 MiscellaneousTechniques ................... 37 1.10.6.1 Transfer Learning based anomaly detection : . . . 37



## Contributing

Please leave a comment  if you wish to get your work be included in the survey kindly leave paper title 

 [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.


## Authors

* **Raghavendra Chalapathy** - *Initial work* 

See also the contributors referenced within the paper .

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Citation and Contact

You find the PDF of the Deep Learning for Anomaly Detection : A Survey  paper at 



If you use our work, please also cite the paper:

If you have any suggestions about paper, feel free to mail me :)
