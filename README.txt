commit a71542fc60cf5aa34cd4c4e74d352d58a60173e3 (HEAD -> master, origin/master, origin/HEAD)
Author: Josef Schlehofer <pepe.schlehofer@gmail.com>
Date:   Tue Dec 28 23:43:57 2021 +0100

    kernel: add kmod-usb-net-lan78xx
    
    Add kernel module for Microchip LAN78XX based USB 2 & USB 3
    10/100/1000 Ethernet adapters. [1]
    
    This kernel module is required for the Seeed Studio's Mini Router
    based on RPI CM4 [2].
    
    [1] <https://cateee.net/lkddb/web-lkddb/USB_LAN78XX.html>
    [2] <https://www.seeedstudio.com/Dual-GbE-Carrier-Board-with-4GB-RAM-32GB-eMMC-RPi-CM4-Case-p-5029.html>
    
    Signed-off-by: Josef Schlehofer <pepe.schlehofer@gmail.com>
    (added kmod-phy-microchip and kmod-fixed-phy dependencies,
    rpi3 needs lan78xx but has it built-in)
    Signed-off-by: Christian Lamparter <chunkeey@gmail.com>
