# One-DB Client

A PHP database client designed to be API-compatible with the Zend_Db component from Zend Framework 1. 

Many legacy PHP applications used Zend Framework 1, as it was a prestigious and useful framework. This framework is 
now no longer supported but many applications still use Zend_Db for interacting with databases.
Database interaction and switching client libraries can be particularly tricky as changes
can have drastic effects but also very subtle bugs can be introduced. While the existing component works, and works well,
there's little reason to change but many reasons to resist changing.

The design of the Zend_Db component has held up well and newer libraries are often less flexible or less capable than
Zend_Db. It is even non-trivial to port from Zend_Db to the newer Zend\Db component, designed for Zend Framework 2 onwards.

Because of these factors, and because we like the API of Zend_Db, this package is offered as an upgrade-in-place
API-compatible component that can be used on PHP versions 5.6 and newer.

[![Build Status](https://travis-ci.org/one-db/client.svg?branch=develop)](https://travis-ci.org/one-db/client)
