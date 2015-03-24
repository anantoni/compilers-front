all: compile

compile:
	java -jar jtb132di.jar calc.jj
	javacc calc-jtb.jj
	javac Main.java

clean:
	rm -f *.class *~
