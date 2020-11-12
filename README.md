# Coursera: -> Full-Stack Web Development with React

### The Hong Kong University of Science and Technology

## Course 2: Front-End Web Development with React

#### Local Server set-up instructions:

1. To implement the server locally, you need to install `json-server` in your PC globally. Simply run `sudo npm install json-server -g`.
2. Place the given `json-server` folder into your `Documents` folder and run `json-server --watch db.json -p 3001 -d 2000` in that folder directory.
3. Once your server is started, you can access data in your browser like this: e.g. `localhost:3001/dishes`.

#### To deploy the project on server:

Simply run `npm run build` and React will generate `build` folder for you.

You can now deploy that folder on server, to verify this as your json-server is already runnig. Copy all files from `build` folder and paste them to the `json-server` -> `public` folder where you have kept this folder (e.g. `Documents` folder).

Now you can access your project by typing `localhost:3001` into you browser as your json-server is running.
