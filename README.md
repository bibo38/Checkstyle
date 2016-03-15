Checkstyle configuration
========================

This are my personal coding preferences packed into a Checkstyle configuration.

URL-Configuration
-----------------

You can configure checkstyle to use the following URL: 
[https://raw.githubusercontent.com/bibo38/Checkstyle/master/checkstyle.xml](https://raw.githubusercontent.com/bibo38/Checkstyle/master/checkstyle.xml)

Gradle
------

To use it with [Gradle](https://gradle.org/) add this project as a Git submodule

```bash
git submodule add https://github.com/bibo38/Checkstyle.git config/checkstyle
```

and then add the following snippet to your `build.gradle` file

```gradle
plugins {
	id 'checkstyle'
}

apply from: 'config/checkstyle/checkstyle.gradle'
```

Now your're ready to go :smirk:
