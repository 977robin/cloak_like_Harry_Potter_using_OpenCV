# cloak_like_Harry_Potter_using_OpenCV
I've always fantasized myslef as a Harry Potter; the way he uses his Invisible Cloak. That's why I had tried to make an invisible cloak, not in real but virtually. The project uses simple computer vision techniques in OpenCV using Python. The image processing technique used here is Color Detection and Segmentation. To run, first we need to have a source video file as "video.mp4". Also we need to have a cloth of same color and no other color should be visible into that cloth. I am taking the red cloth. If you are taking some other cloth, the code will remain the same but with some minute changes. This technique is opposite to the Green Screening. In green screening, we remove background but here we will remove the foreground frame.

The Algorithm is as follows:
1. Capture and store the background frame. (for some seconds)
2. Detect the red colored cloth using color detection and segmentation algorithm.
3. Segment out the red colored cloth by generating a mask. (used in code)
4. Generate the final augmented output to create a magical effect. (video.mp4)
