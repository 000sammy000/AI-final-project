# AI-final-project
Task overview:

在這次的project，我們希望能透過Generative AI，自由調整各種款式的衣服。我們使用到StyleGAN2-ADA訓練出的ClothingGAN model，並在google colab上利用Gradio UI library生成介面，可以藉由調整拉桿生成想要的衣服類型，最後用FID評估並分析結果。


code:
  
  1.ClothGAN.ipynb:
    
    environment:Google Colab
    
    packet:The needed packet can be download in the nootbook
    
    usage:loading model and generating image.
    
    reference:https://github.com/mfrashad/ClothingGAN/tree/master
    
   2.evaluation.ipynb:
   
      environment:Google Colab
      
      packet:The needed packet can be download in the nootbook
      
      usage:Using FID to evaluate the result of model.
      
