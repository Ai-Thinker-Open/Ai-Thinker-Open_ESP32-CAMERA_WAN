idf_component_register(SRCS ./fp_acl_esp32_nvs.c ./main.c ./unabto_application.c ./app_smart_wifi
                       INCLUDE_DIRS "." "../unabto/src" "../components/unabto-esp-idf" "../components/nabtotunnel" "../unabto/src/modules/log"
                       REQUIRES )

