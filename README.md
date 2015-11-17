# Signal-1M-Convert-to-TREC
A script to convert the Signal Media One-Million News Articles Dataset to TREC format.


## Running the script
After obtaining the dataset through this form http://goo.gl/forms/5i4KldoWIX, you can xtracting the JSONL file from the the downloaded Gzip file
Then you run the script like this

```
python convert-to-trec.py -i <path to signalmedia-1m.jsonl> -o <path to your outputfile>
```
