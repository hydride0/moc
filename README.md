# moc
[moc trunk release](svn://svn.daper.net/moc/trunk), patched with [eoranged's PulseAudio patch](http://moc.daper.net/node/831). Added two themes and a file containing configure parameters I use (basically just FFmpeg, MIME magic and PulseAudio).

To build and install it like I do:

```
git clone https://github.com/hydride0/moc
`cat configure.options` (or ./configure if you want your own config)
make -j5
sudo make install
```
