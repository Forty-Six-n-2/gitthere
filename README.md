# gitthere
Just to learn git and play around with features.

+ Features
    * Submodules
    * Learning power of index
    * Merging and Rebasing
    * Use SSH for convenience
    * Understand commits
    * Understand history
    * Test SSH setup
    * Understand a bare repo
    * Understand branches
    

Graph of git process logic

```sh
    |---------------commit->--------->>|
    |--add->------->>|----commit->--->>|
    |----------------|-----------------|------push->-->>|
 [Work]           [index]           [local]        [remote repo]
    |<<----------<-pull or rebase-----------------------|
    |----------------|-----------------|-<<--<-fetch----|
    |<<--<-revert-checkout HEAD--------|
    |<<--<-checkout--|
    |------------diff HEAD-------------|
    |-----diff-------|
```
