# Rob Myers Week 8 Homework
## Networking Fundamentals Homework: Rocking your Network!

Phase 1: "I'd like to Teach the World to Ping"

INSTRUCTIONS: 

        * You have been provided a list of network assets belonging to RockStar Corp. Use fping to ping the network assets for only the Hollywood office.

        * Determine the IPs for the Hollywood office and run fping against the IP ranges in order to determine which IP is accepting connections.

        * RockStar Corp doesn't want any of their servers, even if they are up, indicating that they are accepting connections.

        * Create a summary file in a word document that lists out the fping command used, as well as a summary of the results.

        * Your summary should determine which IPs are accepting connections and which are not.

        * Also indicate at which OSI layer your findings are found.

SOLUTIONS: 

    * Created fping.txt in nano containing all the IP Addresses

![picture](IMAGE/fping_TXT.PNG)

    * From command line ran: fping < fping.txt to show what IP Address is "Alive" and what IP address is "unreachale"

![picture](IMAGE/fping_running.PNG)

    * Last, the OSI layer  corresponding with the IP Address is the Network Layer