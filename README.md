# Introducción a sass-scss, compass y Jade
---

## Welcome

This is an introduction to [sass-scss], [compass] and [jade] By Diego Santiesteban - [@gato_developer][gatodeveloper]

## Tools

* Convert HTML to jade syntax [HTML to Jade]
* Convert Jade to HTML syntax [Jade to HTML]

## Setup

### Requirements
- nodejs
- sass
- compass

#####plus

- bower
- gulp 

How to validate if I have installed this.

```
$ compass -v
```

```
$ sass -v
```

```
$ gulp -v
```

## Installs

Install ruby gems

```
$ gem install sass
; gem install compass
```

if you have nodejs installed, you can install jade, bower and gulp with npm

```sh
$ npm install jade -g;
```

### Compile sass with compass(from path content)


```sh
$ compass watch -c config.rb
```

### Compile jade(from path content)

```
$ jade -w jade -o ../public
```

### Install or download Repo.

```
$ git clone git@github.com:gatodeveloper/sass-jade.git
```

or 

```
$ git clone https://github.com/gatodeveloper/sass-jade.git
```

or [download zip]



## Javascript task Tool (Gulp)

#### Run default task.
```
$ gulp
```

#### Run a specific task

- sass
- jade

```
$ gulp <task>
```


### Version
0.0.1


License
----

MIT

[gatodeveloper]: https://twitter.com/gato_developer
[sass-scss]: <http://sass-lang.com/>
[jade]: <http://jade-lang.com/>
[compass]: <http://compass-style.org/>
[download zip]: <https://github.com/gatodeveloper/sass-jade/archive/master.zip>
[HTML to Jade]: <http://html2jade.org/>
[Jade to HTML]: <http://jade-lang.com/>
