# Martin Luther King Jr Day Quotes

A curated collection of empowering Martin Luther King Jr. quotes for the upcoming holiday, aimed at education and non-profit organizations.

![Thumbnail](./thumbnail.png)

## Template Details

- **Industries:** Education, Non-Profit
- **Message Type:** Newsletter
- **Tags:** inspiration, quotes, mlkday

## Files
- `index.html`: The improved, localized, and branded HTML template.
- `template.blade.php`: Ready-to-use Laravel Blade template with `asset()` helpers.
- `assets/`: Directory containing localized images and styles used in the template.

## Usage in Laravel

### 1. Store the Template
Place the `index.html` content in a Blade view (e.g., `resources/views/emails/martin-luther-king-jr-day-quotes.blade.php`).

### 2. Handle Assets
Move the content of `assets/` to your public directory (e.g., `public/vendor/mail-templates/martin-luther-king-jr-day-quotes/`) and update the paths in the HTML to use the `asset()` helper.

### 3. Send Email
```php
Mail::to($user)->send(new \App\Mail\GenericEmail([
    'view' => 'emails.martin-luther-king-jr-day-quotes',
    'data' => [
        // Your dynamic data here
    ]
]));
```

---
*Created with ❤️ by **[LaravelMail.com](https://laravelmail.com)** - Your source for professional email templates.*
