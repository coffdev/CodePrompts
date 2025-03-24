Firstly, we code the project on VScode and on a Windows computer.

Develop a fully extensible PHP project from scratch using a custom file and folder structure. The project must not rely on any frameworks (such as MVC frameworks); instead, it should use a unique, self-designed architecture that emphasizes simplicity and clarity.

Project Requirements:

Language & Structure:

The project is written in PHP.

Use a simple, custom file/folder structure without any external frameworks or MVC patterns.

Organize files in a way that promotes easy maintenance and future expansion.

Front-End Design & Assets:

Integrate professional UI/UX design elements along with modern design libraries.

All CSS and JavaScript files must be placed in dedicated main folders (e.g., /css and /js).

Do not embed any CSS or JS code directly within the page files. Instead, create and maintain separate .css and .js files for each page as needed.

Ensure the entire design is 100% mobile-responsive.

Implement a global header and footer that are present on every page. Both header and footer should be sticky.

For icons, animations, and interactive elements, actively import and use libraries such as jQuery, GraphQL, GSAP, AJAX, and any other libraries deemed necessary.

Configuration & System Settings:

Centralize all configuration settings in a single config file. This file should include variables for:

Application details (name, URL, version, etc.)

SMTP settings for email

Database credentials and settings

API keys and other essential configuration parameters

All dynamic references (such as application name or version) must be pulled from this configuration file.

Advanced Features:

Implement a custom, advanced logging system that tracks errors and system events.

Build an integrated notification system with push notification support.

Develop an advanced email system for sending out notifications, alerts, or other communications.

Authentication & Social Login:

Provide social login functionality, including integration with Google and Facebook authentication.

Database & SQL Integration:

Use MariaDB as the database system.

Store all SQL scripts in a dedicated folder (e.g., /sql). Any updates to the database should modify these scripts.

Include an installdb.php file that automatically executes the SQL scripts to install or update the entire database. This file should:

Run all necessary SQL scripts to create tables and fields from scratch.

Display detailed, console-like output showing the progress and status of the installation process.

Instructions for Code Generation AI:
Based on the above requirements, generate a comprehensive PHP project that adheres to these specifications. The solution should include clear separation of concerns, a structured and maintainable file layout, and modular design practices. Ensure all elements (UI/UX, configuration management, advanced logging, social authentication, and database integration) are seamlessly integrated into the final project.
