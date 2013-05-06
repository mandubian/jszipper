> EXPERIMENTAL / ALPHA

# JsZipper : Generic Json Zipper

> `JsZipper` is a new tool allowing much more complex & powerful manipulations of Json structures for different Json API:

> `JsZipper` is inspired by the [Zipper](http://en.wikipedia.org/wiki/Zipper_\(data_structure\)) concept introduced by [Gerard Huet](http://en.wikipedia.org/wiki/G%C3%A9rard_Huet) in 1997. 

>The Zipper allows to update immutable traversable structures in an efficient way. Json is an immutable AST so it fits well. FYI, the Zipper behaves like a loupe that walks through each node of the AST (left/right/up/down) while keeping aware of the nodes on its left, its right and its upper. The interesting idea behind the loupe is that when it targets a node, it can modify and even delete the focused node. The analogy to the pants zipper is quite good too because when it goes down the tree, it behaves as if it was <i>opening</i> the tree to be able to drive the loupe through all nodes and when it goes up, it <i>closes</i> back the tree... I won't tell more here, it would be too long.

> `JsZipper` is a specific interpretation of Zipper concept for Json API based on :
>   - Scala Streams to go through / update / construct Json AST in a lazy way
>   - Monadic aspects to provide _funnier_ ways of manipulating the Json AST (plz see below)

_Please note, `JsZipper` is not an end in itself but a tool useful to provide new API to manipulate Json._

Ok, much more can be done...
Have fun!
