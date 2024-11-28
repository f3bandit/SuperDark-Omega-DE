Various properties locations

system color settings

ezkernelnew.c in the sources folder

between lines 153 and 174

// This sections sets the colors for the following properties
// text, button, selected, background, etc.
// search keyword RGB for other color
// settings in this file.
//----------------------------------------
u16 gl_color_selected = RGB(31, 0, 0);
#ifdef DARK
u16 gl_color_text = RGB(31, 31, 31);
u16 gl_color_selectBG_sd = RGB(31, 0, 0);
u16 gl_color_selectBG_nor = RGB(0, 0, 0);
u16 gl_color_MENU_btn = RGB(10, 10, 10);
#else
u16 gl_color_text = RGB(31, 31, 31);
u16 gl_color_selectBG_sd = RGB(31, 0, 0);
u16 gl_color_selectBG_nor = RGB(31, 0, 0);
u16 gl_color_MENU_btn = RGB(10, 10, 10);
#endif
u16 gl_color_cheat_count = RGB(31, 31, 31);
u16 gl_color_cheat_black = RGB(0, 0, 0);
u16 gl_color_NORFULL = RGB(0, 0, 0);
u16 gl_color_btn_clean = RGB(31, 0, 0);
u16 SAV_info_buffer [0x200]EWRAM_BSS;

Credits location

lang.c in sources folder

between 11 and 14
char* gl_theme_credit;
char* gl_theme_credit2;
char* gl_theme_credit3;
char* gl_theme_credit4;

between 162 and 165
const char zh_theme_credit[]="Superdark DE K1.05";
const char zh_theme_credit2[]="f3bandit";
const char zh_theme_credit3[]="Based on Simple DE";
const char zh_theme_credit4[]="Sterophonick";

between 293 and 296
const char en_theme_credit[]="Superdark DE K1.05";
const char en_theme_credit2[]="f3bandit";
const char en_theme_credit3[]="based on Simple DE";
const char en_theme_credit4[]="Sterophonick";

between 394 and 397
gl_theme_credit = (char*)zh_theme_credit;
gl_theme_credit2 = (char*)zh_theme_credit2;
gl_theme_credit3 = (char*)zh_theme_credit3;
gl_theme_credit4 = (char*)zh_theme_credit4;

between 516 and 519
gl_theme_credit = (char*)en_theme_credit;
gl_theme_credit2 = (char*)en_theme_credit2;
gl_theme_credit3 = (char*)en_theme_credit3;
gl_theme_credit4 = (char*)en_theme_credit4;

helpwindow.c

Between 55 and 58
DrawHZText12(gl_theme_credit, 0, 4, 90, gl_color_selected, 1);
DrawHZText12(gl_theme_credit2, 0, 4, 105, gl_color_selected, 1);
DrawHZText12(gl_theme_credit3, 0, 4, 120, gl_color_selected, 1);
DrawHZText12(gl_theme_credit4, 0, 4, 135, gl_color_selected, 1);

lang.h

btween 10 and 13
extern char* gl_theme_credit;
extern char* gl_theme_credit2;
extern char* gl_theme_credit3;
extern char* gl_theme_credit4;


Kernel version

helpwindow.c in sources folder

Line 21
char *ver="K:1.05";


Ezcard_OP.c
Line 535
Clear(0, 0, 240, 160, RGB(0,18,24), 1);

Change

Line 535
//Clear(0, 0, 240, 160, RGB(0,18,24), 1); BAK

Line 536
Clear(0, 0, 240, 160, RGB(31,0,0), 1);

testing

line 593 orininal
sprintf(msg,"FIRMWARE UPDATE");
DrawHZText12(msg,0,75,offset_Y+0*line_x, 0x7FFF,1); cyan

sprintf(msg,"Please use the OFFICIAl kernel to");
DrawHZText12(msg,0,2,offset_Y+3*line_x, 0x7FFF,1);

sprintf(msg,"update firmware. Sorry.");
DrawHZText12(msg,0,2,offset_Y+4*line_x, 0x7FFF,1);

sprintf(msg,"Press (B) to skip.");
DrawHZText12(msg,0,2,offset_Y+6*line_x, 0x7FFF,1);


ezkernelnew.c


Boot_NOR_game

Line 2901 original
Clear(0, 0, 240, 160, gl_color_cheat_black, 1);

Change

Line 2901
//Clear(0, 0, 240, 160, gl_color_cheat_black, 1); BAK

Line 2902
ClearWithBG((u16*)gImage_SPLASH,0, 20, 240, 160-20, 1);

Line 2903
DrawHZText12(gl_Loading,0,(240-strlen(gl_Loading)*6)/2,74, gl_color_text,1);

//WRITE TO NOR CLEAN

Line 3481 original
Clear(0,160-15,200,15,gl_color_cheat_black,1);

Change

Line 3481 
//Clear(0,160-15,200,15,gl_color_cheat_black,1); BAK

Line 3482
ClearWithBG((u16*)gImage_SPLASH,0, 20, 240, 160-20, 1);

//WRITE TO NOR ADDON

Line 3522 original
Clear(0,160-15,200,15,gl_color_cheat_black,1);

change

Line 3522
//Clear(0,160-15,200,15,gl_color_cheat_black,1); BAK

Line 3523


