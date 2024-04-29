# goit-node-cli

## Usage

1. Clone the repository.
2. Navigate to the `goit-node-cli` directory.
3. Use the following commands:

- Get and display the list of all contacts as a table:

  ```
  node index.js -a list
  ```

- Get a contact by ID and display the contact object or null if the contact does not exist:

  ```
  node index.js -a get -i [id]
  ```

- Add a contact and display the newly created contact object:

  ```
  node index.js -a add -n [name] -e [email] -p [phone]
  ```

- Remove a contact and display the deleted contact object or null if the contact does not exist:
  ```
  node index.js -a remove -i [id]
  ```

Please note that you need to replace `[id]`, `[name]`, `[email]`, and `[phone]` with the actual values.
