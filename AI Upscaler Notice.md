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
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Models
 - RealESRGAN_x4plus
 - RealESRNet_x4plus
 - RealESRGAN_x2plus
 - realesr-general-x4v3
 - RealESRGAN_x4plus_anime_6B
 - realesr-animevideov3
(x4 is for turning 1080p to 8k, 720p to 4k etc)
(x2 is for turning 1080p to 4k, 720p to 2k etc)
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Commands
 - tile
 - tile_pad
 - pre_pad
 - outscale
 - fp32 / fp16
 - suffix
 - ext
 - gpu_id
 - face_enhance
 - face_enhance_tile
 - face_enhance_gpu_id
 - alpha-_upsampler
 - model_path
 - cpu
 - denoise
 - verbose
 - tile_mode
 - hal_precision
 - int8
 - num_threads
 - output_8bit
 - export_onnx
 - export_torchscript
 - shop
 - precision
 - input_scale
 - save_metadata
 - overwrite
 - quiet
 - fps
 - extract_frame_first
 - num_process_per_gpu
 - ffmpeg_bin
 - video
 - audio
 - consumer
