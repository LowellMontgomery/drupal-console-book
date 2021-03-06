# Running the project


After using Composer to download dependencies, you can run the project by executing:

```
$ bin/console
```

### Create a symbolic link

You can run this command to easily access the Drupal Console from anywhere on your system:

```
$ sudo ln -s /path/to/DrupalConsole/bin/console /usr/local/bin/console.dev
```

**NOTE:** The name `console.dev` is just an alias you can name it anything you like.

#### Create a custom Phar

To create a Phar file based on our dev version, execute the following command:

```
$ cd /path/to/DrupalConsole
$ box build
```

As a result, you will have the new phar file **console.phar**

**NOTE:** Make sure you set `phar.readonly` to '0' in your [php.ini](http://php.net/manual/en/phar.configuration.php)
