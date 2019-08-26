# RegulonDB Identifiers
Identifiers are used on RegulonDB to identify an object.


# Entry identifier
 
This section provides information about the identifiers in RegulonDB. The main objects in RegulonDB such as Gene, Operon, Regulon, Growth Conditions and more have assigned a unique and persistent identifier that allows their long-lasting reference. Each entry in RegulonDB is assigned a unique identifier.

- - -

## RegulonDB entry identifier structure

The RegulonDB entry identifier consists of 15 alphanumeric characters.  

- The first 3 characters are the reference to the database like RegulonDB.  
For instance, **RDB** 

- The next 5 characteres correspond to the organism, that is taken from the UniProt classification: <https://www.uniprot.org/docs/speclist.txt>  
For example: **ECOLI**  

- The following 2 characteres correspond to the reference object. There is a list of the abbreviations RegulonDB objects name:  

  **OP** = Operon   
  **GN** = Gene  
  **GU** = Gensor Unit  
  **GC** = Growth Condition  
  **RG** = Regulon  
  **SG** = Sigmulon  
  **SR** = sRNA 
  
  __Internal objetcs__
  
  **PM** = Promoter
  **RI** = Regulatory Interaction
  **TU** = Transcription Unit
  **CF** = Conformation
  **BS** = Binding Site
  **TM** = Terminator
  **?** = Datasets
   

- The last 5 characters represent the consecutive numeric identifier of the resource.  
For example: **00001**

Examples:

| Identifier |Description |
| ---------- | ---------- |
| RDBECOLIGR00001   | This is a RegulonDB identifier of the 00001 gene   |
| RDBECOLIOP00001   | Campo B1   |



