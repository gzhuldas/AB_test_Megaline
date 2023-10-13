## Statistical Analysis for Megaline telecom company.

### Project description:
Megaline offers its clients two prepaid plans, Surf and Ultimate. The commercial department wanted to know which of the plans brought in more revenue in order to adjust the advertising budget. The provided data contains 500 Megaline clients: who the clients are, where they're from, which plan they use, and the number of calls they made and text messages they sent in 2020.

### Tasks description:
1. Assisted Yandex analytics team with telecom operator Megaline.
2. Carried out preliminary analysis of the plans based on a relatively small client selection.
3. Analyzed clients' behavior and determined which prepaid plan brings in more revenue.


### Description of the plans:
Note: Megaline rounds seconds up to minutes, and megabytes to gigabytes. For calls, each individual call is rounded up: even if the call lasted just one second, it will be counted as one minute. For web traffic, individual web sessions are not rounded up. Instead, the total for the month is rounded up. If someone uses 1025 megabytes this month, they will be charged for 2 gigabytes.
#### Surf
Monthly charge: $20<br>
500 monthly minutes, 50 texts, and 15 GB of data<br>
After exceeding the package limits:<br>
1 minute: 3 cents<br>
1 text message: 3 cents<br>
1 GB of data: $10<br>
#### Ultimate
Monthly charge: $70<br>
3000 monthly minutes, 1000 text messages, and 30 GB of data<br>
After exceeding the package limits:<br>
1 minute: 1 cent<br>
1 text message: 1 cent<br>
1 GB of data: $7<br>


### Results:
The analysis has shown that the users of Surf plan make more calls, text messages and use more mobile internet than Ultimate plan users on average. The reason is simple, there are twice more Surf plan users. The figures that show the monthly distibution of phone calls' duration, internet use etc, have the same pattern for both mobile plans. The distributions clearly show that the tariffs have been gaining more and more popularity, reaching the peak activity in December. Two hypotheses were tested, the first one with:<br>
H0 - The average profit from users of Ultimate and Surf calling plans does not differ.<br>
H1 - The average profit from users of Ultimate and Surf calling plans differs.<br>
The test showed that the alternative hypothesis can be accepted. The average profit for the plans is different and Surf plan probably generates more revenue. 
The second test:<br>
H0 - The average profit from users in NY-NJ area is not different from that of the users from other regions.<br>
H1 - The average profit from users in NY-NJ area is different from that of the users from other regions.<br>
The second test also showed that the alternative hypothesis can be accepted. The NY_NJ area probably has more potential clients and as a result the profit generated in this area is larger.
   
