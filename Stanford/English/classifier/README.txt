﻿TO TRAIN A MODEL FOR ARGUMENT CLASSIFICATION DO:
################################################

1. run python build-model-classifer.py > ./maxent/train.dat
2. cd .\maxent
3. java -classpath .;./lib/trove-3.0.3.jar;./output/classes CreateModel train.dat

This will creat model trainModel.txt, now take any train.test file and test with this model