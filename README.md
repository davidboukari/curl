## Save to the file -O
* curl -O <url> to download directly on the file setted by the url

## Get headers only
* curl -I : get headers

## Data to send -d
* curl --data 'file=value&file1=value1. or 'curl -d 'file=value&file1=value1' 

## Post -X
* curl -X POST or curl --request POST 

## Get -x
* curl -x GET  or curl --request GET

## Follow redirect -L
* curl -L  -O https://github.com/elastic/elk-index-size-tests/raw/master/logs.gz
