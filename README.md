# webkitSpeechRecognition-punctuation-demo

## what is this

a demo for [Chromium Bug 1408253](https://bugs.chromium.org/p/chromium/issues/detail?id=1408253)

## how to see the problem

- go to https://www.google.com/intl/en/chrome/demos/speech.html
- click the microphone and then say "this is a test period"
- the dictated result should be "This is a test." i.e. the "period" gets converted into the punctuation sign (and the first letter of the sentence gets capitalized as well)

- now, go to this repo's [published page](https://gregsadetsky.github.io/webkitSpeechRecognition-punctuation-demo/demo.html)
- this page uses the exact same code as the page hosted on google.com linked above
- repeat the steps as above: click the microphone and then say "this is a test period"
- the words "this is a test period" will appear i.e. "period" does not get converted into the punctuation sign
