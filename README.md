# Ekuerre

You will get a microservice through HTTP to obtain QR in PNG format.

## Install

    pip install ekuerre

## Simple usage

    python -m ekuerre.main

The process will run in port *32491* so you will access in your browser like this:

    http://localhost:32491/qr.png?data=HelloWorld

## Extra

The name stands for eQR in slang spanish.

# Long live and prosper!

# TODO

* Add binary for calling the service as "ekuerre" instead of "python -m ekuerre"
* Tests
* Configurable port