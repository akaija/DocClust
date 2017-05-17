# DocClust - DELPHI MVP

This repo serves as a rudimentary MVP, complimenting the DELPHI workflow  
developed through Pitt's 2017 H4D course. This repo contains an iPython  
notebook for clustering a small sample set of abstracts from the top 30  
most-cited articles on Web of Science related to cybersecurity.

## Getting started
The following Python packages are required:  
  - numpy  
  - scipy  
  - nltk  
  - sklearn  
  - mpld3  
  - genism  
  
## First time setup
```

# Create virual environment for Python packages    
mkdir -p ~/venv    
pyvenv ~/venv/docclust   
source ~/venv/docclust/bin/activate    

# Install Python packages   
cd path/to/DocClust/repo
pip install -r requirements.txt    
```
  
## Running DocClust
### Activating the htsohm virtual environment:
```
source ~/venv/docclust/bin/activate
```
### Starting notebook:
```
cd path/to/DocClust/repo
python3 -m notebook DELPHI_MVP.ipynb
```
 
Please send questions/comments/concerns to `ark111@pitt.edu`.
  
## License
  
DocClust and related modules released under the MIT License 2017.    
  
## Development environment

```
3.5.1 |Anaconda 2.4.1 (64-bit)| (default, Dec  7 2015, 11:16:01)
[GCC 4.4.7 20120313 (Red Hat 4.4.7-1)]
Bash 4.1.2(1)-release
RHEL 6.6	2.6.32-358
psql (PostgreSQL) 8.4.20
```
