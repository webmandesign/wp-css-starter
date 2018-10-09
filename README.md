# WordPress CSS Starter styles

This stylesheet provides just basic styles for WordPress themes.  
Using mobile first approach with these breakpoints:

- `448px` - starting mobile landscape,
- `672px` - starting tablet portrait,
- `880px` - starting tablet landscape,
- `1280px` - starting laptop,
- `1600px` - starting desktop,
- `1920px` - starting desktop full HD,
- `2560px` - starting desktop WQHD.


## Important notice

When using **LibSass** for compiling (with [Prepros](https://prepros.io/help/sass) it's called *"Node Sass"*), double check if media queries with multiple list parameters passed to the `media()` mixin are processed correctly.  
If they are not, try not to use **LibSass**.


## License

This CSS stylesheet, like WordPress, is licensed under the GPL.
Use it to make something cool, have fun, and share what you've learned with others.

*(C) Copyright WebMan Design, Oliver Juhas*