# ImageSearchEngine
Currently compares images using Python based on RGB values. Imrpovements using edge detection to be implemented


You can run a search by using the following command:

python index.py -d images/ -i output.cpickle

Where images/ is the folder where you have stored all the images you want to index and output.cpickle is the dictionary index

After creating your cpickle file run the following command:

python search_external.py --dataset images --index output.cpickle --query queries/image_you_wish_to_compare_to_index.png

