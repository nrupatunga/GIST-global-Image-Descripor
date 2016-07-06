# GIST-global-Image-Descripor Tool

This is the tool to extract the [GIST descriptor](http://people.csail.mit.edu/torralba/code/spatialenvelope/) for Images. GIST is low dimensional representation for images. 


# GIST t-SNE Visualization 
t-SNE Visualization of GIST neighbors|
:-------------------------:|
![](https://github.com/nrupatunga/GIST-global-Image-Descripor/blob/master/t-sne/gist-nn-large.png)

Gist 1.0 Beta
------------
Usage:

>>gist.exe -i [input directory] -o [output directory]

 - [  input directory ]  - input directory where images are present
 - [ output directory ]  - output directory where file names and respective gist vectors are dumped
                      into gist.txt and filenames.txt
 - gist.txt              - each line contain gist vector for each file in filenames.txt
 

**_Note_**: More updates to come soon
