# jyugyouuuuu
from PIL improt Image
improt sys


input_image = sys.argv[1]
output_image = sya.argv[2]


img = Image.open(input_image)

img_flip = img.transpose(Image.FLIP_LEFT_RIGHT)

img_flip.save(output_image)
