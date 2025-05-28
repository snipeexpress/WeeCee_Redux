<!-- markdownlint-disable MD031 -->

# WeeCee Redux

**WeeCee Redux** is a hardware clone of Rasteri’s **WeeCee v0.3**, enhanced with a variety of improvements for modern usability, better component choices, and more robust design.

## 🔧 Key Improvements

1. **HIDman Integration**  
   
   Replaced the legacy PS/2 port with [HIDman](https://github.com/Rasteri/HIDman), enabling support for modern USB HID devices via USB-to-PS/2 translation.

2. **Improved Audio Circuitry**  
   
   Refined the CS4237B circuitry for enhanced signal filtering and improved ground plane separation for cleaner audio performance.

3. **USB-C Power + On/Off Controller**  
   
   Replaced the micro-USB power input with USB-C. Integrated a **MAX16054** on/off controller for reliable power switching.

4. **On-Board PC Speaker**  
   
   Added a miniature PC speaker directly on the board. Can be disabled via jumper if not needed.

5. **Cost-Optimized Connectors**  
   
   Swapped out the MicroSD and audio output connectors for more affordable variants — the same ones used on Eivind Bøhler’s [TinyLlama](https://github.com/eivindbohler/TinyLlama).

6. **Enhanced Front Panel**  
   
   - Added a power button header for direct connection  
   - Added a reset button  
   - Added a power LED to indicate system status

7. **SD Card Activity Indicator**  
   
   Included circuitry and a front-panel LED to show real-time SD card activity.

8. **RTC Battery Support**  
   
   Added support for a **CR1220** coin cell battery to maintain Real-Time Clock settings.

## 📦 Enclosure Notes

This revision still fits the original enclosure used in Rasteri’s WeeCee v0.3. However, due to the added ports and indicators, **updated front and rear panels are required** for proper alignment.
