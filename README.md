# The Way Through The OpenCv Course 
The project includes exercises from both the Opencv bootcamp and the git exercises.
- https://opencv.org/university/free-opencv-course/
- https://git-scm.com/docs/
## Purpose of the course
A little bit of learning and a lot of fun with programming. You can also use mathematics with visible examples.
```python
img_NZ_bgr = cv2.imread("New_Zealand_Lake.jpg")
b,g,r = cv2.split(img_NZ_bgr)
plt.figure(figsize=[20,5])
plt.subplot(141);plt.imshow(r, cmap="gray");plt.title("Red Channel")
plt.subplot(142);plt.imshow(g, cmap="gray");plt.title("Green Channel")
plt.subplot(143);plt.imshow(b, cmap="gray");plt.title("Blue Channel")

# Merge the individual channels into a BGR image
imgMerged = cv2.merge((b, g, r))
# Show the merged output
plt.subplot(144)
plt.imshow(imgMerged[:, :, ::-1])
plt.title("Merged Output")
```
## Results
It is worth redoing the course by yourself.
![Example](https://github.com/Piotrek-max/LearnOpenCv/blob/master/OPC.png)
And this is just the beginning.
## What next?
Do more projects to improve skills. :sunglasses:
