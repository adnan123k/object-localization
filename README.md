# object-localization
object localization is model that tries to find if the object exist and where it's in the photo.<br/>
the model uses pre-trained model(vgg16) but chop the head off in order to use it to predict where and if the object exist.<br/>
the model will produce 5 values:x,y,height and weights of the box and the probabilites if the object exist
# how to run it
there is two ways to use it:<br/>
1-colab<br/>
2-localy<br/>
if you're using colab just upload the ipynb file and run it<br/>
localy:<br/>
1-you have to install python 3<br/>
2-the recommended libraries<br/>
3-install ide and open the .py file or .ipynb<br/>
4-run it<br/>

# the recommended libraries:
1-tensorflow<br/>
2-numpy<br/>
3-matplotlib<br/>
4-glob<br/>
5-imageio

# reference:
https://machinelearningmastery.com/object-recognition-with-deep-learning/#:~:text=Object%20localization%20refers%20to%20identifying,more%20objects%20in%20an%20image.
