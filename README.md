## Adroid

<a href="https://github.com/chradev/Adroid" target="_blank">Adroid</a> is proposed as an open S.T.E.A.M. platform and a process for building educational aids like robots following the Open Source movement in all its aspects, including but not limited to the ideas, algorithms, internal and external design, mechanical, electronic, and software staff. It is intended to include latest science, technology, and art achievements with a special respect to ***"Learn by Doing"*** and ***"Teach by Learning"*** principles, appropriate for any person's age, interests, and profession.

<img src="https://github.com/chradev/Adroid/blob/main/assets/configs/ProtoDesk-07.png?raw=true" width="100%" align="center" alt="Adroid robots" title="&shy;&#8197;       the Small, the Tall, the Wide, the Smart &#013;      Малкият, Високият, Широкият, Умният &#013;(Дребосъкът, Дангалакът, Дебелакът, Добрякът)">

#### <p align=center>Adroid the project is all about "Learn by Doing" and "Teach by Learning",<br>which aim to perfect your brain and hands using the latest science, technology, and art achievements.</p>

Adroid is not only a platform but it is also a continuous process intended to accumulate all gained knowledge and experience by all participants in S.T.E.A.M. the educational processes using it. A special relational multi-dimensional knowledge base and tools will be created and updated continuously to help the learning and teaching processes. On the other hand Adroid can be used by artists, scientists and engineers to reach better results faster.

## "Learn by Doing" and "Teach by Learning"

The Open S.T.E.A.M. is an idea directly related to a platform for multidisciplinary projects in scope, with the only possible process being the learning through the active participation of the parties in their implementation. In this line of thought, the parties targeted in the process are equal in terms of rights and obligations, with often changing roles as students and teachers.

Therefore, the following topics are outlined in the Adroid project as a beginning:

* Development of AI based "Learn by Doing" S.T.E.A.M. process, knowledge base and instrumentation,
* Speech synthesis and recognition for human like communicating robots optionally based on AI,
* Emotional behavior through animation on the built-in robot display optionally based on AI,
* Active Ball Joint Mechanism incl. 3D absolute positioning system for head movement,
* Distributed, multi-process/thread/core control system based on uROS and ROS 2,
* Advanced stereo and panorama robot vision system with low latency and ePTZ,
* Body transformation based on a set of strength and positioning sensors,
* Development of liquid multi-color jet system for painting robots,
* Migration from RP2040 to RP2350A(B) MCUs etc.

The above list will be updated continuously, so any new ideas are welcome.


## How easy is it to use AI?

#### It is easy to use Raspberry Pi AI Kit (HAILO 8L - 13 TOPS) on Raspberry Pi 5!

Some tests were made to use the Raspberry Pi AI Kit (HAILO 8L - 13 TOPS) on Raspberry Pi 5 16GB with Debian 13 (Trixie) desktop distribution and Linux kernel ver. 6.12.47. AI Kit's M.2 module and 512GB NVMe SSD were mounted on WaveShare PCIe to 2-CHANNEL M.2 HAT+ for Raspberry Pi 5. Arducam 16MP IMX519 autofocus camera was connected to the first CSI interface, and appropriate software (libcamera2, OpenCV etc.) was installed and tested to work. A series of performance tests were also made, and a better Geekbench CPU score was found for Raspberry Pi 5 Model B Rev 1.1 vs. Rev 1.0 ([2091/891](https://browser.geekbench.com/v6/cpu/15497913) vs. [1629/793](https://browser.geekbench.com/v6/cpu/5636316)).

Appropriate software and AI demo examples for the Raspberry Pi AI Kit (HAILO 8L - 13 TOPS) are installed and tested to work.

<table style="width: 100%; height: 100%; margins: 0; padding: 0;">
  <tr style="margins: 0; padding: 0;">
    <td style="width: 20%; height: 100%; margins: 0; padding: 0;">
      <img src="https://www.radevs.net/chradev/Adroid/images/photo_2025-12-12_09-09-43.jpg"></td>
    <td style="width: 20%; height: 100%; margins: 0; padding: 0;">
      <img src="https://www.radevs.net/chradev/Adroid/images/2025-12-12_03%3A24%3A06.png"></td>
    <td style="width: 30%; height: 100%; margins: 0; padding: 0;">
      <img src="https://www.radevs.net/chradev/Adroid/images/2025-12-12_03%3A26%3A35-m.png"></td>
    <td style="width: 30%; height: 100%; margins: 0; padding: 0;">
      <img src="https://www.radevs.net/chradev/Adroid/images/2025-12-12_03:35:39-m.png"></td>
  </tr>
</table>

It is worth noting that when using the Raspberry Pi AI Kit (HAILO 8L - 13 TOPS), the CPU load (16% total and 11.5% for the AI application) and memory usage (1.34 GB total and 233 MB for the AI application) of the Raspberry Pi 5 are negligible. On the other hand, video captured by the Arducam 16MP IMX519 autofocus camera was processed by the Raspberry Pi AI Kit (HAILO 8L - 13 TOPS) with the same frame rate and with a lot of objects analyzed.

