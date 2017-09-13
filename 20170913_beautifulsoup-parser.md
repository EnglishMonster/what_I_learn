When I was writing the code to count up the words in my English practice repository, I faced the problem.  
This code use beautifulsoup, with this library we can scrape the website easily.  
I finished my code with complete implementation.  
But when I had to install pip libraries again for AWS lambda, because that service has no instances.  
So I had to install and make them into zip file.  
The problem was happen with the default python parser.  
when I run the code, default python parser did well, but when AWS lambda run the code, the parser didn't work well.  
After all I got on with the new parser and change the code.
