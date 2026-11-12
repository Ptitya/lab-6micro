idf_component_register(SRCS "main.c"
                       INCLUDE_DIRS "."
                       REQUIRES driver dht11 lcd_hd44780 ultrasonic esp_timer)