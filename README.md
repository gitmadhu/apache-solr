# apache-solr
## Getting started with Solr
* start solr
> bin/solr.cmd start
* stop solr
> bin/solr.cmd stop -all
* run solr with example core 'techproducts' (techproducts: is an example comes with solr )
> bin\solr.cmd start -e techproducts
	* check browse the product at [http://localhost:8983/solr/techproducts/browse](http://localhost:8983/solr/techproducts/browse)
* create core
> bin/start.cmd create -c nameOfTheCore
* add fields to your 'managed-schema' file
* create 'data-import.xml' which defines how data/meta data of pdf will be extracted.
* add dataimport configuaration to you 'solrconfig.xml'
reference
[Sorl index pdf for text search] http://www.codewrecks.com/blog/index.php/2013/05/25/import-folder-of-documents-with-apache-solr-4-0-and-tika/
[data import wiki](https://cwiki.apache.org/confluence/display/solr/Uploading+Structured+Data+Store+Data+with+the+Data+Import+Handler)