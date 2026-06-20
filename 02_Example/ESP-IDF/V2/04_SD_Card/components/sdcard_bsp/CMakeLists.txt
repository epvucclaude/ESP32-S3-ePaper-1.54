idf_component_register(
  SRCS "sdcard_bsp.c"
  PRIV_REQUIRES fatfs sdmmc esp_driver_sdmmc esp_driver_gpio
  INCLUDE_DIRS "./")
#REQUIRES fatfs
#PRIV_REQUIRES