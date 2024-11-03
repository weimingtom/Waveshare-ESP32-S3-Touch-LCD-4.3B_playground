# Waveshare-ESP32-S3-Touch-LCD-4.3B_playground
[WIP] My Waveshare-ESP32-S3-Touch-LCD-4.3B playground

## lvgl_Porting_fiv_pic  
* Need esp-idf 5.3, esp-idf-tools-setup-offline-5.3.exe    
* Show five pictures and switch them by touching  
* core code:  
https://github.com/weimingtom/Waveshare-ESP32-S3-Touch-LCD-4.3B_playground/blob/master/lvgl_Porting_five_pic/main/rgb_lcd_example_main.c   

## Ref  
* https://www.waveshare.net/wiki/ESP32-S3-Touch-LCD-4.3B  
* (main ref code) https://www.waveshare.net/wiki/ESP32-S3-Touch-LCD-4.3  

## SquareLine 1.4.2 project  
* see lvgl_Porting_five_pic/vendor/hello1_v2.7z  

## Extend code section (for ESP32-S3 N16R8 16M Flash size)      
* see lvgl_Porting_five_pic/partitions.csv
* see lvgl_Porting_five_pic/sdkconfig
```
#
# Partition Table
#
# CONFIG_PARTITION_TABLE_SINGLE_APP is not set
# CONFIG_PARTITION_TABLE_SINGLE_APP_LARGE is not set
# CONFIG_PARTITION_TABLE_TWO_OTA is not set
CONFIG_PARTITION_TABLE_CUSTOM=y
CONFIG_PARTITION_TABLE_CUSTOM_FILENAME="partitions.csv"
CONFIG_PARTITION_TABLE_FILENAME="partitions.csv"
CONFIG_PARTITION_TABLE_OFFSET=0x8000
CONFIG_PARTITION_TABLE_MD5=y
# end of Partition Table
```
