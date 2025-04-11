# ERC-Convener-Submission
Q2-Tech

I've used scipy and processed the audio file.Then i did fft on it to chang it to frequency domain.I've plotted the graph and saw that there are two peaks but I didnt think it meant anything (back then) so I've used the highest amplitude containing frequency and demodulated it using that.
Next I tried removing the noise by removing all the frequencies with less amplitudes.Then I inverse fft-ed the result, but didnt really get anywhere.
Then I realized that the audio might have a range of frequencies and also that the 2 peaks meant it's modulated wave is of the form "ACos(M)Cos(Fc)" which means the 2 peaks have the frequencies (Fc-M) and (Fc+M)
But I still couldnt solve it....
