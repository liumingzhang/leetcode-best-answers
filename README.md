# leetcode-best-answers

A pdf document with three top voted answers in the discussion forum for each problem on leetcode.com.

## How it was made

Nothing fancy here... Basically:

- get discussion url for each question based on its url pattern
- crawl (python, lxml) top three voted answers for each question given a discussion url
- write answers for each question into mongodb
- style and display the answers locally via node.js/express.js
- generate pdf with wkhtmltopdf

Note there are answers for locked questions in this pdf. The reason is that while the problem is locked, the dicussion for the problem isn't.


## Note

All answers in the document are attributed to their authors. If you see your answers in there and would rather your answer not be included, send me a note at gnijuohz@gmail.com.


## How do I thank you?

Thought you'd never ask 😉. I just made this because I was needed a break from practicing problems... If you think it's helpful for you, feel free to:

- connect with me on [linkedin](https://www.linkedin.com/in/gnijuohz)  
- try my [app](https://itunes.apple.com/us/app/geeksforgeeks-reader-read/id991254978?mt=8) and send your feedback. (The app is not completely free right now, but will be in the next version, 1.5.0. So you can download first and wait a few days. ;))
- follow my on [twitter](https://twitter.com/gnijuohz).

## Feedback

Just open an issue.
