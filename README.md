# Note on learning Java

- When the library is in jar, you can run in the terminal:
```
java  -classpath ./:stdlib.jar AddTwo.java
```
if `jar` is in the current directory. If a jar file is in the directory above the current direct, run:
```
java  -classpath ../stdlib.jar AddTwo.java
```

- If the `.java` file is in the subdirectory:
```
javac  -classpath ./:stdlib.jar ./week4/AddTwo.java && java -classpath ./:stdlib.jar ./week4/AddTwo
```

- In week10 with stdlib.jar in that directory,
```
javac -classpath ./:stdlib.jar ThreeSum.java
java -classpath ./:stdlib.jar ThreeSum 8 < 8ints.txt
```

- haven't figured out how `package` command should be configured.
