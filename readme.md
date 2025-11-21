# in wp-content folder

```
❯ npx @wp-playground/cli@latest server --auto-mount --port=8080 --verbosity=debug
The fs-ext package is not installed. Internal file locking will not be integrated with host OS file locking.
Starting a PHP server...
Native temp dir for VFS root: /private/var/folders/hg/2snln10d1nb6041vq3zr4kwh0000gn/T/node-playground-cli-site-5140--5140-sdHy5y2lTucM
Mount before WP install: /home -> /private/var/folders/hg/2snln10d1nb6041vq3zr4kwh0000gn/T/node-playground-cli-site-5140--5140-sdHy5y2lTucM/home
Mount before WP install: /tmp -> /private/var/folders/hg/2snln10d1nb6041vq3zr4kwh0000gn/T/node-playground-cli-site-5140--5140-sdHy5y2lTucM/tmp
Mount before WP install: /wordpress -> /private/var/folders/hg/2snln10d1nb6041vq3zr4kwh0000gn/T/node-playground-cli-site-5140--5140-sdHy5y2lTucM/wordpress
Mount after WP install: /wordpress/wp-content/database -> /Users/saulirajala/projects/repo-forkit/wp-playground-wp-content-bug/wp-content/database
Mount after WP install: /wordpress/wp-content/fonts -> /Users/saulirajala/projects/repo-forkit/wp-playground-wp-content-bug/wp-content/fonts
Mount after WP install: /wordpress/wp-content/plugins -> /Users/saulirajala/projects/repo-forkit/wp-playground-wp-content-bug/wp-content/plugins
Mount after WP install: /wordpress/wp-content/themes -> /Users/saulirajala/projects/repo-forkit/wp-playground-wp-content-bug/wp-content/themes
Mount after WP install: /wordpress/wp-content/upgrade -> /Users/saulirajala/projects/repo-forkit/wp-playground-wp-content-bug/wp-content/upgrade
Starting up workers
Resolved WordPress release URL: https://downloads.w.org/release/wordpress-6.8.3.zip
Fetching SQLite integration plugin...
Booting WordPress...
PHP.request() is deprecated. Please use new PHPRequestHandler() instead.
Booted!
Running the Blueprint...
Running the Blueprint – 100%
Finished running the blueprint
Preparing workers...
WordPress is running on http://127.0.0.1:8080 with 1 worker(s)
```

==> http://127.0.0.1:8080 redirects to http://127.0.0.1:8080/wp-admin/install.php



# in plugins/performance-lab or in themes/fleks -folder

```
❯ npx @wp-playground/cli@latest server --auto-mount --port=8080 --verbosity=debug
The fs-ext package is not installed. Internal file locking will not be integrated with host OS file locking.
Starting a PHP server...
Native temp dir for VFS root: /private/var/folders/hg/2snln10d1nb6041vq3zr4kwh0000gn/T/node-playground-cli-site-5245--5245-dy0TEDKE63eN
Mount before WP install: /home -> /private/var/folders/hg/2snln10d1nb6041vq3zr4kwh0000gn/T/node-playground-cli-site-5245--5245-dy0TEDKE63eN/home
Mount before WP install: /tmp -> /private/var/folders/hg/2snln10d1nb6041vq3zr4kwh0000gn/T/node-playground-cli-site-5245--5245-dy0TEDKE63eN/tmp
Mount before WP install: /wordpress -> /private/var/folders/hg/2snln10d1nb6041vq3zr4kwh0000gn/T/node-playground-cli-site-5245--5245-dy0TEDKE63eN/wordpress
Mount after WP install: /wordpress/wp-content/plugins/performance-lab -> /Users/saulirajala/projects/repo-forkit/wp-playground-wp-content-bug/wp-content/plugins/performance-lab
Starting up workers
Resolved WordPress release URL: https://downloads.w.org/release/wordpress-6.8.3.zip
Fetching SQLite integration plugin...
Booting WordPress...
PHP.request() is deprecated. Please use new PHPRequestHandler() instead.
Booted!
Running the Blueprint...
Activating /wordpress/wp-content/plugins/performance-lab – 100%
Finished running the blueprint
Preparing workers...
WordPress is running on http://127.0.0.1:8080 with 1 worker(s)
```

===> WordPress is installed in http://127.0.0.1:8080/ 

# in themes/fleks -folder

```
❯ npx @wp-playground/cli@latest server --auto-mount --port=8080 --verbosity=debug
The fs-ext package is not installed. Internal file locking will not be integrated with host OS file locking.
Starting a PHP server...
Native temp dir for VFS root: /private/var/folders/hg/2snln10d1nb6041vq3zr4kwh0000gn/T/node-playground-cli-site-5415--5415-wlRhtVlFY1yr
Mount before WP install: /home -> /private/var/folders/hg/2snln10d1nb6041vq3zr4kwh0000gn/T/node-playground-cli-site-5415--5415-wlRhtVlFY1yr/home
Mount before WP install: /tmp -> /private/var/folders/hg/2snln10d1nb6041vq3zr4kwh0000gn/T/node-playground-cli-site-5415--5415-wlRhtVlFY1yr/tmp
Mount before WP install: /wordpress -> /private/var/folders/hg/2snln10d1nb6041vq3zr4kwh0000gn/T/node-playground-cli-site-5415--5415-wlRhtVlFY1yr/wordpress
Mount after WP install: /wordpress/wp-content/themes/fleks -> /Users/saulirajala/projects/repo-forkit/wp-playground-wp-content-bug/wp-content/themes/fleks
Starting up workers
Resolved WordPress release URL: https://downloads.w.org/release/wordpress-6.8.3.zip
Fetching SQLite integration plugin...
Booting WordPress...
PHP.request() is deprecated. Please use new PHPRequestHandler() instead.
Booted!
Running the Blueprint...
Activating fleks – 100%
Finished running the blueprint
Preparing workers...
WordPress is running on http://127.0.0.1:8080 with 1 worker(s)
```

