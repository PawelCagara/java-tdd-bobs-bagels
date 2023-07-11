| Classes | Members             | Methods                             | Fields | Scenario          | Output                           |
|---------|---------------------|-------------------------------------|--------|-------------------|----------------------------------|
| Basket  | int Capacity        | addToBasket(String bagle)           |        | if Basket if full | error                            |
|         | List<String> bagles |                                     |        | if not            | space left in basket is capacity |
|         |                     | removeFromBasket                    |        | if item not exist | error                            |
|         |                     |                                     |        | if item exist     |                                  |
|         |                     | changeCapacityOfBasket(int newSize) |        | if newSize<=0     | error                            |
|         |                     |                                     |        | if i>0            | int                              |
|         |                     | getAllBagles                        |        |                   | List<String>                     |
|         |                     |                                     |        |                   |                                  |
|         |                     |                                     |        |                   |                                  |
|         |                     |                                     |        |                   |                                  |
|         |                     |                                     |        |                   |                                  |

List<String> bagle
public Basket(int capacity)