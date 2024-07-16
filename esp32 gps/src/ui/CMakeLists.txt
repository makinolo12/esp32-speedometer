SET(SOURCES components/ui_comp_eventrotate.c
    components/ui_comp.c
    screens/ui_Screen1.c
    ui.c
    components/ui_comp_hook.c
    ui_helpers.c
    ui_events.c
    images/ui_img_e9879a1565935453499d015faae62da8_png.c)

add_library(ui ${SOURCES})
