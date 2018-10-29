# HashgraphExternalOracle

Experimental implementation for a native external oracle with the help of Swirlds SDK
you can run with the SDK 18.05.23

- Each node calls an external data source
- The consensus on the result and order of the external data is supposed to be reached in calculatingStarts
- The algorithm votes votes for the results and the one with the most votes wins

Further information on the algorithm is to be found at:
https://danielszego.blogspot.com/2018/09/creating-native-decentralized-oracle.html



  