#### It is easy to use Raspberry Pi AI Camera – IMX500 12MP on Raspberry Pi 5!

The Raspberry Pi 12MP AI Camera (IMX500) module was installed on the second CSI interface of the same Raspberry Pi 5 16GB, appropriate configuration was set and it was tested to work. After installing of required software AI functionality was tested.

<table style="width: 100%; height: 100%; margins: 0; padding: 0;">
  <tr style="margins: 0; padding: 0;">
    <td style="width: 19%; height: 100%; margins: 0; padding: 0;">
      <img src="https://www.radevs.net/chradev/Adroid/images/photo_2025-12-13_16-03-57.jpg"></td>
    <td style="width: 15.4%; height: 100%; margins: 0; padding: 0;">
      <img src="https://www.radevs.net/chradev/Adroid/images/2025-12-13_15%3A26%3A41-m.png"></td>
    <td style="width: 24%; height: 100%; margins: 0; padding: 0;">
      <img width="100%" src="https://www.radevs.net/chradev/Adroid/images/2025-12-13_15%3A49%3A34-m.png"></td>
    <td style="width: 24%; height: 100%; margins: 0; padding: 0;">
      <img width="100%" src="https://www.radevs.net/chradev/Adroid/images/2025-12-13_15%3A56%3A26-m.png"></td>
  </tr>
</table>

#### AI solutions comparison

Later on both Raspberry Pi AI Camera – IMX500 12MP and Raspberry Pi AI Kit (HAILO 8L - 13 TOPS) with Arducam 16MP IMX519 autofocus camera were tested to work together on Raspberry Pi 5 16GB.

<table style="width: 100%; height: 100%; margins: 0; padding: 0;">
  <tr style="margins: 0; padding: 0;">
    <td style="width: 8.5%; height: 100%; margins: 0; padding: 0;">
      <img src="https://www.radevs.net/chradev/Adroid/images/RPi-AI-Camera.png"></td>
    <td style="width: 18%; height: 100%; margins: 0; padding: 0;">
      <img src="https://www.radevs.net/chradev/Adroid/images/ai-haili-8L.png"></td>
    <td style="width: 19.5%; height: 100%; margins: 0; padding: 0;">
      <img src="https://www.radevs.net/chradev/Adroid/images/imx500-comparison.png"></td>
    <td style="width: 31%; height: 100%; margins: 0; padding: 0;">
      <img src="https://www.radevs.net/chradev/Adroid/images/2025-12-13_17%3A03%3A52-m.png"></td>
  </tr>
</table>

Measured total CPU load was 26% (2.5% and 10.4%, respectively), and total memory usage was 10% or 1.58 GB (316 MB and 230 MB, respectively). As a result of comparison, it can be noted that the RPi AI camera solution is 30% cheaper (84.36 € vs. 85.90 € + 33.75 €) and uses fewer CPU resources (2.5% vs. 10%), but using a standard RPi camera with a HAILO 8L AI accelerator is a more powerful and unified solution.

#### Comparison of AI solutions from different manufacturors

<img style="width: 100%;" src="https://www.radevs.net/chradev/Adroid/images/AI-Comparison-Table-2.png">

**Note:** Prices are from <a href="https://erelement.com/" target="_blank">Erelement Bg - Electronics and robotics</a>.


## Adroid robots comparison tables

#### Adroid robot variants

<table style="overflow-y: hidden; width: 100%;height: 100%;font-size:0.9em;text-align: center; border:1px; border-collapse: collapse;">
<thead>
<tr >
    <th width="10%" style="text-align: center;" > Adroid robot <br> variant / feature </th>
    <th width="18%" style="text-align: center;"> <img src="https://github.com/chradev/Adroid/blob/main/assets/theSmall.png?raw=true" width="auto" height="240px" ></th>
    <th width="18%" style="text-align: center;"> <img src="https://github.com/chradev/Adroid/blob/main/assets/theTall.png?raw=true" width="auto" height="240px" ></th>
    <th width="18%" style="text-align: center;"> <img src="https://github.com/chradev/Adroid/blob/main/assets/theWide-02.png?raw=true" width="auto" height="240px" ></th>
    <th width="18%" style="text-align: center;"> <img src="https://github.com/chradev/Adroid/blob/main/assets/theSmart-07.png?raw=true" width="auto" height="240px" ></th></tr>
</thead><tbody>
<tr >
    <td style="text-align: end;"> Pricing </td>
    <td style="text-align: center;"> Low budget variant </td>
    <td style="text-align: center;" colspan="2" style="text-align: center;"> Advanced variants </td>
    <td style="text-align: center;">Variant with built-in AI acceleration</td></tr>
<tr style="background-color: #fcfccc;">
    <td style="text-align: end;" > Main computer hardware </td>
    <td style="text-align: center;" > Seeed Studio XIAO ESP32S3 Sense module </td>
    <td style="text-align: center;" colspan="2" > RPi 5 4/8/16GB RAM SBC, active cooling, Gen 2/3 PCIe to 2x M.2 hat, up to 2x NVMe SSD, Hailo 8/8L or other AI M.2 accelerator module (optional) </td>
    <td style="text-align: center;" >Nvidia Jetson (Orin) Nano Dev Kit, Gen 3 NVMe SSD</td></tr>
