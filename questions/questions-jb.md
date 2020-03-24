### How do you revert a change from one branch and add it to another?
Scenario: You make an update and commit to the `master` branch. Afterward, you realize that you should've made this 
change to another branch named `staging`. What do you do? 

### Answer
To revert a specific commit to remove its changes from the `master` branch, perform these steps:

1. Click **History**.
1. In the commit history list, click the commit you want to revert.
1. Right-click the commit and click **Revert This Commit**.

Next, to make the change to the `staging` branch:

1. From your local repository, navigate to the `staging` branch. 
1. Create a **Pull** request to add your changes to this branch.

### How do you squash git commits?
Scenario: You have a GitHub branch with 5 separate commits. What is the command line sequence to squash those 5 commits 
into a single commit?

### Answer
1. Make sure your branch is up to date with the master branch.
1. Run `git rebase -i master`.
1. In the text editor that appears, make sure the first commit says `pick`. Replace the words `pick` with `squash` next to the commits you want to squash into the first commit.
1. Save and close the editor.

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
### Answer
The fourth line does not have a comma at the end. The fixed version is as follows:

```
{
  "first_name" : "Franz",
  "last_name" : "Kafka",
  "location" : "San Francisco",
  "streams" : true,
  "kafka" : 2.3 
}
```

### What is the ZooKeeper port?

Scenario: Complete step 1 of [this quick start](https://docs.confluent.io/current/quickstart/ce-docker-quickstart.html) to 
install a local version of Confluent Platform. After completing step 1, what port number is ZooKeeper running on?

### Answer 
After completing step 1, you see the ZooKeeper is running these ports: 2181/tcp, 2888/tcp, and 3888/tcp (see the following).

![](http://path/to/img.jpg "Title")


### What are the default topics created when you install Confluent Platform using the quick start?

Scenario: After you complete step 1 of [this quick start](https://docs.confluent.io/current/quickstart/ce-docker-quickstart.html), 
open Control Center at http://localhost:9021/. What are the names of the default topics that are created by Kafka?

### What is the name of the Connect cluster that is created?

Scenario: Complete step 2 of [this quick start](https://docs.confluent.io/current/quickstart/ce-docker-quickstart.html). 
What is the name of the Connect cluster that is created?
