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

Kernel version

helpwindow.c in sources folder

Line 21
char *ver="K:1.05";