<tr >
    <td style="text-align: end;" > Main computer software </td>
    <td style="text-align: center;" > Free RTOS, C/C++ </td>
    <td style="text-align: center;" colspan="3" > Linux, C/C++, Python, JavaScript </td></tr>
<tr style="background-color: #fcfccc;">
    <td style="text-align: end;" > Dispaly devices </td>
    <td style="text-align: center;" > 3.2" TFT SPI or 4-5" TFT HDMI display and RPi Pico module </td>
    <td style="text-align: center;" colspan="2" > 5-7" TFT HDMI display or multimedia projector </td>
    <td style="text-align: center;" > 7" TFT DisplayPort display or multimedia projector </td></tr>
<tr >
    <td style="text-align: end;" > Auxiliary computer hardware </td>
    <td style="text-align: center;" colspan="4" > RPi Pico module </td></tr>
<tr style="background-color: #fcfccc;">
    <td style="text-align: end;" > Auxiliary computer software </td>
    <td style="text-align: center;" colspan="4" > C/C++, RPi Pico multicore and PIO features </td></tr>
<tr >
    <td style="text-align: end;" > Vision hardware </td>
    <td style="text-align: center;" > 1-2x Seeed Studio XIAO ESP32S3 Sense module with 2&nbsp;MP OV2640 SPI camera </td>
    <td style="text-align: center;" colspan="3" > 1-8x RPi or Arducam 8, 16 or 64 MP CSI cameras connected to RPi&nbsp;5 directly or via Arducam CamArray Hat, RPi AI cameras (optional) </td></tr>
<tr style="background-color: #fcfccc;">
    <td style="text-align: end;" > Vision software </td>
    <td style="text-align: center;" > Free RTOS, C/C++ and WS based MJPEG streaming </td>
    <td style="text-align: center;" colspan="3" > Linux, C/C++, Python, WS based h264 streaming server </td></tr>
<tr >
    <td style="text-align: end;" > Sound system </td>
    <td style="text-align: center;" > External sound card and built-in camera microphones </td>
    <td style="text-align: center;" colspan="2" > Speakers connected to HDMI display or I2S and microphones controlled by RPi 5 </td>
    <td style="text-align: center;" >I2S, sound amplifier and speakers</td></tr>
<tr style="background-color: #fcfccc;">
    <td style="text-align: end;" > Vision PTZ and head control </td>
    <td style="text-align: center;" >  Auxiliary computer with 1-2x geared stepper motors and position sensors </td>
    <td style="text-align: center;" colspan="3" > Auxiliary computer with 1-4x geared stepper motors, optional active ball joint mechanism, 3D position sensors and ePTZ based on camera control </td></tr>
<tr >
    <td style="text-align: end;" > Body slope control </td>
    <td style="text-align: center;" colspan="4" >  Auxiliary computer with 1-2x geared stepper motors and strength and position sensors </td></tr>
<tr style="background-color: #fcfccc;">
    <td style="text-align: end;" > Main movement control </td>
    <td style="text-align: center;" colspan="4" >  Auxiliary computer with 2x stepper motors and distance, line following, edge etc. sensors </td></tr>
<tr >
    <td style="text-align: end;" > Painting system </td>
    <td style="text-align: center;" > Single pen system </td>
    <td style="text-align: center;" colspan="3" > Multiple-pen or liquid multicolor jet system </td></tr>
<tr style="background-color: #fcfccc;">
    <td style="text-align: end;" > Power consumption </td>
    <td style="text-align: center;" > 10W max; 2S LiPo battery</td>
    <td style="text-align: center;" > 15W max; 2S LiPo battery</td>
    <td style="text-align: center;" colspan="2" > 25W max; 3S LiPo battery</td></tr>
<tr style="background-color: #fcfccc;">
    <td style="text-align: end;" > Power control </td>
    <td style="text-align: center;" colspan="4" > Wireless charger and UPS like power control </td></tr>
</tbody></table>

#### Adroid robot main computer variants

<table style="overflow-y: hidden; width: 100%;font-size:0.9em;text-align: center; border:1px; border-collapse: collapse;">
<thead><tr >
<th width="10%" style="text-align: center;vertical-align: middle;" > Adroid robot <br> main computer <br> variant / feature </th>
<th width="18%" style="text-align: center;vertical-align: top;"> Seeed Studio XIAO ESP32S3 <br> (Multiply MCUs & FreeRTOS) <br>
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/XIAO-ESP32-S3_1.jpg?raw=true" width="100%" height="auto" > <br> 
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/xiaoesp32s3sense.jpg?raw=true" width="100%" height="auto" > <br>
                                             2x Seeed Studio XIAO ESP32S3 Sense with OV2640 SPI camera and microphone<br> 
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/rp2040-zero.jpg?raw=true" width="48%"height="auto" >
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/3.2tftspiDisplay.jpg?raw=true" width="48%"height="auto" > <br>
                                             RP2040-Zero and 3.2" TFT 320x240 SPI  built-in display (simple option)<br>
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/rp2040-zero.jpg?raw=true" width="48%"height="auto" >
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/ips-lcd-5-touch-h.jpg?raw=true" width="48%"height="auto" > <br>
                                             RP2040-Zero and 5" TFT 800/480 HDMI  built-in display (advanced option)<br>
                                             </th>
