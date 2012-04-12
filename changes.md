# Tiny Issue Change Log

## Tiny Issue v1.2

- Feature: Requirement check on installation
- Feature: Added ability to edit a issue title / body
- Feature: Autolink URLs in comment and issue body

## Tiny Issue v1.1.1

- Bug fix: Your issue count was not returning the right value
- Bug fix: The activity view was not account for issues assigned to no one

### Upgrading from v1.1

- Replace the app folder

## Tiny Issue v1.1

- Upgraded Laravel 2.x to Laravel 3.1.4, should fix some bugs related to PHP 5.4
- Bug fix: Added a URL option in the config to specify your URL, should fix path bug on non-apache servers

### Upgrading from v1.0

- Move `app/assets/uploads` to `/uploads`
- Run the `install/update_v1-1_1.sql` in your database
- Replace the `app` folder