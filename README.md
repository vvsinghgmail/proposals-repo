# proposals-repo
## About the documents in this repository
This document describes the files in repository, their intended use and conversion using pandoc tool

This repository contains the templates for 
- Delivery proposals
  - All projects on Man day basi or man months
  - All project on that requires a bench of team to operate and deliver services
  
- Quotations
  - Subscriptions
  - Trainings
  - Body shopping work 
  
- Requirements
  - pandoc should be installed

- How to use the documents
  - Download the required document templete i.e. .md files to 
    - your local git OR 
    - use your github account and download form https://github.com/vvsinghkeenable/proposals-repo  OR
    - use wget https://github.com/vvsinghkeenable/proposals-repo/blob/master/filename.md to download a single file without using git 
  - use pandoc command line tool to convert the document i.e pandoc should be installed on your system or use any online conversion tool
    - syntax to use for converting* the document
      $ pandoc -s <sourcedocument> -o <outputdocument>
  
  *Document from .txt can be converted into .odt, .docx, .pdf, .html, .epub and many more as supported by pandoc https://pandoc.org/MANUAL.html
