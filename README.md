# Sample is work in progress

## MT3620 Drivers

[MediaTek MT3620 M4 Driver & Real-Time Application Sample Code](https://github.com/MediaTek-Labs/mt3620_m4_software)

## Azure ThreadX

ThreadX version 6.0.1

## Debugging

Note there is a wait loop for degugger attach.

1. demo_threadx.c -> function: thread_3_and_4_entry

## Exceptions

Exception thrown at:

* Line 277:      status = tx_semaphore_get(&semaphore_0, TX_WAIT_FOREVER);