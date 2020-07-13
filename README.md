# Budget Tracker
The user will be able to add expenses and deposits to their budget with or without a connection. When entering transactions offline, they should populate the total when brought back online.

![screenshot of the code](gif.gif)


# User Story
AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling

# Getting Started
1. Link to github: https://github.com/AlexPR704/budgetTracker;
2. Link to app: https://warm-falls-71848.herokuapp.com/;

# Instructions
Follow the link above to visit the deployed site.
This application uses a service-worker to cache transactions when the user is not online and then retrieves them from the cache the next time the app is used when online. A manifest.json is used to provide metadata for the application so the browser knows how the app should behave when it is installed.


# Built With
Mongoose
Node.js & Express.js
HTML, CSS, Javascript

# Credits
Big credits will have to go to the TA's and instructors to help me on this task. Specvial thanks to the supplement folder provided to us. Also thanks to the study groups.
# License
MIT License

Copyright (c) [2020] [Alexander Garcia]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.