For this project, I drew inspiration from alums of the M24 class who had the idea of transferring style in music through instrument style extraction and transferring it to another son. Nevertheless, the project was never pursued.

Therefore, I attempted to make a project of my own. I first tried to extract a song, let's call it the target style, and transfer it to another song of choice, let's call it the target song. That is shown in the notebook "Music processor not working attempt 1"—the attempt aimed to process the songs as spectrograms and extract and transfer styles. As the title says, it was a failed attempt. Therefore, I decided to use a different approach.

I then found a prominent enough data set comprised of Nintendo Entertainment System (NES) songs and sounds. Then, I decided to use a Mel-frequency Cepstral approach to train an LSTM model on the NES data and use it as a generative model using a target song as the seed. This approach worked much better as it would access the songs, but the output was just a series of beats. I called this a win.

Finally, I could expand my approach by processing the spectrogram songs through an autoencoder to extract more features from the audio, changing the input file type and using thisinputtformsLSTMTMM. This new approach could promise to deliver better results.
