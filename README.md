## Fake and Real News tracking network
There are plenty of news produced by both fake sources(ex. Twitter) and real once. It's possible to train a network to be able to differentiate the real ones based on the collected texts. 
<br>

Each dataset includes those columns:
- title - an article title (str)
- text - an article text (str)
- subject - the main topic of an article (str)
- date - the publish date of an article (str, '%m %d, %y')

The detection made using LSTM implementing five main steps:
* Analyzing data
* Cleaning data
* Preprocessing data
* Applying vectorization 
* Training the network with produced embeddings 
