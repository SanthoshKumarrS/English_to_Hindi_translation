# English_to_Hindi_translation
This repo contains the entire project for translating from English to Hindi using a deep neural network model.

# Description 🧾:

The IIT Bombay English-Hindi corpus contains parallel corpus for English-Hindi as well as monolingual Hindi corpus collected from a variety of existing sources and corpora developed at the Center for Indian Language Technology, IIT Bombay over the years. This page describes the corpus. This corpus has been used at the Workshop on Asian Language Translation Shared Task since 2016 the Hindi-to-English and English-to-Hindi languages pairs and as a pivot language pair for the Hindi-to-Japanese and Japanese-to-Hindi language pairs.

### Source of the dataset - [Click Here](https://www.cfilt.iitb.ac.in/iitb_parallel/)
### Research paper - [Click Here](https://arxiv.org/pdf/1710.02855.pdf)
# 🧭 Problem Statement:

You are provided with a large dataset of language pairs, parallelly in English and Hindi: you have to perform a step-by-step NLP approach to translate English to Hindi after splitting the dataset into train-test-validation sets.

# Steps taken to solve the problem :

✔️ Load the dataset
✔️ Pre-processing the Hindi and English texts
✔️ Character level tokenization using Python list and set data structures
✔️ Encode input and target texts using Python dictionary and Numpy array
✔️ Build the encoder and decoder architecture using LSTMs
