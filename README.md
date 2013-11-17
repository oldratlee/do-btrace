btrace start-up template project
==================================

1. Add your app dependency, then create your btrace script.
1. Compile btrace script by `mvn install`.
1. Get the class of btrace script from directory `target`.
1. Upload the class of the btrace script to the machine that the java process you want to trace is running on.
1. Run Command: `btrace <pid> <btrace script class>`

This project contains the example code from btrace, so you can simply copy and use it.

btrace resource
----------------------

- [BTrace User's Guide](https://kenai.com/projects/btrace/pages/UserGuide)
- [BTrace wiki](https://kenai.com/projects/btrace/pages/Home)
- [btrace一些你不知道的事(源码入手)](http://agapple.iteye.com/blog/1005918)
