# pysparkprod
End to End Pyspark job packaging and deployment 

Step to run the pyspark job

1. make clean 
2. make build
3. cd dist/ 
4. spark-submit --py-files jobs.zip,libs.zip main.py --job wordcount
