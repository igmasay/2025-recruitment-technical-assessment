# DevSoc Subcommittee Recruitment: Platforms
Your task is to send a direct message to the matrix handle `@chino:oxn.sh` using the Matrix protocol. However, this message must be sent over a self hosted instance such as through the Conduwuit implementation or the slightly more complicated Synapse implementation.

For this to work your server must be federated, but you do not have to worry about specifics such as using your domain name as your handle (a subdomain will do!) or have other 'nice to have' features. Just a message will do!

**You should write about what you tried and your process in the answer box below.**

This task intentionally sounds challenging and contains language not frequently used in platforms as it refers to a specific protocol. The aim of this task is to research and make sense to some of the various terminology. If you don't manage to get this working we'll still want to hear about what you tried, what worked and what didn't work, etc, as knowledge isn't required, just the ability to try figure things out! Good luck!

---

> ANSWER BOX
```
Upon hearing of this task, I inquired my brother regarding networking and the use of docker, with the inclusion of individual research to expand my repertoire of knowledge required to complete this task.

I researched the Matrix, and learnt how it worked aswell as differerent homeservers. Following the advice provided as well as through comparison, I decided to use conduwuit as my homeserver. I downloaded it through the github repository.

I decided to create a docker compose for ease of access and security, instead of solely running the command. I created a basic docker compose using with only 2 environment variables.

For the server name, my brother lent me one of his sub domains for me to run the server on. Though I did not create this myself, I understand why I need a server and am willing to learn how to deploy a server myself.

Upon the creation of the docker compose, I ran into several issues with the environment variables, found through runtime errors and the use of federationtester. 
+Insufficent confirmation
+Invalid database path
+Invalid address
+Insufficent certificates


I searched for an example conduwuit docker compose, and managed to fix the confirmation, database path and address, but I had to externally download the certificates and create the variables to proceed.

Once the docker compose was completed, I inserted my server into element.io, and finally sent the message.

```
