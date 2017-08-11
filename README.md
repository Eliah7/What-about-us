# What-about-us
********************************************************************************************************************
-------------------
Project inspiration
-------------------
1. An app that recognizes gestures made by people's hands and takes images of those gestures
2. maps those images to a known dataset of gestures
3. labels those images (possibly a classification problem)

4. generates from the labels a sequence of sounds that are then spoken through some speaker.

5. and the reverse
6. i.e take a sound and generate a gesture recognizable by a deaf person

*****************************************************************************************

-------------------
Implementation
-------------------
As the problem statement the implementation involves two smaller applications.

  1. Gestures to sound
  2. Sound to Gestures
-------------------------------------------------------------------------------------------------------------------
    *** 1. Gestures to Sound ***
        The implementation of this part of the app requires the following:
          1. Input:
            A way to take in images as vectors of pixels. Generate different variants of the images
            i.e grey, color coded etc.
            Use convolutional neural networks to generate features from the image vectors.

          2. Classification:
          Create a convolutional neural network that uses the features and maps to respective labels and use it in
              A. Training
              Train this model on already mapped labels.

              B. Testing
              Use an array images to test which labels it generates for the test images.

          3. Integration with video feeds
          Create a way of generating frames of images from a video feed instead of single images as inputs.

  ------------------------------------------------------------------------------------------------------------------

  ------------------------------------------------------------------------------------------------------------------
  Note: This is the more harder one

*** 2. Sound to Gestures ***
