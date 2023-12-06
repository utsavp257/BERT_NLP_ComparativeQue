This directory consists of all the datasets used in the project.
MySQuADDataset_With_Ans_New.json is the stress-test dataset that is used for testing the performance of fine-tuned BERT models on comparative questions (questions which involve comparison of 2 or more numerical quantities). It consists of 46 questions.
new_squad_train_w_valid.json is the dataset filtered from SQuAD v2.0 dataset. The filtering was done using POS tagging and the notebook for the same is uploaded as well. This dataset contains 243 questions.
new_squad_drop_train.json is the dataset filtered from both SQuAD 2.0 and DROP dataset using the same filtering conditions.This dataset contains of 1333 questions.
combined_train_final.json is the combined dataset from SQuAD and DROP dataset. It consists of around 3501 questions.
final_15k_dataset.json is the final dataset with more than 15,000 questions.
