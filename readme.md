
# Tick

Clocking methods using requestAnimationFrame. It is named _tick_ (and not clock) because it is not meant to be an independent unit, rather a utility that's attached to other processes that just executes on intervals. In that regards, it is merely a more elegant setInterval.


## Usage

First initialize the lib:
```
var tick = new Tick();
```

Then add as many metohds in sequence using the ````add``` method:
```
tick.add(function(){
	// ...
}, 1000);

```
Optionally we can set the interval as a second parameter.

Later we may need to remove the method, we use ```remove```:

```
tick.remove(function(){
	// ...
});

```


## Credits

Initiated by Makis Tracend ( [@tracend](http://github.com/tracend) )

Distributed through [Makesites.org](http://makesites.org)


## License

Released under the [MIT license](http://makesites.org/licenses/MIT)
