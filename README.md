# Elasticsearch-5x-Cookbook-Third-Edition
Code repository for Elasticsearch 5.x Cookbook, published by Packt

This is the code repository for [Elasticsearch 5.x Cookbook](https://www.packtpub.com/big-data-and-business-intelligence/elasticsearch-50-cookbook-third-edition?utm_source=github&utm_medium=repository&utm_campaign=9781786465580), published by Packt. It contains all the supporting project files necessary to work through the book from start to finish.

## Instructions and Navigation
All of the code is organized into folders.Each folder starts with a number followed by the application name.
The commands and instructions will look like the following:

import java.io.BufferedReader;
import java.io.InputStream;
import java.io.InputStreamReader;
import java.net.URL;

…
try {
// get URL content         
  URLConnection conn = url.openConnection();// open the stream and put it into BufferedReader             
  BufferedReader br = new BufferedReader(new InputStreamReader(conn.getInputStream()));              

String inputLine;             
while ((inputLine = br.readLine()) != null){
System.out.println(inputLine);             
}             
br.close();              
System.out.println("Done");          
} catch (MalformedURLException e) {
e.printStackTrace();         
} catch (IOException e) {             
e.printStackTrace();         
}




## Note:
Chapter 01, 02, 10, 11 do not have code files.


## Related products:
* [ElasticSearch Cookbook](https://www.packtpub.com/big-data-and-business-intelligence/elasticsearch-cookbook?utm_source=github&utm_medium=repository&utm_campaign=9781782166627)
* [Mastering ElasticSearch 5.0 - Third Edition](https://www.packtpub.com/big-data-and-business-intelligence/mastering-elasticsearch-50-third-edition?utm_source=github&utm_medium=repository&utm_campaign=9781786460189)
* [ElasticSearch Cookbook - Second Edition](https://www.packtpub.com/networking-and-servers/elasticsearch-cookbook-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781783554836)

###Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform) if you have any feedback or suggestions.
