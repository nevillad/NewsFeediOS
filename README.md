# NewsFeediOS

This is a sample app developed using UIKit framework and having support of minimum iOS version 13.

While developing I have used Clean Swift Architechture and URL Caching that is listed below. 

- [x] [Clean Swift](https://clean-swift.com/)
     - Clean Swift Architechture satisfies SOLID principles and it decouple class responsibility with well established boundries(More easy to test and suitable for TDD), each class has it's own responsibilities and it can be achieved through sepration of concerns using protocols.
     - In Clean Swift, your project structure is built around scenes and we have a set of components in each scene that will "work" for our controller. Following are the components<br /> 
      * **Models**<br /> 
      * **Router**<br /> 
      * **Worker**<br /> 
      * **Interactor**<br /> 
      * **Presenter**<br /> <br /> 

- [x] Cached option with **URLCache**
     - To reduce the redundant API calls I've used URLCache to store respone for a particular day. Below are the steps to achive that,
          - Step 1: Retrive URL Reponse cached for url request
          - Step 2: Check if URL Reponse cached is of same day
                   - If data is of same day return clouser with cached data
          - Step 3: If response data found then cache those data
          - Step 4: Return local cache data if error occuered OR Data not available
     - For Locally Storing Data Coare Data. Used

## Minimum Project Requirements 
Project build on Xcode 12.5.1

## Project Structure
<img width="369" alt="Screenshot 2022-03-06 at 8 12 02 PM" src="https://user-images.githubusercontent.com/3881137/156928071-e57818e9-8c92-4f11-8945-6cac87db44a9.png">


- **Models** Folder contains DataModel Classes
- **Scenes** Folder contains all the screens files e.g ViewController, Intractor, Presenter, Router and Model claess for each screen
- **Network Manager** Folder Network Service related classes
- **HelperClass** Folder contails Extetions, Custom Reviews and Utility Classes



## App UI Screens

- **Models** Folder contains DataModel Classes
- **Scenes** Folder contains all the screens files e.g ViewController, Intractor, Presenter, Router and Model claess for each screen
- **Network Manager** Folder Network Service related classes
- **HelperClass** Folder contails Extetions, Custom Reviews and Utility Classes



## App UI Screens
