# STM32
Testing an arduino variant with an ARM cortex-M chip. 

**resources used to get started with programming through Arduino**  
Note that these resources assume you're programming with an FTDI programmer. 
[Youtube Tutorial](https://www.youtube.com/watch?v=MLEQk73zJoU&t=505s)  
[Blog Post on adding hardware support code](https://tomknabe.com/adding-controllino-boards-to-osx/)  
[Additional Hardware Support Code](https://github.com/rogerclarkmelbourne/Arduino_STM32)  

Other files that are really helpful: 
[Black Pill WIKI](https://wiki.stm32duino.com/index.php?title=Black_Pill)  
[Brand Specific Page](https://wiki.stm32duino.com/index.php?title=RobotDyn_Black_Pill)  
[Brand specific pinout](https://robotdyn.com/pub/media/0G-00005692==STM32F103C8T6-STM32MiniSystem/DOCS/                                                                                                                                                                                                                                                                                                                                                                                                                                                                          nnnPINOUT==0G-00005692==STM32F103C8T6-STM32MiniSystem.pdf) (backup in repo in case of dead url)

Some practical notes:
- BOOT0 needs to be shifted to 1 to enter programming mode. 
- Upload your program through Serial1 (pins A9 & A10).
