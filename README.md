# ELA-META-HASH
Matlab Script, Evaluates ELA with filters, displays file metadata, and hashes.  Note, ELA is not a definitive tool in digital image or photo forensics.  It can be used to assist in evaluation.  https://fotoforensics.com is a good educational site for more information on image analysis.

Can display ELA image with options for differance multiplier and compression quality, inverted image, grayscale ELA image, grayscale ELA image with minimum value as filter, or only display original image using ELA filter with a minimum value as a mask.

Can display file metadate or hashes ('SHA-1', 'SHA-256', 'SHA-384', 'SHA-512', 'MD2', and 'MD5' optional).  
The hash function is from https://github.com/brian-lau/MatlabStan/blob/master/%2Bmstan/DataHash.m which makes up the majority of the code.  These functions can be removed without impacting the GetELA function.



