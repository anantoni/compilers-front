jflex scanner.flex
java -jar java-cup-11b.jar -parser Parser parser.cup
javac -cp java-cup-11b-runtime.jar *.java
