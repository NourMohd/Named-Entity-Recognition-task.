Implementing models for the Named Entity Recog-nition (NER) task.  NER is the task to associate the words in a sentence with their proper name tags.  Forexample, “Marie Curie” may correspond to the tagPER(person) and “Princeton University” may correspondto the tagORG(organization).  In this programming assignment, will use a total of 5 tags:PER(person),ORG(organization),LOC(location),MISC(miscellaneous), andO(non-entity).  For example, the correct tagging ofthe sentence “Steve Jobs founded Apple with Steve Wozniak .”  is⟨PER,PER,O,ORG,O,PER,PER⟩.  Note that whenconsecutive words constitute a named entity, such as “Steve Jobs” in the previous example, they should bothbe tagged asPER.


Using HMMs and MEMMs
