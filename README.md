# Response

Comparison with ALIU and ALDN

<img width="1057" height="285" alt="table" src="https://github.com/user-attachments/assets/ad1998b6-60a8-4f5b-b87b-b960a160916c" />

ALIU: J. Tu, X. Tang, S. Gu, Y. Dai, R. Fan, and C. Hou, “Adaptive learning in imbalanced data streams with unpredictable feature evolution,” IEEE Transactions on Knowledge and Data Engineering, vol. 37, no. 4, pp. 1527–1541, 2025.

ALDN: S. Gu, C. Xu, D. Hu, , and C. Hou, “Adaptive learning for dynamic features and noisy labels,” IEEE Transactions on Pattern Analysis and Machine Intelligence, vol. 47, no. 2, pp. 1219–1237, 2025.

To test the learned network, we do a retrieval experiment in which we use one modality input to get outputs from the other modalities. For instance, when inputting an apple image, we expect to output the word "apple" and the taste of an apple; when inputting the word "sweet," we aim to output the sweet taste in the taste channel. Table 1 shows the results of the experiments. Our method gets the highest accuracy. Task V in Table 1 means we use visual input to get auditory and taste outputs. Task A means using auditory input to get visual and taste outputs, and Task T is defined similarly.


Update rule:

<img width="1201" height="255" alt="Guassian" src="https://github.com/user-attachments/assets/1d6c33bb-7bfa-49af-ba74-8b342147a415" />


Variations of network architecture and connection parameters with channel expansion:

<img width="1758" height="694" alt="Integrator" src="https://github.com/user-attachments/assets/7f6a449c-004a-47c8-9f92-62981128dbc3" />
Change of a substructure of the network which represents concept pear and strawberry. The icons and vectors next to the neurons (circles) represent objects which the neurons maximally respond to.
