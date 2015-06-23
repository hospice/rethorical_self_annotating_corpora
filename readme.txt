All the data are extracted from the PubMed repository (in XML -nxml format) 


+Original_data
	-Methodsentences.txt                                -------->      "Method sentences" with source file name (article) reference removed
	-Resultsentences.txt								-------->	   "Result sentences" with source file name (article) reference removed
	-Conclusionsentences.txt							-------->	   "Conclusion sentences" with source file name (article) reference removed
	-Findingsentences.txt								-------->	   "Finding sentences" with source file name (article) reference removed
	
	-Method_sentences_with_anaphoric_reference.txt      -------->      Original "Method sentences" with their anaphoric reference sentences preceding. Line starts with the name of the file they are extracted from  
	-Result_sentences_with_anaphoric_referencex.txt		-------->	   Original "Result sentences" with their anaphoric reference sentences preceding. Line starts with the name of the file they are extracted from   
	-Conclusion_sentences_with_anaphoric_reference.txt	-------->	   Original "Conclusion sentences" with their anaphoric reference sentences preceding. Line starts with the name of the file they are extracted from  
	-Finding_sentences_with_anaphoric_reference.txt		-------->	   Original "Finding sentences with their anaphoric reference sentences preceding. Line starts with the name of the file they are extracted from  
	
+Processed_data
	-MethodonesentenceWithTense.csv						-------->        "Method sentences", followed by two features denoting the presence of Present tense or Past tense respectively in the sentence 
	-ResultonesentenceWithTense.csv						-------->        "Result sentences", followed by two features denoting the presence of Present tense or Past tense respectively in the sentence 
	-ConclusiononesentenceWithTense.csv					-------->        "Conclusion sentences", followed by two features denoting the presence of Present tense or Past tense respectively in the sentence 
	
	
	-MRCdataWithTense                                   -------->        Method, Result and Conclusion sentences from the Processed_data folder above as used in the paper "An automated method to build a corpus of rhetorically-classified sentences in biomedical texts"
	
	
	For more information See: 
	
	
@InProceedings{houngbo-mercer:2014:W14-21,
  author    = {Houngbo, Hospice  and  Mercer, Robert E.},
  title     = {An automated method to build a corpus of rhetorically-classified sentences in biomedical texts},
  booktitle = {Proceedings of the First Workshop on Argumentation Mining},
  month     = {June},
  year      = {2014},
  address   = {Baltimore, Maryland},
  publisher = {Association for Computational Linguistics},
  pages     = {19--23},
  url       = {http://www.aclweb.org/anthology/W14-2103}
}
	
	
	
	
Author: Hospice Houngbo
email: hhoungbo@uwo.ca, life4everh@gmail.com