# college_c_challenge
- Just a code written by me and my friend, basically to do a challenge proposed by our teachers

- Description:

Problem:

A transport company wants to develop software that calculates the kilometers traveled
involved in their itineraries. For this, a matrix was created containing the distance between the cities
serviced by the carrier. As agreed:

   Cites |    São Paulo | Campinas | Santos | Bragança Paulista | Sorocaba |
                    0         1          2              3              4
São Paulo |   0     0         106        79             90             98
Campinas  |   1     106       0          187            79             98
Santos    |   2     79        187        0              153            171
Bragança  |   3     90        79         153            0              147
Sorocaba  |   4     98        98         171            147             0

The pair must build software capable of reading the itineraries (path to be
traveled) and calculate the total km to be traveled and the fuel cost of the itinerary. To calculate this
cost, the following information will be required: vehicle consumption in Km/l and fuel value.

- Example:

Santos – Campinas – São Paulo itinerary:
2 1 0 (USER INPUT)
Consumo: 12.3 (USER IMPUT)
Fuel value: 6.99 (USER IMPUT)

Distance: 293 Km (EXIT)
Fuel cost: R$ 166,51 (EXIT)
