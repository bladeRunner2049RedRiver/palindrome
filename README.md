# Palindrome
>exercise to verify if a word or phrase is a palindrome (read exacly the same backwards, ex. AMA, 1221, a-M.a, 1.2-2.1)
>>the word or phrase is added to a json file and shows in the screen if is a palindrome or not
>>>send a status code of 200 if is palindrome and 400 if it's not
>>>>even if the server stops, the words or phrases still remain added in the app
>>>>>still working on TDD and BDD tests :(
>>>>>>RESTful, NodeJS, Express, p5, json

# Tips
1. install npm | sudo apt-get install npm
2. install nodeJS | sudo apt-get install -y nodejs
3. on your folder project | npm install express (don't need --save, already in package.json)
4. on your folder project | nodejs app.js
4. url for test the app should be | http://localhost:3000/
3. insert a word or phrase and mouse click in 'Verify!'
4. the word/phrase will be inserted in the json file and inside the canvas
5. open console in your browser and see json inserting the words and the return of the status code
6. your file words.json will grow, if you wish, you can delete the list, save and refresh the page
7. you can check a word or phrase direct in the url to return only the status code,
http://localhost:3000/check/INSERTYOURWORDHERE and enter, returns OK for palindrome or Bad Request
ex.: http://localhost:3000/check/o.Vo returns 'OK'

