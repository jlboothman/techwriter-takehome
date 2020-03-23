### How do you revert a change from one branch and add it to another?
Scenario: You make an update and commit to the `master` branch. Afterward, you realize that you should've made this 
change to another branch named `staging`. What do you do? 

### How do you squash git commits?
Scenario: You have a GitHub branch with 5 separate commits. What is the command line sequence to squash those 5 commits 
into a single commit?

### What is wrong with this sample JSON syntax?

```
{
  "first_name" : "Franz",
  "last_name" : "Kafka",
  "location" : "San Francisco"
  "streams" : true,
  "kafka" : 2.3 
}
```
### Answer (CHECK)
The syntax has unnecessary spaces before and after each colon. Each line needs a comma at the end, and the third line does not have one. The fixed version is as follows:

```
{
  "first_name":"Franz",
  "last_name":"Kafka",
  "location":"San Francisco",
  "streams":true,
  "kafka":2.3 
}
```


### What is the ZooKeeper port?

Scenario: Complete step 1 of [this quick start](https://docs.confluent.io/current/quickstart/ce-docker-quickstart.html) to 
install a local version of Confluent Platform. After completing step 1, what port number is ZooKeeper running on?

### What are the default topics created when you install Confluent Platform using the quick start?

Scenario: After you complete step 1 of [this quick start](https://docs.confluent.io/current/quickstart/ce-docker-quickstart.html), 
open Control Center at http://localhost:9021/. What are the names of the default topics that are created by Kafka?

### What is the name of the Connect cluster that is created?

Scenario: Complete step 2 of [this quick start](https://docs.confluent.io/current/quickstart/ce-docker-quickstart.html). 
What is the name of the Connect cluster that is created?
