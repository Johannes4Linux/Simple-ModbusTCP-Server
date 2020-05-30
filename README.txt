# General

This is the file I have used for my video about creating a Modbus TCP server in Python. Here is the [link](https://www.youtube.com/watch?v=FYPQgnQE9fk) to my video.

# Content

The file *Simple_ModbusServer.py* contains the code for a simple Modbus Server with the following register description:

| Holding Register Addr. | Description |
| --- | --- |
| 0 | Server writes a random value to it every 500 ms |
| 1 | Server monitors this register for changes. If the value is changed by the client, the server will print out the new value |

# Dependencies

To run the script, you need to have pyModbusTCP installed on your machine. To install it, you can use:

~~~~
sudo pip install pyModbusTCP
~~~~
