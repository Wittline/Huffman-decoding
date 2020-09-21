# A New Approach for Efficient Decoding of Huffman Codes

<p align="justify">   
The exponential growth of the volume of data, the high cost of storage and high latency create robust lines of research in the area of data compression, compression speed is a transparent process for the user since the data compression process are currently running and hosted in the cloud, but the decompression process impacts directly on the quality of service (QoS) offered to the end user and this makes the decompression process an area of study of equal importance. Therefore, the static huffman algorithm can be measured in two ways, one in terms of how the storage space is reduced and the other in terms of decoding speed. This research proposes an approach to decoding static Huffman codes based on the amount of information accumulated in the code lengths assigned to symbols of a dataset by the static huffman algorithm, the ascending ordering of the Huffman table based on the length code is not the best sequential decoding option for heterogeneous datasets, this study quantified the results related to the decompression speed and significant results were achieved, it also uses methodology that helped in the observation of the entire pipeline of compression and decompression.
</p>

## Problem Statement

<p align="justify">  
Companies in all sectors need to find new ways to control the rapid growth of the volume of their heterogeneous data generated every day, for this reason mentioning Velocity, Volume and Variety (Laney, 2001) are key concepts to strengthen this document.
</p>

![alt text](https://wittline.github.io/Huffman-decoding/images/3vs.png)

### Velocity
<p align="justify"> 
data must be stored, extracted, transmitted and converted into information quickly before it loses its value. Studies on compression and decompression algorithms could directly impact the speed of how this data is transmitted in real time and could also improve latency in distributed systems.
</p>

### Volume
<p align="justify"> 
Currently, the main providers of cloud services such as Amazon Web Services (AWS), Microsoft Azure, Google Cloud and IBM OpenWhisk (Expósito and Zeiner, 2018), are responsible for storing all types of files in their Data Centers, generating an immense amount of daily information (which in some cases reaches petabytes), which has a high cost associated with the storage and maintenance of data.
</p>

### Variety
<p align="justify"> 
The data is highly heterogeneous, this implies that it can be generated by spacecraft, radio telescopes, telescopes, medical images, social networks, sensors, banking transactions, flight data, smartphones, cameras, GPS and DNA sequences, among others. It can be structured and unstructured data, but in the end it is stored on a server as a string of bits, therefore, focusing on designing, observing and improving a scheme in the decoding of static huffman codes process that is optimal and supports any type of data is essential.
</p>


## Proposed methodology

![alt text](https://wittline.github.io/Huffman-decoding/images/meto.png)

## Code
You can see the code of the whole project here: <a href="https://github.com/Wittline/Huffman-decoding/tree/master/Code" target="_blank">Code</a>

## Results

## References
Based on the above, below we mention some studies performed based on the decompression of huffman codes:
1. [Balancing decoding speed and memory usage for Huffman codes using quaternary tree (Habib y Rahman, 2017)](https://applied-informatics-j.springeropen.com/articles/10.1186/s40535-016-0032-z)	 
2. [Data-Parallel Finite-State Machines (Mytkowicz, Musuvathi y Schulte, 2014)](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/asplos302-mytkowicz.pdf)	
3. [Massively Parallel Huffman Decoding on GPUs (Weißenberger y Schmidt, 2018)](https://dl.acm.org/citation.cfm?id=3225076)