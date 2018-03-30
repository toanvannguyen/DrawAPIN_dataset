# Draw-A-PIN_dataset
Dataset for finger-drawn PIN authentication

## What is Draw-A-PIN
Draw-A-PIN is a user authentication system on a device with a touch interface that supports the use of PINs. In Draw-A-PIN system, the user is asked to draw his/her PIN on the touch screen instead of typing it on a keypad. Consequently, Draw-A-PIN could offer better security by utilizing drawing traits or behavioral biometrics as an additional authentication factor beyond just the secrecy of the PIN. In addition, Draw-A-PIN inherently provides acceptability and usability by leveraging user familiarity with PINs.

<img src="http://toannguyen.me/img/draw_a_pin.gif"/>

To learn more about this authentication technique, please read our journal paper:
_Toan Nguyen, Napa Sae-Bae, and Nasir Memon. "DRAW-A-PIN: Authentication using finger-drawn PIN on touch devices." Computers & Security 66 (2017): 115-128._
[Download](http://toannv.com/Draw-A-PIN.pdf)

## The data set
The data set includes raw data of finger-drawn PIN samples of 20 users over the course of ten days. Each sample contains touch data of four digits in the PIN. Each digit contains five timeseries (x,y-coordinates, pressure, area of touch, and timestamp) captured on a touchscreen when the user draws her PIN. It also includes samples of attackers on two immitation attacks. For more details, please refer to our paper.

Once you download and extract the tarball file, please read **README.txt** for detailed data format.
Contact the first author for any question you have regarding the data set and this research.

Kindly cite following articles in any of your publication that benefits from the this data set:

_Toan Nguyen, Napa Sae-Bae, and Nasir Memon. "DRAW-A-PIN: Authentication using finger-drawn PIN on touch devices." Computers & Security 66 (2017): 115-128._

***bibtex:***
```@article{van2017draw,
  title={DRAW-A-PIN: Authentication using finger-drawn PIN on touch devices},
  author={Van Nguyen, Toan and Sae-Bae, Napa and Memon, Nasir},
  journal={Computers \& Security},
  volume={66},
  pages={115--128},
  year={2017},
  publisher={Elsevier}
}
```

and

_Toan Nguyen, Napa Sae-Bae, and Nasir Memon. "Finger-drawn pin authentication on touch devices." Image Processing (ICIP), 2014 IEEE International Conference on. IEEE, 2014._

bibtex:
```@inproceedings{van2014finger,
  title={Finger-drawn pin authentication on touch devices},
  author={Van Nguyen, Toan and Sae-Bae, Napa and Memon, Nasir},
  booktitle={Image Processing (ICIP), 2014 IEEE International Conference on},
  pages={5002--5006},
  year={2014},
  organization={IEEE}
}
```
