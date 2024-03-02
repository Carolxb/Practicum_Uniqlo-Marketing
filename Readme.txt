Project: Prompt Engineering and API connection

Instructions to run the ipynb file: 
Before opening your Jupyter notebook or any coding platform, make sure to execute this command first:
export REPLICATE_API_TOKEN=r8_WD5wEZ50FkJTafTvJUKRn4H7tRIKH5Q2vMeMC
(This code connects to the Replicate API.)
After entering this command, you can begin running the code.

Within the code, you can change the picture URL in the Replicate API code. For example, here I've used "https://image.uniqlo.com/UQ/ST3/us/imagesgoods/465185/item/usgoods_71_465185.jpg?width=700" as the picture link. You can change to any picture you want and provide instructions to change picture's color or any other adjustments you desire.
 
Before proceeding to the prompt engineering models, I reviewed the PDF file ("instruction.pdf"), which contains all the instructions or templates to be incorporated into the models.

Next, there are three prompt engineering models: LLMChain, Few-shot, and Sequential Chain. For the LLMChain model, you can replace the "image.jpg" file with any file you wish to use as the input image. In the customized_text variable, you can input the user's matrices information. Also, remember to include a question such as "Please write marketing content based on the template" to guide the model in generating marketing content.

For the second model, Few-shot, the same instructions apply. You can replace "image.jpg" with any image for input into the model. Now, input the user's matrices into the suffix variable instead of customized_text.

For the third model, Sequential Chains, the user's matrices are now input into the input_text. Similarly, you can replace "image.jpg" with any image file.
