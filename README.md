# 💬 Laravel Chat Application

A real-time chat application built with **Laravel** and **Laravel Reverb**. This project allows users to communicate instantly using WebSockets, providing a fast and seamless messaging experience.

---

## 📌 Features

- 🔐 User Authentication
- 💬 Real-Time Messaging
- ⚡ Laravel Reverb WebSocket Integration
- 👤 User-to-User Chat
- 📱 Responsive UI
- 🔄 Live Message Updates
- 🟢 Online/Offline User Status *(Optional)*
- 📖 Chat History *(Optional)*

---

## 🛠️ Tech Stack

- Laravel
- PHP 8.x
- MySQL
- Laravel Reverb
- Bootstrap / Tailwind CSS
- JavaScript
- Vite

---

## 📋 Requirements

Before installing, make sure you have:

- PHP >= 8.2
- Composer
- Node.js >= 18
- NPM
- MySQL
- Git

---

# 🚀 Installation

## 1. Clone the Repository

```bash
git clone https://github.com/ronak4549/Chat_Application.git
```

```bash
cd Chat_Application
```

---

## 2. Install PHP Dependencies

```bash
composer install
```

---

## 3. Install Node Dependencies

```bash
npm install
```

---

## 4. Create Environment File

```bash
cp .env.example .env
```

For Windows:

```bash
copy .env.example .env
```

---

## 5. Generate Application Key

```bash
php artisan key:generate
```

---

## 6. Configure Database

Open the `.env` file and update your database credentials.

```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=chat_application
DB_USERNAME=root
DB_PASSWORD=
```

---

## 7. Run Database Migration

```bash
php artisan migrate
```

---

## 8. Install & Configure Laravel Reverb

Publish the configuration:

```bash
php artisan reverb:install
```

Start the Reverb server:

```bash
php artisan reverb:start
```

---

## 9. Start Vite

```bash
npm run dev
```

---

## 10. Start Laravel Server

```bash
php artisan serve
```

Application URL:

```
http://127.0.0.1:8000
```

---

# ⚙️ Reverb Configuration

Example `.env`

```env
BROADCAST_CONNECTION=reverb

REVERB_APP_ID=local
REVERB_APP_KEY=local
REVERB_APP_SECRET=local

REVERB_HOST=127.0.0.1
REVERB_PORT=8080
REVERB_SCHEME=http
```

---

# ▶️ Running the Application

Open **three terminals**.

### Terminal 1

```bash
php artisan serve
```

### Terminal 2

```bash
php artisan reverb:start
```

### Terminal 3

```bash
npm run dev
```

Now visit:

```
http://127.0.0.1:8000
```

---

# 📂 Project Structure

```
app/
bootstrap/
config/
database/
public/
resources/
routes/
storage/
tests/
```

---

# 📷 Screenshots

Add screenshots here.

```
screenshots/

login.png
register.png
chat.png
```

Example:

```markdown
## Login

![Login](screenshots/login.png)

## Chat

![Chat](screenshots/chat.png)
```

---

# 🔧 Useful Commands

Run migrations

```bash
php artisan migrate
```

Rollback migrations

```bash
php artisan migrate:rollback
```

Clear cache

```bash
php artisan optimize:clear
```

Generate application key

```bash
php artisan key:generate
```

Start Reverb

```bash
php artisan reverb:start
```

Run Vite

```bash
npm run dev
```

---

# 📈 Future Improvements

- Group Chat
- File Sharing
- Voice Messages
- Emoji Support
- Read Receipts
- Typing Indicator
- User Presence
- Message Search
- Push Notifications

---

# 🤝 Contributing

1. Fork the repository.
2. Create a feature branch.

```bash
git checkout -b feature-name
```

3. Commit your changes.

```bash
git commit -m "Add new feature"
```

4. Push to your branch.

```bash
git push origin feature-name
```

5. Create a Pull Request.

---

# 👨‍💻 Author

**Ronak Prajapati**

GitHub: https://github.com/ronak4549

---

# 📄 License

This project is licensed under the MIT License.
