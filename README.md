Proteins used for training and benchmarking the RBO-EPSILON contact predictor.

data/train_instances contains the protein IDs used in cross-validation
data/test_instances contains the protein IDs used as a hold out set
data/folds contains splits used in 5-fold cross-validation based on train_instances
data/fasta FASTA files for train_instances and test_instances
data/predictions RBO-EPSILON predictions for the benchmark sets
		./CASP11 (FASTA files in fasta/ subdirectory)
      	
      	./PSICOV (from paper: precise structural contact prediction using sparse inverse covariance estimation on large multiple sequence alignments; removed overlapping proteins; FASTA files in fasta/ subdirectory)
      	
      	./pooled (EPC-map_test, from paper: Combining Physicochemical and Evolutionary Information for Protein Contact Prediction; D329, from paper: Predicting residue–residue contacts using random forest models; SVMcon_test, from paper: Improved residue contact prediction using support vector machines and a large feature set; FASTA files in fasta/ subdirectory)

      	./domains_CASP11_fm_targets (domain ranges used in evaluation)