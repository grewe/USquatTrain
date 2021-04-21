# Evaluation Metrics for Tricky (Outlier) Data that rejected from Dataset

## [Private Google Directory Containy Tricky Data](https://drive.google.com/drive/folders/1bRk_fBvS1afQ3dUdFoFqoZ8kql1q0uby?usp=sharing)

## Confusion Matrix
![image](https://user-images.githubusercontent.com/11790686/115632680-1c2a8780-a2bd-11eb-92af-d05204551f8a.png)

##  Data Dump
[6.070077419281006, 0.3645833432674408, array([[[72.,  0.],
        [24.,  0.]],

       [[74.,  2.],
        [20.,  0.]],

       [[80.,  0.],
        [16.,  0.]],

       [[78.,  0.],
        [18.,  0.]],

       [[78.,  0.],
        [18.,  0.]]], dtype=float32)]
tf.Tensor(
[1 1 2 1 4 4 2 1 1 1 4 1 1 1 2 1 4 2 1 4 1 2 4 0 4 3 2 3 2 2 2 1 1 0 4 3 3
 3 4 4 1 1 1 2 2 1 2 4 1 4 1 1 1 2 2 2 1 0 0 0 2 3 2 3 2 3 0 1 0 3 3 0 2 2
 0 3 0 1 0 0 1 2 1 3 1 3 2 2 1 1 2 1 3 1 3 2], shape=(96,), dtype=int64)
tf.Tensor(
[[10  3  5  6  0]
 [ 0 11  4  0  5]
 [ 0  7  5  4  0]
 [ 2  3  5  5  3]
 [ 0  8  6  0  4]], shape=(5, 5), dtype=int32)
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/good/img_8179.mp4
extected: good -- [2.9223770e-04 9.8208851e-01 6.6731456e-03 3.7982682e-04 1.0566323e-02]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/good/img_8418.mp4
extected: good -- [8.1061333e-04 9.9794525e-01 1.2367587e-03 2.4308126e-06 4.9712726e-06]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/good/shallow_30_kelly_01_29_21_14_04.mp4
extected: good -- [2.7150805e-05 2.7824214e-03 9.3847913e-01 1.2216167e-04 5.8589127e-02]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/good/shallow_30_kelly_02_10_21_19_46.mp4
extected: good -- [3.6955860e-03 9.9217469e-01 2.0765448e-03 1.9335520e-03 1.1973355e-04]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/good/shallow_45_amy_01_31_21_16_50.mp4
extected: good -- [1.3440233e-09 7.9438206e-07 3.4902629e-07 7.9971235e-10 9.9999881e-01]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/good/shallow_45_katlyn_01_30_21_21_46.mp4.mp4
extected: good -- [1.3352512e-05 1.2573531e-01 3.2281557e-03 3.4324887e-05 8.7098891e-01]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/good/shallow_45_katlyn_01_30_21_22_09.mp4
extected: good -- [0.00154714 0.02118167 0.9667285  0.00099354 0.00954913]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/good/shallow_90_katlyn_02_08_21_10_28.mp4
extected: good -- [4.2422434e-07 9.9995017e-01 4.9390866e-05 5.5170051e-09 2.0091916e-08]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/good/bent_over_30_katlyn_01_30_21_21_45.mp4
extected: good -- [1.4272740e-07 9.9997687e-01 1.9715840e-06 1.2326696e-08 2.0990496e-05]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/good/bent_over_45_katlyn_01_30_21_21_45.mp4
extected: good -- [8.6730881e-07 9.8669004e-01 3.5445752e-05 7.2138846e-07 1.3272978e-02]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/good/flip_shallow_45_amy_01_31_21_16_50.mp4
extected: good -- [6.5742518e-09 1.1549985e-06 7.0826860e-07 1.3022240e-09 9.9999809e-01]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/good/flip_shallow_90_katlyn_02_08_21_10_28.mp4
extected: good -- [4.05798403e-07 9.99897838e-01 1.01745085e-04 5.61245939e-09
 1.41710528e-08]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/good/flip_img_8179.mp4
extected: good -- [4.7669985e-04 9.8292130e-01 1.2373341e-02 8.6605403e-04 3.3625937e-03]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/good/flip_img_8418.mp4
extected: good -- [4.8092306e-02 9.5072460e-01 1.1580802e-03 2.0245798e-05 4.7672916e-06]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/good/flip_shallow_30_kelly_01_29_21_14_04.mp4
extected: good -- [8.3754703e-06 1.1121364e-03 9.5304555e-01 6.4589804e-05 4.5769282e-02]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/good/flip_shallow_30_kelly_02_10_21_19_46.mp4
extected: good -- [7.0297383e-03 9.8385400e-01 1.0566699e-03 7.9140579e-03 1.4550905e-04]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/good/flip_shallow_45_katlyn_01_30_21_21_46.mp4.mp4
extected: good -- [3.5071473e-05 1.2921235e-01 2.5787824e-03 7.8621008e-05 8.6809522e-01]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/good/flip_shallow_45_katlyn_01_30_21_22_09.mp4
extected: good -- [5.2146619e-04 1.1930403e-02 9.8590708e-01 2.1003796e-04 1.4310007e-03]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/good/flip_bent_over_30_katlyn_01_30_21_21_45.mp4
extected: good -- [2.1354838e-06 9.9901116e-01 1.9114104e-05 7.4220941e-07 9.6682884e-04]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/good/flip_bent_over_45_katlyn_01_30_21_21_45.mp4
extected: good -- [1.437848e-05 4.629521e-01 4.540136e-04 4.119191e-05 5.365383e-01]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/knees_in/img_8072.mp4
extected: knees_in -- [2.4243502e-05 9.9997544e-01 1.6483291e-07 6.8272584e-08 7.1677043e-08]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/knees_in/img_8195.mp4
extected: knees_in -- [1.09093235e-04 5.59174549e-03 9.90934253e-01 2.01358969e-04
 3.16342874e-03]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/knees_in/img_8398.mp4
extected: knees_in -- [2.6631443e-04 3.3124086e-01 1.6914203e-03 5.0620954e-03 6.6173935e-01]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/knees_in/knee_in_45_krishna.mp4
extected: knees_in -- [9.9807239e-01 4.1959743e-04 1.5544632e-04 1.3364634e-03 1.6038677e-05]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/knees_in/knees_in_0_shivani_02_14_21_13_01.mp4
extected: knees_in -- [7.4733203e-10 3.6075241e-07 3.1036688e-08 1.0834728e-07 9.9999952e-01]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/knees_in/knees_in_0_shivani_02_14_21_13_11.mp4
extected: knees_in -- [5.1288607e-06 6.1960198e-04 8.6367959e-07 9.9528557e-01 4.0889443e-03]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/knees_in/knees_in_30_amy_01_31_21_16_52.mp4
extected: knees_in -- [4.7880094e-06 2.6072926e-06 9.9898535e-01 3.5435244e-06 1.0036367e-03]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/knees_in/knees_in_30_kelly_01_29_21_11_26.mp4
extected: knees_in -- [4.0541985e-03 9.8430231e-02 8.7946514e-03 8.8788104e-01 8.3990162e-04]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/knees_in/knees_in_30_kelly_02_10_21_19_45.mp4
extected: knees_in -- [0.03434958 0.17271216 0.5240026  0.26522583 0.0037099 ]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/knees_in/flip_knees_in_30_amy_01_31_21_16_52.mp4
extected: knees_in -- [2.4330525e-06 1.6527922e-06 9.9908972e-01 2.4686824e-06 9.0367720e-04]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/knees_in/flip_img_8195.mp4
extected: knees_in -- [3.2014857e-04 3.2335650e-02 9.6631658e-01 3.9289668e-04 6.3474261e-04]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/knees_in/flip_img_8072.mp4
extected: knees_in -- [1.7620947e-05 9.9998224e-01 7.2475700e-08 5.0754515e-08 2.8285912e-08]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/knees_in/flip_img_8398.mp4
extected: knees_in -- [5.44320465e-05 9.91998732e-01 8.69224605e-05 1.05043466e-04
 7.75500294e-03]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/knees_in/flip_knee_in_45_krishna.mp4
extected: knees_in -- [9.3452007e-01 2.4624341e-03 8.1120676e-04 6.1775837e-02 4.3048593e-04]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/knees_in/flip_knees_in_0_shivani_02_14_21_13_01.mp4
extected: knees_in -- [2.0904267e-06 6.7696796e-04 1.1945145e-06 1.5509346e-03 9.9776888e-01]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/knees_in/flip_knees_in_0_shivani_02_14_21_13_11.mp4
extected: knees_in -- [3.5967842e-05 1.4787868e-02 2.0406358e-06 9.5878410e-01 2.6389986e-02]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/knees_in/flip_knees_in_30_kelly_01_29_21_11_26.mp4
extected: knees_in -- [0.00397882 0.3900453  0.01987193 0.58099556 0.00510833]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/knees_in/flip_knees_in_30_kelly_02_10_21_19_45.mp4
extected: knees_in -- [7.7703626e-05 3.0763930e-04 2.6261276e-05 9.9953055e-01 5.7919809e-05]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/shallow/shallow_0_amy_01_31_21_16_50.mp4
extected: shallow -- [3.1012803e-04 4.3310021e-04 2.2893174e-01 2.5156159e-02 7.4516886e-01]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/shallow/shallow_0_devin_02_08_21_10_25.mp4
extected: shallow -- [2.7140592e-07 5.8789542e-06 2.9204126e-05 2.0339041e-05 9.9994433e-01]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/shallow/shallow_0_katlyn_01_30_21_21_46.mp4
extected: shallow -- [2.7025447e-07 9.9998617e-01 2.1333683e-06 5.7078452e-08 1.1424790e-05]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/shallow/shallow_0_katlyn_01_30_21_22_09.mp4
extected: shallow -- [3.0373602e-07 9.9999034e-01 9.2520286e-06 9.4910764e-09 3.3642756e-08]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/shallow/shallow_0_kelly_01_29_21_11_29.mp4
extected: shallow -- [3.6580276e-03 9.9582601e-01 4.3335793e-04 8.1433893e-05 1.2481130e-06]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/shallow/shallow_0_kelly_01_29_21_14_03.mp4
extected: shallow -- [8.2144223e-05 1.8496459e-02 9.8049164e-01 4.7312476e-04 4.5663369e-04]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/shallow/shallow_30_katlyn_01_30_21_22_09.mp4
extected: shallow -- [0.00152194 0.25945643 0.7336662  0.00086545 0.00449003]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/shallow/shallow_45_katlyn_02_08_21_10_28.mp4
extected: shallow -- [2.5567789e-07 9.9999011e-01 8.7928101e-06 7.2435467e-09 8.8165439e-07]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/shallow/bent_over_30_amy_01_31_21_16_52.mp4
extected: shallow -- [1.6041270e-01 5.6773552e-04 8.2816482e-01 1.0846156e-02 8.6986265e-06]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/shallow/flip_shallow_0_devin_02_08_21_10_25.mp4
extected: shallow -- [7.3638113e-09 1.9529509e-07 2.9149699e-06 5.5650628e-07 9.9999630e-01]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/shallow/flip_shallow_45_katlyn_02_08_21_10_28.mp4
extected: shallow -- [1.0738896e-05 9.9909699e-01 8.2989456e-04 8.6103216e-07 6.1570012e-05]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/shallow/flip_shallow_0_amy_01_31_21_16_50.mp4
extected: shallow -- [1.1438496e-05 2.1165601e-05 3.3639353e-03 1.4041904e-04 9.9646312e-01]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/shallow/flip_shallow_0_katlyn_01_30_21_21_46.mp4
extected: shallow -- [7.8815974e-06 9.9985361e-01 1.8620556e-05 8.2595998e-06 1.1160811e-04]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/shallow/flip_shallow_0_katlyn_01_30_21_22_09.mp4
extected: shallow -- [3.5729397e-06 9.9992752e-01 6.8636822e-05 9.1053316e-08 1.6127592e-07]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/shallow/flip_shallow_0_kelly_01_29_21_11_29.mp4
extected: shallow -- [1.3376149e-02 9.8582053e-01 5.3339876e-04 2.6895487e-04 1.0997107e-06]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/shallow/flip_shallow_0_kelly_01_29_21_14_03.mp4
extected: shallow -- [1.5488616e-04 9.9234134e-03 9.7602057e-01 1.2849072e-02 1.0520886e-03]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/shallow/flip_shallow_30_katlyn_01_30_21_22_09.mp4
extected: shallow -- [1.1203503e-03 3.2566649e-01 6.7302138e-01 1.0907849e-04 8.2624814e-05]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/shallow/flip_bent_over_30_amy_01_31_21_16_52.mp4
extected: shallow -- [1.02401544e-04 1.51819086e-05 9.99793589e-01 7.61424963e-05
 1.26477307e-05]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/bent_over/bent_over_0_youtube_02_09_21_21_50.mp4
extected: bent_over -- [4.8418358e-10 1.0000000e+00 1.9804395e-08 2.2664022e-11 7.8349494e-10]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/bent_over/bent_over_Emmanuel_06.mp4
extected: bent_over -- [9.8372078e-01 1.8750768e-03 1.4089220e-02 1.5136552e-04 1.6341418e-04]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/bent_over/bent_over_Emmanuel_07.mp4
extected: bent_over -- [9.6937066e-01 3.5219711e-07 3.0627297e-02 1.6709574e-06 8.7962695e-09]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/bent_over/bent_over_Emmanuel_08.mp4
extected: bent_over -- [9.9999404e-01 2.2401534e-07 5.7191364e-06 4.1823505e-08 2.4140724e-11]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/bent_over/bent_over_Emmanuel_10.mp4
extected: bent_over -- [1.7253835e-01 3.6960939e-04 7.8781646e-01 1.0472590e-03 3.8228326e-02]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/bent_over/bent_over_Emmanuel_11.mp4
extected: bent_over -- [5.6393023e-05 5.3144060e-04 2.3707561e-03 9.9702495e-01 1.6379236e-05]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/bent_over/bent_over_Emmanuel_12.mp4
extected: bent_over -- [1.4960320e-06 5.6237692e-05 9.2381978e-01 1.0728092e-04 7.6015264e-02]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/bent_over/bent_over_Emmanuel_13.mp4
extected: bent_over -- [6.6021987e-04 6.4969837e-04 2.0650102e-01 6.6320193e-01 1.2898706e-01]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/bent_over/bent_over_Emmanuel_14.mp4
extected: bent_over -- [3.2557626e-05 1.4248516e-05 9.9679083e-01 3.0148064e-03 1.4763298e-04]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/bent_over/bent_over_Emmanuel_15.mp4
extected: bent_over -- [4.09519271e-05 1.09566281e-04 1.06505394e-01 8.93283188e-01
 6.08974442e-05]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/bent_over/bent_over_90_shivali.mp4
extected: bent_over -- [9.9998736e-01 1.6064108e-06 1.1007641e-05 5.4465325e-08 9.8304220e-10]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/bent_over/bent_over_90_zeel.mp4
extected: bent_over -- [4.6064529e-01 5.3878880e-01 3.3146027e-04 2.2906461e-04 5.4250281e-06]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/bent_over/flip_bent_over_Emmanuel_06.mp4
extected: bent_over -- [9.9817789e-01 6.8627245e-04 1.0830717e-03 4.7746973e-05 5.0933891e-06]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/bent_over/flip_bent_over_Emmanuel_11.mp4
extected: bent_over -- [5.9240643e-05 4.6749855e-04 9.6972063e-03 9.8975629e-01 1.9875934e-05]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/bent_over/flip_bent_over_Emmanuel_15.mp4
extected: bent_over -- [2.1064958e-05 3.9283164e-05 1.5204882e-02 9.8467940e-01 5.5361648e-05]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/bent_over/flip_bent_over_Emmanuel_08.mp4
extected: bent_over -- [9.9999833e-01 3.8666126e-08 1.6623642e-06 4.9313416e-09 1.9756332e-12]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/bent_over/flip_bent_over_Emmanuel_12.mp4
extected: bent_over -- [5.7496190e-06 1.1530448e-04 6.5794075e-01 1.8846003e-03 3.4005368e-01]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/bent_over/flip_bent_over_Emmanuel_14.mp4
extected: bent_over -- [5.3230306e-05 2.1211246e-05 9.7016317e-01 2.8516524e-02 1.2458471e-03]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/bent_over/flip_bent_over_Emmanuel_07.mp4
extected: bent_over -- [9.9996591e-01 4.0997456e-08 3.4034420e-05 1.7764675e-08 2.3549603e-11]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/bent_over/flip_bent_over_Emmanuel_13.mp4
extected: bent_over -- [2.7988752e-04 1.4338455e-04 2.9275483e-02 9.5666957e-01 1.3631662e-02]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/bent_over/flip_bent_over_Emmanuel_10.mp4
extected: bent_over -- [9.8861152e-01 4.2486896e-05 1.1301969e-02 2.2377239e-05 2.1548547e-05]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/bent_over/flip_bent_over_0_youtube_02_09_21_21_50.mp4
extected: bent_over -- [3.2175365e-10 1.0000000e+00 6.8547981e-09 1.5178222e-11 3.2737141e-10]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/bent_over/flip_bent_over_90_shivali.mp4
extected: bent_over -- [9.9999070e-01 4.9460789e-07 8.8061670e-06 1.1658205e-08 3.1517616e-10]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/bent_over/flip_bent_over_90_zeel.mp4
extected: bent_over -- [6.6702944e-01 3.3045003e-01 1.4888555e-03 1.0144856e-03 1.7261664e-05]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/heels_off/img_7991.mp4
extected: heels_off -- [1.0767038e-05 9.7521067e-01 1.9130591e-02 7.6276985e-05 5.5716764e-03]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/heels_off/img_7988.mp4
extected: heels_off -- [5.2573373e-08 1.2064312e-06 9.9999702e-01 4.4593772e-08 1.6711776e-06]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/heels_off/img_8082.mp4
extected: heels_off -- [3.7033463e-04 9.9961662e-01 3.8866756e-06 4.3526957e-06 4.8029615e-06]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/heels_off/heels_off_0_amy_01_31_21_16_51.mp4
extected: heels_off -- [3.6672132e-06 1.8997584e-06 1.2927211e-04 9.9980778e-01 5.7324010e-05]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/heels_off/img_8080.mp4
extected: heels_off -- [1.3423265e-02 9.8636496e-01 2.7926728e-05 1.7183063e-04 1.1958731e-05]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/heels_off/img_8152.mp4
extected: heels_off -- [4.0670919e-05 1.5269735e-04 4.2780678e-04 8.0415076e-01 1.9522804e-01]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/heels_off/img_8149.mp4
extected: heels_off -- [1.7981530e-07 1.3281148e-05 9.9919754e-01 2.1984933e-06 7.8687834e-04]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/heels_off/img_8213.mp4
extected: heels_off -- [2.6781940e-08 2.6666143e-07 9.9937195e-01 5.0518588e-07 6.2736368e-04]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/heels_off/img_8410.mp4
extected: heels_off -- [1.1092577e-07 9.9999964e-01 2.2895073e-07 6.6304234e-10 1.5713665e-08]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/heels_off/flip_img_7991.mp4
extected: heels_off -- [1.7860834e-06 9.9905318e-01 4.8045299e-04 7.4290169e-06 4.5710939e-04]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/heels_off/flip_img_7988.mp4
extected: heels_off -- [1.2055976e-09 8.1827345e-08 9.9999881e-01 1.9495503e-09 1.0445780e-06]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/heels_off/flip_img_8082.mp4
extected: heels_off -- [5.8420387e-04 9.9939263e-01 4.8112411e-06 1.0758200e-05 7.5570993e-06]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/heels_off/flip_heels_off_0_amy_01_31_21_16_51.mp4
extected: heels_off -- [1.91850209e-04 1.05203675e-04 3.54405791e-02 9.61833954e-01
 2.42837425e-03]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/heels_off/flip_img_8080.mp4
extected: heels_off -- [1.19388348e-03 9.98785913e-01 3.79596077e-06 1.40170305e-05
 2.32307252e-06]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/heels_off/flip_img_8152.mp4
extected: heels_off -- [1.4464941e-04 5.2122481e-04 2.0660546e-03 9.7268945e-01 2.4578592e-02]

----------------------------------------
/content/drive/MyDrive/USquat_Training/Test_Set/Mp4_data/heels_off/flip_img_8149.mp4
extected: heels_off -- [2.7455653e-06 9.6193852e-04 9.8071563e-01 2.9716341e-05 1.8290039e-02]
