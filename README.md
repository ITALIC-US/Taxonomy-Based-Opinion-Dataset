# Taxonomy-Based Opinion Dataset
                            
This dataset contains annotated reviews for three different domains: cars, headphones and hotels. The reviews was extracted from Epinions.com. 

For each domain, a set of reviews are included in a directory with the same name. There is one xml file for each review. Opinions are annotated at the feature level, with the following fields:

(Mandatory)
* **polarity**: positive (+) or negative (-).
* **feature**: a feature from the feature taxonomy.
* **opWords**: opinion words. The minimum set of words from the sentence from which you can decide the polarity of this opinion.

(Optional)
* **featWords**: feature words. A set of words from the sentence naming the feature.
* **potency**: potency words. A set of words from the sentence which affect the strength of the opinion.


"opWords", "featWords" and "potency" are expressed as lists of numbers, referring to the tokens from the sentence.

The feature taxonomy is defined in an xml file (featureTaxonomy.xml). For each feature, a set of feature words is included. 

Please, cite the following paper if you use this resource:

Fermín L. Cruz, José A. Troyano, Fernando Enríquez, F. Javier Ortega and Carlos G. Vallejo, ‘Long autonomy or long delay?’ The importance of domain in opinion mining, Expert Systems with Applications, Volume 40, Issue 8, 2013, Pages 3174-3184
