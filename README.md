
## Step 1: Install XAMPP

1. Download **XAMPP** from [https://www.apachefriends.org](https://www.apachefriends.org).
2. Install it on your computer.
3. Open the **XAMPP Control Panel** and start:

   * **Apache** (for PHP)
   * **MySQL** (for the database)

---

## Step 2: Set Up the Database

1. Open your browser and go to:

   ```
   http://localhost/phpmyadmin/
   ```
2. Click **New** to create a database.
3. Name the database: `user_system`
4. Click **Import** → choose your `users.sql` file → click **Go**.
5. This will create the `users` table with the required structure.

---

## Step 3: Copy Project Files

1. Copy all project files (PHP, CSS, JS, etc.) into:

   ```
   C:\xampp\htdocs\AS\
   ```
2. Your folder structure should look like this:

   ```
   AS/
   ├── db.php
   ├── register.php
   ├── login.php
   ├── profile.php
   ├── logout.php
   ├── style.css
   ├── users.sql
   ```

---

## Step 4: Access the Project

1. Open your browser.
2. Go to:

   ```
   http://localhost/AS/register.php
   ```
3. Fill out the **registration form** and submit.
4. After registration, you will be redirected to the **login page**.

---

## Step 5: Login

1. Enter your **registered email and password**.
2. On successful login, you will be redirected to the **profile page**.

---

## Step 6: Profile and Logout

1. On the **profile page**, you can see your username, email, and registration date.
2. Click **Logout** to end your session.
3. After logout, you will return to the **login page**.

---

✅**Tips**:

* Always access pages via **`http://localhost/...`**, not by opening `.php` files directly.
* Make sure Apache and MySQL are running.
* If you change the database username/password, update `db.php`.

---

If you want, I can make a **visual diagram showing the workflow**: Register → Login → Profile → Logout, which makes it even easier to understand.

Do you want me to do that?
