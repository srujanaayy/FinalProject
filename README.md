
Use the google drive link to access the datset below. Recommend to open the project in GoogleColab using the MLProjectLinearCovidData.ipynb file. 

dataset google drive link: https://drive.google.com/file/d/1Tf5dExscpJx8A6zAVICkFi-Qb59xPlZE/view?usp=drive_link



CovidData.csv was 42MB and github has limitation of 25MB so the file was split using

https://github.com/aotimme/gocsv#split

/bin/bash <(curl -s https://raw.githubusercontent.com/aotimme/gocsv/master/scripts/install-latest-darwin-amd64.sh)

gocsv split --max-rows 530000 ./Downloads/CovidData.csv


