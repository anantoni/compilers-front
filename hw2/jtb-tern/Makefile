all: compile

compile:
	java -jar jtb132di.jar tern.jj
	javacc tern-jtb.jj
	javac Main.java


clean:
	rm -f *.class *~