<th width="18%" style="text-align: center;vertical-align: top;"> Raspberry Pi Zero 2 W <br> (Single SBC & Linux) <br>
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/raspberry-pi-zero-2-w.jpg?raw=true" width="100%" height="auto" > <br> 
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/eth-usb-hub-hat.jpg?raw=true" width="100%" height="auto" <br>
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/usb3-sd-card-reader.jpg?raw=true" width="100%"height="auto" >  <br>
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/B016601-1.jpg?raw=true" width="58%" height="auto" > 
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/RaspberryPi_8MP_CAM_V2.jpg?raw=true" width="38%" height="auto" > <br>
                                             Stereo Camera Module V2 and 2x 5/8/12MP RPi cameras  (different options) <br>
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/ips-lcd-5-touch-h.jpg?raw=true" width="48%"height="auto" >
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/ips-lcd-7-touch-h.jpg?raw=true" width="48%"height="auto" > <br>
                                             5" / 7" HDMI built-in display (different options)
                                             </th>
<th width="18%" style="text-align: center;vertical-align: top;"> Raspberry Pi 5 4/8/16GB RAM <br> (Single SBC & Linux) <br>
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/RPi_5_active_cooler-700x700.jpg?raw=true" width="100%" height="auto" > <br>
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/pcie-to-2-ch-m2-hat-plus.webp?raw=true" width="48%"height="auto" > 
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/sk-nvme-2242-256g-ssd-m2.png?raw=true" width="48%"height="auto" > <br>
                                             Gen 2/3 PCIe to 2x M.2 hat with NVMe SSD and AI accelerator <br>
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/pi5-imx219-camera.webp?raw=true" width="31%"height="auto" >
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/camera-imx519.webp?raw=true" width="31%"height="auto" >
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/RPi-AI-Camera.png?raw=true" width="31%"height="auto" > <br>
                                             up to 2x 8/16/64MP or AI RPi cammeras (different options) <br>
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/ArducamMultiCaneraSolution.jpg?raw=true" width="98%"height="auto" > <br>
                                             up to 2x Synchronized Quad-Camera hats with up to 8 cammeras <br>
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/ips-lcd-5-touch-h.jpg?raw=true" width="48%"height="auto" >
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/ips-lcd-7-touch-h.jpg?raw=true" width="48%"height="auto" > <br>
                                             5" / 7" HDMI built-in display (different options) <br>
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/UltraMiniProjector.webp?raw=true" width="59%" height="auto" >
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/HDMI-Monitor.jpg?raw=true" width="37%" height="auto" > <br>
                                             Pico Projector or Desktop Monitor (not includded)
                                            </th>
<th width="18%" style="text-align: center;vertical-align: top;"> Nvidia Jetson (Orin) Nano Dev Kit <br> (Single SBC & Linux) <br>
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/NvidiaJetsonOrinNano.png?raw=true" width="100%" height="auto" > <br>
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/pi5-imx219-camera.webp?raw=true" width="31%"height="auto" >
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/camera-imx519.webp?raw=true" width="31%"height="auto" >
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/SK-NVME-512G-SSD.jpg?raw=true" width="31%"height="auto" > <br>
                                             up to 2x 8/16/64MP or AI RPi cammeras (different options) <br>
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/NvidiaJetsonOrinNanoAdd-2.png?raw=true" width="100%" height="auto" > <br>
                                             up to 2x Synchronized Quad-Camera hats with up to 8 cammeras <br>
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/ips-lcd-5-touch-h.jpg?raw=true" width="48%"height="auto" >
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/ips-lcd-7-touch-h.jpg?raw=true" width="48%"height="auto" > <br>
                                             5" / 7" HDMI built-in display (different options) <br>
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/UltraMiniProjector.webp?raw=true" width="59%" height="auto" >
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/HDMI-Monitor.jpg?raw=true" width="37%" height="auto" > <br>
                                             Pico Projector or Desktop Monitor (not includded)
                                            </th>
</tr></thead><tbody>
<tr >
    <td style="text-align: end;"> Pricing </td>
    <td style="text-align: center;"> Low budget variant </td>
    <td style="text-align: center;"> Middle budget variant </td>
    <td colspan="2" style="text-align: center;"> Highly priced variant </td></tr>
