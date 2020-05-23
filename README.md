# CECS-174-Lab-7
Print out details about a US Interstate Highway given that highway's number

get_interstate_number(): asks user to input an integer highway number, and returns it after validating it is a positive number

is_primary(number): takes a US Interstate number as a parameter, and returns true if and only if that highway represents a 
primary interstate. A primary interstate has a number with only one or two digits. If the number represents an auxiliary 
interstate, has three digits, then the function returns false

compass_orientation(number): this function can only be called on a primary interstate number, and returns the compass 
orientation of that interstate. A primary interstate with an odd number is oriented "north-south", and an even-numbered 
interstate is oriented "east-west".

is_arterial(number): this function can only be called on a primary interstate number, and returns true only if the number 
represents a long-distance arterial highway. An arterial highway has a number that is a multiple of 5. Otherwise false is 
returned

auxiliary_type(number): this function can only be called on an auxiliary interstate number, and returns the type of the 
auxiliary highway. Auxiliary highways can either be radial or spur; these are differentiated by an even first digit for radial 
highways, and an odd first digit for spur highways

parent_highway(number): this function can only be called on an auxiliary interstate number, and returns the parent of the 
highway. Auxiliary highways always connect to a parimary highway in at least one location; the primary highway they connect to 
is the last two digits of the auxiliary number

Research portion:

1. What former U.S. President is credited as the biggest proponent of the foundation of the US Interstate Highway System?

2. According to a 2008 estimate by the Federal Highway Authority, what interstate is the most-heavily traveled in terms of 
vehicles per day?

3. The band Death Cab for Cutie wrote a song called 405 about Interstate 405. In what city/state was the band formed, and why is it unlikely that the song is about the Interstate 405 that runs through Southern California?
