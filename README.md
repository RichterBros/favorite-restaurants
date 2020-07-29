# _Favorite Restaurants_

#### _C# ASP.NET Core MVC and EF Core practice for Epicodus, 07.29.2020_

#### By _**Brittany Lindgren, Erich Richter, & Taylor Somers**_


## Description

_Keep track of your favorite restaurants, any details about them and what type of cuisine they specialize in with this nifty application._


## Specifications

| Behavior   |   Input   |  Output |  Met? (Y/N)  |
|----------|:-------------:|------:|-----------:|
|    |   |    |    |



## Stretch Goals
| Behavior   |   Input   |  Output |  Met? (Y/N)  |
|----------|:-------------:|------:|-----------:|
|  |  |  |  |


## Setup/Installation Requirements

  1. Follow this [link to the project repository](https://github.com/LINDGRENBA/favorite-restaurants.git) on GitHub.  
  2. Click on the "Clone or download" button to copy the project link.     
  3. If you are comfortable with the command line, you can copy the project link and clone it through your command line with the command `git clone`. Otherwise, I recommend choosing "**Download ZIP**".     
   4. Once the ZIP file has finished downloading, you can right click on the file to view the zip folder in your downloads.     
  5. Right click on the project ZIP folder that you have just downloaded and choose the option "**Copy To...**", then choose the location where you would like to save this folder.      
  6. Navigate to the final location where you have chosen to save the project folder.      
  7. To view the code itself, right click, choose **open with...** and open using a text editor such as VS Code or Atom, etc.
  8. Once you are inside of your text editor, open the terminal. If you are in VS Code for example, this can be done by clicking on `Terminal` at the top of the editor and then selecting `New Terminal`. **You can navigate to different directories in the project by typing `cd DirectoryName` to go down into specific directories or `cd ..` to go back up one directory. 
  9. Navigate to the Restaurant directory by typing `cd Restaurant` in your terminal and hitting `enter`. Then type the command `dotnet restore`,`dotnet build`, then `dotnet run` into your terminal and hit enter. You should see files appear inside of your bin folder. The bin folder should appear greyed out. 
  10. Click on the link provided after you see `now listening on: ... ` appear in your terminal.


#### Additional Setup/Installation Notes:

* No additional code is necessary to view this project.   
* Do not alter the bin/ or obj/ directories or any of the files in them.

## Known Bugs

| Bug : Message |  Situation  | Resolved (Y/N) |  How was the issue resolved?  |
| ------- | ----- | ------ | ------- |
| 'RestaurantContext' does not contain a definition for 'Cuisines' and no accessible extension method 'Cuisines' accepting a first argument of type 'RestaurantContext' could be found (are you missing a using directive or an assembly reference?) [Restaurant] | Setting up CuisinesController Index View | Y | Add `public virtual DbSet<Cuisine> Cuisines { get; set; }` to RestaurantContext.cs |
 


## Support and contact details

_Please feel free to contact the authors through GitHub (LINDGRENBA, taylorsomers, RichterBros ) with any feedback, questions or concerns._


## Technologies Used

* C#
* .NET-Core 2.2
* ASP.NET Core MVC
* Visual Studio Code
* Git Version Control
* GitHub


### License

*This site is licensed under the MIT license.*

Copyright (c) 2020 **_{ Taylor Somers, Brittany Lindgren, Erich Richter}_**