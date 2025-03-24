Create a fully extensible PHP project built from scratch using a custom-designed file and folder structure. The project must not rely on any frameworks (e.g., MVC frameworks) but instead use a unique, self-designed architecture that prioritizes simplicity, clarity, and future expansion.

1. Language & Project Structure
Programming Language: The project will be entirely written in PHP.

Development Environment: Develop the project using VS Code on a Windows system.

File/Folder Structure:

Organize the project with a custom structure, avoiding frameworks or predefined MVC patterns.

The root folder should contain dedicated folders such as /css, /js, /config, /sql, /logs, etc.

CSS & JavaScript Files:

Global CSS and JS assets should be placed in the /css and /js folders.

Page-specific CSS and JS should reside in their own files named after the page. For example, for login.php, use css/login.css and js/login.js. No inline or embedded CSS/JS code should be present within the PHP files.

2. Front-End Design & Assets
UI/UX:

Integrate professional, modern UI/UX design elements.

Ensure the design is fully mobile-responsive (100% responsive).

Implement a global header and footer that are present on every page and remain sticky as the user scrolls.

Asset Management:

Do not use traditional image formats. For any graphics, icons, or visual elements, generate and use SVG code instead.

External Libraries:

Integrate modern JavaScript libraries such as jQuery, GSAP, AJAX, GraphQL, etc., as needed for animations, interactive elements, and dynamic data fetching.

3. Configuration & System Settings
Centralized Configuration:

Create a single configuration file (e.g., config/config.php) that contains all global settings.

This file should include:

Application details (name, URL, version, etc.)

SMTP settings for email

Database credentials and settings

API keys and other essential configuration parameters

All dynamic references in the project (like the application name or version) must be pulled from this configuration file.

4. Advanced Features
Custom Session & Cookie Management:

Develop a custom session management system with dedicated user session handling.

Implement custom cookie management to control authentication, session persistence, and security.

Logging & Notifications:

Integrate an advanced logging system that tracks errors and system events. All logs should be stored in the /logs folder.

Build an integrated notification system with support for push notifications.

Email System:

Develop an advanced email system for sending notifications, alerts, and other communications.

Social Authentication:

Implement social login functionality, providing integration with Google and Facebook authentication.

5. Database & SQL Integration
Database System: Use MariaDB as the primary database.

SQL Scripts:

Store all SQL scripts in a dedicated /sql folder. These scripts will be used for creating and updating database tables.

Automatic Database Installation/Update:

Create an installdb.php script that automatically executes all necessary SQL scripts to install or update the database.

This script should output a detailed, console-like log of the installation process, indicating the progress and status of each executed script.

6. Additional Technical Requirements
Modular Architecture:

Ensure that all components of the project are modular, facilitating easy maintenance and future expansion.

Separation of Concerns:

All business logic, presentation, and configuration should be clearly separated.

Avoid mixing HTML, CSS, and JavaScript code directly within PHP files. Use external files for styling and interactivity.

Dynamic Content:

Ensure that all dynamic content (e.g., application name, version) is referenced from the centralized configuration file.

Summary:
Using the above specifications, generate a comprehensive, modular PHP project that is fully extensible and adheres to best practices. The project should include custom session and cookie management, utilize SVGs instead of images, and enforce a strict separation between global and page-specific CSS/JS files (e.g., placing login page styles in css/login.css and its scripts in js/login.js, never embedded in login.php). This approach will ensure that the codebase remains clean, maintainable, and ready for future enhancements.
