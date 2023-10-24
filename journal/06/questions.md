# Single Page Applications with Vue
01. What is the entrypoint of an application?

  > | ANSWER HERE |

02. What is the difference between a vue `component` and `page`?

  > | A page in vue is essentially like the views that are set up in mvc, but are individual files that contain js, css, and html. Components are pieces of vue that we can input into our page model to make our code easier to debug and read. |

03. What is ***Component-Based Architecture***?

  > | ANSWER HERE |

04. What are the three tags that make up a Vue component?

  > | The three tags are template, which contain our HTML to put onto our page, the script, which acts as our main js file for that single vue file, and our style, which serves as a css sheet for that specific file. |

05. What are ***lifecycle hooks***? What are lifecycle hooks used for?

  > | Lifecycle hooks are put in our setup and run on page load or mount and unmount. They are used similar to constructors and are helpful for bringing in data from an API. |

06. Which component in Vue does the vue-router use to mount pages onto?

  > | ANSWER HERE |

07. What is the difference between the `AppState` and the state object within a component?

  > | Our Appstate is reactive and exists outside our vue files, which means properties in the AppState can be called from anywhere and stay in the AppState. Properties in Vue exist only in those files where we make them, and aren't reactive by default. |

08. What is the responsibility of `Services` in our Vue projects?

  > | Services have the same responsibility in Vue as they do in regular MVC, which is to interact with our AppState. |

09. What are ***props*** and how are they used? Provide an example

  > | Props are things that we bind onto our components to send through data from a v-for loop. Once we bind these we can use all their data that we set up to grab to reference to in our curly brackets. An example would be setting up our prop in our component, then when we bring in our component we add :propName="thing" onto it to bring all that data in. |

10. What is the Vue method used to create watchable objects such as `state` or `AppState`?

  > | ref() Then inside of the params we put our value in which allows it to be watched. |
