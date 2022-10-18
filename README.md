# Assignment
1. Transistor

The discovery of the first transistor in 1948 by a team of physicists at the Bell Telephone Laboratories sparked an interest in solid-state research that spread quickly. The transistor, which began as a simple laboratory oddity, was rapidly developed into a semiconductor device of major importance. The transistor demonstrated for the first time in history that amplification in solids was possible. Before the transistor, amplification was achieved only with electron tubes. Transistors now perform numerous electronic tasks with new and improved transistor designs being continually put on the market. In many cases, transistors are more desirable than tubes because they are small, rugged, require no filament power, and operate at low voltages with comparatively high efficiency.
Semiconductor devices that have three or more elements are called TRANSISTORS. The term transistor was derived from the words TRANSfer and resISTOR. This term was adopted because it best describes the operation of the transistor – the transfer of an input signal current from a low-resistance circuit to a high resistance circuit. Transistors were first used as amplifiers, but their use in digital circuits to create logic gates has driven the computing age.

2. Moor’s law

is the observation that, over the history of computing hardware, the number of transistors on integrated circuits doubles approximately every two years. The law is named after Intel co-founder Gorden E. Moore who described the trend in his 1965 paper. His prediction has proven to be accurate, in part because the law is now used in the semiconductor industry to guide long term planning and to set targets for research and development. The period often quoted as “18month’ is due to intel executive David House, who predicted that period for doubling in chips performance (being the effect of more transistors and their being faster). 

3. Lambda calculus

Lambda-Calculus (LC) is the model (or language) of computation (i.e. programming).  It is a system that expresses functions as strings of symbols. Lambda-Calculus is about anonymous functions, called lambda expressions (λ-exprs).

4. How computers work?

A computer, a digital information-processing machine, works by changing information into binary numbers (ones and zeros) and then using simple mathematics to make decisions about how to rearrange those numbers into words or actions. A digital system stores and operates on information in a very specific way by storing information in a bit (or multiple collections of bits). A bit is a variable that can have only one of two values: it can either be a 1, or be a 0. There are two main things to understanding the basics of how a computer works: • A computer treats any type of information (not only numbers but also letters, words, dates) as if it consisted simply of binary ones and zeros. For example, a computer can translate the letter “A” typed into its keyboard into a string of ones and zeros, such as 1000001. One reason for this is that once it is in a binary form, the information can be stored and moved about more easily. On a hard disc, the “ones” could be stored as magnetized spots on the disc, while the zeroes can be stored as un-magnetized spots. Once information has been converted to ones and zeros, the computer can get to work.
 • The second point to consider is that the computer’s functions are based on the movement and transformation of electrical pulses (representing ones and zeroes) in electrical circuits. Inside the computer are electrical circuits that decode the zeros and ones, by adding and subtracting them. These circuits are called the logic of the computer, because the calculations they make are similar to simple logic decisions. For example, if you press the A key on the computer keyboard, circuits inside the computer receive pulses of electricity representing the A in binary form - 1000001. Those pulses are sent to logic circuits that make yes or no decisions based on the input they receive. A very simple example would be a circuit that determines whether the input send to it is a one or a zero. The output of the circuit is a new piece of information - a binary one or zero that is the result of the simple yes or no decision

5. What is DNS?

The DNS is a distributed database across a hierarchy of networks of 
servers and provide ways for devices and software (like browsers and 
email) to query the DNS to get an IP address.

● Domain names must be unique.

● Domain names are used for naming websites and email addresses
Let’s look at a typical domain name.
www.example.com

● “com” is the First Level Domain or Top Level Domain (TLD) 
● “example” is the Second Level Domain
● “www” is the Third Level Domain

How the Domain System work? 

What happens when I type www.example.com in my browser?
The domain name lookup processȀ
1. You type “www.example.com” into your browser’s address bar.
2. The DNS server queries the “root servers” for the information. N.B. The 
root zone only knows information about the zones they are responsible for 
which is the Top Level Domains (TLDs). There are 13 root servers which 
have copies distributed around the world.
3. The root server will refer the DNS server to the “.com” TLD nameservers . 
The TLD Name servers knows information of all second level domains 
under their zone. 
4. The Top Level Domain Name servers will refer us to the DNS servers 
responsible for “example.com”
5. The DNS servers authoritative for example.com will give us the IP address 
for www.example.com” and the web resource is displayed..
com. - .is the root server oot server 


Every time a DNS query is made, the root servers are the first servers to be 
contacted. However, there is no need to contact the root servers every time 
a query is made since results can be obtained from the DNS cache which 
stores information for recent previous queries. If the DNS server do not find 
the results in the cached copies it asks a series of servers through a process 
called recursion until it reaches the authoritative name servers for that 
domain.
