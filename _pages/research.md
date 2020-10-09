---
#layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research areas include application of Deep Learning techniques to problems in Natural Language Processing, Computer Vision and Speech Recognition. 


## Pose Based Action Recognition using Hierarchical BLSTM

<div class="research-sub">
    <b>Computer Vision</b>, <a href="/files/PBAR_Synapse.pdf">Short paper</a>, <i>2020</i>
</div>

<div class="img-wrapper">
    <img src="/images/posebased_hblstm.png" id="pose_img" alt="Model Architecture">
</div>

We propose an end-to-end pipeline for the task of human action recognition on video sequences using 2D joint trajectories estimated from a pose estimation framework. We use a Hierarchical Bidirectional Long Short Term Memory Network (HBLSTM) to model the spatio-temporal dependencies of the motion by fusing the pose based dense trajectories in a part based hierarchical fashion. 

## Fast Multilingual Acoustic Model for Low Resource Languages

<div class="research-sub">
    <b>Speech Recognition</b>, <a href="/files/MASR_Synapse.pdf">Short paper</a>, <a href="/files/MASR___SLT.pdf">Blind paper</a>, <i>2020</i>
</div>

<div class="img-wrapper">
    <img src="/images/multilingual_acousticmodel.png" height="250px" alt="System Design">
</div>

We propose an architecture based on short term contextual temporal features learned on Convolutional Neural Networks (CNNs) with a non-sequential discriminative network for building a multilingual automation speech recognition system. Three low resource Indic languages, Gujarati, Tamil, and Telugu are used ascertain that our proposed architecture trains 5.5x faster and reduces the inference time by a factor of 26 while maintaining word error rates against comparable baseline RNNs. 

## Minimally Supervised Sound Event Detection using a Neural Network

<div class="research-sub">
    <b>Neural Networks</b>, <a href="/files/SoundEventDetection.pdf">ICACCI paper</a>, <a href="https://github.com/skymanaditya1/Neural_Network_Dataset_Generation">code</a>, <i>2016</i>
</div>

<div class="img-wrapper">
    <img id="event_first" class="event_detection" src="/images/soundeventdetection_1.jpg" height="250px" alt="Phase I">
    <img class="event_detection" src="/images/soundeventdetection_2.jpg" height="250px" alt="Phase II">
</div>

We propose a sound event detection system that is trained using a minimally annotated data set of single sounds to identify and separate components of polyphonic sounds. The system uses a Feed Forward Neural Network that is pre-trained using an auto-encoder. Single sounds, represented as MFCCs are used to train the network. Polyphonic sounds are preprocessed using Principal Component Analysis and Non-negative Matrix Factorization (NMF) to obtain source separated sounds. Our system was able to achieve reasonable accuracy of source separation and detection with minimal training set. 

<div class="mid-topic">
    Other Projects
</div>

## Elucidate - Mathematics word problem generation of arbitray complexity 

<div class="research-sub">
    <b>Tech for good</b>, <a href="/files/Elucidate.pdf">Paper</a>, <i>2016</i>
</div>

<div class="img-wrapper">
    <img id="event_first" class="event_detection" src="/images/elucidate_1.png" height="250px" alt="Elucidate 1">
    <img class="event_detection" src="/images/elucidate_2.png" height="250px" alt="Elucidate 2">
</div>

Devised a grammar to generate Mathematics word statement problems dynamically from a given system of non-linear singular questions. Built as a pedagogical tool for learning in India. 

## F.A.R. Framework - A binary framework where information retrieval is Fast, Accurate, and Relevant

<div class="research-sub">
    <b>Information Retrieval</b>, <a href="/files/FAR_Framework.pdf">NCACCT Paper</a>, <i>2015</i>
</div>

Built a framework where the relation between the entities is represented in the form of an adjacency matrix. Set relational operations are performed to extract relevant and accurate information in a timely manner. 
Published as a research paper in IJERT and won the best paper at NCACCT. 

## Apache Giraph deployed on Apache Hadoop - Case study of a Graph database framework 

<div class="research-sub">
    <b>Graph Database Framework</b>, <a href="/files/FAR_Framework.pdf">NCACCT Paper</a>, <i>2015</i>
</div>

Deployed and tracked the performance of Apache Giraph jobs on single node and multi node setup of Apache Hadoop cluster. Also wrote a conversion algorithm to convert the format of Large Network graphs on SNAP (Stanford Network Analysis Project) into the JSON format accepted by Giraph. 

## Shopping Kart - A smart e-commerce framework 

<div class="research-sub">
    <b>Data Structures</b>, <i>2015</i>
</div>

Designed a prototype of an e-commerce application in Android with search functionality implemented using Trie trees and next item purchase prediction using Priority Queues. The project was done as part of the Data Structures and Algorithms coursework. 