# Random App Ideas Generator
A Random App Ideas Generator built using json-server &amp; vanillaJS and deploy with Now.sh

## Installation + Pre-Components
### json-server
json-server: `npm install -g json-server`
```json
{
  "ideas": [
    {
      "id": 1,
      "app-ideas": "A calculator app",
      "details": "A standard calculator: numbers, +, -, *, /, and the result"
    },
    {
      "id": 2,
      "app-ideas": "A book database",
      "details": "Enter the books you own, Enter the books you’d like to buy, Store the book info, images"
    },
    {
      "id": 3,
      "app-ideas": "A recipes app",
      "details": "Enter a name, a description with the steps, Have pictures, Have some ranking for difficulty and quality, Add the time needed, Have different steps with a picture for each, Store them somewhere"
    }
  ]
}
```
Run Dev Server: `json-server --watch db.json`

Deploy: 
  * Upload to Github
  * Deploy with Vercel
  * Uses `domain`+ `db.json`

Use Case JS: Property Path 
  * (app-ideas):`ideas[MathRandom-Here]["app-ideas"]` 
  * (details):`ideas[MathRandom-Here].details`

### vercel-cli/now-cli
now-cli-tool: `npm i -g now`
deploy `now --public`

--------------------

## Links
Helpful Links that I found very useful for building the project.

### json-server
https://github.com/typicode/json-server
https://github.com/jesperorb/json-server-heroku#deploy-to-now

### Apps Ideas
https://flaviocopes.com/sample-app-ideas/

