************************
DisGeNET platform
************************

DisGeNET is a discovery platform integrating information on gene-disease associations from several public data sources and the literature. The DisGeNET data is made available under the Open Database License. For more information, see the Legal Notices page (http://www.disgenet.org/ds/DisGeNET/html/legal.html).
The files in the current directory contain the data corresponding to the latest release (version 3.0, May 2015). The information is separated by tab.

curated_gene_disease_associations.txt 		=> Gene Disease associations from UniProt, ClinVar and Comparative Toxicogenomics Database (human data)
literature_gene_disease_associations.txt	=> Gene Disease associations from literature-derived sources: GAD, BeFree and LHGDN data
befree_gene_disease_associations.txt 		=> Gene Disease associations obtained by text mining MEDLINE abstracts using the BeFree system. 
all_gene_disease_associations.txt 		=> All Gene Disease associations in DisGeNET


The columns in the files are:
geneId 		-> Entrez Gene Identifier
geneSymbol	-> Official Gene Symbol
geneName 	-> Full Gene Name
diseaseId 	-> UMLS concept unique identifier
diseaseName 	-> Name of the disease	
score		-> DisGENET score for the Gene Disease association
NumberOfPubmeds	-> total number of papers reporting the Gene Disease association
associationType	-> DisGeNET association type for the Gene Disease association
source		-> All Sources reporting the Gene Disease association


befree_gene_disease_associations.txt contains also
sentence 	-> the sentence supporting the Gene Disease association
pmidId		-> the ncbi pubmed identifier of the paper reporting the Gene Disease association

Disclaimer

Except where expressly provided otherwise, the site, and all content, materials, information, software, products and services provided on the site, are provided on an "as is" and "as available" basis. The IBIgroup expressly disclaims all warranties of any kind, whether express or implied, including, but not limited to, the implied warranties of merchantability, fitness for a particular purpose and non-infringement. The IBI group makes no warranty that:

    a. the site will meet your requirements 

    b. the site will be available on an uninterrupted, timely, secure, or error-free basis (though IBI will undertake best-efforts to ensure continual uptime and availability of its content) 

    c. the results that may be obtained from the use of the site or any services offered through the site will be accurate or reliable 

    d. the quality of any products, services, information, or other material obtained by you through the site will meet your expectations 

Any content, materials, information or software downloaded or otherwise obtained through the use of the site is done at your own discretion and risk. The IBI group shall have no responsibility for any damage to your computer system or loss of data that results from the download of any content, materials, information or software. The IBI group reserves the right to make changes or updates to the site at any time without notice. 

If you have any further questions, please email us at support@disgenet.org

