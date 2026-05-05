# 📄 Online Bonafide Certificate Generator

A simple web application to generate bonafide certificates online with multiple templates and database storage.

---

## 🚀 Features

- 📝 Fill a simple form to generate a bonafide certificate
- 🎨 Choose from 3 certificate templates
- 💾 Saves certificate data to MySQL database
- ⚡ Instant form submission with confirmation

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | HTML, CSS, JavaScript |
| Backend | PHP |
| Database | MySQL |

---

## 📁 Project Structure

```
bonafide-generator/
├── index.html        # Main form page
├── styles.css        # Styling
├── script.js         # Form validation & interactions
├── save_bonafide.php # Handles form submission & DB connection
└── db.php            # Database configuration
```

---

## ⚙️ Setup & Installation

### Prerequisites
- XAMPP or WAMP (PHP + MySQL)

### Steps

**1. Clone the repository**
```bash
git clone https://github.com/your-username/bonafide-generator.git
```

**2. Move to XAMPP folder**
```
C:/xampp/htdocs/bonafide-generator/
```

**3. Start Apache & MySQL in XAMPP Control Panel**

**4. Create the database**
- Open **phpMyAdmin** → `http://localhost/phpmyadmin`
- Create a new database named `bonafide_generator`
- Import the `database.sql` file if provided

**5. Open the app**
```
http://localhost/bonafide-generator/index.html
```

---

## 🔒 Database Configuration

Update the database credentials in `save_bonafide.php`:

```php
$servername = "localhost";
$username = "root";
$password = "your_password";
$dbname = "bonafide_generator";
```

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
