# Fuzzy-Contextual-Contrast-Enhancement_Code
This repository provides matlab code for  our paper "Fuzzy-Contextual Contrast Enhancement" published in IEEE Transactions on Image Processing, vol. 26, no. 4, pp. 1810-1819, April 2017 

For the citation of the paper: A. S. Parihar, O. P. Verma and C. Khanna, "Fuzzy-Contextual Contrast Enhancement," in IEEE Transactions on Image Processing, vol. 26, no. 4, pp. 1810-1819, April 2017.
doi: 10.1109/TIP.2017.2665975

This code can be executed using MATLAB as following:

------------for color images---------------------
i=imread('3096.jpg');
[ Im_out, etime] = FCCE_Color( i );
figure(1);imshow(Im_out);title('FCCI Color');

----------for gray scale images------------------
i=imread('ruins.jpg');
[ Im_out, etime] = FCCE_Gray( i );
figure(2);imshow(Im_out);;title('FCCI Gray');
