# CSharp and SQL Fundamentals
01. What is the purpose of a `namespace`?

  > | In C#, namespaces basically act like our imports and exports from js, but better as they function more like folders that you can pull in and out from, and code can be accessed in more places. |

02. What is the difference between a `class` and an `interface`?

  > | ANSWER HERE |

03. What is the method that returns an instance of a class, yet it has no return type?

  > | ANSWER HERE |

05. In the Car example what is the access modifier of the `Start()` method?

  ```c#
  abstract class Car
  {
    public string Start()
    {

      return "Vroooom";

    }
  }
  ```

  > | The access modifier on car is public, meaning it can basically be accessed anywhere in the namespace. |

06. In the Car example what is `string` an indication of?

  > | String is the type of property that is expected to be returned. |

07. In the Car example what is `abstract` preventing?

  > | ANSWER HERE |

08. In a SQL table, what is the difference between information in a row and information in a column?

  > | Information in a row would contain a single property, like id, over several columns, like 1, 2, 3, and so on. A column contains several Properties about just one object.  |

09. Demonstrate the necessary SQL for creating a table called `characters` with the values `name, age, description` as strings, and an `int` id.

  > | CREATE TABLE character(
      id INT NOT NULL AUTO_INCREMENT PRIMARY KEY,
      name CHAR(255) NOT NULL,
      age CHAR(255) NOT NULL,
      description VARCHAR(5500) NOT NULL
  ) default charset utf8
  |

10. In SQL how can you query more than a single table? Provide an example.

  > | ANSWER HERE |
