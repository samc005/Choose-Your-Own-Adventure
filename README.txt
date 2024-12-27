Choose Your Own Adventure: Harry Potter Edition

You were accepted into the Hogwarts School of Witchcraft and Wizardry, and you have to navigate your first year.

Level One: Diagon Alley to buy your school supplies
Level Two: Hogwarts Express, Choose House, Duel
Level Three: Battling Voldemort

Topics: 
- STL: I used vectors to store my different options for each level that the user can choose from.
- Templates: I used template for the vector options, because it could be any type and I wanted it to be flexible depending on what options I wanted to put in the vector.
- Namespace: I used a namespace to avoid conflicts in naming, because of the multiple levels in each file that could clash when I run the code, and organize the code.
- Classes (constructor, destructor, assignment operator): This initialized my game and also deleted the levels once played, and copied if needed, which I set up in game.h.
- exceptions: I threw an exception most times the user was required to input a number to choose in level.cpp.
- inheritance: The level1, level2, level3 classes are all derived from the base class level, which initialized most of the functions and variables that the child classes used.
- virtual functions/abstract classes: included pure virtual functions that could be then used for each individual level, and I could use the same functions, but modify it for each level in level.cpp 
- sorting algorithms: I used the sort function to sort each vector alphabetically whenever it was outputted to show the user the options.

Sources:
https://www.geeksforgeeks.org/how-to-add-timed-delay-in-cpp/#
https://www.geeksforgeeks.org/exception-handling-c/
https://www.geeksforgeeks.org/pure-virtual-functions-and-abstract-classes/
https://www.open-std.org/jtc1/sc22/wg21/docs/papers/2024/p3068r4.html







