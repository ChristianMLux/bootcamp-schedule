# basic workflows with git & repos

## Repo - Flow
1. Repo auf Github erstellen
2. Ordner auf PC erstellen
3. Dateistruktur + .gitignore erstellen
<details>
<summary>struktur</summary>
<br>

src/ <br>
	index.html<br>
	script.js<br>
.github/workflows<br>
	workflow.yml<br>
.gitignore<br>
README.md<br>
</details>
<details>
  <summary>.gitignore</summary>
  <br>
    	[pre defined .gitignore](https://github.com/github/gitignore/blob/master/Node.gitignore)
</details>



4. git init
5. git remote add origin 
6. git add & initial commit & push

## Git - Flow
1. git checkout -b "branchName"
2. commit & push 
3. merge & branch delete
4. git checkout main 
5. pull

## NPM / Prettier / ESLint
1. npm init 
2. [git-flow](https://github.com/ChristianMLux/bootcamp-schedule/blob/main/FLOWS.md#git---flow)
3. npm i serve --save-dev
4.1. workflow add : - run: npm run devserver &
5. [git-flow](https://github.com/ChristianMLux/bootcamp-schedule/blob/main/FLOWS.md#git---flow)
6. npm i cypress --save-dev
	6.1. add cypress script to package.json
	6.2. run script once to create base files
	6.3. add baseUrl to cypress.json
	6.4. delete/move test examples /cypress/integration
	6.5. add test file (xxx.spec.js) in /cypress/integration
	6.6. workflow add : - run: npm run e2e:ci
7. [git-flow](https://github.com/ChristianMLux/bootcamp-schedule/blob/main/FLOWS.md#git---flow)
8. ESLint
	8.1. npm i eslint --save-dev 
	8.2. init eslint (npx eslint --init)
	8.3. ignore file (.eslintignore)
	8.4. configure eslint
	8.5. if parsing error occures on html, install eslint-html-parser
9. [git-flow](https://github.com/ChristianMLux/bootcamp-schedule/blob/main/FLOWS.md#git---flow)
10. Prettier 
	10.1. npm i prettier --save-dev
	10.2. dont forget to implement it in workflows
