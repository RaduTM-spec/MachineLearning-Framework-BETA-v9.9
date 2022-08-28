# MLAgent
Set of C# Scripts that can be used to train your AIs in Unity Engine.
Use the latest stable version of the Framework's folder ONLY.
![Image](NNPNG.png)
Neural Network Class contains the code for instantiating a feedforward multilayerPerceptron Neural Network that can be train heuristicaly by backpropagating user actions.

The use of this framework is done by implementing a training strategy, strictly said by overriding some methods where you send observations (inputs) and receive actions (outputs) + creating a suitable, stable and well designed training environment.Check the documentation "How to use the Framework.docx" placed inside the folder of the version.<br />


https://user-images.githubusercontent.com/67599940/187075770-ba61939c-e40e-4d1f-a270-5a8bcec31c84.mp4



-Performance leaks were solved starting from version 2.0.<br />
-NeuralNetwork is more performant starting with version 2.9<br />
-Most tested variant is v3.0 (is monoenvironmental)<br />
-Multienvironmental Training started in version 3.7<br />
-Heuristic Training released in version 4.78<br />
-Substantial testing set for last version 5.0<br />

Current stable version: v4.78 - heuristicTraining free, resonable testing
