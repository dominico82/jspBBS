# jspBBS
simple board using jsp, bootstrap

create table bbs(
bbsID int,
bbsTitle varchar(20),
userID varchar(20),
bbsDate datetime,
bbsContent varchar(2048),
bbsAvailable int,
primary key(bbsID)
);

create table user(
userID varchar(20),
userPassword varchar(20),
userName varchar(20),
userGender varchar(20),
userEmail varchar(50),
primary key(userID)
);

