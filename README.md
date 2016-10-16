2. Move to the directory and install gem dependencies
    ```bash
      bundle install
    ```

3. Migrate the database
    ```bash
    rails db:migrate
    ```

4. Move to the angular2-client directory and install Angular2 dependencies
    ```bash
    cd angular2-client
    npm install
    ```

## Run the app

1. Run the rails server in the main directory with
    ```bash
    rails server
    ```

2. Open a second terminal and run the npm server in the angular2-client directory with
    ```bash
    npm start
    ```

3. Open [http://localhost:3001/](http://localhost:3001/) in your browser

