idf_build_get_property(target IDF_TARGET)

idf_component_register(SRCS "main.c" 
                    INCLUDE_DIRS "include"
                    REQUIRES esp_driver_i2c esp_driver_gpio)
