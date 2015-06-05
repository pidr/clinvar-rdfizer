# clinvar-rdfizer
A script using bio2rdf-api to rdfize Clinvar data

## Use

Assuming a dump of clinvar (ClinVar.xml) is inside the current folder (hence no need to download it), run this command, inside bio2rdf directory : 
php ./runparser.php parser=clinvar files=all indir=./ outdir=./ download=false

