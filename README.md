# BTC-ETH-Prices
A website that shows the prices of BTC and ETH on Coinbase.com and Blockchain.com.

Clink this <a href="https://brianonieal.github.io/BTC-ETH-Prices/">link</a> for a live demo!

Questionnaire:
1.	Are there any sub-optimal choices( or short cuts taken due to limited time ) in your implementation?
	  The 4 statements below the prices need to go. I would have liked to have a green highlight over the recommended buy/sell
	   price on Coinbase or Blockchain. I also would have used absctractions to make it scalable.
     
2.	Is any part of it over-designed? ( It is fine to over-design to showcase your skills as long as you are clear about it)
	  I don't feel that it's overdesigned. I kept it fairly simple and easy to read. 
    
3.	If you have to scale your solution to 100 users/second traffic what changes would you make, if any?
	  I would put this API on a server, run it on Apache and use Oracle or MySQL for the database. Use a 
    caching server to reduce the response time and load on the server. Use a CDN server to improve page
	  load times.
    
4.	What are some other enhancements you would have made, if you had more time to do this implementation
  	I would like to have made the UX smoother and easier to read with the green highlight in lieu of the 4
	  statements. I would like the prices to load in real time as opposed to using refresh.
