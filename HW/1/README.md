#Exam Questions <img src="../../Resources/exam.png" width=50px alt="Tick Sheet">

##Instructions
Edit this document and answer the questions in the sections surrounded by ```.

There are 30 marks available and are awarded grades as follows:

|Score|Grade|
|-----|-----|
|<6|U|
|6+|G|
|9+|F|
|12+|E|
|15+|D|
|18+|C|
|21+|B|
|24+|A|
|27+|A*|


##Data Representation

1 - Why do we represent data using binary when using computers (1 mark)
computers understand it 
2 - How would we represent the number 147 in binary? (1 mark)
10010011
3 - Can you convert the hexadecimal number b5 to denary, there is a mark for you working. (2 marks)
1011 0101
4 - Here is a function written is pseudocode.

FUNCTION validUser (users , user)
   FOR x <-1 to LEN(users)
       IF users[x] = user
           RETURN True
       ENDIF
   ENDFOR
   RETURN False
ENDFUNCTION

(a) What type of data is users? (1 mark)
text
(b) What type of data is returned by this function? (1 mark)
boolean


6 - This program is supposed to find the mean of a list of numbers and print it out for the user:

line1:      tot <- 0
line2:      nums <- [1,6,4,2,5,3]
line3:      FOR x <- to LEN(nums)
line4:          tot <- nums[x]
line5:      ENDFOR
line6:      mean <- tot
line7:      OUTPT mean
(a) On which line is there a syntax error? (1 mark)
7
(b) What is meant by a syntax error? (1 mark)
outpt
(c) Identify a logical error in the program and suggest how this might be fixed. (2 marks)

(d) Describe and give an example of the 3rd kind of programming error. (2 marks)
runtime is when the program runs but stops at some point in the code

7 - Write an algorithm that if given a list of numbers could find the largest. Try to use pseudocode.

If (x >= y)  
  largest = x
  Smallest = y
Else 
   largest = y
   Smallest =x

If (z >= largest)
   Largest = z
If (z <= smallest)
   Smallest = z

8 - Research the following methods (topologies) for connecting devices to a network. In each case give a description and at least 1 advantage and 1 disadvantage.

Bus Topology (6 marks)

Describe:computers and servers are all connected to one cable

Advantages: 
1) It is easy to add to the bus network.
2) Cable length required is less than other network types
3) Bus topology costs less.
4) Good for LAN

Disadvantages:
1)limit on central cable length 
2)Maintenance costs can eventually get higher
3)Not suitable for networks with heavy traffic
4)Security is low because all computers get the signal from the source
Ring Topology (6 marks)

Describe:all the computers connect to each other in a loop 

Advantages:
1)when the load on the server increases the performance is better 
2)more componants that are added to the network did not effect the performance
3)each computer gets equal

Disadvantages:
1)if one work station goes down the entire network gets effected
2)network is heavily dependent on the wire connecting the computer
3)MAU?s and network cards are expensive as compared to Ethernet cards and hubs. 

Star Topology (6 marks)

Describe:all devices are conected to a central hub

Advantages:
1)safer than bus because all computers have indipendent signals
2)new devices can be added with hardly any effect on the other devices
3)centralised management

Disadvantages:
1)too dependent on hub
2)the hub increases the overall cost of the network
3)performance is dependent on hub
