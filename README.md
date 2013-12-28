Local SalesForce [On Hold]
=======

We built a Salesforce data mirror while I was at Groupon.
It was built in Node.js and stored data in a Local MySQL Database 
so we could run queries much faster and do nested joins for our BI.

Sadly it was close-source (kept internal to Groupon). :-(
I briefly considered re-building it after I left.

But have moved away from Salesforce towards more open platforms...
And since Salesforce updates its API every 3 months 
its a bit of a moving target.

If anyone ever requests a better Salesforce query interface,
I can russle one up quite quickly. But I suggest you try using:

- https://github.com/kevinohara80/nforce
- https://github.com/stomita/node-salesforce

- - -

Need to run Queries on your Salesforce Data 
without being *limited* by Force.com SOQL?
**Done.**

If you're *sick* of not being able to do 
**Nested Semi-Joins** in your SOQL Queries 
or getting *Time-outs* when querying 
**"large" datasets**, let me *soothe your pain*.

- - -

## Pre-Requisites

The only **pre-requisites** for using this project are:

- ( **Basic** ) Knowledge of **Salesforce.com Admin** 
(enough to set up **Remote Access** on your Org)
- ( **Basic** ) Google Drive/Docs **Spreadsheet** Skills 
(To specify which SF Objects you want to *"localise"*)
- ( **Basic** ) **MySQL** Database Setup and Query Skills 
(create your database and run any queries you want!)
- ( **Basic** ) **Command Line** skills (Terminal) - 
if you don't have experience, don't worry, you can/will learn!
- ( **Basic** ) **Ruby** (not rails) Knowledge to edit 
a configuration file and run a script.

**Why Ruby?** ... Its simple for *beginners* to understand 
and works well for large(ish) data sets.

**Why MySQL?** ... Its *FREE*, Relational fits the Salesforce 
Tabular Data Model quite well, 
and its easy for beginners to get started and find 
example queries online. 

**Why Google Docs/Drive?** ... Again *FREE* and provides a 
familiar/friendly UI to non-technical users.

*Enough Questions! Lets Get Started!* ;-)

- - -

## Getting Started

Everything that you need to get up and running is ...

- - -

## Development Log

### Configuration File

If you have *Zero* development experience 
( that's **totally fine** 
[BTW](http://www.urbandictionary.com/define.php?term=btw) ), 
a "Config" file allows you to put things like settings
and passwords in a file that you can then easily change **centrally**
( and in the case of a *Public Project*, *hide* sensitive info from everyone! )

In Ruby the *standard* way of organising Config files is to use 
[YAML](http://en.wikipedia.org/wiki/YAML). If you have
never seen a **.yml** file before I suggest you read a quick primer on it 
e.g. [Xavier Shay's YAML Tuturial](http://rhnh.net/2011/01/31/yaml-tutorial)

I'm going to build up an **/examples** folder in this project so anyone 
can learn what's going on by following
by following a few basic examples.
