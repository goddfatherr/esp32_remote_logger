idf_component_register(SRCS "logger.c"
                    INCLUDE_DIRS "."
                    REQUIRES "protocol_examples_common" "esp_event" "nvs_flash" "log" "esp_system" "esp_netif" "esp_wifi" "esp_eth" "esp_http_server" )

# set_target_properties(${COMPONENT_LIB} PROPERTIES COMPILE_FLAGS -Wno-maybe-uninitialized)