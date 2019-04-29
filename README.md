# Assignment 1B


What are Channels and Kernels (according to EVA)?

Kernels interchangebly known as Filter/Mask is a square matrix that is used on the original image to extract features, kernel usually of matrix size 1X1, 2X2, 3X3 is run across the orignal image top to bottom.

Why should we only (well mostly) use 3x3 Kernels?



How many times do we need to perform 3x3 convolution operation to reach 1x1 from 199x199 (show calculations)

CODE 
---------
imagesize=199
pixeldeductionsize=2
ksize=''
count=0
convoperation=0
while (imagesize >1):
  count+=1
  for index in range(10):
      ksize += str(imagesize) + "|"
      imagesize = imagesize-pixeldeductionsize
  
  print(ksize)
  ksize=''
 
convoperation =  count * 10
print( 'Convoultion operation count -->' ,convoperation)

OUTPUT
------
199|197|195|193|191|189|187|185|183|181|
179|177|175|173|171|169|167|165|163|161|
159|157|155|153|151|149|147|145|143|141|
139|137|135|133|131|129|127|125|123|121|
119|117|115|113|111|109|107|105|103|101|
99|97|95|93|91|89|87|85|83|81|
79|77|75|73|71|69|67|65|63|61|
59|57|55|53|51|49|47|45|43|41|
39|37|35|33|31|29|27|25|23|21|
19|17|15|13|11|9|7|5|3|1|
Convoultion operation count --> 100
-----------------------------------
