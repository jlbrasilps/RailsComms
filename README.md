HEAD
# 🟣 RailsComms – Discord Clone built with Ruby on Rails 🧵

RailsComms is a functional **project ** built with **Ruby on Rails**, supporting **chat rooms**, **real-time messaging** via **Action Cable**, and **user authentication** with Devise.

> 📌 A fullstack project focused on real-time communication, inspired by Discord's architecture.

---

## ⚙️ Technologies used

- **Ruby on Rails** 7+
- **Action Cable** (WebSockets)
- **PostgreSQL** (or SQLite, depending on your setup)
- **Devise** for authentication
- **Bootstrap** or **TailwindCSS** (depending on UI)
- **Redis** (optional, for pub/sub performance boost)
- **StimulusJS + Turbo** (optional, if using Hotwire)

---

## 📦 Key Features

- 🔐 User registration and login
- 🧠 Server (_Guild_) creation
- 💬 Channels within servers
- ⚡ Real-time messaging with WebSockets
- 🧹 Delete accounts, messages, and servers
- ✏️ Inline message editing
- 🖥️ 100% MVC structure using Rails conventions

---

## 🛠️ How to run locally

```bash
# Clone the project
git clone https://github.com/jlbrasilps/RailsComms.git && cd RailsComms

# Install dependencies
bundle install

# Set up the database
rails db:create db:migrate db:seed

# Run the server
rails s
```
=======
# RailsComms
386fb8cc2c78986a8c909c0fa1cd23e9001a3793
