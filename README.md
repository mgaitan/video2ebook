# video2ebook

## The idea

Film a video turning pages of the book/document. This will be the input to our script. 

The script will process in few steps. 

1. Find the best frame to use as input image for each page.  TO DO in #1
2. Filter/process these images to be ready to ocr.  Use this https://github.com/mzucker/page_dewarp
3. make the ocr to get the text . Use this https://github.com/jlsutherland/doc2text
4. create the epub. Use https://github.com/aerkalov/ebooklib


To install opencv https://gist.github.com/Asymptote/6d95396a1a45b55e3b63c3ee4d2b7c24
