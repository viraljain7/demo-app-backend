# Chai Aur Code(Special thanks to Hitesh sir)

### Step 1

```js
npm init
```

### Add this line in package.json

- after `main`

  ```js
  "type":"module",
  ```

- in script

  ```js
  "dev": "nodemon src/index.js",
  ```

### open terminal and run this command

touch .env .gitignore .prettierrc .prettierignore

```js
mkdir src public
```

```js
cd src
```

```js
mkdir controllers models utils db middlewares routes
```

```js
touch app.js constants.js index.js
cd ..
```

### dev dependencies

```js
npm i -D nodemon prettier
```
