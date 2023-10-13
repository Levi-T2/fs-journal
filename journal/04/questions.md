# Understanding Asynchronous Code, and API's
01. What is the difference between `asynchronous` code and `synchronous` code?

  > | All code thats normally written is synchronous, which means it runs line by line going down the page, and if something takes to long the task gets skipped over. With asynchronous code it can be invoked to run, and while its being run other pieces of code can be run as well. |

02. What is an event listener?

  > | An event listener is something like a string within your Appstate.on that listeners for a key to change or be emitted in order to run the specified function. |

03. What does *REST* stand for, and in simple terms what does it mean??

  > | Rest stands for representational state transfer. It was made to force APIs into specific guidelines to follow so that  they were easy to access and utilize.  |

04. What is a callback / higher order function?

  > | A callback function takes in a function as its argument to use. Then it can be utilized or invoked during the higher order function. |

05. What is a `promise`? How do you capture an error from a `promise`?

  > | A promise in JS is a guarantee that we make that we will do something in the future. Once the promise completes it has two outcomes, either resolved or rejected. We can capture the error by looking at our rejected catch by using a try catch wih error.|

06. Name three processes used to make requests over `HTTP`?

  > | Three of the processes that are used are .get, which grabs all the data from the api and imports it to us. A .post pushes our newly created objects into our api, and . delete deletes our objects from the api. All of these send and receive requests. |

07. What does the `API` acronym stand for?

  > | API stands for Application Programming Interface. |

08. What must you do in order to `await` a promise inside of a function?

  > | In order to be able to wait for a function, you need to add the async tag to it so it can run asynchronously with the rest of your code. |

09. What is the purpose of encapsulation in programming?

  > | The purpose of encapsulation is to limit the amount of access the user has to the components of your webpage. This makes for a safer and more secure webpage and is crucial in protecting user data.|

10. What is `HTTP` response code for a successful request?

  > | HTTP - 200 or ok is the code for when you make a request and its successfully given. |

11. What is a 400 error?

  > | An HTTP error 400 is a bad request error and usually means that you tried to request something incorrectly within your code. |
