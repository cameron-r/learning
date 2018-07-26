# Setup
1. Clone/download repo somewhere
2. Find "build.gradle" in finder, rightclick -> open with IntelliJ
3. Project should be open! Navigate to src/main/java/fizzbuzz to see the 2 files I created

At some point intellij might ask you where java or gradle are. If you followed a "normal" install, Java should be somewhere like `Program Files/java/jdk10.xxx` and Gradle should be in `C:/Gradle/gradle4.y/bin/gradle`

# FizzBuzz
Fizz Buzz is a simple problem some programmers use as a "Hello World" type exercise

The idea is you take a number `n` as input, and then increment from `1` to `n` and print the number at each increment, BUT:

If the number is divisible by 3, print `Fizz` instead of the number
If the number is divisible by 5, print `Buzz` instead of the number
If the number is divisible by 3 _and_ 5, print `FizzBuzz` instead of the number

Example output:
```
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz
16
17
Fizz
...
```

