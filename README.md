# python

from PIL import Image
#Open image using Image module
im = Image.open("M:\SOFTWARES & ACCESSORIES\Wallpapers\halo_4_2013-wallpaper-1920x1080.jpg")
#Show filename with extension
print(im.filename)
print(im.format)
print(im.mode)
print(im.size)
print(im.width)
print(im.height)
