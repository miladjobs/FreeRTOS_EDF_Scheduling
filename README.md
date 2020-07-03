# FreeRTOS EDF Scheduling

FreeRTOS with EDF algorithm scheduling

# Requirements
  - ```$ sudo apt install libc6-dev-i386```
  
# Compile And Run
  - ```$ make```
  - ```$ ./FreeRTOS-Sim```

# Run without EDF
  - ```$ make clean```
  - set ```configUSE_EDF_SCHEDULER = 0``` in FreeRTOSConfig.h
  - ```$ make```
  - ```$ ./FreeRTOS-Sim```
