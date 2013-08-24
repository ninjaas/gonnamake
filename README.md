<a href="http://goonamake.com/">
    <img src="https://si0.twimg.com/profile_images/2690694370/d103186cdb45afbf7d4b27a653236129_bigger.png" width="100px">
</a>

# Gonnamake v0.0.0
Gonnamake is an advance and powerful open-source front-end framework system for fastest customisied and easier web development, created and maintained by [Ray Ch](http://iraycd.com) - [Ninjaas](http://ninjaas.com)

[Gonnamake Documentation](http://goonamake.com/documentation/)!



## Quick start

Read the [Getting Started page](http://goonamake.com/start-making/) for information on the framework contents, basic template guidelines, and more.


## Bugs and feature requests

Have a bug or a feature request? [Please open a new issue](https://github.com/ninjaas/gonnamake/issues). Before opening any issue, please search for existing issues and read the [Issue Guidelines](CONTRIBUTING.md).



## Documentation

Gonnamake's docs are built using [Jekyll](http://jekyllrb.com) and hosted on [GitHub Pages](http://pages.github.com/). To view the [Gonnamake Docs](http://goonamake.com/documentation/) locally, you'll need to [install Jekyll](https://github.com/mojombo/jekyll/wiki/install) to run a local server.


### Running Jekyll locally alongside Sass / Compass

We have [Sass](http://sass-lang.com) set up to compile static CSS into the directory that Jekyll "watches" when instructed to automatically regenerate.  If you are wanting to view documentation locally at ```localhost:9001```, we recommend uncommenting the ```auto: --auto``` instruction in ```_config.yml```.  This way, when running ```$ compass watch```, the updated CSS files injected into the directory Jekyll is watching will force regeneration of your static documentation files.  

You should also comment out the remote url instruction in ```_config.yml``` and uncomment the local ```url: /``` declaration so that the dynamic ```{{ site.url }}``` tags in the Jekyll templates will generate URLs that will work on your rig.



## Compiling CSS

### General Way

Goonamake makes use of [Sassy CSS](http://sass-lang.com) and [Compass](http://compass-style.org), so you'll need to install both ruby gems to generate static CSS.

```
$ sudo gem install sass
```

```
$ sudo gem install compass
```

Once you've installed these gems, simply run terminal from your repo directory, and run

```
$ compass watch
```

This will poll your Sass (`.scss`) source files for changes, and automatically update your static CSS for you.  To make this polling a little more user-friendly on a mac, we recommend installing [Compass Growl](https://github.com/Compass/compass-growl)

```
$ sudo gem install compass-growl
```

Then you can be notified via your native OSX growl notifications by adding this to your watch command

```
$ compass watch -r compass-growl
```


### Like a ninja

At ninjaas we use [Guard : Handle events on file system](http://ninjaas.com/blog/guard-handle-events-on-file-system/) with [Guard:Compass plug-in](https://github.com/guard/guard-compass)



## Contributing

Please submit all pull requests against *gm-wip branches. If your pull request contains JavaScript patches or features, you must include relevant unit tests.


## Authors

**Ray Ch**

+ [htpp://iraycd.com](http://iraycd.com)
+ [http://twitter.com/iraycd](http://twitter.com/iraycd)
+ [http://github.com/iraycd](http://github.com/iraycd)



## Copyright and license

Copyright 2013 Ninjaas - under [GNU GENERAL PUBLIC LICENSE](LICENSE).