PHPass
======

Java PHPass hash implementation

This is a Fork
==============

This is a fork of https://github.com/Wolf480pl/PHPass. Wolf480pl is the original author. The sole purpose of the fork is to make it usable as a Maven dependency.

I do not vouch for this implementation when used to **hash** passwords. I am merely using it to **check** passwords that were originally hashed and stored using the [PHPass](http://www.openwall.com/phpass/) PHP library. I myself am using [JBcrypt](http://www.mindrot.org/projects/jBCrypt/) to hash new passwords, and to transition PHPass passwords to bcrypt.

The Maven dependency coordinate for this project is:

```xml
<dependency>
  <groupId>com.jkkramer</groupId>
  <artifactId>phpass</artifactId>
  <version>1.0</version>
</dependency>
```
