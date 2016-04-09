# CandidateHeatMap
Heat Map of Candidate Word Frequencies

Computes a heat map of candidate debate speech from the late 2015 adn early 2106 Republican and Democratic debates. 
The program allows to filter for spcific topics. 

Input .txt files of the debates are also included. Data are acquired from the [UCSB Presidency Project](http://www.presidency.ucsb.edu/). Text were clipped from a web browswer, pasted into Apple Pages on a MacbookAir, and then exported as .txt files. All subsequent processing is done in __R__.

A sample output of the program is shown [here](http://rpubs.com/ww44ss/debateheatmap)


###FILES: 

File Name                                         | _descritpion_
--------------------------------------------------|--------------------------
[Party] Candidates Debate [Location] [Date].txt   |_text of_ [Party] _debate held in_ [Location] _on_ [Date]  
                                                  |                                  |
candidate_text.R                                  |_raw text of candidate speech_     
candidate_text_tc.R                               |_returns a text corpus using the_ {tm} _package_   
load_debate_text.R                                |_load raw_ .txt _files_  
multiplot.R                                       |_Multiple plot function from_ [here](http://www.cookbook-r.com/Graphs/Multiple_graphs_on_one_page_(ggplot2)/)   
vector.normalize.R                                |_Makes a vector unit length_   
--------------------------------------------------|-----------------------------
Candidate_HeatMapR_1.Rmd                          |_Produces a heat map graph of candidate text (filterable)_    



