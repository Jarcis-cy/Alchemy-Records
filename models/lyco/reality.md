# 真实

1. [FilmGirl 胶片风 Film Grain LoHA & LoRA](https://civitai.com/models/33208?modelVersionId=74547)

   ```text
   Provia版本不同于之前0.1到4.0版本LoRA模型，Provia是全新的胶片模拟LoHA模型，使用60张优选后的胶片照作为训练集，以及505张胶片照作为正则化图像集训练而来。其使用方法与Lora类似，需要将模型放入\models\Lora文件夹中，然后使用<lora:FilmGX2:XXX>指令调用。

   Provia版本的胶片质感要明显强于1.0到4.0版本，面部错误率要明显强于0.1和0.2版本。如果你非常在意胶片真是质感，那这个版本是整个胶片系列模型中最推荐使用的版本。但请注意，因为这个版本没有融合其他模型进行面部优化，因此面部崩坏的概率会比v4高一些。
   
   Provia版本不在需要Trigger Words。我常用的CFG范围是6~7，Lora权重通常在0.6~0.8。
   
   请注意：
   
   Clip skip设为1或2时，生成的效果会有所不同，大家可以多尝试看自己喜欢哪种风格。
   
   本LoHA模型的训练集主要为亚洲胶片人像照片，生成欧美人像的效果会受影响。
   ```

   ![](../../assets/reference/FilmGirlLoha.jpeg ':size=40%')
   ![](../../assets/reference/FilmGirlLoha2.jpeg ':size=40%')