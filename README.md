# Deep Efficient End-to-end Reconstruction (DEER) Network for Few-view Breast CT Image Reconstruction
To start the training process, please prepare your training/validation/testing data in the following format

* ``img_data`` (Few view images, FDK, FBP, etc): N * 1 * img_width * img_height
* ``projection_data``: N * 1 * num_views * num_detector
* ``label``: N * 1 * img_width * img_height

Here, N represents the number of input data.
All datasets are stored in a hdh5 file.


## Contact
huidong.xie at ieee dot org

Any discussions, suggestions and questions are welcome!
