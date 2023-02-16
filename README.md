# Footed-Dynamic-NAND
A dynamic logic gate uses clocking and charge storage properties of MOSFETs to implement
logic operation. The clock provides a synchronized data flow which makes the technique useful
in designing sequential networks. The characterising feature of a dynamic logic gate is that the
result of a calculation is valid only for a short period of time. A foot(clock) is applied to bottom
NMOS which gives it its name footed NAND.
Boolean expression: Y = (A*B)’

## Circuit Diagram:
![foot_cir](https://user-images.githubusercontent.com/108890713/219371965-0dad36ba-bcf3-4db0-b383-87cb863f7e5e.jpeg)

## Euler's Path:
![foot_euler](https://user-images.githubusercontent.com/108890713/219372119-1c7ebc43-e270-4147-b91c-f31df718c053.jpeg)

## Stick Diagram:
![foot_stick](https://user-images.githubusercontent.com/108890713/219372206-81f44137-ad4e-4848-b34f-a40c55b0e7d9.jpeg)

## Magic Layout:
![foot_mag](https://user-images.githubusercontent.com/108890713/219372321-146266b9-aaf8-4680-95a4-d0944d57c37d.png)

## AC Analysis Output:
![foot_out](https://user-images.githubusercontent.com/108890713/219372441-c809ffa3-8a10-470d-9049-0c7b7d2bcc4c.png)

## Calculations:
Wp to Wn ratio(W p/W n) = 3 (Taken for the simulation)
rise time = 3.5ns
fall time = 3.2ns
Here, rise time and fall time come out to nearly be the same.

## Observation:
It is observed that the output is NAND of the three inputs and the rise and fall times obtained
are almost equal.
