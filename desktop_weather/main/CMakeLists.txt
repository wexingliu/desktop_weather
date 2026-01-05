idf_component_register(
    SRCS
        "spi_lcd_touch_example_main.c"
        "lvgl_demo_ui.c"
        "myi2c.c"
        "gxhtc3.c"
        "font_alipuhui.c"
        "font_led.c"
        "font_myawesome.c"
        "font_qweather.c"
        "image_taikong.c"
    INCLUDE_DIRS "."
    EMBED_TXTFILES "devapi_qweather_chain.pem"
)
