idf_component_register(
  SRCS "multi_button.c" "button_bsp.c"
  PRIV_REQUIRES esp_timer esp_driver_gpio main
  INCLUDE_DIRS "./")
