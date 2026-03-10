# Custom-Metadata-Blocks

All the tsv-files for the custom metadata blocks will be stored here. 

## Construction of properties files

Each tsv-file need to have a corresponding properties file with all the strings in there 
that can then also be translated to Dutch for instance. 

The explanation is here: `https://guides.dataverse.org/en/latest/admin/metadatacustomization.html`. 

Better copy from other sources; like the DANS Datastations code. 
For the DANSMetadata we have used the `dansRights` from `dans-cores-systems` in `provisioning/files/custom-metadata-block-properties`. 

Especially the `controlledvocabularies` can be a hassle, and some form of automation would be helpful. 

__Note__ that the properties files are input for the translation repository (`TranslationDataverseUI`)!
