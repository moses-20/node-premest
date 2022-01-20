### Primer on terminal
1. concept of directories
2. working in a directory

``` bash
# view current directory
$ pwd
```

``` bash
# view directory contents
$ ls 
$ ls -a
```

``` bash
# changing directory
$ cd ..
$ cd /
$ cd ~
$ cd <directory name>
```

### Interacting with Node
1. Checking Node version
``` bash
$ node -v
```

2. Node in REPL

``` js
// entering the REPL console
$ node

// exploring node
> .help
> .exit
```

``` js
// hello node
> console.log('Hello Node!');
> 123 + 456;
> let name = 'Gbemu Terra';
> console.log(name);
```

``` js
// simple program
> class Person{
    constructor(name, favColor){
        this.name = name;
        this.favColor = favColor;
    }

    introduce(){
        console.log(`I am ${this.name} and I love ${this.favColor}`);
    }
}

> let debby = new Person('Deborah', 'darkblue');

// reading debby
> debby.name
> debby.favColor
> debby.introduce()
```

### Using Node Package Managers
``` js
// basic npm
npm -v
npm -h
npm install yarn
```