===> WordPress is installed in http://127.0.0.1:8080/ 


# First in themes/fleks -folder and then in wp-content folder
```
~/projects/repo-forkit/wp-playground-wp-content-bug/wp-content/themes/fleks main
❯ npx @wp-playground/cli@latest server --auto-mount --port=8080 --verbosity=debug
The fs-ext package is not installed. Internal file locking will not be integrated with host OS file locking.
Starting a PHP server...
Native temp dir for VFS root: /private/var/folders/hg/2snln10d1nb6041vq3zr4kwh0000gn/T/node-playground-cli-site-10783--10783-UBhGTr8o0n9y
Mount before WP install: /home -> /private/var/folders/hg/2snln10d1nb6041vq3zr4kwh0000gn/T/node-playground-cli-site-10783--10783-UBhGTr8o0n9y/home
Mount before WP install: /tmp -> /private/var/folders/hg/2snln10d1nb6041vq3zr4kwh0000gn/T/node-playground-cli-site-10783--10783-UBhGTr8o0n9y/tmp
Mount before WP install: /wordpress -> /private/var/folders/hg/2snln10d1nb6041vq3zr4kwh0000gn/T/node-playground-cli-site-10783--10783-UBhGTr8o0n9y/wordpress
Mount after WP install: /wordpress/wp-content/themes/fleks -> /Users/saulirajala/projects/repo-forkit/wp-playground-wp-content-bug/wp-content/themes/fleks
Starting up workers
Resolved WordPress release URL: https://downloads.w.org/release/wordpress-6.8.3.zip
Fetching SQLite integration plugin...
Booting WordPress...
PHP.request() is deprecated. Please use new PHPRequestHandler() instead.
Booted!
Running the Blueprint...
Activating fleks – 100%
Finished running the blueprint
Preparing workers...
WordPress is running on http://127.0.0.1:8080 with 1 worker(s)

===> WordPress is installed in http://127.0.0.1:8080/ 


~/projects/repo-forkit/wp-playground-wp-content-bug/wp-content/themes/fleks main 11s
❯ cd ../../


~/projects/repo-forkit/wp-playground-wp-content-bug/wp-content main
❯ npx @wp-playground/cli@latest server --auto-mount --port=8080 --verbosity=debug
The fs-ext package is not installed. Internal file locking will not be integrated with host OS file locking.
Starting a PHP server...
Native temp dir for VFS root: /private/var/folders/hg/2snln10d1nb6041vq3zr4kwh0000gn/T/node-playground-cli-site-10942--10942-u3ZKarbK662B
Mount before WP install: /home -> /private/var/folders/hg/2snln10d1nb6041vq3zr4kwh0000gn/T/node-playground-cli-site-10942--10942-u3ZKarbK662B/home
Mount before WP install: /tmp -> /private/var/folders/hg/2snln10d1nb6041vq3zr4kwh0000gn/T/node-playground-cli-site-10942--10942-u3ZKarbK662B/tmp
Mount before WP install: /wordpress -> /private/var/folders/hg/2snln10d1nb6041vq3zr4kwh0000gn/T/node-playground-cli-site-10942--10942-u3ZKarbK662B/wordpress
Mount after WP install: /wordpress/wp-content/.DS_Store -> /Users/saulirajala/projects/repo-forkit/wp-playground-wp-content-bug/wp-content/.DS_Store
Mount after WP install: /wordpress/wp-content/fonts -> /Users/saulirajala/projects/repo-forkit/wp-playground-wp-content-bug/wp-content/fonts
Mount after WP install: /wordpress/wp-content/plugins -> /Users/saulirajala/projects/repo-forkit/wp-playground-wp-content-bug/wp-content/plugins
Mount after WP install: /wordpress/wp-content/themes -> /Users/saulirajala/projects/repo-forkit/wp-playground-wp-content-bug/wp-content/themes
Mount after WP install: /wordpress/wp-content/upgrade -> /Users/saulirajala/projects/repo-forkit/wp-playground-wp-content-bug/wp-content/upgrade
Starting up workers
Resolved WordPress release URL: https://downloads.w.org/release/wordpress-6.8.3.zip
Fetching SQLite integration plugin...
Booting WordPress...
PHP.request() is deprecated. Please use new PHPRequestHandler() instead.
Booted!
Running the Blueprint...
Running the Blueprint – 100%
Finished running the blueprint
Preparing workers...
WordPress is running on http://127.0.0.1:8080 with 1 worker(s)


===> WordPress is installed in http://127.0.0.1:8080/ and the plugin and theme is also installed
```