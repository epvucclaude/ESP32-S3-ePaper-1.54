idf_component_register(
  SRCS "epaper_driver_bsp.cpp"
  REQUIRES
  esp_driver_spi
  esp_driver_gpio
  INCLUDE_DIRS "./")
