# $name$

An awesome Java-based DeepLearning4J project.

## Training

Use maven to train the model.

Example:

    mvn exec:java -Dexec.mainClass="$organization$.$name;format="lower,word"$.Train" -Dexec.args="--input iris.train.csv --output out1.model --epoch 10"

## Evaluation

Example:

    mvn exec:java -Dexec.mainClass="$organization$.$name;format="lower,word"$.Evaluate" -Dexec.args="--input iris.test.csv --model out1.model"

