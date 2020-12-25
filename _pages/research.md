---
#layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research areas include application of Deep Learning techniques to problems in Natural Language Processing, Computer Vision and Speech Recognition. 

## People Also Ask
<div class="research-sub">
    <b>Deep Learning, Data Science, Natural Language Processing</b>, Data Scientist, Microsoft Bing Search Technology Center India (STCI)
</div>

<div class="img-wrapper">
    <img src="/images/paa.png" id="paa_img" alt="People Also Ask for query - artificial intelligence">
</div>

I work on Bing's People Also Ask (PAA) Experience which shows a block of related questions and answers for a given user query on Bing's search page serving more than 6 billion queries a month. I focus on multilingual techniques to enable PAA in more than 200 markets and 100+ languages. Additionally, I work on PAA freshness, ensuring that our data is super fresh and delights the user, to aid him in query exploration and reformulation. 


## Fast Multilingual Acoustic Model for Low Resource Languages

<div class="research-sub">
    <b>Deep Learning, Speech Recognition</b>, <a href="/files/MASR_SLT_CameraReady.pdf">Paper</a>, <i>(accepted at SLT 2021)</i>
</div>

<div class="img-wrapper">
    <img src="/images/cnn-dnnv2.jpg" id="slt_img" alt="System Design">
</div>

<b>Abstract</b>: Multilingual automatic speech recognition (ASR) system is a single entity capable of transcribing multiple languages sharing a common phone space. The performance of such a system is highly dependent on the compatibility of the languages. State of the art speech recognition systems is built using sequential architectures based on recurrent neural networks (RNN) limiting the computational parallelization in training. This poses a significant challenge in terms of time taken to bootstrap and validate the compatibility of multiple languages for building a robust multilingual system. Complex architectural choices based on self-attention networks are made to improve the parallelization thereby reducing the training time. In this work, we propose Reed, a simple system based on 1D convolutions that use very short context to improve the training time. To improve the performance of our system, we use raw time-domain speech signals directly as input. This enables the convolutional layers to learn feature representations rather than relying on handcrafted features such as MFCC. We report improvement on training and inference times by at least a factor of 4x and 7.4x respectively with comparable WERs against a standard RNN based baseline system on SpeechOcean's multilingual low resource dataset.  


## An Approach Towards Action Recognition Using Part Based Hierarchical Fusion

<div class="research-sub">
    <b>Deep Learning, Computer Vision</b>, <a href="/files/humanactionrecognition_partbasedhierarchicalfusion.pdf">Paper</a>, <a href="/files/slides_190.pdf">Presentation</a>, <i>(accepted at ISVC 2020)</i>
</div>

<div class="img-wrapper">
    <img src="/images/posebased_hblstm.png" id="pose_img" alt="Model Architecture">
</div>

<b>Abstract</b>: The human body can be represented as an articulation of rigid and hinged joints which can be combined to form the parts of the body. Human actions can be thought of as a collective action of these parts. Hence, learning an effective Spatio-temporal representation of the collective motion of these parts is key to action recognition. In this work, we propose an end-to-end pipeline for the task of human action recognition on video sequences using 2D joint trajectories estimated from a pose estimation framework. We use a Hierarchical Bidirectional Long Short Term Memory Network (HBLSTM) to model the Spatio-temporal dependencies of the motion by fusing the pose based joint trajectories in a part based hierarchical fashion. To denote the effectiveness of our proposed approach, we compare its performance with six comparative architectures based on our model and also with several other methods on the widely used KTH and Weizmann action recognition datasets. 


## Characterization and Localization of An Urban Noise Nuisance - "The Ranchland's Hum"

<div class="research-sub">
    <b>Acoustics, Signal Processing, Machine Learning</b>, <a href="/files/Calibrating_microphone_android_device.pdf">Short Paper</a>, <a href="https://github.com/skymanaditya1/Hum_App_Master">Code</a>, <i>(MITACS, The University of Calgary Canada)</i>
</div>


