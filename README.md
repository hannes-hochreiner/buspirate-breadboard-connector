# Bus Pirate Breadboard Connector

The title says it all: a simple connector to facilitate the use of a Bus Pirate with breadboards.

## Why?

I really enjoy using my Bus Pirate to program AVR chips and debug prototypes.
To shorten the iteration cycles, I started using SPI in-system programming set-ups with optional UART connections for debugging.
Since all connections can remain unchanged between programming and testing, it made sense to create a connector that allowed hooking-up the Bus Pirate to the breadboard using a single cable.

I have tried using a commercially available 2x5 pin header connector.
The one I bought connects well to the breadboard, but it comes off very easily.
It works for connecting quickly, but not for the case where I have the connector installed semi-permanently.

## How?

I started out with a prototype on perfboard.
I used a shrouded header to avoid connecting the cable the wrong way.
Since OSH Park offers cheap high quality PCBs, the next iteration will be using [custom PCB](https://oshpark.com/shared_projects/N2lwszC6).

## BOM

  * Perfboard or PCB (1x)
  * 2x5 pin shrouded header (1x)
  * 5 pin headers (2x)

## References

  * [Bus Pirate](http://dangerousprototypes.com/docs/Bus_Pirate)
  * [OSH Park](https://oshpark.com/)
  * [KiCad](http://kicad-pcb.org/)
