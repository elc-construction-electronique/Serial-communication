# Serial-communication
<h2>Classical serial communication with programmable power supplies.</h2>   <br/>The procedure is for the ALR3206T but is compatible with other products.<br/>
</br>
Open the Satelline Saterm application of the attached compressed folder “Satelline_SaTerm_4_0_0”
</br>
<img src=images/ri_3.png alt="Sateline home">
</br>

In the Mode menu, select Open Terminal:</br>
Locate the COM port of the ALR3206T (in normal mode) and complete the settings with:
<ul>
	<li>COM port
	<li>Baud rate: 9600
	<li>Handshake: None
	<li>Parity: None
	<li>Data bits: 8
	<li>Stop bits: 1
	<li>View: ASCII
	<li>Miscellaneous: “Local echo” and “CR->CR/LF”
</ul> 
</br>
<img src=images/ri_1.png alt="Satelline Setup">
</br></br>
Test the communication with the ALR3206T by sending "0 IDN RD" or "0 VOLT1 WR 1" or "0
TEST" . If the power supply returns the correct character string or "0 ERR", the communication is
operational. </br>  

</br>
<img src=images/ri_2.png alt="Serial Communication in Satelline">
</br>

