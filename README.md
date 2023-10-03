The supplied code for this project is an extremely primitive version of the GUI toolkit and paint program, comprising a few files:

Gctx (graphics context) module: gctx.ml, gctx.mli
Widget module: widget.ml, widget.mli
Eventloop module: eventloop.ml, eventloop.mli
Deque implementation: deque.ml, deque.mli
Some unit tests: widgetTest.ml (uses the Assert module)
Some testing programs: gdemo.ml, lightbulb.ml
Paint application: paint.ml
g-native.ml.x and g-js.ml.x: wrappers for the Graphics module\

The modules gctx, widget, and eventloop are the main components of the GUI toolkit. The gdemo and lightbulb programs test some of the functions you must add to the gctx and widget modules. Finally, paint is the paint application itself.
