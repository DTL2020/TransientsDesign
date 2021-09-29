Visual web-browser based tool to design colour transients in 4:2:2 Y'CbCr subsamped format.
Typical workflow - fill left and right Y'CbCr colour values, push Set Left Colour and Set Right Colour buttons to apply changes. Push Set Hard jump button to set initial transients values as hard jump at the middle of 10 transient samples. Adjust 10 transient samples to get linear R,G,B and I(ntensity ?) values to be smooth as expected (as possible).
Switch Chroma Int button switches chroma interpolation between Hard cut sinc (only in-between Cb Cr samples are interpolated) or Anti-ringing filtering + interpolation. 
AR filtered input samples and interpolated displayed in geryed-out fields below input Cb Cr samples.
Rec.709 matrix and transfer version comitted.
For displaying charts - Chart.js is used . See license on Chart.js project.
