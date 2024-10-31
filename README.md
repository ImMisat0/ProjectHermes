# ProjectHermes
This project is a Book Review Portal, built using Laravel framework along with TailwindCSS & AlpineJS.

## **IMPORTANT NOTE BEFORE INSTALLING** 
Before cloning the repo, you should check the version of your Laravel/Composer/PHP version
My project version are:
```
Composer version 2.7.4 
PHP version 8.2.12
Laravel Framework 11.21.0
```
It should help with preventing some unexpected issues from appearing. 

# DOWNLOADING GUIDE
## Installation 
1. Cloning the repo:
```bash
git clone https://github.com/ImMisat0/ProjectHermes.git
cd First_crud_project-OD
```
2. Installing dependacies 
```
composer install
```

3. Copy .env.example to .env and configure environment variables
```
cp .env.example .env
```

4. Set up the database
```
php artisan migrate
```

## Usage
Right after you've done clone the repo, navigate to the root directory and type this into the terminal:
```
php artisan serve
``` 
This will start the server, after that just ctrl+click on the link.

## Features
1. Book Listing: Displaying a list of books with their ratings and review counts.

2. Book Search: Enabling users to search for books by title.

3. Book Details: Providing detailed information about a specific book, including reviews.

4. Review Submission: Allowing users to add their own reviews for books.

5. Popular Books: Displaying a list of the most popular books based on various criteria (e.g., most reviews, highest ratings).

6. Top-Rated Books: Displaying a list of the highest-rated books.

7. Database Relationships: Implementing database relationships between books and reviews to efficiently retrieve and display related data.

8. User Interface: Designing and implementing a user-friendly interface using Tailwind CSS.

## Troubleshooting
- Problem: Cannot connect to the database.
+ Solution: Check if the database credentials in the `.env` file are correct.

- Problem: No application encryption key has been specified
+ Solution (step-by-step): 
1. Navigate to the root of your Laravel project in the terminal and run:
```
php artisan key:generate
```
2. Check the `env.` file, make sure it exists in the project root. You can create one by copy the `env.example`:
``` 
cp .env.example .env
```
3. After confirming/setting up the `.env` file, run the `php artisan key:generate` command again to resolve the issue.
4. (Optional) Clearing the config caches after generating the key:
```
php artisan config:clear
```


## Contribution
Any contributions to the project are welcome and very much appriciate. 
To contribute: 
1. Copy the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Creating a pull request.

## Credits
- Tailwind.Css(https://tailwindcss.com) - for styling.
- Alpine.JS (https://alpinejs.dev) 
