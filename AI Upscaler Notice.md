# Important
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
 - Check all of the main scripts for the AI Upscaler (in the Scripts folder).
 - Make sure "--tile" is set to "256".
 - Open Task Manager, run one of the scripts, and watch your GPUs VRAM
 - You want to keep at least 2-3gb freed at all times, otherwise you risk damaging your system over time, and causing errors like a BSOD
 - Keep raising the tile more until you reach your max
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Note
 - It is recommended to not go over "1920" for your tile number
 - 1920 will make a 1080p video render 1 full frame at a time
 - You can increase Worker Counts if your pc can handle it, this makes it render more frames at once
 - Setting the tile number to 0 will leave it uncapped (not good)
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Recommended Tile Numbers
 - **Low End**: 64, 128, 256
 - **High End**: 512, 796, 1080
 - **Maximum Recommended**: 1920
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Outscale
 - Outscaling is double what it actually says
 - A 2x outscale will turn 1080p into 4k, not 2k
 - It multiplies the height and width instead of the actual resolution
