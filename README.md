# candice-online-restaurant

Hello and welcome to my project!

This is actually an upgrade to one of the first algorithms that I ever did - the original was written in paper and in a pseudo-programming language, so my objective with this project is to implement everything that my original algorith was supposed to do in a real programming language (Python) and to go even further beyond, with a few more features etc.

The program presents three main arrays: meal, price and kcal, all of them with 12 values. The meals are separated in three categories: dish, dessert and drink, and each meal has its respective price and amount of calories. 

The code has some "continue-exit" function calls wich I'll not dive too deep into, but there are two functions in particular that I need to talk about in order to explain the core of this program: meal_exit and choose_meal. Basically, after the customer has seen the menu, meal_exit is called and he is asked to choose between a dish, a dessert and a drink, and after that choose_meal is called and he is asked to choose his meal. 

choose_meal returns the number the customer typed and then this number is writen into order.txt, a file that will save all customer inputs. When the customer wants to finish his order and go to checkout, the program then opens order.txt and links each value to its corresponding index in the meal, price and kcal arrays.

Finally, the program asks if the customer wants to make another order, and if he answers yes then all values inside order.txt are deleted and the program returns to the meal_exit function call section - if the answers is no, the program calls the farewell function and ends.

This is a very simplified explanation of the operating of this project, so if you feel that there's anything that I should have explained more clearly or more in detail, please feel free to let me know!
