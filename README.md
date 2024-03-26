# Animal Shelter API : Frontend
by Hayeong Pyeon

## How To Run This Project

### Set Up and Run the Animal Shelter API
First, following the instructions in the README of this [repo](https://github.com/hypyeon/epicodus-project16-animal-shelter-api) to set up and run the Animal Shelter API.

### Set Up and Run This Project
1. Clone this repo.
2. Open the terminal and navigate to this project's production directory called **AnimalShelterClient**.
3. Add the `RestSharp` and `NewtonSoft.Json` packages by running the following:
```
dotnet add package RestSharp --version 108.0.3
dotnet add package Newtonsoft.Json --version 13.0.2
```
4. Within the production directory, run `dotnet watch run` in the command line to start the project in development mode with a watcher.
> Open the browser to https://localhost:7277/. If you cannot access https://localhost:7277 it is likely because you have not configured a .NET developer security certificate for HTTPS. 

## Known Bugs
When updating information or deleting an animal from the list, the redirected page after making changes sometimes does not render the change - user has to refresh page to see the update.    

## License
[MIT](/LICENSE.txt) | Copyright © 2024 Hayeong Pyeon