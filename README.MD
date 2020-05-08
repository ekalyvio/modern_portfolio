Continue at ->
https://www.youtube.com/watch?v=7WaohfclZRs&list=PLillGF-RfqbYoGoCjKoMgOkVznV6aSXKzU&index=3

Tutorial from:
https://www.youtube.com/watch?v=HguAyYnWBuU&list=PLillGF-RfqbYoGoCjKoMOkVznV6aSXKzU&index=2

1. npm init
2. npm i node-sass
3. On package.json:
   "scripts": {
   "sass": "echo \"Hello\""
   }
4. npm run sass
   Should display "Hello"
5. On package.json:
   "scripts": {
   "sass": "node-sass -w scss/ -o dist/css/ --recursive"
   },
6. npm run sass
7. Get CDN code from FontAwesome.com and add to index.html (script).
