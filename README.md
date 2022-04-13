# site_laravel

# 1 - Install Laravel
 - https://laravel.com/docs/9.x#getting-started-on-macos
 - curl -s "https://laravel.build/example-app" | bash
 - ./vendor/bin/sail up (run containers)
# 2 - Install AlpineJS
 - ./vendor/bin/sail shell (open container terminal)
 - npm install alpinejs  
 - Initialize alpinejs on file /resources/js/app.js
 - Build the file app.js -> npm run watch

# 3 - Test AlpineJS
 - On file welcome.blade.php in the end import app.js -> <script src="{{ asset('js/app.js') }}"></script>
 - Create code to test

# 4 - Install TailwindCSS
 - npm install tailwindcss
  - Generate tailwindcss config file -> npx tailwindcss init
  - Config tailwindcss on file tailwind.config.js -> https://laravel.com/docs/9.x/mix#tailwindcss
