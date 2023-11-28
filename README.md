# USC MS Computer Science - Graduate Coursework Projects

## CSCI 572: Information Retrieval and Web Search Engines

### PROJECT 1: Comparing search engines (Google vs. Bing)

The project compared the search results from Google and Bing for 100 pre-determined queries, determined the overlap with the search results, and calculated correlation using Spearman's rank coefficient (Spearman's rho).

#### Languages, Libraries, and Frameworks:

- Java
- Jsoup
- Gson
- Apache Commons CSV
- Apache Commons Math


### PROJECT 2: Web Crawling 

The project leveraged crawler4j library to crawl a news site and gather/measure various aspects of the crawl, study crawl characteristics and gather webpage metadata. 

#### Languages, Libraries, and Frameworks:

- Java
- Crawl4j
- Jsoup
- Open CV
- Sleepycat Berkeley DB


  
### PROJECT 3: Inverted-index creation

Created a program that index words from multiple text files in k-v format. Processed the files to remove the tab characters. Used MapReduce to count words in the files. The output is the inverted index with unigrams and bigrams. 

#### Languages, Libraries, and Frameworks:

- Java
- Hadoop MapReduce
- HashMap data structure
- Apache Hadoop for handling distributed storage and processing
- Classes provided by Hadoop for specifying the input and output formats for MapReduce jobs
- Hadoop-specific data types for representing textual and integer data in MapReduce jobs



### PROJECT 4: 

### PART 1: Use vector-based similarity search, to retrieve search results that are not keyword-driven

#### Languages, Libraries, and Frameworks:

- Used Weaviate (via Docker) and vectorizer transformer
- Loaded data in json format that would be searched



### PART 2: Crawl a set of pages to create a json file be used by LLM 

- Builder.io GPT-crawler
- npm



### PART 3: Using LLM model with knowledge source 

- small (3.56G) model
- Llama
- external knowledge source (.txt file) vectorized using Chroma
- .gguf format
- Streamlit
  

 
---





## CSCI 576: Multimedia Systems Design (Spring 2023 taught by Instructor Parag Havaldar)

### PROJECT 1: Resampling and Filtering in spatial and temporal domains

The project consists of two parts, each focusing on different aspects of sampling and aliasing. The overall project covers resampling, filtering, spatial and temporal aliasing, and the impact of various parameters on the output.

#### Part 1 - Spatial Resampling and Aliasing:

- Develop a program that processes images.
- The program displays two images side by side: original image displayed on the left: A 512x512 image with a radial pattern of black lines on a white background. Processed output image displayed on the right: The output of the algorithm applied to the original image, creating a resampled image based on the indicated parameters.


#### Part 2 - Temporal Aliasing:

- Develop a program that processes videos.
- Display two videos side by side: original video displayed on the left: A 512x512 video with a radial pattern of black lines, rotating clockwise at a specified speed. Processed output video displayed on the right: A temporally sampled version of the original video, updated at specific times.
- The project includes analysis questions related to experiments with different values of s and fps and a formula for relating them.

### PROJECT 2: Resampling and Filtering in spatial and temporal domains

The project implement image compression using Vector Quantization (VQ). It uses 2-pixel vectors and a specified number of vectors. The steps involve initializing codewords, clustering vectors around codewords, refining and updating codewords iteratively, and quantizing input vectors to produce an output image. The project also covers the following areas:

#### Color Theory:
Color theory using a Rubik's cube under different colored lights.

#### Color Theory Algorithm:
Mapping of a printer's gamut to that of a color CRT monitor. Effectiveness of the algorithm, its performance on different types of images, and suggest improvements.

#### Entropy Coding:
Entropy functions and probabilities for symbols. 

#### Huffman Coding/Entropy:
Huffman codes for text and telegram versions of a letter, compare code lengths, and find which version contains more information.




### FINAL PROJECT: Interactive Media Player  

The project's purpose is to provide an in-depth understanding of multimedia technology. The project involves extracting structure from media elements (video/audio) and building an interactive media player for exploring the media content. The project represents a solution that automatically creates a logical index or table of contents from a video with audio input.

#### Extracting Indexes from Video:

- The project creates a solution that automatically builds a logical index or table of contents from a video with audio input.
- The index is hierarchical .
- The project relies on both visual and auditory information in the input video file.

#### Interactive Media Player:

- Once the index is extracted, the project builds an interactive media player that allows users to explore the media content.
- The media player enables users to jump to any index and browse the video/audio interactively.
- The audio and video components are synchronized.
- Basic player controls (play, pause, stop) are provided.
  
#### User Interface Design:

- The project includes a simple, functional interface that displays the extracted table of contents alongside the video.
- The table of contents is hierarchical and allows selection of different segments (scenes, shots).
- The interface supports play, pause, and stop buttons.


