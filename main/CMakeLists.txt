idf_component_register(SRCS "main.c"
                    PRIV_REQUIRES esp_wifi nvs_flash lwip esp_timer esp_netif esp_adc
                    INCLUDE_DIRS "")
