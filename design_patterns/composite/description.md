Composite Pattern
-----------------

Once you grasp its recursive nature, the Composite pattern is really quite simple. Sometimes we need to model objects that naturally group themselves into larger components. These more complex objects fit into the Composite pattern if they share some characteristics with the individual components: The whole looks a lot like one of the parts. The Composite pattern lets us build arbitrarily deep trees of objects in which we can treat any of the interior nodes—the composites—just like any of the leaf nodes.

The Composite pattern is so fundamental that it is not surprising that it reap- pears, sometimes in disguise, in other patterns. As we will see in Chapter 15, the Interpreter pattern is nothing more than a specialization of the Composite pattern.

Finally, it is difficult to imagine the Composite pattern without the Iterator pattern. The reasons behind this hand-in-glove relationship are about to be revealed, because the Iterator pattern is the topic of the very next chapter.