# capture colour schemes
Various .Xresources colour schemes made from combining stuff in my Adobe capture CC library

## Preview

[Creek Colours](http://adobe.ly/1QP9ri8) + [Colours 10](http://adobe.ly/1SeOvAo):

![pic.png](preview/cc-c10.png)

[Warm Winter](http://adobe.ly/1Zryidl) + [Colours 07](http://adobe.ly/1J7cyz9)

![pic.png](preview/warm_winter.png)

## How to use:

```bash
$ git clone https://github.com/AdrianKoshka/capture_colourschemes.git
$ cd capture_colourschemes
$ cp .Xresources ~/ #assuming you don't have one of your own
$ cp ccc10 /path/to/where/you/want/
$ vim ~/.Xresources # or any editor you want
$ # change #include<path/to/cc10> to match the path of where you put the ccc10
$ xrdb -load ~/.Xresources
```
