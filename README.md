# 22to16-Downsampler

In digital signal processing, downsampling and decimation are terms associated with the process of resampling in a multi-rate digital signal processing system. 
When a digital signal is downsampled, it is necessary to apply a low pass filter to the signal to reduce the signal's bandwidth to less than the Nyquist rate of the new sample rate; otherwise, aliasing will result. It is sometimes necessary to downsample in order to transfer a sample or other signal to a different system that records or stores at a different sample rate. 
This repositories contains a fast and simple 22.5 KHz to 16.0 KHz down-sampler in Java that used in an Android app project in 2015. You can convert `in.wav` file using

```{r, engine='bash', count_lines}
java -jar Downsampler.jar
```

In order to decompress this `.jar` file and see the contents you can use: 
```
jar xf Downsampler.jar
```

## Authors: 
* [Amin Aghaee](https://github.com/aminrd/)
* [Milad Asgari](https://github.com/miladasgari380)
