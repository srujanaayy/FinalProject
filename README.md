CovidData.csv was 42MB and github has limitation of 25MB so the file was split using

https://github.com/aotimme/gocsv#split

/bin/bash <(curl -s https://raw.githubusercontent.com/aotimme/gocsv/master/scripts/install-latest-darwin-amd64.sh)

gocsv split --max-rows 530000 ./Downloads/CovidData.csv
