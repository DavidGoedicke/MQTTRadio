# MQTTRadio

I noticed that on ```mqtt.eclipse.org``` the BBC publishes "real time" transcripts of their radio shows.

This simple script waits for one sentence to finish and starts speaking it outloud (using the OSX ``say`` comand).

Requires `MacOS` and the ``paho.mqtt`` python package.

## Running 

```shell
python3 MQTTRadio.py
```
