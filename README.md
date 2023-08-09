# Midterm-Prep-02

Gym API :
Branch Table
------------
BranchId (Primary Key)
Name
Trainer Table
-------------
TrainerId (Primary Key)
Name
BranchId (Foreign Key to Branch)
Client Table
------------
ClientId (Primary Key)
Name
TrainerId (Foreign Key to Trainer)
SubscriptionDurationId (Foreign Key to SubscriptionDuration)
SubscriptionTypeId (Foreign Key to SubscriptionType)
SubscriptionDuration Table
--------------------------
SubscriptionDurationId (Primary Key)
Duration
SubscriptionType Table
----------------------
SubscriptionTypeId (Primary Key)
Type
The relationships between entities are as follows: Many trainers can be associated with one branch, creating a Many-to-One relationship between Trainer and Branch. This is represented by the BranchId foreign key in the Trainer table, referencing the Branch table's primary key (BranchId). Many clients can have one trainer, creating a Many-to-One relationship between Client and Trainer. This is represented by the TrainerId foreign key in the Client table, referencing the Trainer table's primary key (TrainerId). Many clients can have one subscription duration, creating a Many-to-One relationship between Client and SubscriptionDuration. This is represented by the SubscriptionDurationId foreign key in the Client table, referencing the SubscriptionDuration table's primary key (SubscriptionDurationId). Many clients can have one subscription type, creating a Many-to-One relationship between Client and SubscriptionType. This is represented by the SubscriptionTypeId foreign key in the Client table, referencing the SubscriptionType table's primary key (SubscriptionTypeId).

[Mirro Link](https://miro.com/welcomeonboard/MzFTSDNYZ2R6cFpXYVBMT0l5NWVaS1ZJVWN1VFFTMjVVUEw2cE9ab3lWUTJXTVVaeVlQNGJ0Q0xHQkdrNUNVbXwzNDU4NzY0NTQ5OTQ2MzU2NzU3fDI=?share_link_id=91603817963)


Bank API 


Mall API 
