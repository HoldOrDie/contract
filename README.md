# Hold or Die

Hold or Die is the first token with a variable sell rate that depends on the hold time of each individual wallet.

  Buy: 11% slippage (10 % tax)      
  Hold 1 day -> (34 % tax)  
  Hold 2 day -> (32 % tax)    
  Hold 3 day -> (30 % tax)  
  Hold 4 day -> (26 % tax)   
  Hold 5 day -> (22 % tax)   
  Hold 6 day -> (18 % tax)   
  Hold 7 day or more -> (10 % tax)   

It has been implemented with a history in a hashMap, without using lists or loops. In this way, all blocking problems due to excessive use of gas are avoided when the number of holders is very large.
