# gomysql


https://www.jianshu.com/p/71a319c1ff85





CREATE TABLE `userinfo` (
    `autid` INT(10) NOT NULL AUTO_INCREMENT,
    `username` VARCHAR(64) NULL DEFAULT NULL,
    `departname` VARCHAR(64) NULL DEFAULT NULL,
    `password` VARCHAR(64) NULL DEFAULT NULL,
    `uid` VARCHAR(64) NULL DEFAULT NULL,
    `created` DATE NULL DEFAULT NULL,
    PRIMARY KEY (`autid`)
);

