#Flexbox LESS Mixins
This repository focuses on the mixins defined in the StyleSheet.less file. 
The mixins abstract the complexities required with using flexbox in its current, non-completely
baked state.

The flexbox CSS rules included are:

* display:flex
* flex-direction
* align-items
* align-self
* order
* flex-wrap

There is much room for improvement. So please do.

##Browser Support

The browsers tested are:

* IE 10
* Chrome 26
* Firefox 20 (with layout.css.flexbox.enabled set to true)

Note that the current version of Firefox, 20, does not use the current flexbox spec. To use it,
the user must turn on a configuration change, which no actual users will. This effectively means
that this won't work on Firefox until version 22. 

Read more about this at http://notebookheavy.com/2013/04/24/flexbox-less-mixin/

###References

1. http://www.w3.org/TR/css3-flexbox/ (September 2012 Version)
2. http://msdn.microsoft.com/en-us/library/ie/hh772069(v=vs.85).aspx (IE 10 Flexbox API Reference)
