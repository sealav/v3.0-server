# Astonia 3

## Preface

Astonia 3 is a small MMO. It has all the stuff a fantasy role-playing game needs (character development with attributes, skills and spells, quests, equipment and monsters), and it can handle maybe 1000 players online at once per shard. A realistic limit for the number of shards is around 25. With some investments into the database server hardware more is possible.

Astonia 3 is the successor to my hobby project Mercenaries of Astonia 2. It was developed mostly by me for Intent Software. Intent Software was so kind to allow me to release the project to the public.

## License

Non-legalese version:

You may do whatever you want with this, provided you

a) give proper credit (eg. "is based on the Astonia 3 engine by Intent Software" somewhere in your game / on your website).

b) do not make money with it.

Contact me at daniel at brockhaus dot org if you need a commercial license. I'd also like to hear what you're doing with my work (but don't expect me to actually check it out ;)).

Bugfixes, extensions and links to actually working projects are welcome. I'd like to add all these to this page...

## Existing Projects

Astonia 3 with a commercial license
Requirements

## Server

The server needs Linux, MySQL development libraries and 32 bit gcc environment to compile. To run it needs a MySQL server on the same host.

The three files ending in .sql need to be imported into the MySQL server. The MySQL user root needs the password set to the one contained in the file MYSQLPASSWORD.

To create accounts, use the command line tool "create_account" and to create characters use "create_character".

Check the script "start" for an example on how to start the server. A multi-area server will need the chatserver running as well.

## Client

You will need the free Borland C++ 5.5 command line tools (available below)

Also requires libpng and zlib, but both are part of the client source code package.

Have fun and good luck.

