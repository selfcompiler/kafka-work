# kafka-work
1. Kafka Theory
2. Kafka Cluster Mgmt
3. Kafka Cli 
4. Kafka Java API
5. Kafka Real World Example


Download https://kafka.apache.org/downloads


Download from mirror : https://www.apache.org/dyn/closer.cgi?path=/kafka/2.4.0/kafka_2.12-2.4.0.tgz

$ tar xvf kafka_2.12-2.4.0.tgz


In summary, for Mac OS X
Install brew if needed: /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

Download and Setup Java 8 JDK:

brew tap caskroom/versions
brew cask install java8
Download & Extract the Kafka binaries from https://kafka.apache.org/downloads

Install Kafka commands using brew: brew install kafka

Try Kafka commands using kafka-topics (for example)

Edit Zookeeper & Kafka configs using a text editor

zookeeper.properties: dataDir=/your/path/to/data/zookeeper

server.properties: log.dirs=/your/path/to/data/kafka

Start Zookeeper in one terminal window: zookeeper-server-start config/zookeeper.properties

Start Kafka in another terminal window: kafka-server-start config/server.properties
