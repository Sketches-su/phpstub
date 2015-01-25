# Quick and dirty class/interface generator for Composer-based stuff

This generator is for simplifying developer's life without an IDE. It creates a class or an interface in the proper subdirectory of your project and fills some docblocks with the info picked from your `composer.json`. The code is quite unstable but seems to work. Feel free to send issues.

**Installation**:
1. Clone the repo
2. Create a symlink to `phpstub` from a place under your `$PATH`.

Maybe someday I'll publish it on Packagist.

**Usage** looks like this:
```
user@home:~/path/to/your/project/root$ phpstub class 'Foo\Bar\Baz'
```
where `~/path/to/your/project/root` is where your `composer.json` is located (script must be called only from there).

More verbose documentation can be seen by simply running `phpstub`.

