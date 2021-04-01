# java-native-cli-example

Build OS native CLI application with java and GraalVM.

## Build & Run

1. sdk install java 21.0.0.r11-grl
2. sdk use java 21.0.0.r11-grl
3. mvn -DbuildArgs=--no-server clean verify
4. ./target/java-native-cli-example -h
5. ./target/java-native-cli-example -a=MD5 target/java-native-cli-example

The produced executable application only be 22MB on Mac.

## References

> Follow the turial from [Building native CLI apps in Java with picocli and GraalVM ](https://github.com/remkop/picocli-native-image-maven-demo).
> Learn more at [Build Great Native CLI Apps in Java with Graalvm and Picocli](https://www.infoq.com/articles/java-native-cli-graalvm-picocli/).

