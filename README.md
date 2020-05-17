# Github-Search
#### 15/05/2020
#### By **Jorim Midumbi Okong'o Opondo**
## Description

Github-Search is an Angular App that uses Github API to retrieve user data. Submit a username and it gives you repository details of the user, including number of repositories, commits and branches and also when it was last updated. 

![Github-Search]()

## Requirements

Both the CLI and the project have dependecies that require Node together with NPM. So make sure you have these installed and working before proceeding.

##### Technologies Used

- This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.1.4.
- HTML & CSS (Bootstrap)

##### Setup Instructions and Installation

- Clone this repository to a location in your file system.`git clone https://github.com/JORIM1981/Github-Search.git`
- Open terminal command line then navigate to the root folder of the application.
- Run `ng serve` command.
- Navigate to `http://localhost:4200/` in your browser.


## Behaviour Driven Development

##### Github-Search

1. Displays GitHub info of a user when user name is entered
   - INPUT: "user name entered"
   - OUTPUT: "Displays User Details"
2. Displays all repositories of a user when show repositories button is pressed
   - INPUT: "Show repositories button pressed
   - OUTPUT: "Displays User Repo Details"
3. Displays an error message if you leave the name input field blank
   - INPUT: " " 
   - OUTPUT: "Name's required" 
4. Displays an error message if you leave the repo name input field blank
   - INPUT: " " 
   - OUTPUT: "Repo Name is required"
5. Displays an error message if the user name entered couldn't be found
   - INPUT: "username"
   - OUTPUT: "User Doesn't Exist"
6. Displays an error message if the repo name entered couldn't be found
   - INPUT: "repository" 
   - OUTPUT: "Repository Doesn't Exist"
## Development

Want to contribute? Great!

To fix a bug or enhance an existing module, follow these steps:
- Fork the repo
- Create a new branch (git checkout -b improve-feature)
- Make the appropriate changes in the files
- Add changes to reflect the changes made
- Commit your changes (git commit -am 'Improve feature')
- Push to the branch (git push origin improve-feature)
- Create a Pull Request

## Known Bugs

If you find a bug (the website couldn't handle the query and or gave undesired results), kindly open an issue here by including your search query and the expected result.

If you'd like to request a new function, feel free to do so by opening an issue here. Please include sample queries and their corresponding results.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

##### Link to Live Site : [https://jorim1981.github.io/Github-Search/](https://jorim1981.github.io/Github-Search/)

## Inspiration

Project inspired by Brad Traversy's tutorial (Modern Javascript From The Beginning)


### License

*MIT*
Copyright (c) 2020 **Jorim Midumbi Okongo Opondo**

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.