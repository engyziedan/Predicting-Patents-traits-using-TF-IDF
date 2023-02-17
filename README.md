# Predicting-Patents-traits-using-TF-IDF
On a sample of 6000 ish patents we predicted whether the medical device patent pertains to portability or safety
/data/predictions_v2.xlsx is available upon request. Its produced from scrapping 80,000 patents that mention terms related to dialysis. Running a TF-IDF model that predicts "relevant patents". We find that only 6000 patents with terms related to dialysis are kidney dialysis machines. 
The output of this code is portability_safety_with_probs_6000_patents.xlsx which assigns to each of the 6000 patents a probability value. 
