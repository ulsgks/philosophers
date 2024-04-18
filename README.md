
# Philosophers

# 🍝 General information
Version: 10. Mandatory part only.
Write and tested on MacOS.

## 🍽 Features
- *Simple implementation*: a saw a lot of philo make overcomplicated implementation, I try to keep my code simple as possible.
- *Clean code*: with comments for most important functions.
- *Security*: all system calls are checked for errors and the program is properly terminated if an error is detected (that was painful to implement without `exit()` function).

## 📋 Testing 
This philosopher project passed all basic tests, but not all advanced ones. It potentially has some bugs.
| Results | Description | Repository |
| --- | --- | --- |
| basic + data race with valgrind | [philosophers_tester](https://github.com/kichkiro/philosophers_tester) | ✅❓ Helgrind fail, I don't know why |
| CPU check | [socrates](https://github.com/GOAT095/philosophers-tester) | ✅⏱️ Except once |
| lot of test | [42-philosophers-tester](https://github.com/dantonik/42-philosophers-tester) | ✅ ❌ For mandatory, some other fail |

## 📚 Resources
- [Threads, Mutexes and Concurrent Programming in C - codequoi](https://www.codequoi.com/en/threads-mutexes-and-concurrent-programming-in-c/)
- [The dining Philosophers | by oceanO | Medium](https://medium.com/@jalal92/the-dining-philosophers-7157cc05315)
- [Philosophers visualizer](https://nafuka11.github.io/philosophers-visualizer/)

## 🌟 Good projects that inspired me
- [dantonik/42-philosophers](https://github.com/dantonik/42-philosophers)
- [DeRuina/philosophers](https://github.com/DeRuina/philosophers)
