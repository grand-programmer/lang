# Laravel-lang

In this repository, you can find the lang files for the framework PHP, [Laravel 4/5/6/7](https://laravel.com).

## Install

#### Via Composer
* For Laravel 7.x : run `composer require grand-programmer/lang:~6.0` in your project folder
* For Laravel 6.x : run `composer require grand-programmer/lang:~5.0` in your project folder
* For Laravel 5.8 : run `composer require grand-programmer/lang:~4.0` in your project folder
* For Laravel 5.1-5.7 : run `composer require grand-programmer/lang:~3.0` in your project folder
* For Laravel 5 : run `composer require grand-programmer/lang:~2.0` in your project folder
* For Laravel 4 : run `composer require grand-programmer/lang:~1.0` in your project folder
* Files of languages are in "vendor/grand-programmer/lang" directory
* Copy the folders of languages that you want, in the *resources/lang* folder of your Laravel application (*app/lang* in Laravel 4).

#### Via GitHub

* Clone the [GitHub repository](https://github.com/grand-programmer/lang/) : *git clone https://github.com/grand-programmer/lang.git*
* Or download the [zip file](https://github.com/grand-programmer/lang/archive/master.zip)
* Choose the branch:
    * `laravel4` for Laravel 4 project
    * `master` for Laravel 5, 6, 7 projects
* Copy the folders of languages that you want, in *resources/lang* folder of your Laravel application (*app/lang* in Laravel 4).

#### Via SVN

Run this in your project directory:

```sh
# Laravel 5:
svn export https://github.com/grand-programmer/lang/trunk/src/[language-code] resources/lang/[language-code]

# Laravel 4:
svn export https://github.com/grand-programmer/lang/branches/laravel4/[language-code] app/lang/[language-code]
```

Replace `[language-code]` by any of the languages listed [here](src).

## Usage [Laravel only]

In the file *config/app.php*, change the value of *locale* by the short name of your language (*app/config/app.php* in Laravel 4).


## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Status of files

* Check the [todo.md](todo.md) file to see the missing translations.

## Projects based on this package

* [LaravelLang by ARCANEDEV](https://github.com/ARCANEDEV/LaravelLang) - Translations manager and checker for Laravel.
* [Laravel-lang by overtrue](https://github.com/overtrue/laravel-lang) - Command to add languages in your project.
* [laravel-lang-installer by ablunier](https://github.com/ablunier/laravel-lang-installer) - Command for easily add languages to a Laravel project.
* [laravel-lang-publisher by Andrey Helldar](https://github.com/andrey-helldar/laravel-lang-publisher) - Easy installation and update of translation files for your project.

## Credits

- [caouecs](https://github.com/caouecs)
- [All Contributors](https://github.com/grand-programmer/lang/graphs/contributors)
