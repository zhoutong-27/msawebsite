## jemdoc

jemdoc is a light text-based markup language designed for creating websites. It takes a text file written with [jemdoc markup](https://jemdoc.jaboc.net/example.html), an optional configuration file and an optional menu file, and makes static websites that look something like this one, [that one](http://stanford.edu/~boyd) or [another one](http://www.stanford.edu/class/ee364a/).

[jemdoc on github.](https://github.com/jem/jemdoc)

### Usage

1. edit or add the `doc/**.jemdoc` file 

   more things about how to edit the jemdoc file, please view the [website](https://jemdoc.jaboc.net/example.html).

2. use python script  to create `html/**.html` file 

   ```shell
   # python3
   
   # for signle file
   $ python jemdoc -c mysite.conf -o html/ /doc/***.jemdoc
   # for all files
   $ python jemdoc -c mysite.conf -o html/ /doc/*.jemdoc
   ```

### License

Copyright © 2007–2012 Jacob Mattingley.