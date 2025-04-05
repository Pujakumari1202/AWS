## Steps to run the code

## CREATEthe virtual environment

```bash
conda create -n venvAws python==3.13
```

## This lambda required the recent version of boto3 for that we will create a zip file of all the recent version
````bash
pip install boto3 -t python/
````

## Zip the folder
````bash
zip -r lambda.zip python/
````

