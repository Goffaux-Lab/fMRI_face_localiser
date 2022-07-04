## fMRI_face_localiser
This folder contains the localiser experiment to test.
One run has a duration of ~= 12min

For everything to work properly:
- don't change or move any files/folders
- to end (break the loop) press Ctrl+C -> your data will be saved anyway 
- you can also press "esc" instead of a "normal" trial response

Caution: Extremely boring :D (especially very long! 744 secs, or 12.4 mins)

Some examples of the images used in the localiser (along with their phase
scrambled counter parts) are:

![example_images](example_images/examples.png)

### Brief description of the stimuli and procedure
There are 10-second blocks, alternated by 10 seconds of fixation with a
12-second fixation period at the beginning and end of the run. 

Subjects view grayscale images of either intact or scrambled faces, hands or
instruments. Images from all categories are presented in 36 blocks in total
(one image category per block), with 6 blocks per condition. A condition is
never repeated twice in a row and the order of conditions is counterbalanced
across subjects. A block consists of 10 images in a random order, all images
are repeated three times during the whole localiser run. Each image appears for
500ms, followed by a 500ms interstimulus interval.

The task is to detect a rare and brief colour change of the stimulus by
pressing a button with the right index finger. In each block, there are two
targets (blue: HSV profile 1.0, 1.0, 0.8). One colour change occurs per block
half, but never during the first stimulus of a block. Subjects are instructed
to fixate on its central intersection at all times.
