# 21 Days of Lucid
## https://github.com/tensorflow/lucid
## Day 1: 
**Today's Progress:**
##### 1. Read the articles 'Using Artificial Intelligence to Augment Human Intelligence' and 'Visualizing Representations : Deep Learning and Human Beings' from the recomended readings section of tensorflow/lucid
##### 2. Reviewed the code from the colab notebooks 'Lucid Tutorial' and 'Model Zoo'
##### 3. Messed with some of the code; successfully generated a banner for my next meetup

**Link to code:** https://colab.research.google.com/drive/1hgd-ZjzBJIktI9m5JEXsG4EhdbYGqlJm

**Thoughts:**
##### I found the article 'Using Artificial Intelligence to Augment Human Intelligence' very interesting. The authors discuss how learning math and art (and other things) augment our ability to conceptualize and communicate. And so if we learn about Neural Nets, we open our minds to potentially greater depth. My feeling is that certain topics have a richness that allows for this... while others allow for it to a lesser degree. Take for example the 'study' of video-games. A persons mind is probably made much deeper by playing a complex strategy game, than a quick-reaction shooter... however, I would expect some improvements in both gamers cognition. 

**Future Work:**
##### 1. Explore the parameters 'transforms' and 'param_f' in greater detail
##### 2. Look more into the functions that I copied from the 'Feature Inversion Caricatures' notebook
##### 3. Learn to generate perlin noise in numpy (in 1D, 2D, and 3D)
##### 4. Learn to make larger output sizes
##### 5. Learn the interpolation method discussed in the paper 'Differential Image Parameterizations'
##### 6. Bridge my understanding of deep-dream and lucid
##### 7. Reproduce the work of Gene Kogan in lucid (gradient blending, looping animations)
##### 8. Produce a deep-dream zoom animation in lucid
##### 9. Learn the style transfer method discussed in the paper 'Differential Image Parameterizations'
##### 10. Bring the Deep Movie method to lucid
##### 11. Design a short music video (proof of concept: 30 seconds) using feature visualization as a visual effect
##### 12. Learn the 3D method discussed in 'Differential Image Parameterizations'
##### 13. Apply interpolation to a 3D model
##### 14. Explore the work from the research section of tensorflow/lucid
##### 15. Network with the lucid team through slack

## Day 2: 
**Today's Progress:**
##### 1. Read article 'Feature Visualization'
##### 2. Reviewed some colab notebooks: 'Negative Neurons', 'Diversity Visualization', 'Neuron Interactions', and 'Regularizing Visualizations'
##### 3. Found a repo that demonstrates perlin noise in numpy; began documenting the code in detail

**Link to code:** https://colab.research.google.com/drive/1L_CMEVJ3wvKOOHL5xRlycS5IVRPwUg5o

**Thoughts:** 
##### I found the task of producing perlin noise surprisingly difficult. The code repo I found today helped tremendously, but I still need to understand certain parts of it better.

**Future Work:**
##### 1. Extend the perlin noise to 3 dimensions
##### 2. Add in non-linear interpolation
##### 3. Tomorrow I will focus on interpolating between feature visualizations

## Day 3: 
**Today's Progress:**
##### 1. Read 'Building Blocks of Interpretability'
##### 2. Reviewed the code from 'Aligned Interpretation'
##### 3. Succeeded at today's goal to create an interpolation of feature visualizations
**Link to code:** https://colab.research.google.com/drive/1bbSn8p7KjK-2utuhnjgoBMJBwcXvXAES

**Thoughts:**
##### Today was an overall success. I still have along way to go to understand the code fully. I also need to improve my understanding of tensors overall.

**Future Work:**
##### 1. Create a script in gimp using python-fu (better yet imageio python library) to convert panels to animation
##### 2. Review the following colab notebooks: 'semantic dictionaries', 'activation grids', 'spatial attribution', and 'neuron groups'
##### 3. Create a version where the panels optimize to each other's edges (to make a continuous blend)
##### 4. Comment the code; figure out how the lowres_tensor operation works
##### 5. Tomorrow I will give effort to understanding style-transfer

