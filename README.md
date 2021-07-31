


*Last updated: 31 July 2021:* New paper Arkhangelsky et. al. (2021) added.


# Notes

This repository tracks the recent developments in the Difference-in-Difference (DiD) literature. Currently, it is just a dump of my bookmarks from different websites including Twitter, GitHub, YouTube etc. This will be sorted out over time as the literature converges to some consensus. But this might still take a while.

This is a working document, if you want to contribute, just message, or open an issue on GitHub. 


# Why do DiD?

TO BE ADDED


# Stata packages

| Name | Installation |  Package by | Reference paper | 
| --- | --- | --- |   --- | 
| `bacondecomp` | `ssc install bacondecomp, replace` <br><br>  | [Andrew Goodman-Bacon](http://goodman-bacon.com/) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/agoodmanbacon) <br><br> [Thomas Goldring](https://tgoldring.com/) <br><br> Austin Nichols [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/AustnNchols) |   Andrew Goodman-Bacon (2021). [Difference-in-differences with variation in treatment timing](https://www.sciencedirect.com/science/article/abs/pii/S0304407621001445). Journal of Econometrics | 
| `eventstudyinteract` | *See end of table*  | [Liyang Sun](http://economics.mit.edu/grad/lsun20) |   Liyang Sun, [Sarah Abraham](https://www.cornerstone.com/Staff/Sarah-Abraham#) (2020). [Estimating dynamic treatment effects in event studies with heterogeneous treatment effects](https://www.sciencedirect.com/science/article/abs/pii/S030440762030378X). Journal of Econometrics. | 
| `did_multiplegt` | `ssc install did_multiplegt, replace` |   [Clément de Chaisemartin](https://sites.google.com/site/clementdechaisemartin/) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/CdeChaisemartin) <br><br> [Xavier D'Haultfoeuille](https://faculty.crest.fr/xdhaultfoeuille/)  | Clément de Chaisemartin, Xavier D'Haultfoeuille (2020). [Two-Way Fixed Effects Estimators with Heterogeneous Treatment Effects](https://www.aeaweb.org/articles?id=10.1257/aer.20181169). American Economic Review. <br><br>  Clément de Chaisemartin, Xavier D'Haultfoeuille (2021). [Two-way fixed effects regressions with several treatments](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3751060).  <br><br>  Clément de Chaisemartin, Xavier D'Haultfoeuille (2021). [Difference-in-Differences Estimators of Inter-temporal Treatment Effects](https://arxiv.org/abs/2007.04267). |
| `did_imputation` | `ssc install did_imputation, replace` |  [Kirill Borusyak](https://sites.google.com/view/borusyak/home) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/borusyak) <br><br> [Xavier Jaravel](https://www.lse.ac.uk/economics/people/faculty/xavier-jaravel) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/XJaravel) <br><br> [Jann Spiess](https://www.gsb.stanford.edu/faculty-research/faculty/jann-spiess) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/jannspiess)  |   Kirill Borusyak, Xavier Jaravel, Jann Spiess (2021). [Revisiting Event Study Designs: Robust and Efficient Estimation](https://www.google.com/url?q=https%3A%2F%2Fwww.dropbox.com%2Fs%2Fy92mmyndlbkufo1%2FDraft_RobustAndEfficient.pdf%3Fraw%3D1&sa=D&sntz=1&usg=AFQjCNGGDRt4xPz3hCXhTWxchHJWh-1m_Q) | 
| `drdid`   | *See end of table*    | [Fernando Rios-Avila](https://friosavila.github.io/playingwithstata/index.html) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/friosavila) <br><br> [Asjad Naqvi](https://github.com/asjadnaqvi) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/asjadnaqvi) <br><br> [Pedro H.C. Sant'Anna](https://pedrohcgs.github.io/) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/pedrohcgs) |  Pedro H.C. Sant'Anna, [Jun Zhao](https://www.junbeanzhao.com/) (2020). [Doubly robust difference-in-differences estimators](https://www.sciencedirect.com/science/article/abs/pii/S0304407620301901), Journal of Econometrics.  |
| `csdid`   |  *See end of table*    | [Fernando Rios-Avila](https://friosavila.github.io/playingwithstata/index.html)   |  [Brantly Callaway](https://bcallaway11.github.io/), Pedro H.C. Sant'Anna (2020). [Difference-in-Differences with multiple time periods](https://www.sciencedirect.com/science/article/abs/pii/S0304407620303948), Journal of Econometrics.  |
| `flexpaneldid` | `ssc install flexpaneldid, replace`   | [Eva Dettmann](https://www.iwh-halle.de/en/about-the-iwh/team/detail/eva-dettmann/) <br><br> [Alexander Giebler](https://www.iwh-halle.de/ueber-das-iwh/team/detail/alexander-giebler/) <br><br> [Antje Weyh](https://www.iab.de/754/section.aspx/Mitarbeiter/359)   | Eva Dettmann, Alexander Giebler, Antje Weyh (2020). [Flexpaneldid: A Stata Toolbox for Causal Analysis with Varying Treatment Time and Duration](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3692458). IWH Discussion Papers No. 3/2020 |
| `xtevent` | *See end of table*   | [Simon Freyaldenhoven](https://simonfreyaldenhoven.github.io/) <br><br> [Christian Hansen](https://voices.uchicago.edu/christianhansen/) <br><br> [Jorge Perez Perez](https://jorgeperezperez.com/) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/jorpppp) <br><br>  [Jesse M. Shapiro](https://www.brown.edu/Research/Shapiro/)  | Simon Freyaldenhoven, Christian Hansen, Jesse M. Shapiro (2019). [Pre-event Trends in the Panel Event-Study Design](https://www.aeaweb.org/articles?id=10.1257/aer.20180609). American Economic Review. |
| `did2s` |  `ssc install did2s, replace`     |  [Kyle Butts](https://kylebutts.com/) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/kylefbutts) | [John Gardner](https://jrgcmu.github.io/) (2021). [Two-stage differences in differences](https://jrgcmu.github.io/2sdd_current.pdf). |
| `stackedev` | *See end of table*    | [Joshua Bleiberg](https://sites.google.com/view/joshbleiberg) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/JoshBleiberg) | [Doruk Cengiz](https://dorukcengiz.netlify.app/) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/dcdorukcengiz), [Arindrajit Dube](https://arindube.com/) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/arindube), [Attila Lindner](https://sites.google.com/site/attilalindner/), [Ben Zipperer](https://www.epi.org/people/ben-zipperer/) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/benzipperer) (2019). [The effect of minimum wages on low-wage jobs](https://academic.oup.com/qje/article/134/3/1405/5484905). The Quarterly Journal of Economics.    |

*Note*: The length of the installation paths from GitHub repositories is messing up the table. Till this is sorted out, links are here:

* `bacondecomp` alternative: `net install ddtiming, from(https://tgoldring.com/code/)`
* `drdid`: `net install drdid, from ("https://raw.githubusercontent.com/friosavila/csdid_drdid/v0.1/code") replace`
* `csdid`: `net install csdid, from ("https://raw.githubusercontent.com/friosavila/csdid_drdid/main/code/") replace`
* `eventstudyinteract`  : `net install eventstudyinteract, from("https://raw.githubusercontent.com/lsun20/EventStudyInteract/main/") replace`
* `xtevent`   : Manually download and install from `https://simonfreyaldenhoven.github.io/software/`
* `stackedev`: `net install stackedev, from("https://raw.githubusercontent.com/joshbleiberg/stackedev/main/")`



## How to use these packages?

For individual packages, check their helpfiles for example code. 

For using and plotting multiple DiD packages in Stata, the `event_plot` command (`ssc install event_plot, replace`) by [Kirill Borusyak](https://sites.google.com/view/borusyak/home) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/borusyak) is highly recommended. It estimates and combines results from [five different estimators](https://github.com/borusyak/did_imputation/blob/main/five_estimators_example.png). Example of how to do event study plots using different packages is given in the [five_estimators_example.do](https://github.com/borusyak/did_imputation/blob/main/five_estimators_example.do) dofile on [GitHub](https://github.com/borusyak/did_imputation).

The `event_plot` usage example has been extended twice:

* [David Burgherr](https://www.lse.ac.uk/International-Inequalities/People/David-Burgherr) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/d_burgherr) has a dofile on [Dropbox](https://www.dropbox.com/s/p5i94ryf4h9o335/five_estimators_example_adapted.do?dl=0).

* [Pietro Santoleri](https://pietrosantoleri.github.io/) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/santpietro) has a dofile on [GitHub](https://github.com/pietrosantoleri/staggered_did) that plots [seven different estimators](https://github.com/pietrosantoleri/staggered_did/blob/main/output/seven_estimators_example_allt.png).


# R packages

Packages installation paths have been split across lines to preverse table formatting in Markdown.

| Name | Installation |  Package by | Reference paper | 
| --- | --- | --- |   --- | 
| `bacondecomp` | `install.packages("bacondecomp")` <br><br>  | [Evan Flack](https://github.com/evanjflack) <br><br> [Ed Jee](https://edjeeongithub.github.io/)  |   [Andrew Goodman-Bacon](http://goodman-bacon.com/) (2021). [Difference-in-differences with variation in treatment timing](https://www.sciencedirect.com/science/article/abs/pii/S0304407621001445). Journal of Econometrics. | 
| `fixest` with `sunab()` function | `install.packages("fixest")` | [Laurent Bergé](https://sites.google.com/site/laurentrberge/) | [Liyang Sun](http://economics.mit.edu/grad/lsun20), [Sarah Abraham](https://www.cornerstone.com/Staff/Sarah-Abraham#) (2020). [Estimating dynamic treatment effects in event studies with heterogeneous treatment effects](https://www.sciencedirect.com/science/article/abs/pii/S030440762030378X). Journal of Econometrics. | 
| `TwoWayFEWeights` | `install.packages("TwoWayFEWeights")` | [Shuo Zhang](https://github.com/shuo-zhang-ucsb) | Clément de Chaisemartin, Xavier D'Haultfoeuille (2021). [Two-Way Fixed Effects Estimators with Heterogeneous Treatment Effects](https://www.aeaweb.org/articles?id=10.1257/aer.20181169). |
| `DIDmultiplegt` [not as recent as Stata version] | `install.packages("DIDmultiplegt")` | [Shuo Zhang](https://github.com/shuo-zhang-ucsb) | [Two-Way Fixed Effects Estimators with Heterogeneous Treatment Effects](https://www.aeaweb.org/articles?id=10.1257/aer.20181169). |
| `drdid`   |  `devtools::install_github` `("pedrohcgs/DRDID")`   |  [Pedro H.C. Sant'Anna](https://pedrohcgs.github.io/) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/pedrohcgs) <br><br> [Jun Zhao](https://www.junbeanzhao.com/) | Pedro H.C. Sant'Anna, [Jun Zhao](https://www.junbeanzhao.com/) (2020). [Doubly robust difference-in-differences estimators](https://www.sciencedirect.com/science/article/abs/pii/S0304407620301901), Journal of Econometrics.  |
| `did`   |   `install.packages("did")`   | [Pedro H.C. Sant'Anna](https://pedrohcgs.github.io/) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/pedrohcgs)  <br><br> [Brantly Callaway](https://bcallaway11.github.io/) |  Brantly Callaway, Pedro H.C. Sant'Anna (2020). [Difference-in-Differences with multiple time periods](https://www.sciencedirect.com/science/article/abs/pii/S0304407620303948), Journal of Econometrics.  |
|	`staggered`	|	`devtools::install_github` `("jonathandroth/staggered")`		|	[Jonathan Roth](https://jonathandroth.github.io/) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/jondr44), Pedro H.C. Sant'Anna (2021)		|	[Jonathan Roth](https://jonathandroth.github.io/) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/jondr44), Pedro H.C. Sant'Anna (2021) [Efficient Estimation for Staggered Rollout Designs](https://arxiv.org/pdf/2102.01291.pdf)	|
| `did2s` |  `devtools::install_github` `("kylebutts/did2s")`     |  [Kyle Butts](https://kylebutts.com/) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/kylefbutts) | [John Gardner](https://jrgcmu.github.io/) (2021). [Two-stage differences in differences](https://jrgcmu.github.io/2sdd_current.pdf). <br><br> [Kirill Borusyak](https://sites.google.com/view/borusyak/home) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/borusyak), [Xavier Jaravel](https://www.lse.ac.uk/economics/people/faculty/xavier-jaravel) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/XJaravel), [Jann Spiess](https://www.gsb.stanford.edu/faculty-research/faculty/jann-spiess) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/jannspiess) (2021). [Revisiting Event Study Designs: Robust and Efficient Estimation](https://www.google.com/url?q=https%3A%2F%2Fwww.dropbox.com%2Fs%2Fy92mmyndlbkufo1%2FDraft_RobustAndEfficient.pdf%3Fraw%3D1&sa=D&sntz=1&usg=AFQjCNGGDRt4xPz3hCXhTWxchHJWh-1m_Q) <br><br> Liyang Sun, Sarah Abraham (2020). [Estimating dynamic treatment effects in event studies with heterogeneous treatment effects](https://www.sciencedirect.com/science/article/abs/pii/S030440762030378X). Journal of Econometrics. <br><br> Brantly Callaway, Pedro H.C. Sant'Anna (2020). [Difference-in-Differences with multiple time periods](https://www.sciencedirect.com/science/article/abs/pii/S0304407620303948), Journal of Econometrics. <br><br> [Jonathan Roth](https://jonathandroth.github.io/) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/jondr44), Pedro H.C. Sant'Anna (2021) [Efficient Estimation for Staggered Rollout Designs](https://arxiv.org/pdf/2102.01291.pdf). |



# Literature


## Papers

SORTABLE TABLE TO BE ADDED. 

Papers are in alphabetical order by last name. Papers without journals are pre-prints. Please click on paper links for details.

[Dmitry Arkhangelsky](https://sites.google.com/view/dmitry-arkhangelsky/home) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/ArkhangelskyD), [Guido Imbens](https://www.gsb.stanford.edu/faculty-research/faculty/guido-w-imbens), [Lihua Lei](https://lihualei71.github.io/) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/lihua_lei_stat), [Xiaoman Luo](https://xiaomanluo.github.io/) (2021). [Double-Robust Two-Way-Fixed-Effects Regression For Panel Data](https://arxiv.org/abs/2107.13737).

[Kirill Borusyak](https://sites.google.com/view/borusyak/home) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/borusyak), [Xavier Jaravel](https://www.lse.ac.uk/economics/people/faculty/xavier-jaravel) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/XJaravel), [Jann Spiess](https://www.gsb.stanford.edu/faculty-research/faculty/jann-spiess) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/jannspiess) (2021). [Revisiting Event Study Designs: Robust and Efficient Estimation](https://www.google.com/url?q=https%3A%2F%2Fwww.dropbox.com%2Fs%2Fy92mmyndlbkufo1%2FDraft_RobustAndEfficient.pdf%3Fraw%3D1&sa=D&sntz=1&usg=AFQjCNGGDRt4xPz3hCXhTWxchHJWh-1m_Q).

Brantly Callaway, Andrew Goodman-Bacon, Pedro H.C. Sant'Anna. [Difference-in-Differences with a Continuous Treatment](https://arxiv.org/pdf/2107.02637.pdf).

Brantly Callaway, Pedro H.C. Sant'Anna (2020). [Difference-in-Differences with multiple time periods](https://www.sciencedirect.com/science/article/abs/pii/S0304407620303948), Journal of Econometrics.

Clément de Chaisemartin, Xavier D'Haultfoeuille (2020). [Two-Way Fixed Effects Estimators with Heterogeneous Treatment Effects](https://www.aeaweb.org/articles?id=10.1257/aer.20181169). American Economic Review.

Clément de Chaisemartin, Xavier D'Haultfoeuille (2021). [Two-way fixed effects regressions with several treatments](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3751060).

Clément de Chaisemartin, Xavier D'Haultfoeuille (2021). [Difference-in-Differences Estimators of Inter-temporal Treatment Effects](https://arxiv.org/abs/2007.04267).

Simon Freyaldenhoven, Christian Hansen, Jesse M. Shapiro (2019). [Pre-event Trends in the Panel Event-Study Design](https://www.aeaweb.org/articles?id=10.1257/aer.20180609). American Economic Review.

[John Gardner](https://jrgcmu.github.io/) (2021). [Two-stage differences in differences](https://jrgcmu.github.io/2sdd_current.pdf).

[Andrew Goodman-Bacon](http://goodman-bacon.com/) (2021). [Difference-in-differences with variation in treatment timing](https://www.sciencedirect.com/science/article/abs/pii/S0304407621001445). Journal of Econometrics.

[Jonathan Roth](https://jonathandroth.github.io/) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/jondr44), Pedro H.C. Sant'Anna (2021). [Efficient Estimation for Staggered Rollout Designs](https://arxiv.org/pdf/2102.01291.pdf).

Pedro H.C. Sant'Anna, [Jun Zhao](https://www.junbeanzhao.com/) (2020). [Doubly robust difference-in-differences estimators](https://www.sciencedirect.com/science/article/abs/pii/S0304407620301901), Journal of Econometrics.

[Liyang Sun](http://economics.mit.edu/grad/lsun20), [Sarah Abraham](https://www.cornerstone.com/Staff/Sarah-Abraham#) (2020). [Estimating dynamic treatment effects in event studies with heterogeneous treatment effects](https://www.sciencedirect.com/science/article/abs/pii/S030440762030378X). Journal of Econometrics.




## Books

[Scott Cunningham](https://www.scunning.com/) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/causalinf) (2020). [Causal Inference: The Mix Tape](https://mixtape.scunning.com/).

[Nick Huntington-Klein](https://nickchk.com/) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/nickchk) (2021). [The Effect](https://theeffectbook.net/).


# DiD knowledge curation

Here are people who are actively involved in curating information on the latest DiD developments. This includes blogs, lecture series, tweets.


## Events and Videos

[Scott Cunningham](https://www.scunning.com/) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/causalinf): [CodeChella](https://causalinf.substack.com/p/codechella-announcement) the ultimate DiD event **Workshop 1: Friday July 16th, 2021** and **Workshop 2: Friday July 23, 2021** which will be live on [Twitch](https://www.twitch.tv/causalinf_did). The videos from the first workshop are now up on [YouTube](https://www.youtube.com/user/scunning/videos).

[Chloe East](https://www.chloeneast.com/) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/ChloeEast2) organizes an online [DiD reading group](https://www.chloeneast.com/metrics-discussions.html).

[Taylor J. Wright](https://taylorjwright.github.io/) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/taylor_wright) organizes an online [DiD reading group](https://taylorjwright.github.io/did-reading-group/). The lecture recordings can also be viewed on [YouTube](https://www.youtube.com/channel/UCA7Idy0MfpP-uAjOebsFVuA/videos).


## Blogs
[Scott Cunningham](https://www.scunning.com/) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/causalinf): Scott's [Substack](https://causalinf.substack.com/) is the goto place for an easy-to-digest explanation of the latest metric-heavy DiD papers.

[Andrew C. Baker](https://andrewcbaker.netlify.app/) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/Andrew___Baker) has notes on [Difference-in-Differences Methodology](https://andrewcbaker.netlify.app/2019/09/25/difference-in-differences-methodology/) with supporting material on [GitHub](https://github.com/andrewchbaker).


## Notes

[Paul Goldsmith-Pinkham](https://paulgp.github.io/) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/paulgp) has a brilliant set of [lectures on empirical methods including DiD on GitHub](https://github.com/paulgp/applied-methods-phd). These are also supplemented by [YouTube videos](https://www.youtube.com/playlist?list=PLWWcL1M3lLlojLTSVf2gGYQ_9TlPyPbiJ). 

Jeffrey Wooldridge [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/jmwooldridge) has made several notes on DiD which are shared on his [Dropbox](https://www.dropbox.com/sh/zj91darudf2fica/AADj_jaf5ZuS1muobgsnxS6Za?dl=0) including Stata dofiles.

[Fernando Rios-Avila](https://friosavila.github.io/playingwithstata/index.html) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/friosavila) has a great explainer for the Callaway and Sant'Anna (2020) CS-DID logic on his [blog](https://friosavila.github.io/playingwithstata/main_csdid.html).

[Christine Cai](https://christinecai.github.io/) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/Christine_Cai27) has a [working document](https://christinecai.github.io/PublicGoods/applied_micro_methods.pdf) which lists recent papers using different methods including DiDs.


## Interactive dashboards
These (related) interactive R-Shiny dashboards showcase how TWFE models give wrong estimates.

[Kyle Butts](https://kylebutts.com/) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/kylefbutts): https://kyle-butts.shinyapps.io/did_twfe/

[Hans Henrik Sievertsen](https://hhsievertsen.github.io/) [<img width="12px" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" />](https://twitter.com/hhsievertsen): https://hhsievertsen.shinyapps.io/kylebutts_did_eventstudy/




## Tweets

Twitter threads that summarize the DiD literature. In order to render these properly, you need to view them on the [Jekyll website](https://asjadnaqvi.github.io/Diff-in-Diff-Notes/).

<br>

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">I spent this past week catching up with the DiD literature. Here is my list🧵:<br>1. Read (if you haven&#39;t) Andrew Goodman-Bacon&#39;s &quot;Difference-in-Differences with Variation in Treatment Timing.&quot; The paper that started all for me (there are others before).Link: <a href="https://t.co/GBFjBnHDcj">https://t.co/GBFjBnHDcj</a></p>&mdash; Jesús Villero (@jotavillero) <a href="https://twitter.com/jotavillero/status/1393957055514529803?ref_src=twsrc%5Etfw">May 16, 2021</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<br>

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Navigating the DiD revolution from one applied researcher&#39;s perspective. <br><br>A LONG 🧵 on what I&#39;ve learned &amp; what I&#39;m still trying to figure out. Advice/insights welcome!<br><br>My <a href="https://twitter.com/michaelpollan?ref_src=twsrc%5Etfw">@michaelpollan</a> 🥦🍅🥕🫑 inspired TL;DR take:<br><br>&quot;Apply DiD in context, not every 2x2, mostly event studies&quot; <a href="https://t.co/CWmwyo1Btp">pic.twitter.com/CWmwyo1Btp</a></p>&mdash; Matthew A. Kraft (@MatthewAKraft) <a href="https://twitter.com/MatthewAKraft/status/1408147332164640769?ref_src=twsrc%5Etfw">June 24, 2021</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>


<br>

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">I&#39;ve been catching up on staggered diff-in-diff/two-way fixed effects recently. Simulating helped me see how bad TWFE performs with dynamic treatment effects (see those pre-trends). I also tried implementing Sun &amp; Abraham (2020)&#39;s interaction-weighted estimator in Stata <a href="https://t.co/FQBCQi0m7d">pic.twitter.com/FQBCQi0m7d</a></p>&mdash; Shan Huang (@ShanHuang_ec) <a href="https://twitter.com/ShanHuang_ec/status/1272928307441475585?ref_src=twsrc%5Etfw">June 16, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>


