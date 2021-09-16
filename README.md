# pysparkprod
End to End Pyspark job packaging and deployment 

Step to run the pyspark job

1. make clean 
2. make default
3. make build
4. cd dist/ 
5. spark-submit --py-files jobs.zip,libs.zip main.py --job wordcount
