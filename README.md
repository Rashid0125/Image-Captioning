# Image-Captioning
Explaining Encoder and Decoder
Encoder:
than a million images from the ImageNet database. The network is 50 layers deep and can classify 
images into 1000 object categories, such as keyboard, mouse, pencil, and many animals. As a result, 
the network has learned rich feature representations for a wide range of images. The network has an 
image input size of 224-by-224.
Decode:
For Decoder we use LSTM. Long Short-Term Memory (LSTM) networks are a modified version of 
recurrent neural networks, which makes it easier to remember past data in memory. The vanishing 
gradient problem of RNN is resolved here. LSTM is well-suited to classify, process and predict time 
series given time lags of unknown duration. It trains the model by using back-propagation
For Encoder we use VGG-16. VGG-16 is a convolutional neural network that is trained on more
 generate_caption("1001773457_577c3a7d70.jpg")
---------------------Actual---------------------
startseq black dog and spotted dog are fighting endseq
startseq black dog and tri-colored dog playing with each other on the road endseq 
startseq black dog and white dog with brown spots are staring at each other in the street 
endseq 
startseq two dogs of different breeds looking at each other on the road endseq 
startseq two dogs on pavement moving toward each other endseq
--------------------Predicted--------------------
startseq two dogs play with each other in the grass endseq
generate_caption("1002674143_1b742ab4b8.jpg")
---------------------Actual---------------------
startseq little girl covered in paint sits in front of painted rainbow with her hands in
bowl endseq startseq little girl is sitting in front of large painted rainbow endseq
startseq small girl in the grass plays with fingerpaints in front of white canvas with
rainbow on it endseq
startseq there is girl with pigtails sitting in front of rainbow painting endseq
startseq young girl with pigtails painting outside in the grass endseq
--------------------Predicted--------------------
startseq little girl in pink dress is lying on the side of the grass endse
