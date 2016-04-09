# CandidateHeatMap
Heat Map of Candidate Word Frequencies

Computes a heat map of candidate debate speech from the late 2015 adn early 2106 Republican and Democratic debates. 
The program allows to filter for spcific topics. 

Input .txt files of the debates are also included. Data are acquired from the [UCSB Presidency Project](http://www.presidency.ucsb.edu/). Text were clipped from a web browswer, pasted into Apple Pages on a MacbookAir, and then exported as .txt files. All subsequent processing is done in __R__.

A sample output of the program is shown [here](http://rpubs.com/ww44ss/debateheatmap)


##DATA FILES:  
[Party] Candidates Debate [Location] [Date].txt   text of [Party] debate held in [Location] on [Date]  

##PROGRAM FILES  
candidate_text.R                                  raw text of candidate speech     
candidate_text_tc.R                               returns a text corpus using the {tm} package   
load_debate_text.R                                load raw .txt files  
multiplot.R                                       Multiple plot function from [here](http://www.cookbook-r.com/Graphs/Multiple_graphs_on_one_page_(ggplot2)/)   
vector.normalize.R                                Makes a vector unit length   

Candidate_HeatMapR_1.Rmd                          Produces a heat map graph of candidate text (filterable)   



