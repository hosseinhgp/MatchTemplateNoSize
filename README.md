# MatchTemplateNoSize
cv2 match template with no dependence to sample size

use matchtemplate method from cv2 package to find mathes with template picture, but this method can't fine template with deferent size from orginal template, so we solve this by changing the template size in specific sclae(for example 0.5 or 2). so this method can fine template with any size and scale.

sperm : template tree, because of rotation we set the first picture bigger than orginal sperm sample and after rotation we crop extra aria. 
test : picture with a sample tree in it but in different size
