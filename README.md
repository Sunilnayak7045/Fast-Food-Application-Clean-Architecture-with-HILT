# Fast-Food-Application-Clean-Architecture-with-HILT

# Clean Architecture :

Presentation : A layer that interacts with the UI, mainly Android Stuff like Activities, Fragments, ViewModel, etc.
                     It would include both domain and data layers.

Domain: Contains the business logic of the application. 

Data: This layer is responsible for providing the data required by the application. 
      It includes the domain layer. It would implement the interface exposed by domain layer and dispenses data to app

Use Cases : in this architecture, a UseCase is an action that defines how a ViewModel interacts with the data layer.
            A use case is a potential scenario in which a system receives an external request (such as user input) and responds to it

![image](https://user-images.githubusercontent.com/47368515/173746594-60a78511-90b2-4fb1-b978-2b835e83f9fe.png)
