# Session6_GAN
Session 6 GAN Assignment

In this assignment, we used Indian Car Images. We used only Red car images. The dataset is lying in folder:
https://drive.google.com/file/d/1eFxfsD0Rhgh8yTYjv_7CWlcc6Ucgh10z/view?usp=sharing

We used DCGAN code to generate Images:

After 4500 eochs the output is like below:

![Project Report](/DCGAN_step04500.jpg )

Logs are as below:

Epoch: 0/10000, Step: 0, D Loss: 1.3927, G Loss: 0.8709, Time:05:15:00
Epoch: 0/10000, Step: 0, D Loss: 1.4078, G Loss: 0.8566, Time:05:15:01
Epoch: 0/10000, Step: 0, D Loss: 1.4065, G Loss: 0.8490, Time:05:15:02
Epoch: 0/10000, Step: 0, D Loss: 1.3922, G Loss: 0.8237, Time:05:15:03
Epoch: 0/10000, Step: 0, D Loss: 1.3577, G Loss: 0.8054, Time:05:15:04
Epoch: 0/10000, Step: 0, D Loss: 1.3273, G Loss: 0.7902, Time:05:15:05
Epoch: 500/10000, Step: 500, D Loss: 1.3400, G Loss: 0.6438, Time:05:30:03
Epoch: 500/10000, Step: 500, D Loss: 1.3400, G Loss: 0.6335, Time:05:30:04
Epoch: 500/10000, Step: 500, D Loss: 1.3400, G Loss: 0.6265, Time:05:30:04
Epoch: 500/10000, Step: 500, D Loss: 1.3400, G Loss: 0.6181, Time:05:30:05
Epoch: 500/10000, Step: 500, D Loss: 1.3400, G Loss: 0.6120, Time:05:30:06
Epoch: 500/10000, Step: 500, D Loss: 1.3400, G Loss: 0.6072, Time:05:30:07
Epoch: 1000/10000, Step: 1000, D Loss: 1.3523, G Loss: 0.7198, Time:05:45:07
Epoch: 1000/10000, Step: 1000, D Loss: 1.3523, G Loss: 0.7062, Time:05:45:07
Epoch: 1000/10000, Step: 1000, D Loss: 1.3523, G Loss: 0.6933, Time:05:45:07
Epoch: 1000/10000, Step: 1000, D Loss: 1.3523, G Loss: 0.6844, Time:05:45:08
Epoch: 1000/10000, Step: 1000, D Loss: 1.3523, G Loss: 0.6772, Time:05:45:10
Epoch: 1000/10000, Step: 1000, D Loss: 1.3523, G Loss: 0.6691, Time:05:45:11
Epoch: 1500/10000, Step: 1500, D Loss: 1.4358, G Loss: 0.6634, Time:06:00:09
Epoch: 1500/10000, Step: 1500, D Loss: 1.4241, G Loss: 0.6962, Time:06:00:10
Epoch: 1500/10000, Step: 1500, D Loss: 1.4047, G Loss: 0.7107, Time:06:00:11
Epoch: 1500/10000, Step: 1500, D Loss: 1.3816, G Loss: 0.7108, Time:06:00:12
Epoch: 1500/10000, Step: 1500, D Loss: 1.3845, G Loss: 0.7088, Time:06:00:13
Epoch: 1500/10000, Step: 1500, D Loss: 1.3694, G Loss: 0.6987, Time:06:00:13
Epoch: 2000/10000, Step: 2000, D Loss: 1.3623, G Loss: 0.6467, Time:06:15:11
Epoch: 2000/10000, Step: 2000, D Loss: 1.3623, G Loss: 0.6394, Time:06:15:12
Epoch: 2000/10000, Step: 2000, D Loss: 1.3623, G Loss: 0.6375, Time:06:15:12
Epoch: 2000/10000, Step: 2000, D Loss: 1.3623, G Loss: 0.6293, Time:06:15:13
Epoch: 2000/10000, Step: 2000, D Loss: 1.3623, G Loss: 0.6235, Time:06:15:14
Epoch: 2000/10000, Step: 2000, D Loss: 1.3623, G Loss: 0.6203, Time:06:15:15
Epoch: 2500/10000, Step: 2500, D Loss: 1.3180, G Loss: 0.7166, Time:06:30:15
Epoch: 2500/10000, Step: 2500, D Loss: 1.3180, G Loss: 0.6792, Time:06:30:15
Epoch: 2500/10000, Step: 2500, D Loss: 1.3180, G Loss: 0.6609, Time:06:30:16
Epoch: 2500/10000, Step: 2500, D Loss: 1.3180, G Loss: 0.6468, Time:06:30:16
Epoch: 2500/10000, Step: 2500, D Loss: 1.3180, G Loss: 0.6392, Time:06:30:18
Epoch: 2500/10000, Step: 2500, D Loss: 1.3180, G Loss: 0.6329, Time:06:30:19
Epoch: 3000/10000, Step: 3000, D Loss: 1.4229, G Loss: 0.7324, Time:06:45:17
Epoch: 3000/10000, Step: 3000, D Loss: 1.4339, G Loss: 0.7853, Time:06:45:18
Epoch: 3000/10000, Step: 3000, D Loss: 1.3230, G Loss: 0.7866, Time:06:45:19
Epoch: 3000/10000, Step: 3000, D Loss: 1.3130, G Loss: 0.7687, Time:06:45:20
Epoch: 3000/10000, Step: 3000, D Loss: 1.2969, G Loss: 0.7995, Time:06:45:21
Epoch: 3000/10000, Step: 3000, D Loss: 1.2955, G Loss: 0.8196, Time:06:45:22
Epoch: 3500/10000, Step: 3500, D Loss: 1.1955, G Loss: 0.6486, Time:07:00:19
Epoch: 3500/10000, Step: 3500, D Loss: 1.1955, G Loss: 0.6273, Time:07:00:20
Epoch: 3500/10000, Step: 3500, D Loss: 1.1955, G Loss: 0.6062, Time:07:00:20
Epoch: 3500/10000, Step: 3500, D Loss: 1.1955, G Loss: 0.5869, Time:07:00:21
Epoch: 3500/10000, Step: 3500, D Loss: 1.1955, G Loss: 0.5781, Time:07:00:22
Epoch: 3500/10000, Step: 3500, D Loss: 1.1955, G Loss: 0.5595, Time:07:00:23
Epoch: 4000/10000, Step: 4000, D Loss: 1.1225, G Loss: 0.8848, Time:07:15:23
Epoch: 4000/10000, Step: 4000, D Loss: 1.1225, G Loss: 0.8373, Time:07:15:23
Epoch: 4000/10000, Step: 4000, D Loss: 1.1225, G Loss: 0.7944, Time:07:15:24
Epoch: 4000/10000, Step: 4000, D Loss: 1.1225, G Loss: 0.7691, Time:07:15:25
Epoch: 4000/10000, Step: 4000, D Loss: 1.1225, G Loss: 0.7346, Time:07:15:26
Epoch: 4000/10000, Step: 4000, D Loss: 1.1225, G Loss: 0.7190, Time:07:15:27
Epoch: 4500/10000, Step: 4500, D Loss: 2.1457, G Loss: 0.8616, Time:07:30:25
Epoch: 4500/10000, Step: 4500, D Loss: 1.3128, G Loss: 1.8381, Time:07:30:26
Epoch: 4500/10000, Step: 4500, D Loss: 1.2139, G Loss: 1.3026, Time:07:30:27
Epoch: 4500/10000, Step: 4500, D Loss: 1.1207, G Loss: 1.0061, Time:07:30:28
Epoch: 4500/10000, Step: 4500, D Loss: 0.5481, G Loss: 1.5315, Time:07:30:29
Epoch: 4500/10000, Step: 4500, D Loss: 1.0919, G Loss: 1.1356, Time:07:30:30
Epoch: 5000/10000, Step: 5000, D Loss: 0.9107, G Loss: 0.7951, Time:07:45:28
Epoch: 5000/10000, Step: 5000, D Loss: 0.9107, G Loss: 0.7737, Time:07:45:28
Epoch: 5000/10000, Step: 5000, D Loss: 0.9107, G Loss: 0.7326, Time:07:45:29
Epoch: 5000/10000, Step: 5000, D Loss: 0.9107, G Loss: 0.7038, Time:07:45:30
Epoch: 5000/10000, Step: 5000, D Loss: 0.9107, G Loss: 0.7269, Time:07:45:31
Epoch: 5000/10000, Step: 5000, D Loss: 0.9107, G Loss: 0.6964, Time:07:45:32
Epoch: 5500/10000, Step: 5500, D Loss: 0.3060, G Loss: 1.6652, Time:08:00:32
Epoch: 5500/10000, Step: 5500, D Loss: 0.3060, G Loss: 1.4998, Time:08:00:32
Epoch: 5500/10000, Step: 5500, D Loss: 0.3060, G Loss: 1.4276, Time:08:00:33
Epoch: 5500/10000, Step: 5500, D Loss: 0.3060, G Loss: 1.3692, Time:08:00:33
Epoch: 5500/10000, Step: 5500, D Loss: 0.3060, G Loss: 1.3049, Time:08:00:34
Epoch: 5500/10000, Step: 5500, D Loss: 0.3060, G Loss: 1.3213, Time:08:00:35
Epoch: 6000/10000, Step: 6000, D Loss: 0.4553, G Loss: 1.6347, Time:08:15:33
Epoch: 6000/10000, Step: 6000, D Loss: 0.2955, G Loss: 2.3095, Time:08:15:34
Epoch: 6000/10000, Step: 6000, D Loss: 0.5620, G Loss: 1.9382, Time:08:15:35
Epoch: 6000/10000, Step: 6000, D Loss: 0.3668, G Loss: 2.1440, Time:08:15:36
Epoch: 6000/10000, Step: 6000, D Loss: 0.2589, G Loss: 2.3757, Time:08:15:37
Epoch: 6000/10000, Step: 6000, D Loss: 1.5959, G Loss: 1.6180, Time:08:15:38
Epoch: 6500/10000, Step: 6500, D Loss: 0.3745, G Loss: 1.1666, Time:08:30:36
Epoch: 6500/10000, Step: 6500, D Loss: 0.3745, G Loss: 1.2121, Time:08:30:36
Epoch: 6500/10000, Step: 6500, D Loss: 0.3745, G Loss: 1.1090, Time:08:30:36
Epoch: 6500/10000, Step: 6500, D Loss: 0.3745, G Loss: 1.0437, Time:08:30:37
Epoch: 6500/10000, Step: 6500, D Loss: 0.3745, G Loss: 1.0153, Time:08:30:38
Epoch: 6500/10000, Step: 6500, D Loss: 0.3745, G Loss: 0.8928, Time:08:30:39
Epoch: 7000/10000, Step: 7000, D Loss: 0.0186, G Loss: 4.4567, Time:08:45:39
Epoch: 7000/10000, Step: 7000, D Loss: 0.0186, G Loss: 4.3594, Time:08:45:40
Epoch: 7000/10000, Step: 7000, D Loss: 0.0186, G Loss: 4.3150, Time:08:45:40
Epoch: 7000/10000, Step: 7000, D Loss: 0.0186, G Loss: 4.3447, Time:08:45:41
Epoch: 7000/10000, Step: 7000, D Loss: 0.0186, G Loss: 4.5043, Time:08:45:42
Epoch: 7000/10000, Step: 7000, D Loss: 0.0186, G Loss: 4.3285, Time:08:45:43
Epoch: 7500/10000, Step: 7500, D Loss: 0.6438, G Loss: 2.2295, Time:09:00:41
Epoch: 7500/10000, Step: 7500, D Loss: 0.3659, G Loss: 2.6075, Time:09:00:42
Epoch: 7500/10000, Step: 7500, D Loss: 0.2397, G Loss: 2.7985, Time:09:00:43
Epoch: 7500/10000, Step: 7500, D Loss: 0.4123, G Loss: 1.9093, Time:09:00:44
Epoch: 7500/10000, Step: 7500, D Loss: 0.2843, G Loss: 2.0649, Time:09:00:45
Epoch: 7500/10000, Step: 7500, D Loss: 0.2837, G Loss: 2.3892, Time:09:00:46
Epoch: 8000/10000, Step: 8000, D Loss: 0.4377, G Loss: 1.0333, Time:09:15:44
Epoch: 8000/10000, Step: 8000, D Loss: 0.4377, G Loss: 0.9418, Time:09:15:44
Epoch: 8000/10000, Step: 8000, D Loss: 0.4377, G Loss: 0.8733, Time:09:15:45
Epoch: 8000/10000, Step: 8000, D Loss: 0.4377, G Loss: 0.8699, Time:09:15:45
Epoch: 8000/10000, Step: 8000, D Loss: 0.4377, G Loss: 0.8821, Time:09:15:46
Epoch: 8000/10000, Step: 8000, D Loss: 0.4377, G Loss: 0.7967, Time:09:15:47
Epoch: 8500/10000, Step: 8500, D Loss: 0.0829, G Loss: 2.9274, Time:09:30:47
Epoch: 8500/10000, Step: 8500, D Loss: 0.0829, G Loss: 2.7106, Time:09:30:47
Epoch: 8500/10000, Step: 8500, D Loss: 0.0829, G Loss: 2.6975, Time:09:30:47
Epoch: 8500/10000, Step: 8500, D Loss: 0.0829, G Loss: 2.4272, Time:09:30:48
Epoch: 8500/10000, Step: 8500, D Loss: 0.0829, G Loss: 2.3136, Time:09:30:49
Epoch: 8500/10000, Step: 8500, D Loss: 0.0829, G Loss: 2.2734, Time:09:30:50
Epoch: 9000/10000, Step: 9000, D Loss: 1.0282, G Loss: 1.6085, Time:09:45:48
Epoch: 9000/10000, Step: 9000, D Loss: 0.3145, G Loss: 2.3148, Time:09:45:49
Epoch: 9000/10000, Step: 9000, D Loss: 0.1438, G Loss: 3.0724, Time:09:45:50
Epoch: 9000/10000, Step: 9000, D Loss: 0.0689, G Loss: 3.7336, Time:09:45:51
Epoch: 9000/10000, Step: 9000, D Loss: 1.6924, G Loss: 2.1782, Time:09:45:52
Epoch: 9000/10000, Step: 9000, D Loss: 0.1591, G Loss: 1.8119, Time:09:45:52
Epoch: 9500/10000, Step: 9500, D Loss: 0.3563, G Loss: 1.4326, Time:10:00:50
Epoch: 9500/10000, Step: 9500, D Loss: 0.3563, G Loss: 1.5574, Time:10:00:50
Epoch: 9500/10000, Step: 9500, D Loss: 0.3563, G Loss: 1.4853, Time:10:00:50
Epoch: 9500/10000, Step: 9500, D Loss: 0.3563, G Loss: 1.3683, Time:10:00:51
Epoch: 9500/10000, Step: 9500, D Loss: 0.3563, G Loss: 1.3611, Time:10:00:52
Epoch: 9500/10000, Step: 9500, D Loss: 0.3563, G Loss: 1.4182, Time:10:00:53


