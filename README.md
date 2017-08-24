# vhdl_uart
VHDL uart communication
This entity is a generic UART block 
--               UART allows to work with one or two bits stop
--               baud : 1200, 2400, 4800, 9600, 19200, 38400, 57600, 115200
--                      230400, 460800, 921600
--               Note:
--                   Br*br_divisor=921.600
--                   Fclk/921.600=clk_divisor
--                   => Br=Fclk/(clk_divisor*br_divisor)=1/((clk_divisor*Tclk)*br_divisor) 
