# Backend Setup (Stack)

# Current Wesite

We are going to modify the current website. To update the functioning.

## PHP

* add a DB for events (Mulhern)
* add CAS and a user accounts (Mikko)
* get Letsencrypt (Mulhern/Mikko)
* Front end redesign non major ()

## New hosting service altogether?

* Let's face it, having the server in University's network is a bit wonky. There are a lot of security concerns on their side, and opening a port for - say, sending emails from the server to authenticate registered users - will need weeks of negotiation. We don't have direct internet access so installing new packages and maintaining the server is a pain in the long run.
* We could either somehow escalate the privileges for the server, e.g. reach a compromise between the University that we could open/close ports we want (unlikely), move the server to a better location with direct internet i/o access (where?), or pay for a hosted server (costs moneys).

# New Web Server

This may or may not happen

Options:

* Apache

* Nginx

## CGI

Options:

* Passenger
    * Multi Threaded
* Puma
    * Multi Threaded
* Unicorn
    * Single thread

# Scripting 

Ruby & Rails

We will use Ruby as students will be using it and more familiar with the language, they will eventually use Rails.

Will need a CGI interface see above.


