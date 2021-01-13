# What

This is a silly little shell script that I took 5 minutes to write in order to automate the gathering of information on foreign networks that I attach to via my laptop.  The script runs a few traceroutes, looks up the source IP, DNS querier IP, etc.  It's as basic as you get.

## OS Support

It's tested on Linux and macOS.  It might work with other Unix-based operating systems and might work under WSL.

## Requirements

There are no requirements.  It calls MTR, if you have it (just fails if otherwise) as well as an ```ipin``` Perl script of mine (if you have it) that looks up ASN and PTR records.  It can be obtained here:

https://www.prolixium.com/files/code/ipin/

# Usage

Just run:

```./lifeforms```

And it'll spit out a text file for you.
