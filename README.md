# MS-BING Speech Streaming Example

This code is an example of how to use the BING api through the (unofficial) [Microsoft Speech to Text Service](https://github.com/noopkat/ms-bing-speech-service). The code starts the streaming service, reads a file, sends its chunks of data to Bing, and prints back the results of the transcription.

# Before running

Since this is an example, it's a very simple script. Open the file `main.js` and inform the correct values for the `BING_SUBSCRIPTION_API` and `FILENAME` variables. 

 - The bing subscription can be obtained via this link https://azure.microsoft.com/en-gb/try/cognitive-services/, under the "Speech" tab;
 - The filename is the input wav file you wanna run the example with

# To run

Make sure to have `npm` installed. Install the dependencies...

```
$ npm install
```

... and run.

```
$ npm start
```

This should do it. :)