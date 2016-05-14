# processing_s7Bot_FK_088
!!! see s7Bot_GUI_092 for a newr version !!!

processing app to teach, record and play positions. safe/load to/from disk / change in v088: set a name for save or load file


// processing for 7Bot Beta version 0.8 > Pinaut 5/2016
// sorry for the mess!
//
// ============== READ THIS ===================== !!!!!!
// this code alows you teach the robot by hand, safe positions and replay later.
//
// download the libary for sliders (https://github.com/sojamo/controlp5)
// upload softwareSystem.ino from https://github.com/7Bot/7Bot-Arduino-lib to the arduino before start this sketch!!!
// calculations in the sketch are done with 0-1000 from the servo feedback NOT in degrees
// !servo speed not propper working with slow speeds, because the resolution in the arduino libary is poor (1-25)!
// Use Buttons or Keyboard shortcuts: 
// 'R' record mode
// 'P' play the stored positions (restart while pause)
// 'SPACE' add position to program
// 'C' clear last position
// 'S' safe recorded positions to file
// 'O' open file 
// In the textfield located right from filename you can type a name for the file. Folder 'data' on the sketch folder
// This name (default: 7Bot data') is used while safe file to disk and load from disk

!!! see s7Bot_GUI_092 for a newr version !!!
