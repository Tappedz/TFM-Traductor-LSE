# TFM-Traductor-LSE
## RESUMEN
La lengua de signos es el principal método de comunicación para personas sordas y sordomudas y es esencial para garantizar la inclusión de estas personas en una sociedad en expansión y cada vez más diversificada. En España, la lengua de signos se remonta incluso hasta el siglo XVII, siglo en el cual está datado el considerado como primer tratado moderno para la enseñanza oral de sordos. Desde entonces, la lengua de signos española no ha hecho más que evolucionar y actualmente se encuentran variantes de la lengua por comunidades, imitando la propia historia lingüística de la península. 
En este trabajo se presenta el desarrollo de herramientas para la detección del alfabeto de la lengua de signos española que permitan la traducción de estos signos a la población general y que permitan una introducción amigable a la lengua a personas no signantes o aprendiendo la lengua.
El conjunto de herramientas ha sido entrenado con una colección de imágenes del alfabeto de la lengua de signos española. En esta colección a cada letra le corresponden alrededor de 100 muestras que han sido aumentadas a través de la generación sintética de datos. Las herramientas desarrolladas son una CNN básica, un Transformer visual (ViT) y la arquitectura YOLO, todas han sido pre entrenadas con ‘datasets’ generales y en todas se ha realizado un ‘fine-tuning’.
Los resultados obtenidos junto con la comparación de los modelos implementados han resaltado la importancia del conjunto de datos elegido y la eficacia del ‘fine-tuning’ de modelos pre entrenados en la tarea del reconocimiento y detección de signos. Tras la comparación realizada, YOLO es el modelo que ha brillado sobre el resto destacando por su alto rendimiento y su enfoque en la detección de objetos en tiempo real. Sin embargo, el conjunto de datos ha sido un gran limitante y ha tenido un impacto negativo en la calidad de la solución. Disponiendo de un conjunto de datos más amplio y robusto, es muy probable que la solución implementada pudiese detectar los signos de la Lengua de Signos Española de forma más precisa.

## Palabras clave
•	Transformers
•	CNN
•	Reconocimiento de Imágenes
•	Lengua de Signos 
•	Detección de Objetos

## ABSTRACT
Sign language is the primary method of communication for deaf and deaf-mute individuals, and it is essential to ensure the inclusion of these people in an expanding and increasingly diverse society. In Spain, sign language dates back as far as the 17th century, the century in which what is considered the first modern treatise for the oral education of deaf people was written. Since then, Spanish Sign Language has only continued to evolve, and today there are regional variants of the language across different communities, mirroring the linguistic history of the Iberian Peninsula itself.
This work presents the development of tools for the detection of the Spanish Sign Language alphabet, enabling the translation of these signs for the general population and offering a friendly introduction to the language for non-signers or those learning it.
The toolset has been trained using a collection of images of the Spanish Sign Language alphabet. In this collection, each letter corresponds to approximately 100 samples, which have been augmented through synthetic data generation. The developed tools include a basic CNN, a Vision Transformer (ViT), and the YOLO architecture; all have been pre-trained on general datasets and fine-tuned for this specific task.
The results obtained, together with the comparison of the implemented models have highlighted the importance of the chosen dataset and the effectiveness of fine-tuning pre-trained models in the task of sign detection and recognition. After the comparison, YOLO stood out as the most outstanding model due to its high performance and its focus on real-time object detection. Nevertheless, the dataset has been a major obstacle and has impacted negatively on the quality of the solution given. With access to a broader and more robust dataset, it is highly likely that the implemented solution could detect Spanish Sign Language sings with greater accuracy.

## Keywords
•	Transformers
•	CNN
•	Image Recognition
•	Sign Language
•	Object Detection
