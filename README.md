# brat-to-inception
The script brat_to_inceptions.ipynb converts brat annotation files to inception. 
The file typesystem.xml is mandatory and contains the description of the ADR annotation and relations

Procedure:
1 - make new inception project 
2 - import both layers (ADR_Entity, ADR_Relation) in the new inception project 
3 - import both constrains (ADR_Constrains, ADR_Relation_Constrains) in the new inception project 
4 - change the entry_folder in the script to where .txt and .ann 5 - import the new generated .xmi documents using “UIMA CAS XMI (XML 1.0)”
