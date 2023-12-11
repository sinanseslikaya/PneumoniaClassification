# PneumoniaClassification

Abstract—Pneumonia is one of the most common forms of lung
disease. It (aside from women giving birth) is the leading cause
of hospital admissions in the United States. The condition can
manifest as a result of bacterial or viral infection of the lungs, and
can range from being inconsequential to the patient to potentially
fatal for those with preconditions. For compromised patients,
early/proactive diagnosis can be important for successful curative
treatment for the disease. In this project, we seek to increase the
accessibility, reliability and quality of diagnosis of pneumonia
to improve patient recovery and to assist the doctors in the
location of lung inflammation using chest x-rays of patients. In
the project, this is accomplished using standard image processing
Convolutional Neural Networks and applying transfer learning
to constrain the model for use on pneumonia diagnosis. Similar
work has been done using transfer learning / ensemble learning
on chest x-ray data, however, this project is set apart in it’s use
of a performant yet lightweight CNNs (EfficientNetB0). We use a
dataset from a kaggle library which contains nearly 6000 x-ray
scans. After training our model, we learned that using transfer
learning in medical diagnosis has promising results, and that
upon further development and model iterations, as well as cross
validation ensemble learning, that the diagnosis of Pneumonia
using transfer learning CNNs can be of great assistance to the
doctors of hospitals as a secondary ”opinion”


### Data from: 
Kermany, Daniel; Zhang, Kang;
Goldbaum, Michael (2018),
"Labeled Optical Coherence Tomography (OCT) and Chest X- Ray Images for Classification",
Mendeley Data, v2
http://dx.doi.org/10.17632/rscbjbr9sj.2
