
Java based STT Sample Recognition
===================

**Version**
--------------
>**Environment**
	Ubuntu 16.04.3

>**Java**
	JDK: 8.0
	
>**GRPC**
	grpc-java: 1.2.0
	java protoc: 3.5.0
	




_________________
**Install** 
-------------------------
> **Java**

	Install JDK/JRE(https://www.digitalocean.com/community/tutorials/how-to-install-java-on-ubuntu-with-apt-get)

>**ProtoBuf Gradle**

	Install protobuf gradle plugin(https://github.com/google/protobuf-gradle-plugin)

>**Environment Setting**
	export **MINDS_ROOT=/home/{account}/minds**
	export **PATH=$PATH:/home/{account}/minds/bin**
	export **LD_LIBRARY_PATH=$LD_LIBRARY_PATH:/home/{account}/minds/lib**
	export **LD_LIBRARY_PATH=$LD_LIBRARY_PATH:/usr/local/lib**


-----------------------------------------------

**Execution**
----------------------
>**Execute JAR File**
	cd **~/minds/stt_sample/out/artifacts/stt_sample_main_jar/**
	java - jar **stt_sample.jar**


____________________________________

**Result**
-------------------------------
>**Output**
	/minds/stt_sample/out/artifacts/stt_sample_main_jar$ java -jar stt_sample.jar 
	127.0.0.1:9801
	Model  : baseline
	Sample Rate : 8000
	Lang : 0
	Running : true
	Server Address : 10.122.66.76:33317
	Invoked by : pong
	RESULT : 오늘 날씨 어때






