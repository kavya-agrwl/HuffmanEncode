
Huffman encoding is a popular algorithm for lossless data compression. It assigns variable-length codes to input characters, with shorter codes assigned to more frequent characters. This way, the overall size of the data is reduced.

Key Files in the Project
heap.js

Implements a min-heap data structure, which is crucial for building the Huffman tree.
Methods include insertion, deletion, and heapify operations to maintain the heap properties.
huffman.js

Contains the core Huffman coding logic.
createFrequencyTable: Generates a frequency table of characters in the input data.
buildHuffmanTree: Uses the frequency table and the min-heap to construct the Huffman tree.
generateCodes: Traverses the Huffman tree to generate the binary codes for each character.
encode: Encodes the input data using the generated Huffman codes.
decode: Decodes the encoded data back to its original form using the Huffman tree.

index.html
Provides the user interface to interact with the Huffman coding implementation.
Users can input data to be encoded or decoded, and see the results.

index.php
Handles server-side interactions if any server-side processing is required.

sample.txt
A sample text file to test the encoding and decoding functionality.

script.js
Bridges the interaction between the HTML interface and the Huffman coding functions.
Contains event listeners and handlers to capture user inputs and display results.

style.css
Defines the styles for the HTML interface, making the UI visually appealing and user-friendly.
