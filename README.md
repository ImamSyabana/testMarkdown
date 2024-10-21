_________________________________________________________________
 Layer (type)                Output Shape              Param #   
=================================================================
 conv2d_63 (Conv2D)          (None, 124, 129, 32)      320       
                                               ## Subheader
                                               ini adalah edit dari lokal                  
 max_pooling2d_62 (MaxPoolin  (None, 62, 65, 32)       0         
 g2D)                                                            
                                                                 
 conv2d_64 (Conv2D)          (None, 62, 65, 64)        18496     
                                                                 
 max_pooling2d_63 (MaxPoolin  (None, 31, 33, 64)       0         
 g2D)                                                            
                                                                 
 conv2d_65 (Conv2D)          (None, 31, 33, 128)       73856     
                                                                 
 max_pooling2d_64 (MaxPoolin  (None, 16, 17, 128)      0         
 g2D)                                                            
                                                                 
 dropout_61 (Dropout)        (None, 16, 17, 128)       0         
                                                                 
 conv2d_66 (Conv2D)          (None, 16, 17, 256)       295168    
                                                                 
 max_pooling2d_65 (MaxPoolin  (None, 8, 9, 256)        0         
 g2D)                                                            
                                                                 
 dropout_62 (Dropout)        (None, 8, 9, 256)         0         
                                                                 
 flatten_16 (Flatten)        (None, 18432)             0         
                                                                 
 dropout_63 (Dropout)        (None, 18432)             0         
                                                                 
 dense_32 (Dense)            (None, 64)                1179712   
                                                                 
 dropout_64 (Dropout)        (None, 64)                0         
                                                                 
 dense_33 (Dense)            (None, 8)                 520       
                                                                 
=================================================================
Total params: 1,568,072
Trainable params: 1,568,072
Non-trainable params: 0
_________________________________________________________________
