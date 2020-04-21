# ganilla_for_recommender

Experiments by noah and yves


THIS CODE IS FROM https://github.com/giddyyupp/ganilla/
Modified for a recommender system

Run test.py
``` bash
python test.py --dataroot .\datasets\recomm --name recomm_cyclegan --model cycle_gan --netG resnet_fpn
```

Run train.py
``` bash
python test.py --dataroot .\datasets\recomm --name recomm_cyclegan --model cycle_gan --netG resnet_fpn --niter 9 --niter_decay 1 --continue_train
```
