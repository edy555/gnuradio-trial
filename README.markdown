gnuradio-trial
==============

# What is this?

GNURadio is the toolkit that treats realtime signal processing written
in C++ and python. GNURadio is used for composing Software Defined
Radio (SDR). I tried to use GNURadio in these days, I had some
experiences about GNURadio. I thought that my experience is valuable
for newbies of GNURRadio, so I started to share know-hows about
using GNURadio for amatures.

This folder contains a number of GNURadio trivial samples.

[jp]

GNURadioは、C++とpythonで実装された信号処理ツールキットです。ソフトウェ
アレディオ(SDR)を構築するために使われています。先日GNURadioを使い始めま
した。初心者の経験したことはGNURadioをこれから始める方にお役に立つので
はないかと思ったので、アマチュアがGNURadioを使うためのノウハウを公開す
ることにしました。

このフォルダには、GNURadioの簡単なサンプルがあります。

# Requirements

## Software

 * GNURadio http://gnuradio.org/
 * RTL-SDR http://sdr.osmocom.org/trac/wiki/rtl-sdr
 * Linux or OSX

## Hardware

 * PC or Mac
 * RTL2832U DVB-T USB-Dongle
 * Antenna

# How to run

        $ git clone git://github.com/edy555/gnuradio-trial
		$ cd gnuradio-trial
  		$ gnuradio-companion fmradio.grc

# Contains

 * fmradio.grc
   * Wideband FM Broadcasting RX
 * fmradio-fft.grc
   * FM-RX with FFT
 * fmradio-osmosdr-fft.grc
   * FM-RX using osmosdr block
 * nbfm-2m-fft.grc
   * 144MHz Narrow-band FM RX with FFT
 * nbfm-70cm.grc
   * 435MHz Narrow-band FM RX
 * airband-fft.grc
   * VHF AM radio
 * acars-audioin.grc
   * ACARS RX - VHF Aircraft Location info (reqiuires gr-acars)
 * README.markdown
   * This file you read
 * udp_audio_sink.grc

# References

 * GNURadio http://gnuradio.org/
 * RTL-SDR http://sdr.osmocom.org/trac/wiki/rtl-sdr
 * gr-acars https://www.cgran.org/wiki/ACARS

# Author

 * web site http://ttrftech.tumblr.com/ (written in Japanese)
 * twitter @edy555
 * github https://github.com/edy555/gnuradio-trial
