# airline-source-data

Airline On-time Flight data used as sample data to support various demos, hands on labs, and workshops.

## How to setup the Data Instructions

To use this data you will need to download the data first.  These instructions are to be executed on a MacBook

1. Download this Repository
   * Select `<> Code` > `Download ZIP`
   * This will take approximately 20 minutes
   * It will download a file named `airline-source-data-main.zip`

2. Unzip Repo zip - airline-source-data-main.zip
   * Locate the downloaded .zip file using Finder
   * Double click on the .zip file

3. Open a `Terminal` window and run the following commands

* Navigate to the “flights” directory
```
cd Downloads/airline-source-data-main/airlines-csv/flights
```

* Decompress the flights.csv file
```
cat flights.tar.gz.* | tar xzvf -
```

* Move flights.csv to main `flights` directory
```
mv flights/flights.csv .
```

* Remove empty flights sub-directory
```
rm -rf flights/
```

* Remove the `tar` files 
```
rm flights.tar.gz.*
```

