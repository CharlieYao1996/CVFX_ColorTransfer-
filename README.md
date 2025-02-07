# CVFX_ColorTransfer 

  # 1.cycleGAN training process 
  We use apple2orange dataset and we trained 200 epoches.
  <br>
  While we find that 180 epoches have the best performance.
  ![image](https://github.com/CharlieYao1996/CVFX_ColorTransfer-/blob/master/progress%20bar.png)
  # 2.Inference cycleGAN in personal image
  >## situation1:white_base &only one target
  >>### apple2orange
  >>![image](https://github.com/CharlieYao1996/CVFX_ColorTransfer-/blob/master/apple2orange_Epoch200_01.png)
  >>### orange2apple
  >>![image](https://github.com/CharlieYao1996/CVFX_ColorTransfer-/blob/master/orange2apple_Epoch200_01.png)
  >## situation2:lots of targets
  >>### apple2orange
  >>![image](https://github.com/CharlieYao1996/CVFX_ColorTransfer-/blob/master/apple2orange_Epoch200_02.PNG)
  >>### orange2apple
  >>![image](https://github.com/CharlieYao1996/CVFX_ColorTransfer-/blob/master/orange2apple_Epoch200_02.PNG)
  # 3.Compare with [Super fast color transfer between images](https://github.com/jrosebr1/color_transfer)
  >## situation1:white_base &only one target
  >>### apple2orange
  >>![image](https://github.com/CharlieYao1996/CVFX_ColorTransfer-/blob/master/apple2orange_ref_01.png)
  >>### orange2apple
  >>![image](https://github.com/CharlieYao1996/CVFX_ColorTransfer-/blob/master/orange2apple_ref_01.png)
  >## situation2:lots of targets
  >>### apple2orange
  >>![image](https://github.com/CharlieYao1996/CVFX_ColorTransfer-/blob/master/apple2orange_ref_02.PNG)
  >>### orange2apple
  >>![image](https://github.com/CharlieYao1996/CVFX_ColorTransfer-/blob/master/orange2apple_ref_02.PNG)
  # 4.conclusion
  According to the above results, CycleGan has better performance in 2 situations. Since CycleGan though the repeatedly training sessions, it can identify the geometric of the target(apple or orange), than transfer the color to right position. Super fast color transfer just transfer the whole color pattarn from source to target, so in situation 1(white_base &only one target), the effect would irrational.
