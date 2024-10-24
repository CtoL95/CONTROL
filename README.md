# AI-experiments
Simple AI experiments


Notes
https://code.google.com/archive/p/sparcraft/wikis/ArtificialIntelligence.wiki
**We have developed a version of Alpha Beta tree search called Alpha Beta Considering Durations (ABCD). This algorithm was introduced in the following 2012 AIIDE paper: Fast Heuristic Search for RTS Game Combat Scenarios. The algorithm is implemented in SparCraft/source/AlphaBetaSearch.cpp ** https://skatgame.net/mburo/ps/aiide12-combat.pdf
**UCT is another popular tree search algorithm, and we have modified it for use with RTS combat. It is available in SparCraft/source/UCTSearch.cpp - A paper detailing this UCT implementation is currently submitted to CIG2013 and will be posted here if accepted. SparCraft/source/UCTSearch.cpp**
**Our newest greedy search technique which loses to AB/UCT at small combat sizes, but easily defeats them at larger sizes. It is implemented in SparCraft/source/PortfolioGreedySearch.cpp - A paper detailing this greedy search implementation is currently submitted to CIG2013 and will be posted here if accepted.**
