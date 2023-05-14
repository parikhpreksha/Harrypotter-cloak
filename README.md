# Harrypotter-cloak
This is the invisibility -cloak of harry potter.

The project is “Invisible Cloak” using simple computer
vision techniques in OpenCV. Here, I have created this
magical experience using an image processing technique
called Color detection and segmentation. You must
have a cloth of same color and no other color should be
visible into that cloth. I have taken the red cloth. If you
are taking some other cloth, the code will remain the
same but with minute changes.
This technique is opposite to the Green Screening. In
green screening, we remove background but here we will
remove the foreground frame.


Steps:

1.Capture and store the background frame [ This will be
done for some seconds ]

2. Detect the red colored cloth using color detection and
segmentation algorithm.

3. Segment out the red colored cloth by generating a
mask. [ used in code ]

4. Generate the final augmented output to create a
magical effect. 




