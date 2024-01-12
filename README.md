# ORNL-Fall-2023

The code in this repository contains snippets of 16 weeks of work during an URSI(Undergradute Student Research Internship) at Oak Ridge National Lab. 

The Goal of this internship was to ease machine learning usage for scientists that are not directly from the domain of machine learning(ML) or computer science. This came largely came in the form of physicists, or chemists. A variety of fascillities exist at Oak Ridge National Lab that generate massive amounts of data, this includes electron microscopes, a spallation neutron source, a high flux isotope reactor and more. Scientists used machine learning to analyze the data.

With the rising prevalance of machine learning in a variety of science domains, it is essential to ensure responsible usage of artificial intelligence and a large part of that involves tracking data provenance or essentially keeping a record of all data manipulations as well as all of the settings and hyperparameters that were used in the production of a machine learning model. It is also essential to see how these models compare to eachother in accuracy as well as to understand the energy expenditures needed to result in models of different accuracies. The program I worked on, Flowcept, aimed to tackle these issues by storing a great amount of information about each machine learning model workflow without adding significant overhead.

Specifically for this program I had 3 major contributions: a convenient querying function to report data about specific ML models, enabling the usage of flowcept with Google Colab so no other system setup is required(data storage systems like mongoDB and Redis function remotely), and by creating an HTML page that could be dynamically populated with all the information that a scientist would need about a specific ML task. 

In addition to these contributions I generally helped by contributing to the Flowcept program and made multiple commits to its repository.