<tr style="background-color: #fcfccc;">
    <td style="text-align: end;"> Rough BOM <br> [incl. VAT] </td>
    <td style="text-align: center;"> 100 &euro; </td>
    <td style="text-align: center;"> 225 &euro; (with 2x 8MP cameras and 5" display) </td>
    <td style="text-align: center;"> 350 &euro; (with 8GB RAM, 512 GB NVMe SSD, 2x 16MP cameras and 7" display)<br>+200 &euro; (add 3x 16MP cameras, Camarray Hat and Hailo 8L 13 TOPS AI accelerator) </td>
    <td style="text-align: center;"> 520 &euro; (Jetson Orin Nano Super with 512 GB NVMe SSD, 2x 16MP cameras and 7" display)<br>+130 &euro; (add 3x 16MP cameras, Camarray Hat) </td></tr>
<tr >
    <td style="text-align: end;vertical-align: top;"> Base features </td>
    <td style="text-align: center;vertical-align: top;"> XIAO ESP32S3 Module, ESP32-S3R8 MCU with 240 MHz Xtensa LX7 dual-core, 32-bit CPU, 8MB PSRAM, 8MB Flash, 2,4 GHz Wi-Fi (802.11 B/G/N), Bluetooth 5 (LE) & Bluetooth Mesh, 3.7V LiPo battery charger (up to 100mA), USB native, UART, I2C, SPI, I2S, ADC, GPIOs, 2x modules XIAO ESP32S3 Sense with OV2640 camera and microphone, RP2040-Zero module and 3.2" TFT 320x240 SPI display </td>
    <td style="text-align: center;vertical-align: top;"> RPi Zero 2 W SBC, RP3A0 SoP (custom-built system-in-package with 1GHz quad-core 64-bit ARM Cortex-A53 CPU), 512MB of SDRAM, Wi-Fi 802.11.b/g/n, Bluetooth 4.2/BLE, I2C, SPI, UART, I2S, CSI, GPIOs, USB HUB / 100MB Ethernet HAT for Raspberry Pi Zero, SD card reader and fast SD card, Stereo Camera Module V2 and 2x 8MP RPi Camera V2, 5" 800x480 HDMI display with capacity USB Touch screen and audio output </td>
    <td style="text-align: center;vertical-align: top;"> RPi 5 4/8/16GB RAM SBC, Broadcom BCM2712 2.4GHz quad-core 64-bit Arm Cortex-A76 CPU, with Cryptographic Extension, 512KB per-core L2 caches, and a 2MB shared L3 cache, VideoCore VII GPU, supporting OpenGL ES 3.1, Vulkan 1.2, Dual 4Kp60 HDMI display output with HDR support, 4Kp60 HEVC decoder, 8GB LPDDR4X-4267 SDRAM, Dual-band 802.11ac Wi-Fi, Bluetooth 5.0 / Bluetooth Low Energy (BLE),  microSD card slot, with support for high-speed SDR104 mode, 2x USB 3.0 ports, supporting simultaneous 5Gbps operation, 2x USB 2.0 ports,  Gigabit Ethernet, 2x micro-HDMI ports supporting 4kp60 with HDR, 2x 4-lane MIPI camera/display transceivers,  PCIe 2.0 x1 interface for fast peripherals, PCIe to 2-CHANNEL M.2 HAT for RPi 5, 256GB M.2 NVME 2242 high-speed SSD with high-quality 3D TLC flash memory, I2C, SPI, UART, I2S, GPIOs, RPi 5 Active Cooler, 2x 16MP RPi IMX519 Camera with autofocus, 7" 1024x600 IPS HDMI display with capacity USB Touch screen and audio output </td>
    <td style="text-align: center;vertical-align: top;">Jetson Orin Nano 8GB System-On-Module (SOM): AI Performance: 67 INT8 TOPS; GPU: NVIDIA Ampere architecture with 1024 CUDA cores and 32 tensor cores; CPU: 6-core Arm® Cortex®-A78AE v8.2 64-bit CPU 1.5MB L2 + 4MB L3; RAM: 8GB 128-bit LPDDR5 102GB/s; Support for external NVMe; Power: 7 W – 25 W<br>Carrier Board: 4 x USB 3.2 Gen2 Type-A; 1 x USB-C; 1 x Gigabit Ethernet; Video output: DisplayPort 1.2 (no HDMI port); 2 x MIPI CSI connectors for cameras; 40-pin GPIO connector (I2C, SPI, UART, PWM и др.); M.2 Key M slot for NVMe SSD (no NVME modul); M.2 Key E slot for Wi-Fi / Bluetooth module (WiFi modul mounted); microSD slot for microSD card; DC power jack</td></tr>
<tr style="background-color: #fcfccc;">
    <td style="text-align: end;"> Dimensions </td>
    <td style="text-align: center;"> 21 x 17,5 mm </td>
    <td style="text-align: center;"> 65 x 30 mm </td>
    <td style="text-align: center;"> 85 x 56 mm </td>
    <td style="text-align: center;"> 91 x 103 mm </td></tr>
</tbody></table>

#### Adroid robot commom staff

<table style="overflow-y: hidden; width: 100%;font-size:0.9em;text-align: center; border:1px; border-collapse: collapse;">
<thead><tr >
<th width="43%" style="text-align: center;vertical-align: top;"> Powering system <br><br>
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/WirelessRobotCharger.png?raw=true" width="100%" height="auto" > <br>
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/ups-module-2s-2.png?raw=true" width="48%"height="auto" >
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/ups-module-3s-2.png?raw=true" width="48%"height="auto" >
                                             </th>
<th width="27%" style="text-align: center;vertical-align: top;"> Main movement system <br><br>
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/001.png?raw=true" width="100%" height="auto" > <br>
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/2-StepMotorControl.png?raw=true" width="100%" height="auto" >
                                             </th>
<th width="30%" style="text-align: center;vertical-align: top;"> Auxiliary movement systems <br><br>
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/002.png?raw=true" width="100%" height="auto" > <br>
                                             <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/4-StepMotorControl.png?raw=true" width="100%" height="auto" >
                                             </th>
</tr><tr>
<td>
    <img src="https://github.com/chradev/Adroid/blob/main/assets/configs/RP2350-Stamp-and-Stamp-XL-02.png?raw=true" width="100%" height="auto" >
</td>
<td colspan="2" style="vertical-align: middle;">
The new RP2350 series of MCUs from Raspberry is now available, and migrations from previous MCUs like RP2040 is an option for Adroid robot common staff.
<br><br>
Significant advantages in the new generation of MCUs are:
<ul>
  <li>dual-core architecture with 150MHz Cortex-M33 or Hazard3 RISC-V cores;</li>
  <li>bigger internal RAM (520KB of SRAM) and 2 MB internal flash (in RP2354);</li>
  <li>up to 16 MB of external QSPI flash/PSRAM via dedicated QSPI bus;</li>
  <li>a special High Speed Transmit (HSTX) peripheral that drives 4 lanes of differential data transmission to DVI output;</li>
  <li>12x PIO state machines - 3x PIO blocks with 4 state machines each;</li>
  <li>more GPIOs (up to 48 in QFN-80 package), peripherals, security options etc.</li>
</ul>
</td>
</tr></thead></table>

## Leading principles and selection criteria

#### The core principle is ***OPENNESS***, as defined in the "Open Source" movement and expanded upon later:

The "open source way" is based on key principles of open exchange, collaborative participation, rapid prototyping, transparency, meritocracy, and community-oriented development. In the beginning, the "open source" referred to computer programs in which the source code is available to the general public for use or modification of the original design. Later on, this way of thinking spread to almost all aspects of human life and was also recognized by the businesses. Computer hardware, electronic, mechanical, etc. designs, the works of art, the musical compositions and their performances, and many others were also influenced. Finally, ***OPENNESS*** became the only real answer to the madness of globalization.

#### Another leading principles are:

* "Keep it as simple as possible" is essential for achieving the best results in the most effective way.
* Collaboration and communication are mandatory for the effective implementation of the training as the main goal.
* To work alone and as a teammate, to give and receive, to understand and explain at the same time, is essential in any case.
* Intensive use of the third-party expertise makes everyone a better expert, so use what others have already done to the maximum.
* The best way to constantly develop yourself is by using your own mind and hands to make improvements to what has already been achieved.

#### The selection of the hardware and software suitable for the project is based on the following criteria:

* Professional, technical and technological grade - the best products in their field are preferred.
* Accessibility, longevity, popularity and costs - the priority of the listed criteria is in descending order.
* Size and professionalism of the supporting community - a bigger and more responsive community of professionals is preferable.
* Openness and depth of the hardware and software support - open source software is a must, while it is good to have for the hardware.

Assessment of the products is based on a wide investigation, own tests and precise analysis. The test results are public and a subject of discussion. If significant flaws are discovered in the choice made, it will be subject to re-evaluation. When new products with better qualities appear, they can be recognized as alternative options.

#### List of the selected technologies and techniques for overall design and production:

* Laser-cut plastic materials, custom or prototyping PCBs for the supporting flat mechanical details and electronic components.
* 3D printing of unified mechanical details using appropriate materials like ABS, PLA, PETG, nylon, rubber, resin, etc.
* Manual drilling and screwing of the mechanical details and fastening with spacers of the electronic components.
* Using of bolts, screws, and nuts for joining all mechanical details and electronic components together.
* Soldering, crimping and interconnecting with cables and connectors of the electronic components.

In the development and testing phases, additional connections to external equipment such as power supplies, Ethernet hubs, Internet routers, monitors, keyboards, mice, etc. may be desired, which may require specific knowledge and skills. Some advanced skills like measuring with multimeter, oscilloscope, analyzer etc. may be needed when certain problems occur.

Laser-cut and 3D-printed details require 2D and 3D CAD/CAM design skills. The design and ordering for the fabrication of PCBs require specific knowledge and skills. For the production of the details with laser cutting and 3D printing, specific equipment and skills to work with it are required.

#### Software development - the art of the Computer Sciences

* Software design requires a wide set of theoretical knowledge and practical skills.
* Programming and testing require the ability to use a wide variety of software products and tools.
* The languages chosen for development and software implementation are C/C++, JavaScript, and Python.
* The operating systems chosen for development and software implementation are FreeRTOS for MCU and Linux for SBC.
* The main software architecture chosen is a distributed, multi-process/thread/core system based on uROS and ROS 2.
* The main communication technology chosen are web sockets and the publish-subscribe model. 

## Next steps to be done

#### Electrical and mechanical issues

* Schematic of motor drivers for driving wheels motors like auxiliary geared stepper motors;
* Unification of the motor control based on RPi Pico PIO algorithm by Van Hunter Adams;
* Modifying of 3D printed driving wheels to use both O-rings and silicone/rubber tires like in Pololu wheels;
* Unification of sets of motor pairs for driving wheels, head and body movement, including appropriate sensors;
* Adding of distance, line following and edge sensors to the driving wheels' setup;
* Adding of a pair of hall sensors for head movement for controlling of end and middle positions;
* Change from a single to a pair of auxiliary geared stepper motors for body movement (two-arm model);
* Migration from free wheel ball bearing to nylon pulley with bearing for arms;
* Adding of a pair of hall and PCB made strain gauge sensors for body movement by arms;
* Development of a PCB with arm sensors, electronics and geared stepper motors driver;
* Selecting an appropriate communication interface for both the RPi Pico MCUs and the RPi 5 board;
* Development and prototyping of appropriate printed circuits boards;
* Revising of chosen PRi 5 UPS power supply module;
* Investigation of the possibility to use a liquid based true color printing system.

#### Software issues

* Splitting of algorithms for deeply embedded applications for dual-core RPi Pico MCUs;
* Integration of uROS and ROS 2 systems into RPi Pico and RPi 5 firmware;
* Defining of appropriate configuration and command infrastructure;
* Implementation of appropriate control algorithms and information structure;
* Development of interactive user interface based Web Sockets ;
* Development of a task based interface for high level robot control.

## More new ideas

#### Adding some measurment features

Adding one more RPI Pico board, a multichannel [***100 Msps Logic Analyzer***](https://github.com/gusmanb/logicanalyzer/tree/master) and/or [***500Ksps Digital Oscilloscope***](https://github.com/fhdm-dev/scoppy) can be embedded in Adroid hardware. A better performance in measurement can be reached by using RPi Pico 2 or some other board with better analog features. Logic Analyzer can be enhanced by adding [protocol analyzers](https://github.com/gusmanb/logicanalyzer/wiki/06---The-LogicAnalyzer-program#analyzing-protocols). All these features can be used for both development and learning purposes. 

<img src="https://github.com/chradev/Adroid/blob/main/assets/configs/LogicAnalyserFeature.png?raw=true" alt="RPi Pico Logic Analyzer" width="100%">

#### Use Active Ball Joint Mechanism for head movement

Using the idea of an active ball joint mechanism in combination with the motor control based on the RPi Pico PIO algorithm proposed by Van Hunter Adams will make head movement functionality extremely efficient.

<img src="https://github.com/chradev/Adroid/blob/main/assets/ActiveBeallJoint-2.png?raw=true" alt="Active Beall Joint Mechanism" width="100%">

The absolute positioning can be based on the measurement and the processing of the 3 spatial components of the magnetic flux density vector (i.e. BX, BY and BZ). Melexis has a long list of 2D and 3D sensing devices, like the one shown in the picture below.

<img src="https://github.com/chradev/Adroid/blob/main/assets/3dPositioningMelexis.png?raw=true" alt="Active Beall Joint Mechanism" width="100%">

#### Applying the Transformer's idea at body sloping

The ability to transform the robot from four-wheeled (2 driving and 2 auxiliary wheels) to two-wheeled balancing variant can be realized by adding auxiliary wheels to the robot arms. Some sensors, like an absolute positioning rotational sensor (360 degrees) and a strain gauge sensor to measure the reaction force, will help to enlarge precision of the body movement.

<img src="https://github.com/chradev/Adroid/blob/main/assets/TransformerIdea.png?raw=true" alt="Transformance Idea" width="100%">

#### Use alternative painting technology

Using an alternative to pen painting technology will give you the freedom to use multiple colors (cyan, magenta, yellow, black and white) and to paint on both black and white surfaces. The use of the CMYK color model will make it possible to paint even true color pictures. Different methods to atomize liquid paint, like air (airbrushes), ultrasonic, electrostatic, etc., can be assessed and/or tested to find the best painting solution for the Adroid robots.

<img src="https://github.com/chradev/Adroid/blob/main/assets/PintingRobot.png?raw=true" alt="Active Beall Joint Mechanism" width="100%">

#### Some alternatives it can be assessed and/or tested

Alternatives to be assessed and tested:

* Captain (rope) gear for body movement using two arms schematics
* Strain gauge sensor made as PCB including all electronic staff
* Absolute positioning rotational sensor (360 degree) for head and arms

<img src="https://github.com/chradev/Adroid/blob/main/assets/SameAlteratives.png?raw=true" alt="Same Alteratives" width="100%">

## First real prototypes

#### Mechanical design prototypes

Three real Adroid prototypes (the Small, the Tall and the Wide) are shown in the picture below. It was chosen to use NEMA 42HB34 stepper motors for the main robot movement and 28BYJ-48 geared stepper motors as auxiliary with ULN2003 drivers for body and head movement. The body movement is based on a single stepper motor, belt gear based on 16- and 60-tooth GT2 pulleys, and an arm with a pair of ball bearing free wheels on springs. Two of them (the Tall and the Wide) are running on their RPi 5 boards Linux OS and a dual camera streaming server with ePTZ control written on Python. The RPi 5 boards are powered by 3S Li-Po UPS modules. The head movement (pan only) of these two prototypes is based on a single auxiliary geared stepper motor. The Small Adroid prototype (low budget variant) contains three RPi Pico MCUs and ULN2003 drivers for stepper motor control, two MCUs with a 2 MP OV2640 SPI camera and microphone each, and one for the server staff based on the Seeed Studio XIAO ESP32S3 Sense modules. All these low consumption modules are extremely small (21mm x 17,5mm) and have 8MB RAM, 8MB of flash, 2.4GHz Wi-Fi, BLE 5.0, a wide set of interfaces, and can be programmed via their USB-C конектор.

<img src="https://github.com/chradev/Adroid/blob/main/assets/Prototypes-b.png?raw=true" alt="Prototypes" width="100%">

#### Some software staff developed and/or tested (short videos)

##### Head and body movement using geared stepper motors controled by RPi Pico PIO

Van Hunter Adams' algorithm for the RPi Pico PIO is downloaded, built and tested on the head and body movement auxiliary geared stepper motors in the Small Adroid prototype. For the building of the firmware, Linux OS on the RPi 5 board at the Wide Adroid prototype is used. The complete set of the RPi Pico C/C++ SDK and all the required libraries and tools to build and flash it on the target are also installed. The video shows synchronized body and head movements controlled by the RPi Pico PIO. The animation with 46.5 fps visible on the 3.2" TFT SPI display is generated on a separate overclocked at 250 MHz RPi Pico MCU using the TFT_eSPI library and transferred over SPI at 62.5 MHz.

[IMG_1380.webm](https://github.com/user-attachments/assets/fc1d304b-d6ce-423e-b7e3-0300df6fe03b)

##### Dual camera streaming server with ePTZ control

The next video is a compilation of a user interface based Web Sockets and remote terminals running corresponding server staff and shows the real time ePTZ control of both cameras. In addition, the almost real time video streaming and its low latency are observable thanks to embedded and synchronized clocks running at both server and user ends.

https://github.com/chradev/pi-h264-to-browser-streamer/assets/11261306/cbac77e0-3cdb-4b67-8a05-6e53c996912c

#### 3D printed unified details and wide mount variant with own wheel design

In the picture below is shown the second generation of 3D printed unified details, including own Pololu like driving wheel with two O-rings, hub and 60-tooth GT2 pulley. It is planned instead of a single motor with belt gear and a single arm with a pair of free ball bearing wheels for body movement to use a dual arm scheme with a directly coupled geared stepper motor, a nylon pulley with bearing, a PCB made strain gauge, and a pair of hall sensors for each arm. On the photo is shown a new prototype variant with two body movement auxiliary geared stepper motors;

<img src="https://github.com/chradev/Adroid/blob/main/assets/3D-Printing-Details-Gen4-Plus.png?raw=true" alt="3D Printing Details" width="100%">

#### Third party components

The components shown on the picture are before the second generation of 3D printed unified details and include Pololu wheels and belt geared body movement scheme staff.

<img src="https://github.com/chradev/Adroid/blob/main/assets/ThirdPartyStaff.png?raw=true" alt="Third Party Staff" width="100%">

#### Simulated design configurations

The simulation web application was developed in the very beginning and did not reflect later modifications made in prototyping process.

<img src="https://github.com/chradev/Adroid/blob/main/assets/AllDesignConfigurations.webp?raw=true" alt="All Design Configurations" width="100%">

### Related projects and links

Some of the links include staff from different projects, investigations and tests that could be used in the current development process.

 * [A simple web application to test different design configurations of STEAM robots](https://github.com/chradev/steam-robot-design-simulator)
 * [Dual camera, near-real-time, h.264 video streamer from RPi 5 to a bowser](https://github.com/chradev/pi-h264-to-browser-streamer)
 * [Own implementation of open source intelligent robot - startup design notes (PDF)](https://github.com/chradev/Adroid/blob/main/assets/pdfs/DesignNotes.pdf)
 * [Unified ILI9341 Graphic Test](https://github.com/chradev/Unified-ILI9341-Graphic-Test)
 * [Unified ili9340 Graphic Test plus](https://github.com/chradev/Unified_ili9340_Graphic_Test_plus)
 * [DrawWithDMA](https://github.com/chradev/DrawWithDMA)
 * [Unified Multicore Low Power IoT Platform (PDF)](https://github.com/chradev/Adroid/blob/main/assets/pdfs/Unified_Multicore_Low_Power_IoT_Platform.pdf)
 * Open S.T.E.A.M. initiative (PDFs): [En](https://github.com/chradev/Adroid/blob/main/assets/pdfs/OpenSTEAM.pdf), [Bg](https://github.com/chradev/Adroid/blob/main/assets/pdfs/OpenSTEAM_bg.pdf)
