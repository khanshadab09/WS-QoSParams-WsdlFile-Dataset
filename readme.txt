----------------------------------------------------------------------------------
 * README document for the Integrated Dataset, which incorporates QoS parameters 
   along with OWL-S Semantic Web Service descriptions presented in dual formats — 
   Natural Language and SWRL/KIF (Version 1.0):
 
 * Last updated: 2025/12/11
----------------------------------------------------------------------------------
			######## ABOUT THE DATA SET ########
----------------------------------------------------------------------------------
 * The research utilized QWS (Dataset-1) and WS-DREAM (Dataset-2), which were 
   deemed most appropriate due to their provision of comprehensive, verified 
   QoS metadata and corresponding WSDL URIs.

 * The dataset provides a comprehensive integration of QoS metrics and the 
   associated semantic description in OWLS language of the Web Services.

 * The generated semantic descriptions are available in both a Natural Language 
   format and the machine-readable SWRL/KIF format.

 * Semantic descriptions were successfully generated for 169 web services from 
   QWS (Dataset-1) and 286 web services from WS-DREAM (Dataset-2). Each service 
   is represented in two semantic formats—Natural Language (NL OWL) and SWRL/KIF
   (SWRL OWL)—yielding a total of 910 OWL-S semantic files across both datasets.

+-----------------------+------------------+------------------------+-------------+
| Dataset               | NL Format (OWL-S)| SWRL/KIF Format (OWL-S)| Total Files |
+-----------------------+------------------+------------------------+-------------+
| QWS (Dataset-1)       | 169              | 169                    | 338         |
+-----------------------+------------------+------------------------+-------------+
| WS-DREAM (Dataset-2)  | 286              | 286                    | 572         |
+-----------------------+------------------+------------------------+-------------+
| Total Semantic Files  | 455              | 455                    | 910         |
+-----------------------+------------------+------------------------+-------------+

 * It is available for downloading at: 
   https://khanshadab09.github.io/WS-QoSParams-WsdlFile-Dataset/
----------------------------------------------------------------------------------
			######## List of contents ########
----------------------------------------------------------------------------------
 The dataset files include:

 * WS_Integrated_Dataset
	└── Integrated_Dataset.xlsm
	
	This is a macro-enabled Excel file containing two sheets: QWS (Dataset-1) 
	and WS-DREAM (Dataset-2). The QoS details for both datasets are preserved 
	as they are, and the last two columns of each sheet include hyperlinks to 
	the corresponding Semantic Description files of the web services. Each web
	service has its semantic description provided in OWL-S, available in two 
	formats: Natural Language and SWRL/KIF.

 * WS_Semantic_Description_Files
	└── QWS Ver 2
		└── NL OWL
		└── SWRL OWL
	└── WS-DREAM Dataset1
		└── NL OWL
		└── SWRL OWL
	
	The NL OWL and SWRL OWL directories store the semantic description files of
	the web services, presented in Natural Language and SWRL/KIF formats, 
	respectively.

 * readme.txt
----------------------------------------------------------------------------------
			######## References ########
----------------------------------------------------------------------------------

 * QWS (Dataset-1):

 	The QWS dataset is available free of charge for educational and non-commercial 
	purposes. In exchange, we kindly request that you make available to us the 
	results of running the QWS dataset. Please use the following references in 
	citing the dataset:

  	- Al-Masri, E., and Mahmoud Q. H., "Investigating web services on the world 
	wide web", 17th international conference on World Wide Web (WWW '08), 
	pp.795-804.

	- Al-Masri, E., and Mahmoud, Q. H., "QoS-based Discovery and Ranking of Web 
	Services", IEEE 16th International Conference on Computer Communications and 
	Networks (ICCCN), 2007, pp. 529-534.

	- Al-Masri, E., and Mahmoud, Q. H., "Discovering the best web service", 
	16th International Conference on World Wide Web (WWW), 2007, pp. 1257-1258.

 * WS-DREAM (Dataset-2):
	
	Please refer to the following papers for the detailed descriptions of this 
	dataset:

	- Zibin Zheng, Yilei Zhang, and Michael R. Lyu, “Investigating QoS of Real-
 	World Web Services”, IEEE Transactions on Services Computing , vol.7, no.1, 
	pp.32-39, 2014.
  
	- Zibin Zheng, Yilei Zhang, and Michael R. Lyu, “Distributed QoS Evaluation 
	for Real-World Web Services,” in Proc. of the 8th International Conference 
	on Web Services (ICWS'10), Miami, Florida, USA, July 5-10, 2010, pp.83-90.

 * IF YOU USE THIS DATASET IN PUBLISHED RESEARCH, PLEASE CITE THE ABOVE PAPERS.
   THANKS!

	

