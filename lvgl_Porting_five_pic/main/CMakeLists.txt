idf_component_register(SRCS "rgb_lcd_example_main.c" "lvgl_demo_ui.c"
	export/screens/ui_Screen1.c
    export/ui.c
    export/components/ui_comp_hook.c
    export/ui_helpers.c
    export/images/ui_img_pic001_png.c
    export/images/ui_img_pic002_png.c
    export/images/ui_img_pic003_png.c
    export/images/ui_img_pic004_png.c
    export/images/ui_img_pic005_png.c
                       INCLUDE_DIRS "." "./export")
