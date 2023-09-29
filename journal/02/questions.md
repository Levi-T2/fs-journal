# Intro to JavaScript
01. Which keywords are used to declare a variable in JavaScript?

    > | You can use let, var, and const, but they differ slightly from each other. |

02. What is the definition of a function?

    > | Functions are made in Js and they are subprograms of code that are used to execute certain tasks within
    Js. They are important to use in Js and need to be invoked to be used. |

03. What are the `SOLID` principles?

    > | The solid principles is an acronym that outlines five design principles that shouldn't be broken. 
    S - Single Responsibility - a class should only have one job.
    O - Open Closed - a class should be able to be modified without having to change the class itself.
    L - Liskov - Every subclass should be substitutable.
    I - Interface Segregation - Clients shouldn't be forced to use things that they don't need to use.
    D - Dependency - Entities need to depend solely on abstractions.
    |

04. Given this array: How could you remove the `pineapple`?

    ```js
    let fruit = ['apple', 'banana', 'pineapple', 'orange', 'strawberry']
    ```

    > |  I would use the function delete and then index to fruit at 2. This would get rid of pineapple but leave
    an empty slot.|

05. Given these two objects: How could you add each to the others friends arrays?

    ```js
    let you = {
        name: "You",
        hair: true,
        friends: []
    }
    let them = {
        name: "Them",
        hair: false,
        friends: []
    }
    ```

    > | I would write it out as you.friends = them, and them.friends = you. This would add each of the arrays into the others
    friends variable within them. |

06. Give an example of a JavaScript `Conditional`:

    > | if statements, else statements, and else if. These are all conditionals that allow code to run. |

07. What is the main difference between `parameters` and `arguments`?

    > | Parameters are variables that you add that are placeholders, and don't have a value assigned to them. An argument is what you give to the function for it pass and invoke. |

08. Instead of writing everything to the console, what is a better way to debug your code?

    > | Utilize chrome dev tools that allow you to view what line your error is being thrown from. You can also use error messages in js to throw things back. They're also debugging tools that you can put in and use in your html. |

09. What is the difference between a `primitive` value and a `reference` value?

    > | In js, a primitive value are values such as numbers, string, and booleans. These are primitive as they only have a singular value assigned to them. Reference values are things like  objects and arrays, which hold several different values that can be referenced to.  |

10. Demonstrate a loop that prints the numbers between -100 and 100?

    > | I would write it out as ( for (let i = -100; i <= 100; i++)) |