Hums are sporadic low-frequency noise nuisances that have adverse health implications, including anxiety, sleeplessness, and can cause vibroacoustic diseases. In response to community requests for assistance, preliminary analysis of audio recordings using expensive industry-grade devices was made in the past. However, deploying such expensive equipment at scale was not a feasible option. In response, I 
1. developed an easily accessbile android application to capture and store the data
2. developed a number of signal processing and machine learning algorithms to analyze the recorded data and categorize the noise based on its characteristics 
3. devised a calibration technique to calibrate the frequency response of the device as the frequency response captured at low-frequency was questionable due to known low-frequency bandwidth limitations of a standard cell phone microphone. 

# Recording Preferences Settings:
In the Hum application developed initially by Das, Gaspard, and Smith <a href="https://ccrma.stanford.edu/~orchi/Documents/EMBC16_3168_FI.pdf">Paper</a>, there was an option to make recordings of 5 seconds each. The said recording is called an impulse. In the real world scenario, user should be given the freedom to choose the recording time and duration of the recording. In this regard, I made several additions to the way audio was being captured by the cell phone microphone. More details in this <a href="/files/mitacs_uofc/Recording_Preferences_Settings.pdf">document</a>.

<div class="img-wrapper">
    <img id="event_first" class="ranchlands_hum" src="/images/mitacs_uofc/recording_preferences1.png" alt="Preferences Settings">
    <img id="event_first" class="ranchlands_hum" src="/images/mitacs_uofc/recording_preferences2.png" alt="Preferences Settings Saved">
    <img class="ranchlands_hum" src="/images/mitacs_uofc/recording_preferences_3.png" alt="Microphone Recording">
</div>

# Calibrating the Microphone of An Inexpensive Android Device:
To record the frequency response of an inexpensive android device using its internal microphone accurately, calibration must be done to ensure correctness. In the original hum application developed, the frequency response obtained using the internal microphone was getting cut-off at lower frequency ranges (<30Hz) due to the limitations involved with the inexpensive recording hardware of the android device. To overcome this limitation, calibration is done using a standard industry grade external microphone. More details in this <a href="Calibration_document.pdf">document</a>

<div class="img-wrapper">
    <img id="event_first" class="ranchlands_hum" src="/images/mitacs_uofc/calibration.png" alt="Calibration">
    <img class="ranchlands_hum" src="/images/mitacs_uofc/calibrated_file.png" alt="Calibrated Values">
</div>


## Minimally Supervised Sound Event Detection using a Neural Network

<div class="research-sub">
    <b>Acoustics, Deep Learning, Neural Networks</b>, <a href="/files/SoundEventDetection.pdf">Paper</a>, <a href="/files/icacci_poster2016.pdf">Poster</a>, <a href="https://github.com/skymanaditya1/Neural_Network_Dataset_Generation">Code</a>, <i>(accepted at ICACCI 2016)</i>
</div>

<div class="img-wrapper">
    <img id="event_first" class="event_detection" src="/images/sound_event_detection/soundeventdetection_1.jpg" height="250px" alt="Phase I">
    <img class="event_detection" src="/images/sound_event_detection/soundeventdetection_2.jpg" height="250px" alt="Phase II">
</div>

<b>Abstract</b>: The paper proposes a sound event detection system that is trained using a minimally annotated data set of single sounds to identify and separate components of polyphonic counds. The system uses a Feed Forward Neural Network with a single hidden layer that is pre-trained using an autoencoder. Single sounds, represented as Mel Frequency Cepstral Coefficient (MFCC) feature vectors, are used to train the neural network using back propagation. Polyphonic sounds are pre-processed using Principal Component Analysis (PCA) and Nonnegative Matrix Factorization (NMF) to obtain source separated sounds. These source separated sounds are then tested for sound classification using the feed-forward algorithm. Our system is able to achieve reasonable accuracy of source separation and detection with minimal training set. The ultimate goal of our system is to bootstrap from minimal data and learn new sounds leading to a better sound detection system.  


## Elucidate - Generating Mathematics Word Problems of Arbitrary Complexity 

<div class="research-sub">
    <b>Technology for Society, Software Engineering</b>, <a href="/files/Elucidate.pdf">Project Paper</a>, <i>2016</i>
</div>

<div class="img-wrapper">
    <img id="event_first" class="event_detection" src="/images/elucidate_1.png" height="250px" alt="Elucidate 1">
    <img class="event_detection" src="/images/elucidate_2.png" height="250px" alt="Elucidate 2">
</div>

