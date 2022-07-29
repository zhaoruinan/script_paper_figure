# script_paper_figure

Put image path into img_list like:
```
img_list=['lab_rgb_img_4x_out.png','lab_rgb_img_2x_out.png','lab_rgb_img.png','lab_rgb_img_denoise.png']
```
'scale' means size of the crop part to / full size of the image.

'start' means start position(x,y scale in full size).
```
for img_path in img_list:
    draw_img(img_path,scale=0.05,start=(0.35,0.82))
```
