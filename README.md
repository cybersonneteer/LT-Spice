# LT-Spice
This repository documents my work with LTspice simulations carried out as part of the academic course Low Power VLSI Design. It includes a collection of exercises and circuit simulations developed while learning and applying low power design concepts at the transistor and circuit levels.

The purpose of this repository is to systematically record my learning progress, reinforce theoretical concepts through practical implementation, and maintain a structured reference for future revision. The contents may be updated or refined over time as my understanding of low-power VLSI techniques improves.

This repository is intended primarily for academic and learning purposes and may also be useful to fellow students exploring LTspice and low-power CMOS/VLSI design.

<details>
  <summary><strong> 13/01/2025: CMOS Inverter</strong></summary>

  <br>

  <p>
  A CMOS inverter is the most fundamental building block in digital integrated circuit design.
  It consists of a complementary pair of MOSFETs: a PMOS transistor connected to the supply
  voltage (VDD) and an NMOS transistor connected to ground (GND). Both transistors share a
  common input, and the output is taken from the connection between them.
  </p>

  <p>
  When the input is low, the PMOS turns ON and the NMOS turns OFF, pulling the output high.
  Conversely, when the input is high, the NMOS turns ON and the PMOS turns OFF, pulling the
  output low. This complementary operation results in logical inversion with very low static
  power consumption, which is a key advantage of CMOS technology.
  </p>

  <p>
  Due to its simplicity and efficiency, the CMOS inverter serves as the foundation for more
  complex digital circuits such as logic gates, flip-flops, and memory cells, making it an
  essential starting point in low power VLSI design.
  </p>

  <br>

  <h3>Circuit Schematic:</h3>
  <img width="979" height="605" alt="CMOS Inverter Schematic"
       src="https://github.com/user-attachments/assets/bc0bc97a-d9e7-4f4d-b2a6-bedbdd765ad5" />

  <br><br>

  <h3>Parameters Used:</h3>

  <ul>
    <li><strong>Vpulse:</strong><br>
      <img width="881" height="715" alt="Vpulse Parameters"
           src="https://github.com/user-attachments/assets/b50b9abb-0a33-48ee-a375-7641b7661b7d" />
    </li>
    <br>
ul>
  <li>
    <strong>VDC:</strong><br>
    <img width="519" height="199" alt="VDC Parameters"
         src="https://github.com/user-attachments/assets/0bec6686-2cb1-480a-8bf4-ef6bd028ab1f" />
  </li>

  <li>
    <strong>Transient Analysis specifications:</strong><br>
    <img width="672" height="558" alt="Transient Analysis"
         src="https://github.com/user-attachments/assets/34cc00b3-87dd-48b4-a49a-61a8b6e3a204" />
  </li>

  <li>
    <strong>DC Sweep:</strong><br>
    <img width="664" height="565" alt="DC Sweep"
         src="https://github.com/user-attachments/assets/ccf3e0ca-8744-4fa6-be36-957b93d5970d" />
  </li>
</ul>
  <br>

  <h2>Outputs:</h2>

  <h3>Transient Analysis:</h3>
  <p>
  When the input voltage (Vin), represented by the green waveform, is high (5V),
  the output voltage (Vout) is low (0V), confirming inverter operation.
  </p>
  <img width="940" height="210" alt="Transient Output"
       src="https://github.com/user-attachments/assets/9ba00899-124a-4742-8b10-772cfb124124" />

  <br><br>

  <h3>Transfer Characteristics:</h3>
  <p>
  When Vin equals Vout, a short-circuit condition occurs, leading to the presence
  of crowbar current during the switching transition.
  </p>
  <img width="940" height="210" alt="Transfer Characteristics"
       src="https://github.com/user-attachments/assets/f7fd3585-fefc-4bda-b230-a55f44cb6a3c" />

</details>