We proposed a method on how word problems can be generated by taking a non-singular system of linear equations and inspecting the solution. The corresponding English statements generated can be treated as a "figurative" translation of the non-singular system as an equation like x+y=4 may be understood as the process of adding two quantities which produce a result of 4. We call it a "figurative" translation as the two quantities 'x' and 'y' can be mapped to any entity but the semantics of the equation is always retained. This forms the basis of problem generation. The proposed system defines a set of regular expressions using which the linear equations are translated to English statements. The non-singular system of linear equations must undergo a normalization phase in order to apply the regular expressions. The complexity of the word problems generated is a function of the nature of the system of linear equations and hence arbitrary and tunable. The number of linear equations in the system and diversity in the signs of the terms contribute to the complexity of the generated problems. The proposed method provides a systematic procedure which can be employed to generate word problems from a given non-singular system of linear equations. The proposed method has been implemented as a pedagogical tool by capturing the transformations that the equations undergo and portraying the changes as a video play, which would provide a keen insight on the dynamics that are in play when one attempts to solve such a system. 


## F.A.R. Framework - A binary framework where information retrieval is Fast, Accurate, and Relevant

<div class="research-sub">
    <b>Information Retrieval</b>, <a href="/files/ijert_ncacct.pdf">NCACCT Paper</a>, <i>2015</i>
</div>

<div class="img-wrapper">
    <img id="event_first" class="event_detection" src="/images/ncacct_1.png" alt="Adjacency Matrix of people numbered from 1 to 7">
    <img class="event_detection" src="/images/ncacct_2.png" alt="Set relational operations on the matrix">
</div>

Abstract: Data Resource Management is the development and execution of architectures, policies, practices and procedures that properly manage the full data lifecycle needs of an enterprise. Retrieving relevant and meaningful information as specified in the search query from the ocean of data, along with the retrieval being efficient with regard to memory and computation is the purpose of the proposed method. If related data is organized according to the proposed method, all the set operations such as union, intersection, difference and cross-product can be performed in O(n) without having the overhead of maintaining a sorted list or any other constraints. Every Boolean Algebra expression can be translated to a set-relation equation. Since the proposed framework is compatible with any set-relation operation, with the help of translation, Boolean Algebra operations can be performed. Every Boolean Algebra operation has a meaning in the proposed framework and hence, innumerable meaningful information can be obtained with every different combination of Boolean expression. 


## Apache Giraph deployed on Apache Hadoop - Case study of a Graph database framework 

<div class="research-sub">
    <b>Graph Database Framework</b>, <a href="/files/CCBD_ProjectReport_ApacheGiraph.pdf">Project Report</a>, <a href="https://github.com/skymanaditya1/Apache-Giraph-Deployed-on-Apache-Hadoop">Code</a> <i>2015</i>
</div>

Apache Hadoop is a set of algorithms for distributed storage and distributed processing of very large data sets on computer clusters built from commodity hardware. It consists of a storage part (Hadoop Distributed File System HDFS) and a processing part (Map Reduce). Hadoop splits files into large blocks and distributes the blocks amongst the nodes in the cluster. To process the data, Hadoop Map/Reduce transfers code to nodes that have required the data, which the nodes then process in parallel. 

Apache Giraph is an iterative graph processing system built for high scalability. It is currently used at Facebook to analyse the social graph formed by the users and their connections. It originated as the open counterpart of Pregel. 

We ran and tracked the job performance of Map Reduce jobs such as Pi Estimator and Word Count Program on Apache Hadoop Cluster. Additionally, we deployed and tracked the performance of Giraph jobs such as Word Count on single node and multi node Hadoop Cluster. Moreover, we ran Giraph jobs on large network graphs from SNAP such Twitter and Facebook graphs. Due to the discrepancy in the data format of running Giraph jobs on SNAP graphs, I wrote a complex conversion algorithm to convert the SNAP's edge list format to the JSON format accepted by Giraph. <a href="https://github.com/skymanaditya1/Apache-Giraph-Deployed-on-Apache-Hadoop/blob/master/EdgeListToJsonConversionFormatClass.java">Code</a>.

<div class="img-wrapper">
    <img src="/images/snap_conversion.png" alt="SNAP data format to Giraph data format conversion">
</div>