This sample file is for converting the ABRAM code, along with all its submodules, from an online to an offline setup.

Run this in Google Colab

!git clone https://github.com/andrepiz/abram.git


%cd /content/abram/


!pwd


!git submodule init


!git submodule update


!zip  /content/abram_v2.zip /content/abram






After that, transfer the .zip file to the offline environment.
