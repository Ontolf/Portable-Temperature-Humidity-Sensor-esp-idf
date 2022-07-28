idf_component_register(SRCS "temperature_monitor.c" 
                            "../components/sensors/DHT_c.c"
                    INCLUDE_DIRS "."
                    SRC_DIRS "./" "../components/display" "../components/sensors")
