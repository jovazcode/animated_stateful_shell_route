# animated_stateful_shell_route

This is an "animated" version of the official example "[__Stateful Nested Navigation__](https://github.com/flutter/packages/blob/main/packages/go_router/example/lib/stateful_shell_route.dart)" of the "_go_router_" Library which demonstrates how to use a `StatefulShellRoute` to create stateful nested navigation, with a `BottomNavigationBar`.

This version adds 2 animations when transitionning from one navigation branch to another:
- A fading opacity (duration: 300ms)
- A quick translation transformation (duration: 125ms) with a given direction according to the new index value (direction is "left-to-right" if new index is greater than previous, and "right-to-left" if new index is lesser than previous)
