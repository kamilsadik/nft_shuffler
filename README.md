# NFT Shuffler

This Jupyter Notebook is designed to help NFT collection creators to shuffle the images in their collection. The use case is a situation in which a creator creates their collection in a manner resulting in clusters of various NFT types, which they would then like to shuffle to ensure a fair mint.

The notebook ingests image files and metadata files from a source directory, shuffles them (while maintaining correspondence between each image and its metadata), and then writes them to the destination directory.