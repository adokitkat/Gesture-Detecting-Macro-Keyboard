
idf_component_register(
    SRCS main.c
        tf_gesture_predictor.cc
        gesture_model_tflite.cc
        touchpad_sensor.cc
        ble_hid.c
        keymap_config.c
        display.c
        keypress_input.c
        crypto.c
        menu.c<
        key_backlight.c
    INCLUDE_DIRS "include"
    #REQUIRES freertos nvs_flash driver esp_http_client
    #        esp_hid led_strip tfmicro Trill-esp-idf u8g2
    )
