# platziverse-db

## Usage 

```js

const setupDatabase = require('platziverse-db');

setupDatabase(config).then(db =>{
	const {agent,metric} = db
	}).catch(err => console.log(err))

```