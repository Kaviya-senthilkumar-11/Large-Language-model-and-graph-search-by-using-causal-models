# Large-Language-model-and-graph-search-by-using-causal-models
Using the Tennessee Eastman Process(TEP) Simulation Dataset as our study's foundation dataset. 
Using large language models (LLMs), this dissertation suggests an innovative framework for comprehensive causal graph discovery. Our method leverages breadth-first search (BFS) to reduce the number of pairwise queries to linear, improving efficiency compared to earlier LLM-based approaches that require an increasing number of queries. Observational data can also be added to the system to enhance performance. Our approach is successful and efficient in identifying relationships between variables, as demonstrated by state-of-the-art findings on real-world causal graphs. We examine how LLMs can be used to provide diagnostic criteria, analyse control system overviews, and recommend fault techniques. We additionally examine graph search techniques for identification and component relationship modelling. We assess the diagnostic efficiency and accuracy of the framework by applying the data collected from the Tennessee Eastman Process (TEP) Simulation Dataset. 

RESEARCH GAP
However, it is noteworthy that intelligent application of both large language models (LLMs) and graph search algorithms is not yet quite achieved, therefore, the research gap in their combination still exists and requires tackling to improve fault diagnosis in control systems. Currently, the main methodologies dealing with either implementing LLMs to perform text-oriented assignments or traditional search techniques to explore fault analysis are in place, though, a great framework that integrates both techniques to produce a rich and flexible feature is yet to be fully developed. Below, we outline specific gaps in the current research: 
The present research utilizes LLMs in the analysis of pairwise interrelationships but there are no clear algorithms in the literature accruing to proving the entire causal graphs. Incorporating LLMs into graph search methods brings down the level of errors in structural diagnoses untested yet.

Two prompts per pair:
Does changing variable A cause a change in variable B? Please answer in a single word: yes or no.
Does changing Variable B cause a change in Variable A? Please answer in a single word: yes or no.

