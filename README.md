# How-To-Use-Lobster-Marc-s-Group

This repository is set up for basic scripts so that if you have no idea how to use lobster and really don't want to learn you can copy and paste over and hopefully it should work!

Lobster is an opportunistic system that takes avantage of the large computing power that ND can provide. It is a front end to the HTCondor system which automatically bundles your CMSSW enviorment. Since ND has such a large computing power relative to its user base most to all analysis will be faster using the ND system than using CMS global cluster systems such as Crab or htcondor on lxplus. It also can access the hadoop storage and save root files to your hadoop storage. 

I am by no means an expert on this subject, if you have any actually debuging issues you should email Hannah Nelson (hnelson2@nd.edu) or ask the slack channel which I or Hannah will be able to help you find.

Another huge note, Lobster does not support python3, which means your CMSSW enviroment should be CMSSW_10 or below! A new program called TaskVine is being devolped here at ND which will allow you to run non-CMSSW jobs using this opportunistic resource, and there is currently someone working on CMSSW support for TaskVine and Taskvine does support python3!

# Setup
Lobster uses a conda enviorment! I have attached a github that has the basic instruction on how to set up this conda enviroment and start running simple jobs.

https://github.com/NDCMS/lobster/blob/lobster-with-conda/hackathon_instructions.md

