# Centre for Crop Disease Control (CCDC)
NEUON's submission for HackWknd AgroFest - CCDC

Team Name : Neuon AI  
Members: Chang Yang Loong, Sophia Chulif, Heng Kiat Jing, Danish Ezwan

## Links

#### Project Proposal
https://github.com/coffeestains1908/neuon-hackwknd-cropai/blob/master/CCDC_proposal.pdf

#### Slide


#### Prototype apk
You can download the prototype APK file here: 

https://github.com/coffeestains1908/neuon-hackwknd-cropai/releases/download/rc-0/apk.zip  
Extract & install  


## Project Description
Crop diseases impose a negative impact on the yield of crops and consequently lead to economic damage.
Human expertise such as plant pathologist are not always available in rural farms to detect the disease before the outbreak and spreading.
With the advancement of machine learning especially deep learning in visual recognition, there has been various successful cases where human expert knowledge can be transferred to the machine for assistant in visual recognition including plant diseases.
However, the direct adoption of such technology would raise new problems:
1. Existing plant disease data are not region invariant
2. Data required for deep learning task is large
3. Data needs to be diverse in terms of capturing condition, disease stages and image quality
 
In order to tackle the challenges mentioned, we propose a system that encapsulates the whole process from data collection to continuously growing crop disease recognition model as shown in [Figure 1](https://github.com/coffeestains1908/neuon-hackwknd-cropai#overall-framework). The farmers and users would participate in data collection via App created by CCDC which is complete with labelling UI for meta information. These data will later be processed by the expert to either label or validate the images. Then, these annotated images are used to train and update an existing model of crop disease. Finally, the AI model is deployed/updated in the form of App for the farmer to recognize various diseases. The cycle continues as the farmers continuously submit their detected data and disease queries via the same App to enrich the crop disease data to produce a better AI model.
 
There are a few notable outcomes of CCDC:
1. Produce a reliable and continuously learning AI for crop disease.
2. Reduce the cost of data collection by crowdsourcing the community.
3. Farmers would be benefited by this system in early detection of crop disease to ensure quality yield at the same time maintain production quantity.
4. The related agriculture authority could detect and control disease outbreak within the community.


## Overall framework
<p align="center">
  <img src="overall_framework_v2.png"><br />
  Figure 1
</p>

## Project Prototype / Proof of Concept (POC)
In our POC, we choose tomato as our subject and develop an AI model to predict their disease. There are 9 diseases plus a healthy class is used to train an AI to distinguise between different disease. The result is as shown below (Table 1):
<p align="center">
  <img src="quantitative_result.png" width="600"><br />
  Table 1
</p>

More result details can be found in our [project proposal](https://github.com/coffeestains1908/neuon-hackwknd-cropai#project-proposal).

### Android App
A simple app is developd to use the model trained on mobile phone, the result are shown below. The app can be downloaded via link provided at [beginnig of this page](https://github.com/coffeestains1908/neuon-hackwknd-cropai/blob/master/README.md#prototype-apk).
<p align="center">
  <img src="cropAi_android.png"><br />
  Figure 2
</p>

### PC GUI
Similar user interface is also created to utilise the AI model trained.
<p align="center">
  <img src="cropAI_PC.png"><br />
  Figure 3
</p>

## About us
Neuon AI is a Sarawak based AI solution company specialize in machine learning, computer vision and Internet of Things (IoT). Visit us at www.neuon.ai for more information regarding our projects.
