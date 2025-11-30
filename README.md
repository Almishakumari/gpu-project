# GPU-Project

GPU Glitch Art Generator. This project creates glitch-style visual effects using GPU acceleration with CuPy.
I processed two images — a human face and an apple — and applied several glitch filters such as noise, color swap, RGB offset, scan lines, and block shifting. The GPU makes these effects much faster compared to CPU processing

##Project Goal
To use GPU computing in a creative way by generating glitch-art effects.
The purpose is to show how GPUs can quickly modify image pixels and apply visual transformations.

I use 2 images - 
1. human face
2. an apple

Each image is processed with the following GPU-based effects:
Row Shift – randomly shifts rows sideways
Color Channel Swap – mixes RGB channels
Noise Addition – adds pixel noise
Block Shuffle – shifts image blocks
Scan Lines – adds horizontal dark lines
RGB Offset – shifts red and blue channels apart

Output:- 

For human_face.jpg file i got- 
human_face_shift.jpg – shifted rows
human_face_color_swap.jpg – colors swapped
human_face_noise.jpg – random noise
human_face_block_shuffle.jpg – blocks shifted
human_face_scan_lines.jpg – horizontal scan lines
human_face_rgb_offset.jpg – RGB channel offset
human_face_comparison.png – 3×3 grid showing all effects

For apple.jpg file i got- 
apple_shift.jpg – shifted rows
apple_color_swap.jpg – colors swapped
apple_noise.jpg – random noise
apple_block_shuffle.jpg – blocks shifted
apple_scan_lines.jpg – horizontal scan lines
apple_rgb_offset.jpg – RGB channel offset
apple_comparison.png – 3×3 grid showing all effects

Performance Output:
the program should prints the GPU processing time for each image:
