![](https://img.shields.io/badge/Microverse-blueviolet)

# Project Name: Hello World Ruby on Rails Back-end

> This project implements the Ruby on Rails back-end


## Built With

- Ruby on Rails
- PostgreSql

## Getting Started

To get a local copy up and running follow these simple example steps.
- Clone Repository using
`git clone https://github.com/NeckerFree/hello-rails-back-end`
- Move into project directory
`cd hello-rails-back-end`

### Setup Database 
- Make sure that your Postgres database is installed.
-  Open the file config\database.yml
- Modify the connection parameters to point your Postgres database:
    `username: [your_user]`
    `password: [your_password]`

- If required drop existing database : `rake db:drop`
- Create databases: `rake db:create`
- Create db structure including tables : `rake db:migrate`
- Generate Seed data running the command : `rails db:seed`

### Run API 
- Located in the root path run `rails server` to start the API
- Visit http://localhost:3000/ in your browser!
- Navigate to http://localhost:3000/api/v1/greetings to see random Greeting in the API

## Author

👤 **Elio Cortés**

- GitHub: [@NeckerFree](https://github.com/NeckerFree)
- Twitter: [@ElioCortesM](https://twitter.com/ElioCortesM)
- LinkedIn: [elionelsoncortes](https://www.linkedin.com/in/elionelsoncortes/)


## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- Hat tip to anyone whose code was used
- Inspiration
- etc

## 📝 License

This project is [MIT](./LICENSE) licensed.
