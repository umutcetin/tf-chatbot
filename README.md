Code is based on seq2seq / NMT tutorial.
https://github.com/tensorflow/nmt


Dependencies
============
* numpy
* scipy
* six
* tensorflow (https://www.tensorflow.org/versions/r0.12/get_started/os_setup.html)


Usage
===========

To train the bot, change `mode = train` in `seq2seq.ini`

Training takes several hours to return relevant answers.

``python execute.py``

To test change `mode = test` in `seq2seq.ini` and execute again.
