erlang-pbkdf2
=============

A [PBKDF2][] implementation for [Erlang][] extracted from [Apache CouchDB][].

[PBKDF2]: http://en.wikipedia.org/wiki/PBKDF2
[Erlang]: http://www.erlang.org
[Apache CouchDB]: http://couchdb.apache.org

This was taken from https://github.com/basho/erlang-pbkdf2, which is a fork of https://github.com/whitelynx/erlang-pbkdf2, which is a fork of CouchDB with everything removed except the PBKDF2 implementation.

However, using _that_ means fetching the entire repository (including CouchDB) when all you want is the PBKDF2 implementation. So this is a brand-new repository with _nothing else_ in it.

It was taken from basho/erlang-pbkdf2@7076584.
