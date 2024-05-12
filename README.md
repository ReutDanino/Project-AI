# Project-AI
Assisting dyslexic individuals in identifying reversed letters written in mirror script is the aim of this project.                                                                                                                         
Such individuals often struggle to discern whether they've written a letter correctly.

Presently, there exists no solution to aid them in handwritten writing; technological alternatives primarily involve computerized assistance.                                                                                                 
To enable them to engage in manual writing tasks like others, we devised this project.

Users are required to upload a photo of handwritten text, which will then be returned to them with reversed letters highlighted.                                                                                                      
Leveraging an existing model from Hugging Face, designed to transcribe handwritten text into digital format, we facilitated a comparison across three texts.
This involved the original model's output, images of individual letters uploaded to the model and returned, and the reverse image, with each letter being analyzed.
By juxtaposing these texts, we successfully identified the reversed letters, which were then highlighted and returned to the user.
