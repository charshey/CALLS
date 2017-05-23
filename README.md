
# CALLS

Computational Assistant for Language Learning Systems

CALLS is a system of python and bash scripts that take input webpage text (e.g. A simple English Wikipedia page), process this text and output language learning problems in the Openwords markup language (OWML). CALLS will take input from the user on the kinds of language concepts that are desired in outputed language learning problems.

The OWML represents language learning problems in a simple text format, and is read by the Openwords webapp. Alternatively, OWML problems could be transfered to other problem expression formats.

CALLS is divided into several different Modules. Currently the design includes a total 

## Module 1
The purpose of Moddule 1 is to take user input on various priorities for problem development. These priorities include the following.
1) Page/s to scrape.
2) Vocabulary list (words that can be prioritized for insertion into new problems). Prompts the user/curricula builder to upload a list/s of vocabulary. These lists can be used for several different purposes.
- A list of words that have already been covered by learners in previous lessons or experience.
- A list of new priority words in upcoming lesson/s.
3) Grammatical concepts to prioritizing. For example, prioritizing syntax with particular word order. Catagories of language concepts are displayed to the user/curricula developer in the terminal, and they select the priorities for that lesson.

## Module 2

## Module 3
Module 3 scrapes text from the Simple English wikipedia. Instead we use Wikimedia's API called [Media Wiki API](https://www.mediawiki.org/wiki/API:Main_page). To access this API we use a python wrapper accessing Media Wiki Api.
