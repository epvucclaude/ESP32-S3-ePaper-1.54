idf_component_register(
  SRCS "i2c_bsp.c"
  PRIV_REQUIRES main esp_driver_i2c
  INCLUDE_DIRS "./")
