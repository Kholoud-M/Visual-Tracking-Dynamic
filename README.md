# Visual Tracking Dynamic
Human visual attention has been widely studied using eye-tracking to monitor where a subject
looks and when. Decisions about where to look at any given instant appear to be determined by a
combination of multiple, constantly changing internal and external factors including top-down task
demands, such as searching for a specific object (Torralba, Oliva, Castelhano, & Henderson, 2006;
Yarbus, 1967), bottom-up image features, such as colors/contrast (L Itti, Koch, & Niebur, 1998), and
familiarity with the objects in a scene (Najemnik & Geisler, 2005). Computational descriptions of visual 
attention have quantified each of these phenomena (Laurent Itti & Koch, 2001) and, in many cases, 
it is possible to accurately predict where a person will look in a scene and when (Judd, Durand, & Torralba, 2012).
Although these models have had a great deal of success, the majority of work in this area has focused on describing
visual attention to simplified stimuli: static images or videos with still cameras. In everyday life, on the other hand,
our bodies are constantly moving and we direct our visual attention in the presence of large, global translations and 
rotations of the entire visual scene (Koenderink, 1986). Our central hypothesis is that, when visual stimuli are highly dynamic, 
gaze behavior shifts from being a series of fixations to static objects and instead to a series of smooth-pursuit movements where 
subjects track objects in the presence of global motion. Here we will use a research-grade, non-contact eye-tracker to monitor subject’s 
eye position,head position, and pupil size, while subjects view dynamic visual stimuli.The focus of this project is on developing new 
data analysis and computational models of eye movements of healthy participants. By examining what stimulus features affect where the subjects look,
and comparing eye movement during stimuli with and without global motion, we will gain insight into processes underlying visual attention. 

# Stimuli
280 natural movies taken from 4 documentaries and the middle frame from each clip is played as a static non moving image for the same amount of time. 

# Data Analysis
Gaze data will be acquired at 250-500Hz and we will analyze how features of the stimulus affect
subject eye movements moment to moment. Data from each subject will be examined separately,
and the primary analysis will be in comparing eye movements for different types of stimuli (e.g.
global motion of different amplitudes). In particular, we will correlate (using nonlinear
regression) features of eye movement (e.g. speed, direction, and fixations) with stimulus features
(e.g. color, contrast, direction/strength of optic flow, and object locations). These relationships
will allow us to characterize how visual attention varies with global motion.


