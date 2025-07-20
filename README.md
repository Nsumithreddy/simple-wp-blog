📝 Simple WordPress Blog (Customized Theme)

This project is a customized WordPress blog built using the **Twenty Twenty-Four** theme. The header and styling have been modified to include a personal logo and blog title.

🚀 How to Run Locally

1. Install **XAMPP** and start Apache + MySQL.
2. Copy the `twentytwentyfour` folder into:

C:/xampp/htdocs/wordpress/wp-content/themes/

3. Open **phpMyAdmin** and import the database:
- Create a new database: `simple_wp_blog`
- Import the file: `simple_wp_blog.sql`

4. Go to:
[http://localhost/wordpress/wp-admin](http://localhost/wordpress/wp-admin)

- Login and activate the `Twenty Twenty-Four` theme.


📂 Folder Structure

simple-wp-blog/
├── twentytwentyfour/       ← Customized WP theme folder
│   ├── style.css           ← Modified with personal styles
│   └── ...                 ← Other theme files (unchanged)
├── simple\_wp\_blog.sql      ← Exported WordPress DB
├── README.md               ← This file


✨ Customizations Done

- Added a logo and title in the `header.php`
- Updated colors and fonts in `style.css`

🔑 Notes

- This is a static backup of the theme and database.
- WordPress core files are not included.

📌 Author

Sumith Reddy – Custom WordPress Blog Project



