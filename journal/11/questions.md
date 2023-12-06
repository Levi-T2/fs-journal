# A bit more CSharp and SQL
1. What does ***inheritance*** accomplish for us in C#?

  > | Inheritance is most commonly used in c# to be able to reuse similar classes, so that you write less code but still have full functionality. When a class in c# inherits from a base class, it effectively becomes that class, then you can build onto it from there. |

2. How does ***member inheritance*** work in C#? Does a `Class` inherit all members of the base `Class`?

  > | When we inherit on classes in C#, the class that we are inherited on to will have all properties of that base class, and then you can add more properties onto just that class. |

3. How does ***accessibility*** affect inheritance?

  > | If a base class has methods that are declared private, derived classes will not have the ability to utilize them. |

4. What is the difference between a `PRIMARY KEY` and a `FOREIGN KEY`

  > | A primary key is what we put on our table is SQl to be able to have a unique property on each piece of data so we can interface with our data better. A foreign key is a key that we bring in from another table for use on our table. |

5. What is an ***alias***?

  > | ANSWER HERE |

6. Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

  ```SQL
  CREATE TABLE doctors (
    id INT NOT NULL AUTO_INCREMENT,
    -- CODE OMITTED
    PRIMARY KEY (id)
  )

  CREATE TABLE patients (
    id INT NOT NULL AUTO_INCREMENT,
    -- CODE OMITTED
    PRIMARY KEY (id)
  )

  CREATE TABLE patient_doctors (
    id INT NOT NULL AUTO_INCREMENT,
    doctorId INT NOT NULL,
    patientId INT NOT NULL,

    FOREIGN KEY (doctorId)
      REFERENCES doctors(id),
    FOREIGN KEY (patientId)
      REFERENCES patients(id),
  )

  ```

  > | ANSWER HERE |
