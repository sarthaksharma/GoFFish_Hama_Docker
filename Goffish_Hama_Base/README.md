# GoFFish Hama Base Docker

This is the Base Image for GoFFish Hama Docker, on which the other images (i.e. Bin and Source) depend. 

Follow these steps to build the image

1. **Before you build, please download the foloowing: Oracle Java and Apache Hadoop.**
    
    ```
    git clone https://github.com/sarthaksharma/GoFFish_Hama_Docker
    
    cd GoFFish_Hama_Docker/Goffish_Hama_Base/
    
    curl -LO http://ftp.jaist.ac.jp/pub/apache/hadoop/core/hadoop-2.7.1/hadoop-2.7.1.tar.gz
    
    curl -LO 'http://download.oracle.com/otn-pub/java/jdk/8u73-b02/jdk-8u73-linux-x64.rpm' -H 'Cookie: oraclelicense=accept-securebackup-cookie'

    ```

2. **Build**

    ```
    docker build -t sarthaksharma96/goffish-hama-base .
    
    ```


**or**



1. **Pull the image from Dockerhub**
    You can always fetch the latest image for use, directly from the [DockerHub](https://hub.docker.com/r/sarthaksharma96/goffish-hama-base/).


