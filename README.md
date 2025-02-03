# Mapping the South African research landscape using BERTopic

#### Foreword

My honours year at the Stellenbosch University CS Department
required a thesis project. I decided to take an irresponsible
dive into natural language processing under the supervision 
of
[Marcel Dunaiski](https://scholar.google.co.za/citations?user=3K4dIR8AAAAJ&hl=en). 
The project investigates methods of analysing and summarising the trends in South African research.

The project was unfortunately not extended for further research; 
I entered the working world. The project is property to [Stellenbosch University](https://www.sun.ac.za/english).
I am rather proud of the results, even with some shortcomings that can be found in any researcher's first attempt.

I would appreciate anyone who takes the time to read the attached academic paper.
Below are a few key selling points that might just sway someone:

* The dataset consisted of South African masters' theses and PhD dissertation totalling to 108.470 papers. 
The dataset came from an independent research institution and was augmented with various sources.
* The first science mapping method used as a comparison to the proposed method, groups papers by finding optimal modules based on citation counts. 
This method boils down to a wondrous minimisation problem to find citation-based clusters.
* The second, proposed method is a transformer-based topic modelling technique called [BERTopic](https://maartengr.github.io/BERTopic/index.html).
Papers are clustered based on content, and require a new class-based TF-IDF measure to represent.
* Both methods come with very apparent pros and cons. I won't spoil anything here. Both results use a variety of  bibliometric indices to enhance the analysis.
* The result was a good understanding of the South African research landscape over the last few decades. 
The extent of the data caused some analysis paralysis, but taking a step back with the Python/React app allowed some clear, interesting trends to be found.
* Not sold yet? DATA SCIENCE! LANGUAGE MODELS! DIMENSIONALITY REDUCTION! NEURAL NETWORKS! **TRANSFORMERS!!!**

A lot of work went into this, I hope any readers do find some insight and some joy :)
