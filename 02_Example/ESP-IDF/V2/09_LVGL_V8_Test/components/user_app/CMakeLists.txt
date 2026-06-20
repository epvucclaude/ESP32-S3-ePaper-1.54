idf_component_register(
  SRCS "user_app.cpp"
  PRIV_REQUIRES
  board_power_bsp
  esp_driver_gpio
  main
  ui_bsp
  button_bsp
  REQUIRES
  epaper_driver_bsp
  INCLUDE_DIRS ".")
