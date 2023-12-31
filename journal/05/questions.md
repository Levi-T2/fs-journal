# Intro to Server side concerns with JavaScript
01. What do the letters of the acronym `CRUD` stand for?

  > | The C in crud stands for create, R is for read, U is for update, and D is for delete. These all are for working with an API. |

02. Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?

  > | C in crud stands for .post, R stands for .get, U stands for .put, and D stands for .delete. |

03. What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB

  > | ORM stands for object relation mapping and its important for how we are able to get our information put up onto our database. We use mongoose for this. |

04. Which two `HTTP` request types include a body?

  > | .Put and .post are the two methods that pass through data from out request and give it to our database. |

05. In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.

  > | The first blank is synchronous, and the second is asynchronous and await. |

06. What are the three types of data relationships? Provide an example of each.

  > | One to One = A relationship between just two things. Each hold single variables that only link to other single variables. One to Many = A data relationship were an object has many different objects on it but those objects are only on that larger object. Many to Many = A relationship where something might have many contributors, and those contributors might have made many other projects. |

07. What is middleware?

  > | Middleware is software that does the job for us when it comes to us communicating between our database. Mongoose is an example of middleware that we use frequently. |

08. The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 

  > | Server, Client. |

09. Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.

  > | const test = await .get(req.query.winter , req.query.tag) res.send(test)|


10. What is a ***virtual property***?

  > | We use virtual properties on our Schemas to pass through more information about our objects in our request. They take our models and pass through extra info based on what we give them. |
