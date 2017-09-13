# gender_difference_fMRI
the code of the project of gender difference with both fMRI data and behaviour data

## Procedure
  1. Read bev/demo.mat get filename id and gender label
  2. Read features from 4_MRI2atlas_AAL_thr_2hao/ folder, only get upper triangle
   items of each matrix without including the diagonal items, change to vector
   by row 
  3. Apply classifier to get 5 cross validation accuracy

## Results

1. AdaBoostClassifier achieve best accuracy 
   - 0.684 accuracy without feature scaling
   - 0.727 accuracy with feature scaling
2. Top three most important features: 5810 (0.040000), 6179 (0.040000), 4820 (0.040000)

