idf_component_register(
  SRCS "user_app.cpp"
  PRIV_REQUIRES
  port_bsp
  ui
  esp_driver_gpio
  my_button
  codec_board
  waveshare__pcf85063a
  REQUIRES
  INCLUDE_DIRS ".")