## Day 4: 
**Today's Progress:**
##### 1. Reread the paper, 'Differential Image Parameterizations'
##### 2. Reviewed the colab notebook 'Sytle Transfer Beyond VGG'
##### 3. Reproduced the technique in a notebook with a different content and style image

**Link to code:** https://colab.research.google.com/drive/18N_Lq-mCI5Ie2pbaW93P7CJv9api7L2y

**Thoughts:** I feel like I accomplished just a bit better than the minumum today. That said, I learned a good amount about the 'gram matrix' which is produced my multiplying a matrix by its transpose. 

**Future Work:**
##### 1. Try a different set of layers for the content and style
##### 2. Try a different model
##### 3. Compare the code for deepdream provided by Siraj to the feature visualization code
##### 4. Read up on deepMovie and style transfer in the video domain
##### 5. Read the papers linked in 'Differential Image Parameterizations'
##### 6. Look at Gene Kogan's approach
##### 7. Explore the work of the original authors, create a visualization of the branching threads (google scholar API)

## Day 5:
**Today's Progress:**
##### 1. Reread the section from 'Differential Image Parameterizations' (DIP) on 'Compositional Pattern Producing Networks' (CPPN)
##### 2. Reproduced the technique 'CPPN'

**Link to code:** https://colab.research.google.com/drive/1FIkCm0AKmyVpgDVyjOM2pANZtfigR2xK

**Thoughts:** I had glossed over this section before. Now I'm feeling as though it deserves a full paper to itself. We learn about the title of the paper in this section: "CPPNs are a differentiable image parameterization — a general tool for parameterizing images in any neural art or visualization task"

**Future Work:**
##### 1. Try varying the activation function
##### 2. Try making a video of the training
##### 3. Try rendering at arbitrary resolutions (time it)
##### 4. Try interpolating between visualizations
##### 5. Read the original paper on CPPN
##### 5. Tomorrow I'll look into generating semi-transparent patterns

## Day 6:
**Today's Progress:**
##### 1. Reread the section on 'Generation of Semi-Transparent Patterns' (from DIP)
##### 2. Reproduced the technique in a colab notebook

**Link to code:** https://colab.research.google.com/drive/1Qvli2GDBPXA09WzMpQsoET9YCuMD11I6

**Thoughts:** The images seem very different from the original feature visualizations.

**Future Work:**
##### 1. Compare the visualizations produced by a given neuron in vanilla feature visualization VS CPPN VS semi-transparent
##### 2. Find a way to visualize the output of the image_sample function directly (seems to produce perlin noise)
##### 3. Try the FFMPEG technique demonstrated in the paper
##### 4. Tomorrow I'll try out feature visualization projected onto a 3d model

## Day 7:
**Today's Progress:**
##### 1. Reread the section on 'Efficient Texture Optimization through 3D Rendering'
##### 2. Experimented with creating a texture for a 3d model through feature visualization

**Link to code:** https://colab.research.google.com/drive/1fQvGxE2JFZJ33Ofcm3C20jPM0B8wCtZl

**Thoughts:** Feeling thrilled that this came together. I was anticipating this section greatly over the last few days. As it turns out, I had to make several attempts in order to get the 3D model to display with a texture at all. The way I have it now is somewhat hacky... but I'm happy with the aesthetic quality of the results.

**Future Work:**
##### 1. Bring the generated texture back into the 3d software environment (blender)
##### 2. Design a vase.
##### 3. Display the texture the "correct" way (using a seam rather than numerous tiles).
##### 4. Create an animated texture (also display in blender)
##### 5. Find some robotic looking layers... design a cool robot model in blender with feature visualization as a part of the workflow {shiny outer shell, complex internals showing through the cracks}
##### 6. Tomorrow I plan to try out 3D style transfer

