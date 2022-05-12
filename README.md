# Building the Intuition

1. Get the `window.speechRecognition` and make a `new` instance of it.
2. Put `recognition.interimResults` to populate results continuously as we speak.
3. Create a 'p' element and append it to 'words' element as a child.
4. Add an event listener to recognition for the event `result`
5. Convert the coming event to array with `Array.from()` and map over it twice to get the transcript and then join them
6. Add another event listener for the end event and run `recognition.start`.
7. make the p text content equal to transcript.
8. and use the isFinal bool to create a new p element & populate it.
9. We can play with `transcript.contains`.
