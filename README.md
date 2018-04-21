Forked from: old-jekyll-templates/Linear-Jekyll-Theme

To run the program locally on your laptop:
cd <gd.github.io/>
jekyll serve
http://0.0.0.0:4000

To batch compress images to 800 pixels wide:
convert "*.JPG[800x]" -set filename:base "%[base]" "compressed_images/%[filename:base].jpg"

