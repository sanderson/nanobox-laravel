![Laravel from scratch](https://guides.nanobox.io/assets/quickstart-icons/laravel.png)

#### Clone the repo

```bash
# clone the code
git clone https://github.com/nanobox-quickstarts/nanobox-laravel.git

# cd into the laravel app
cd nanobox-laravel
```

#### Run the app

```bash
# Run laravel as you would normally, with Nanobox
nanobox run php artisan serve --host 0.0.0.0
```

#### Check it out

```bash
# Add a convenient way to access your app from the browser
nanobox dns add local laravel.dev
```

Visit your app at <a href="http://laravel.dev:8000" target="\_blank">laravel.dev:8000</a>

#### Explore

With Nanobox, you don't have to have anything installed on your machine to run your app:

```bash
# drop into a Nanobox console
nanobox run

# where ruby is installed,
ruby -v

# your gems are available,
gem list

# and your code is mounted
ls
```

#### Now What?
For more details about running laravel apps with nanobox visit [guides.nanobox.io/ruby/laravel/](https://guides.nanobox.io/ruby/laravel/)
