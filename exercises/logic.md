# Logic

*Taken from [CodingBat](http://codingbat.com/python/Logic-1)*

**Cigar Party** [source](http://codingbat.com/prob/p195669)   

When squirrels get together for a party, they like to have cigars. A squirrel party is successful when the number of cigars is between 40 and 60, inclusive. Unless it is the weekend, in which case there is no upper bound on the number of cigars. Return True if the party with the given values is successful, or False otherwise. 

> *Example:*   
cigar_party(30, False) → False  
cigar_party(50, False) → True  
cigar_party(70, True) → True  

**Alarm Clock** [source](http://codingbat.com/prob/p119867)

Given a day of the week encoded as 0=Sun, 1=Mon, 2=Tue, ...6=Sat, and a boolean indicating if we are on vacation, return a string of the form "7:00" indicating when the alarm clock should ring. Weekdays, the alarm should be "7:00" and on the weekend it should be "10:00". Unless we are on vacation -- then on weekdays it should be "10:00" and weekends it should be "off". 

> *Example:* 
alarm_clock(1, False) → '7:00'  
alarm_clock(5, False) → '7:00'  
alarm_clock(0, False) → '10:00'

**Near Ten** [source](http://codingbat.com/prob/p165321)

Given a non-negative number "num", return True if num is within 2 of a multiple of 10. Note: (a % b) is the remainder of dividing a by b, so (7 % 5) is 2. See also: Introduction to Mod   

> *Example:*  
near_ten(12) → True  
near_ten(17) → False  
near_ten(19) → True

You can click through to the [CodingBat website](http://codingbat.com/python/Logic-1) for a whole bunch of exercises. These exercises are in Python, but you can do them in any language you want. 
