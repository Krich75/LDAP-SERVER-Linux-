# LDAP-SERVER-Linux-
LDAP SERVER LINUX



What is LDAP?

We know that Linux keeps registered users on /etc/passwd file, so if you want to access the machine, you must have a user defined on that file.

This is good when you are working one or few machines, but what if you have hundreds of machines or maybe thousands, and how you will maintain user management tasks like password modification or any other administrative task like somebody left the work and you need to close his account, would you go to every machine to do that?

That could be a nightmare, or you need to create a new account. In this case, we need a centralized user account management system, a database to keep all information related to user accounts.

The most used solution for this problem is the Lightweight Directory Access Protocol (LDAP).

LDAP uses the usual client/server paradigm.

 

Uses of LDAP

LDAP not only keeps a list of users, but you can also use it as storage for your files.

It can be used for authenticating users as we mentioned above.

You can store DNS records in LDAP server.

LDAP can be used as a yellow pages directory service for an organization to provide information about users or employees, departments, contact information, phone numbers, addresses, private data or whatever.

 
LDAP Server Implementations

LDAP is an open standard protocol, many companies make its own implementation of the protocol.

There are commercial implementations of LDAP like:

    Microsoft Active Directory.
    Oracle Internet Directory.
    Oracle Unified Directory.
    IBM Security Directory Server.
    UnboundID Directory Server.
    NetIQ eDirectory or eDirectory.
    CA Directory or CA eTrust Directory.

And free open source implementations like:

    OpenLDAP.
    ForgeRock OpenDJ.
    Apache DS.
    389 Directory Server.
