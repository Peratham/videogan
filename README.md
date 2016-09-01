Generating Videos with Scene Dynamics
=====================================

This repository contains an implementation of:

    Generating Videos with Scene Dynamics
    Carl Vondrick, Hamed Pirsiavash, Antonio Torralba
    NIPS 2016

which learns from unlabeled video to hallucinate tiny videos.


<table><tr><td>
<strong>Beach</strong><br>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/beach/1.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/beach/2.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/beach/3.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/beach/4.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/beach/5.gif'><br>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/beach/6.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/beach/7.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/beach/8.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/beach/9.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/beach/10.gif'><br>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/beach/11.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/beach/12.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/beach/13.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/beach/14.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/beach/15.gif'>
</td><td>
<strong>Golf</strong><br>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/golf/1.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/golf/2.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/golf/3.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/golf/4.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/golf/5.gif'><br>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/golf/6.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/golf/7.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/golf/8.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/golf/9.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/golf/10.gif'><br>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/golf/11.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/golf/12.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/golf/13.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/golf/14.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/golf/15.gif'>
</td></tr><tr><td>
<strong>Train Station</strong><br>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/train_station/1.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/train_station/2.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/train_station/3.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/train_station/4.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/train_station/5.gif'><br>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/train_station/6.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/train_station/7.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/train_station/8.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/train_station/9.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/train_station/10.gif'><br>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/train_station/11.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/train_station/12.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/train_station/13.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/train_station/14.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/train_station/15.gif'>
</td><td>
<strong>Baby</strong><br>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/hospital/1.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/hospital/2.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/hospital/3.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/hospital/4.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/hospital/5.gif'><br>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/hospital/6.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/hospital/7.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/hospital/8.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/hospital/9.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/hospital/10.gif'><br>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/hospital/11.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/hospital/12.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/hospital/13.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/hospital/14.gif'>
<img src='http://mit.edu/vondrick/tinyvideo/supp/supp/hospital/15.gif'>
</td></tr></table>



Training
--------

The code requires a Torch7 installation. 

To train a generator for video, see main.lua. For the conditional version, see
main_conditional.lua. To generate videos, see generate.lua

Data
----
The data loading is designed assuming videos have been stabilized and flattened
into JPEG images. For our stabilization code, see the extra directory.
Essentially, you should convert each video into an image of vertically
concatenated frames (this is to make IO more efficient). You then pass a text
file of these frames into the learning code.

Models
------
We provide some pre-trained generators in models/

Notes
-----
The code is based on DCGAN in Torch7.

If you find this useful for your research, please consider citing our NIPS
paper.
