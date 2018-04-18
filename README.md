# Usage

1. Open PHPMyAdmin or any other db tool, create a db & import `db.sql`.

2. Install all the dependencies.
```bash
# with npm
npm install

# or with yarn
yarn
```

3. Create a `.env` file & insert the following code. Replace values with yours!!
```javascript
PORT=YOUR PORT [STRING]
SESSION_HASH_SECRET=SESSION_HASH_KEY [STRING]
SESSION_BLOCK_SECRET=SESSION_BLOCK_KEY [STRING]
DB_USER=DB_USER [STRING]
DB_PASSWORD=DB PASSWORD [STRING]
DB=DB YOU JUST CREATE [STRING]
```

> See the default `.env` file to see an example of it

4. My root folder name is `Iris-Mini-Social-Network`, if yours is different then go ahead & change it as it used for imports. It can be done easily by searching the whole project.

5. Now run the app.
```javascript
npm start [OR] yarn start
```

6. Run the app in browser.
```javascript
localhost:[PORT]
```

7. Enjoy
