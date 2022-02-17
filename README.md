# stationxml-tools
Tools for working with StationXML, including a validator and a convertor to SEED format

## Inspiration

This repository was inspired by [this blog post](https://coderwall.com/p/ssuaxa/how-to-make-a-jar-file-linux-executable)

## Java jar file source

The jar files can be found at [iris-edu/stationxml-validator](https://github.com/iris-edu/stationxml-validator) or [iris-edu/stationxml-seed-converter](https://github.com/iris-edu/stationxml-seed-converter)

## Making stationxml-validator

To make the stationxml-validator executable, run the following line with the correct jar file version in the second command

    cat wrapper.sh > stationxml-validator
    cat station-validator-<version>.jar >> stationxml-validator

Give stationxml-validator executable permissions and copy to the desired destination like "/usr/local/bin".

## Making stationxml-seed-converter

To make the stationxml-seed-converter executable, run the following line with the correct jar file version in the second command

    cat wrapper.sh > stationxml-seed-converter
    cat station-seed-converter-<version>.jar >> stationxml-seed-converter

Give stationxml-seed-converter executable permissions and copy to the desired destination like "/usr/local/bin".
