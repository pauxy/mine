# DEAD BABE IS DEAD

## Question Text

HELP!!I CANT OPEN THIS FILE:((
I NEED IT FOR AN ASSIGNMENT ;_;

Created by paux

## Setup Guide
1. upload files

## Distribution
image for "decrypt"
- flag.jpg 

## Solution
1.	The first 7 bytes of a jpg header file are changed, disabling it from being opened. 
2.	This can be solved by using "hexeditor" on linux to edit the front 7 bytes from "de ad ba be 15 de ad" to "ff d8 ff e0 00 10 4a"
3.	enabling you to be able open the jpg file successfully
4.	The next step is to use photoshop/online tools to retrieve the watermark with the flag on it.

## Recommended Reads
- personally recommend this for quick checking of images
#https://29a.ch/photo-forensics/